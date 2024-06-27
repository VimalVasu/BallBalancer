# BallBalancer
Camera-Motor-ROS mechanical platform for balancing a ball on a platform.  Uses OpenCV to detect the position of the ball via an overhead camera, and sends this data to 3 stepper motors which adjust the angles of the platform to let the ball fall to the set point.  Uses ROS topics to handle data communication between the camera and 3 stepper motors.
