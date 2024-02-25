# Dustbin Robo Blender

## Introduction
This project aims to design and animate a dustbin robot using Blender. The robot consists of several components including the body, legs, light, and camera adjustments for creating a dynamic scene. Additionally, it provides guidelines for rigging, walk cycle creation, camera adjustments, and exporting the model to Unity.

## Part 1: Designing the Character
### Constructing the Body
- Start with a cylinder primitive and shape it into a dustbin-like form using extrusion and scaling.
- Refine the shape using Bevel and Subdivision modifiers.
- Design the lid, bottom, and handle for the lid.

### Constructing the Legs
- Begin with a plane primitive and form the leg shape through extrusion.
- Add thickness and smoothness using the Skin and Subdivision modifiers.

### Adding the Robot's Light
- Create a light using a cylinder and sphere.
- Refine the light using Bevel and Subdivision modifiers.

## Part 2: Rigging and Walk Cycle
### Adding Bones and Inverse Kinematics
- Add an armature to the leg objects and set up Inverse Kinematics.
- Parent the legs to the body for animation control.

### Creating a Walk Cycle
- Use a Bezier circle as a path for leg movement.
- Adjust leg position and rotation along the path to simulate walking motion.

### Adding Direction and Motion Control
- Insert an empty sphere as a "Direction Controller" and use it to control the robot's movement along a path.

## Part 3: Camera Adjustments
### Positioning the Camera
- Add a camera and adjust its position, rotation, and focal length for optimal view.

### Path Control for Camera Movement
- Define a camera path using a Bezier curve and make the camera follow it using Object Constraints.
- Add a target object for the camera to focus on.

### Adjusting Camera Axis
- Align the camera to the curve's starting point for desired focus.

### Creating a Moving Camera
- Keyframe the camera's movement along the path and adjust the offset for controlled motion.

## Part 4: Export Model in Unity
- Export the model from Blender to Unity for further development and integration.

## Part 5: Texture and Materials
- Apply textures and materials to the dustbin robot and environment to enhance visual appeal.

## Part 6: Final Rendered Output
- Render the final animation of the dustbin robot and its environment for presentation or further use.

## Conclusion
This project provides a comprehensive guide to designing, animating, and exporting a dustbin robot using Blender, with additional instructions for camera adjustments, rigging, and texture application. The final output can be used in Unity for various applications.
