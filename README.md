# Hand Gesture Controlled Presentation 🎤👋
<br>
<br>

<font size="5">This project demonstrates a Python application for controlling presentation slides using hand gestures. By leveraging the cvzone library's HandTrackingModule, a real-time webcam feed detects hand landmarks and interprets specific gestures to interact with presentation slides.</font>

**Features:**

    Hand gesture recognition: Utilizing the HandDetector class from cvzone, the application identifies hand landmarks and detects gestures for interaction.
    Presentation slide navigation: Gestures such as swiping left or right control the presentation slide navigation, enabling seamless transitions between slides.
    Drawing mode: Activating the drawing mode using a specific finger gesture empowers users to annotate or draw on the presentation slides.
    Real-time visualization: The application presents a real-time view of the webcam feed with overlaid hand landmarks and gesture threshold line.

**Usage:**

    Install necessary libraries: Make sure to install the required dependencies, including cv2 (OpenCV) and numpy.
    Set up the camera: Configure the camera for the appropriate resolution (width, height).
    Define gesture threshold: Choose the threshold level to detect the height of the face for slide control.
    Prepare presentation images: Ensure the Presentation folder contains the images for the presentation.
    Run the application: Execute the Python script and use hand gestures in front of the camera to navigate through slides and activate the drawing mode.

**Hand gestures guide:**

    Swipe left with one finger raised to move to the previous slide.
    Swipe right with one finger raised to move to the next slide.
    Raise the index finger to draw on the slide during the drawing mode.
    Lower the index finger to stop drawing.
    Raise the index and middle fingers together to start a new annotation sequence.
    Lower the ring finger to undo the most recent annotation sequence.

**Note:** Remember to adjust the gesture threshold and other parameters as per your preferences and lighting conditions.

**Enjoy your interactive hand gesture-controlled presentations! 👋📊📚**
