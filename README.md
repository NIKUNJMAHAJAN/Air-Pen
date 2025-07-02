# Air-Pen
The Air Marker is a motion-based input device that allows users to draw letters in the air, which are then recognized and displayed using an IMU sensor and machine learning. It captures real-time motion data—such as acceleration and angular velocity—as the user moves the device to form characters. This data is then preprocessed and passed into a trained ML model that classifies the motion pattern into letters.

The system involves both hardware and software integration. A microcontroller is connected to the IMU sensor, which tracks the user’s hand movements. Once data is collected, it's cleaned and labeled to train a machine learning model (e.g., decision tree, SVM, or neural network). The trained model is then embedded into the system to enable live predictions of letters as users "write" in the air.

The final output is displayed on a screen or console, providing real-time feedback. The entire setup enables virtual writing without any physical surface, opening up possibilities for innovative human-computer interactions.

Potential applications include:
* Assistive technologies for individuals with disabilities
* Augmented and Virtual Reality for gesture-based inputs
* Educational tools for interactive learning
* Touchless input systems in hygiene-sensitive environments
* This project demonstrates the practical combination of sensor data processing, embedded systems, and AI-based classification in creating a novel input method.
