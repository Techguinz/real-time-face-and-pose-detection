# eal-time-face-and-pose-detection-program
communicates with Unity via a TCP connection. It uses computer vision techniques to detect facial landmarks, eyes, and mouth features, stabilize their movements, and send this data to Unity for 3D model animation or interaction.


1. Imports Necessary Libraries
cv2 and mediapipe: For camera input and real-time facial landmark detection.
numpy: For mathematical operations.
socket: To establish TCP communication with Unity.
Custom modules:
FaceMeshDetector: Detects facial landmarks.
PoseEstimator: Calculates head pose (roll, pitch, yaw).
Stabilizer: Smooths noisy head/eye/mouth position values.
FacialFeatures: Detects eye, iris, and mouth properties.
Install required libraries (opencv-python, mediapipe, etc.).
