## 🖐️ 3D Hand Model Development

The 3D hand models were created using **Blender** to represent American Sign Language (ASL) hand gestures.

The development process involved several stages:

### 1. 🧊 3D Modelling

Creating the 3D hand models and shaping their fingers and overall structure.

<kbd>
<img src="https://github.com/syuhada2808/Pictures/blob/dffdfa971850b1939fbc6eb4df5498b7147fc73a/Picture%202.png" width="600">
</kbd>

📌 *3D models of hand signs for SignLingo AR were developed using Blender. The modelling process focused on creating detailed and accurate representations of each hand gesture.*

### 2. 🦴 Rigging & 🎨 Weight Painting

Creating a bone structure and assigning weights to the hand mesh to ensure the fingers and hand move naturally with the bones.

<kbd>
<img src="https://github.com/syuhada2808/Pictures/blob/dffdfa971850b1939fbc6eb4df5498b7147fc73a/Picture%203.png" width="600">
</kbd>

📌 *After the hand model is shaped, an armature, or skeleton, is added to make it move. Bones are placed in each finger and the wrist to allow the hand to bend and pose naturally. Weight painting is then used to connect the hand model to the bones,making sure that every part of the hand moves smoothly when animated. This is an important step to ensure the hand gestures look lifelike and work correctly.*

### 3. 🎬 Animation

Creating different hand poses and movements to represent ASL alphabets (A–Z) and numbers (1–10).

<kbd>
<img src="https://github.com/syuhada2808/Pictures/blob/dffdfa971850b1939fbc6eb4df5498b7147fc73a/Picture%204.png" width="600">
</kbd>

📌 *To make the hand models interactive, animations are added in Blender using keyframes. Each hand gesture is created by moving the fingers and setting keyframes to capture the positions. The transitions between gestures are carefully adjusted to make the movements smooth and natural. These animations are what bring the hand to life, making it easy for users to learn the correct gestures. Once the animations are complete, the models are exported in a format that works with Unity for use in the app.*

### 4. 🎮 Unity Integration

Importing the completed 3D hand models and animations into Unity for use in the AR application.

<kbd>
<img src="https://github.com/syuhada2808/Pictures/blob/72321b3aa7327b99180f65b54e790d9c11d2faee/Picture%205.png" width="400">
</kbd>
<kbd>
<img src="https://github.com/syuhada2808/Pictures/blob/72321b3aa7327b99180f65b54e790d9c11d2faee/Picture%206.png" width="400">
</kbd>

📌 *After completing the 3D models of the hand signs, they were imported into Unity to integrate them into the SignLingo AR application Using Vuforia's Software Development Kit (SDK), the 3D models were linked to their respective markers. This process involved setting up the AR camera, creating target databases in Vuforia, and assigning each marker to its corresponding hand sign model. In Unity, the models were carefully positioned and scaled to ensure they aligned naturally with the physical markers when viewed through the app. Tests were conducted to check the alignment and interaction between the markers and 3D models. These adjustments helped ensure the AR experience was smooth and engaging for users, making the learning process intuitive and enjoyable.*
