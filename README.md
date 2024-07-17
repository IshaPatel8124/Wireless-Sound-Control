# Wireless-Sound-Control

Gesture recognition helps computers to understand human body language. This helps to build a more potent link between humans and machines, rather than just the basic text user interfaces or graphical user interfaces (GUIs). The camera in our device is used for this project. It detects our hand with points in it so as it can see the distance between our thumb finger tip and index finger tip. The distance between the points 4 and 8 is directly proportional to the volume of device.

![image](https://github.com/user-attachments/assets/06bf2367-6a12-4216-945c-ec1ce330fcd2)

## Methodology
1. Detect hand landmarks.
2. Calculate the distance between thumb tip and index finger tip.
3. Map the distance of thumb tip and index finger tip with volume range. For my case, distance between thumb tip and index finger tip was within the range of 30 – 350 and the volume range was from -63.5 – 0.0.
4. In order to exit press ‘Spacebar'.

## Libraries used
- `numpy` : Supports large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.
- `math` : Provides access to the mathematical functions.
- `cv2` : OpenCV provides image processing in python.
- `mediapipe` : High-fidelity hand and finger tracking solution. It uses machine learning to infer 21 key 3D hand information from just one frame.
- `pycaw` : Python Audio Control Library
- `comtypes` : Lightweight Python COM package, based on the ctypes FFI library. `comtypes` allows to define, call, and implement custom and dispatch-based COM interfaces in pure Python.

COM(Component Object Model) is a mechanism that allows the re-use of objects (or rather components), independently of the languages used by the programmer who implemented the component and the programmer who uses it, and independently of whether the component was implemented in the client's program or elsewhere on the machine (or network).
