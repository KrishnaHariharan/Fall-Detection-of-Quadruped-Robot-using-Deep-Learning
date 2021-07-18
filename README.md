# Fall-Detection-of-Quadruped-Robot-using-Deep-Learning
There are many mobile robots designed and developed over the decade for doing specific tasks such as transportation, carrying loads, etc. but when it comes to traverse in rough terrain and weather conditions the design of robot mimicking the gait pattern of animals have proven to be versatile, robust, and beneficial which is known as a quadruped robot. This robot have the capability of dynamic walking pattern which can be obtained using various actuation methods such as pneumatic, hydraulic as well as electric actuations.
<br />
<br />
They are mainly used in applications such as military applications, space explorations and for industrial purposes. When traversing in rough surfaces sometimes the quadruped robot may become unstable due to external weather conditions and other factors and may tend to fall or tilt position. This may go unnoticed if there is no proper feedback communication with the robot and that there is no or less chance in detecting its state.
<br />
<br />
In our research paper we aim to find out the state of the quadruped robot using neural networks architecture so that necessary actions could be taken earlier. Our main objective is to collect the raw data attached with the robot from the proprioceptive sensors and analyze the signal coming from the sensors to detect the difference in pattern between walking and falling. The proprioceptive sensors used are accelerometers, magnetometer sensors and gyroscope sensors.
<br />
<br />
A neural network is trained based on the data from the sensors and is used to classify different stages of the quadruped robot for fall detection. The input to neural network is fed as a Continuous wavelet transform (CWT). Many such images with different patterns of the quadruped robot are given to the neural networks to train the model for good accuracy, then the state of the robot is classified as idle state, tilt state, walking state and fall state
<br />
<br />
Research Gap:

<br />
<br />
The research mainly focused on improving the stability of the quadruped robot to enable it to gait in rough and extreme conditions. For this purpose, many algorithms such as Reinforcement learning, Curriculum learning, Central pattern generator algorithms are used. The literatures focused on gait planning of the robot using neural networks and machine learning algorithms where the system is trained to adapt and generate gait patterns by itself to the changing external environmental conditions.
<br />
<br />
Though there are many research papers that focused on the gait and trot pattern of the quadruped robot, there are very few papers that addressed the fall factor that the quadruped robot might go through. Researchers in ETH Zurich, has developed quadruped robot that can come out of the fall by itself using reinforcement learning. But there are no papers that researched on detecting the fall of the quadruped robot using proprioceptive sensors.
<br />
<br />
With lot of research focusing on the gait and trot pattern of the quadruped robot, they have reached a point where they are potentially used in industries for reading gauge values and detect gas leakage. They are used in industries and that too in remote places of industries, but there is no system developed to detect the fall of the quadruped robot

<br />
<br />
Objective:

<br />
<br />
To obtain various data from the proprioceptive sensors accelerometer, magnetometer and gyroscope that are planted on the quadruped robot and then to analyze the signal from the robot to study the difference in pattern of the signals for each conditions and then to identify the state of the big dog by training a neural network model by providing the signal from sensor in the form of continuous wavelet transform (CWT) as input to the model and classify the signals for fall detection.
<br />
<br />
To obtain the signal from the sensor of the required information only and to avoid the unwanted noise and other signals, use of filters are carried out to provide a clear information of the waveforms to the neural network model. So we aim at finding out the state of the quadruped robot using machine learning approach and to monitor the robot continuously so that in case of a fall or tilt from its normal position is detected , measures can be taken at an earlier stage possible to avoid further damage and save cost of repair and time. We also aim to study the performance and accuracy of our neural network model in detecting the fall of the quadruped robot.
