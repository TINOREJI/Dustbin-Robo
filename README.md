# Dustbin Robo Blender

## Introduction
This project aims to design and animate a dustbin robot using Blender. The robot consists of several components including the body, legs, light, and camera adjustments for creating a dynamic scene. Additionally, it provides guidelines for rigging, walk cycle creation, camera adjustments, and exporting the model to Unity.

Gdrive Link:- https://drive.google.com/drive/folders/1Jiv-ZZXWE-Lx_bKVs3TNWEEFR3h0HKKP?usp=sharing
## Part 1: Designing the Character
### Constructing the Body
- Start with a cylinder primitive and shape it into a dustbin-like form using extrusion and scaling.
- Refine the shape using Bevel and Subdivision modifiers.
- Design the lid, bottom, and handle for the lid.
![image](https://github.com/TINOREJI/Dustbin-Robo/assets/95184183/a066b59f-a8c5-48aa-ac53-af6ddbda9a7f)
![image](https://github.com/TINOREJI/Dustbin-Robo/assets/95184183/9ffcc621-68d5-44f8-a3e0-778bf15e2270)
![image](https://github.com/TINOREJI/Dustbin-Robo/assets/95184183/762c9506-7a47-4005-a8b8-bbef2b85ecfd)#### Dustbin

![image](https://github.com/TINOREJI/Dustbin-Robo/assets/95184183/7d94b11b-97ef-4c42-ada1-49a08957b038)#### LID

### Constructing the Legs
- Begin with a plane primitive and form the leg shape through extrusion.
- Add thickness and smoothness using the Skin and Subdivision modifiers.
![image](https://github.com/TINOREJI/Dustbin-Robo/assets/95184183/dd1a6b0b-2479-4e7e-893c-7a869166ddb7)

### Adding the Robot's Light
- Create a light using a cylinder and sphere.
- Refine the light using Bevel and Subdivision modifiers.
![image](https://github.com/TINOREJI/Dustbin-Robo/assets/95184183/ae9a56c4-a2fc-457e-b03f-bb0712e545ba)


### Part 1: Result
![image](https://github.com/TINOREJI/Dustbin-Robo/assets/95184183/c921a2b0-f21f-4a37-b061-e75ef601eddc)

## Part 2: Rigging and Walk Cycle
### Adding Bones and Inverse Kinematics
- Add an armature to the leg objects and set up Inverse Kinematics.
- Parent the legs to the body for animation control.
![image](https://github.com/TINOREJI/Dustbin-Robo/assets/95184183/8dbeffac-4fa2-4df2-8d28-a98dd3be7021)

### Creating a Walk Cycle
- Use a Bezier circle as a path for leg movement.
- Adjust leg position and rotation along the path to simulate walking motion.
![image](https://github.com/TINOREJI/Dustbin-Robo/assets/95184183/9df5cbbe-9968-4074-9fa1-ae3201db942a)

### Adding Direction and Motion Control
- Insert an empty sphere as a "Direction Controller" and use it to control the robot's movement along a path.
![image](https://github.com/TINOREJI/Dustbin-Robo/assets/95184183/c5e6934f-2795-4e3e-bd1c-ea76fa9f707e)

## Part 3: Camera Adjustments
### Positioning the Camera
- Add a camera and adjust its position, rotation, and focal length for optimal view.
![image](https://github.com/TINOREJI/Dustbin-Robo/assets/95184183/833ce226-e13a-447c-801b-7b8e577e0a9a)

### Path Control for Camera Movement
- Define a camera path using a Bezier curve and make the camera follow it using Object Constraints.
- Add a target object for the camera to focus on.
![image](https://github.com/TINOREJI/Dustbin-Robo/assets/95184183/1ff17fe1-cdab-44a8-aafe-d89c747ec5c2)

### Adjusting Camera Axis
- Align the camera to the curve's starting point for desired focus.

### Creating a Moving Camera
- Keyframe the camera's movement along the path and adjust the offset for controlled motion.
![image](https://github.com/TINOREJI/Dustbin-Robo/assets/95184183/de5c3601-dedc-4921-9613-066b89150287)

## Part 4: Export Model in Unity
- Export the model from Blender to Unity for further development and integration.
![image](https://github.com/TINOREJI/Dustbin-Robo/assets/95184183/15bdf5f6-8500-4341-8f3d-d7f704126326)
![Uploading image.png…]()

## Part 5: Texture and Materials
- Apply textures and materials to the dustbin robot and environment to enhance visual appeal.
![Uploading image.png…]()
![Uploading image.png…]()
![Uploading image.png…]()

## Part 6: Final Rendered Output
- Render the final animation of the dustbin robot and its environment for presentation or further use.
![Uploading image.png…]()
![Uploading image.png…]()
![Uploading image.png…]()

## Conclusion
This project provides a comprehensive guide to designing, animating, and exporting a dustbin robot using Blender, with additional instructions for camera adjustments, rigging, and texture application. The final output can be used in Unity for various applications.
