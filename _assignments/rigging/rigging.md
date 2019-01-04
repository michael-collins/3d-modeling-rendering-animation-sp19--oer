---
title: Rigging
subtitle: 
layout: exercise
submission-id: rigging-05-YOURNAME
assignment-dropbox: 
exercise: exercise-5
asset-path: /assets/exercise-images
download-path: /assets/exercise-downloads
---

In this exercise, you will practice creating a rig for a polygon mesh. You will create a simple biped rig starting with the [base mesh FBX file]({{site.baseurl}}{{page.download-path}}/biped-base-mesh.fbx).

## Learning Resources:

Lynda.com: [Character Rigging](https://www.lynda.com/Blender-tutorials/Rigging-Humanoid-Character-Blender/365285-2.html?org=psu.edu)

[Weight Painting](https://www.youtube.com/watch?v=Tl4qTgwQwYw)

Lynda Tutorials: [12 Principles of Animation](https://www.lynda.com/3ds-Max-tutorials/12-Principles-Animation-CG-Animators/474685-2.html?org=psu.edu)

## Steps to Completion

1. Watch the level rigging tutorials.
2. Download the base [base mesh FBX file]({{site.baseurl}}{{page.download-path}}/biped-base-mesh.fbx).
3. File → Import the FBX mesh into a new Blender scene.
4. Scale up the model.
5. Add subdivisions (edge loops) to the polygonal mesh to minimize unwanted distortion when posing the mesh. Add geometry to articulate the knee, elbows, and arms.
6. Object → **Apply** all transforms including scale, rotation, and location.
7. Create joints for the torso, hips, knees, legs, feet, shoulders, arms, neck, and head. Name and number them for your reference. See image below:
![image alt text]({{ site.baseurl }}{{ page.asset-path }}/maya-rigging-1.jpg)
8. Attach the armature to the polygonal mesh. Do this by selecting the mesh first, select the armature, and then press 'CTRL-P,' and choose "with automatic weights." If you do not see this option, you have selected in the reverse order.
9. Adjustments the weight influence where needed to create a posable character.
10. Pose the biped to be in a sitting pose. (You can add a chair if you like)
11. Save your scene as **_{{ page.submission-id }}_** in the project folder.
12. Compress the project folder once you’ve completed the tutorial and rename it **_{{ page.submission-id }}.zip._**
13. Upload the .zip file to the dropbox.
14. Ensure you’ve included everything properly. Failure to ensure that you’ve uploaded the file will result in your exercise being graded according the grading criteria.