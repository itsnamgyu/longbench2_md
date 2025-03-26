# Metadata

- ID: 66ec7ba6821e116aacb1d114
- Domain: Multi-Document QA
- Subdomain: Academic
- Difficulty: hard
- Length: short

# Question

If we refer to "Enhancing Mobile Voice Assistants with WorldGaze" as Paper 1 and "Selecting Real-World Objects via User-Perspective Phone Occlusion" as Paper 2, what are the differences in the implementations for head-gaze method in user studies between these two papers?

# Choices

- A: Paper 1 uses front cameras to track the user's head direction and raycasts it into the 3D world scene captured by the rear camera.
But Paper 2 utilizes an occlusion-based method where the phone itself helps determine the selection area, simplifying user interaction by reducing the need for precise head orientation.
- B: Paper 1 uses front cameras to track the user's head direction and raycasts it into the 3D world scene captured by the rear camera.
But Paper 2 introduces a different approach where both the front and rear cameras are used to estimate the occlusion area, and then the user's gaze direction can be calculated from the phone's positioning and the occlusion area.
- C: Paper 1 uses front cameras to track the user's head direction and raycasts it into the 3D world scene captured by the rear camera, so they only uses the smartphone's built-in cameras.
But Paper 2 employs a head-worn camera to accurately measure the ground truth of head orientation.
- D: Paper 1 uses front cameras to track the user's head direction and raycasts it into the 3D world scene captured by the rear camera, so they only uses the smartphone's built-in cameras.
Paper 2's method refers to the implementation of Paper 1, while they add an extra camera to the phone to accurately measure the ground truth of head orientation.

# Answer

C
