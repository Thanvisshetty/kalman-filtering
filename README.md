# Kalman-Filtering
Kalman filtering is a mathematical algorithm that uses a series of measurements observed over time, containing statistical noise and other inaccuracies, to produce estimates of unknown variables that tend to be more precise than those based on a single measurement alone. It is widely used in control systems, navigation, and time series analysis2.

# Practical Applications of Kalman Filtering
•	Navigation and Control: Used in aerospace for trajectory estimation of aircraft and spacecraft.
•	Economics: Used in econometrics for signal extraction in time series analysis.
•	Robotics: Used for robotic motion planning and control.
•	Computer Vision: Used for tracking moving objects in video streams.

# why is it called kalman filtering
The Kalman filter is named after Rudolf E. Kálmán, a Hungarian-American engineer and mathematician who developed the theory behind it in the early 1960s. Although Peter Swerling had developed a similar algorithm earlier, Kálmán's work was more comprehensive and widely recognized2. His publication in a prestigious journal helped popularize the method, leading to it being named after him

# Difference Between Kalman Filtering and Gaussian Filtering
## Kalman Filtering:
* Uses a series of measurements over time to estimate the state of a system.
* Assumes that errors have a normal (Gaussian) distribution.
* Combines predictions and measurements to refine the state estimate.
## Gaussian Filtering:
* Focuses on estimating the probability distribution of a variable.
* Assumes that the underlying process is governed by Gaussian processes.
* Used in scenarios where the state of the system is not directly observable.
## Example:
Kalman Filter: Used in GPS navigation to estimate the position of a vehicle by combining noisy sensor data over time.
Gaussian Filter: Used in image processing to smooth out noise in an image by assuming the noise follows a Gaussian distribution
