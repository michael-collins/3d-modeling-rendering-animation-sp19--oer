---
title: Advanced Texturing # In the future, change this assignment title to PBR Modeling, Texturing, and Rendering
subtitle: 
layout: exercise
submission-id: advanced-texturing-YOURNAME
asset-path: /assets/exercise-images
exercise: exercise-3
---

In this exercise, you will use a PBR workflow to add realistic textures, set up lights, and configure render settings.

## Learning Resources

---
**Level 1 & 2: Beginner and Intermediate Students**

Physically based materials:

- Blender: [Principled shader documentation](https://docs.blender.org/manual/en/dev/render/cycles/nodes/types/shaders/principled.html)
- [Secrets to photorealism](https://www.youtube.com/watch?v=m9AT7H4GGrA)
- [Ways to Speed Up Blender Cycles Rendering](https://www.youtube.com/watch?v=8gSyEpt4-60)
- [Removing render "fireflies"](https://www.blenderguru.com/articles/7-ways-get-rid-fireflies)

Example texture packs:

- [Texture Haven](https://texturehaven.com/textures/)
- [HDR Environment Assets](https://drive.google.com/drive/folders/1L6gc6B0RFNEZX780XSKj6GXMGo8vEkpY)
- [Rock Texture Pack]({{ site.baseurl }}/assets/exercise-downloads/RockGrey009.zip)
- [Wood Texture Pack]({{ site.baseurl }}/assets/exercise-downloads/WoodFine08.zip)

Blender:

- Blender Reference Sheet: [Blender Hotkeys](http://download.blender.org/documentation/BlenderHotkeyReference.pdf)
- Lynda - Watch Chapters 5-9: [Blender Essentials](https://www.lynda.com/Blender-tutorials/Blender-Essential-Training/87088-2.html?org=psu.edu)
- [Setting up the redner camera in Blender](https://www.youtube.com/watch?v=SG6yOoq7FKI)
- [PBR Materials Demo](https://www.youtube.com/watch?v=FRNCp9GueUs) By Joe Foresman

---

**Level 3: Experienced Students**

- [Character scuptling](https://www.lynda.com/Blender-tutorials/Sculpting-fine-details/135362/146888-4.html?org=psu.edu)
- [Retopologize](https://www.youtube.com/watch?v=k9NAv_q_wfU)
- [Normal Maps and Nodes](https://www.youtube.com/watch?v=gzZqFrFlcEE)

---

## Steps to Completion

Choose a either level 1, level 2, or level 3 to complete based on your prior experience with 3D tools. If you are a novice, choose Level 1. If you have some experience, choose Level 2. If you are very experienced with 3D tools, choose Level 3.

[Level 1 and 2 Steps](#level-1-2) | [Level 3 Steps](#level-3)

### <a name="level-1-2"></a>Level 1 and 2:

1. Create a polygonal model of a lamp against a wall using Principled BSDF shaders.
  - The object should have a bulb with an emission (emissive) material and act as a light source
  - You can download and use [texture packs](https://texturehaven.com/textures/).
  - There should be a background environment HDR image.
  - There should be a floor and one more walls of a room visible in the render, use any material you'd like for these. The lamp should not be "floating in space."
2. Unwrap the UVs for each object if you intend to use textures. Ensure that your materials are mapping with your object's UVs.
3. Adjust the camera's framing and focal length to create a good composition. Explore the camera presets. See video tutorial linked in resources.
4. In Blender, **render** and image using Cycles renderer with the following settings:
  - Image size: X=1920px, Y=1080px
5. In the render window, Image --> Save As **_{{ page.submission-id }}_**.png in the project folder.
9. Save the blend file as **_{{ page.submission-id }}.blend_** in the project folder.
10. Compress the project folder once you’ve completed the tutorial and rename it **_{{ page.submission-id }}.zip._**
11. Upload the .zip file to the [submission dropbox]({{ site.assignments.[page.exercise].dropbox-url }})
12. Ensure you’ve included everything properly. Failure to ensure that you’ve uploaded the file will result in your exercise being graded according the grading criteria.

### <a name="level-3"></a>Level 3:

1. Your model should be a low to medium resolution mesh with a detailed normal map applied. There should also be a finished diffuse texture map.
2. Add an emissive texture to create glowing spots on the creature.
7. Save your **emissive** map in the project folder as **_emissive-{{ page.submission-id }}.png_**.
2. Use an HDR environment map and PBR workflow to light and render your creature.
4. Save the render as **_render-{{ page.submission-id }}.png_**..
6. Save your file as **_{{ page.submission-id }}-L3_.blend**
7. Compress the project folder once you’ve completed the tutorial and rename it **_{{ page.submission-id }}-L3.zip._**
8. Upload the .zip file to the assignment dropbox.
9. Ensure you’ve included everything properly. Failure to ensure that you’ve uploaded the file will result in your exercise being graded according the grading criteria.

**Example _Level 3_ folder structure**

```

{{ page.submission-id }}-L3.zip
|
├── {{ page.submission-id }}-L3
├── normal-{{ page.submission-id }}.png
├── diffuse-{{ page.submission-id }}.png
├── emissive-{{ page.submission-id }}.png
├── {{ page.submission-id }}.png (you may include additional texture maps as needed)
├── render-{{ page.submission-id }}.png
└── {{ page.submission-id }}.blend

```