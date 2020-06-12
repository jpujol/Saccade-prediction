# Saccade-prediction

Neural Network approach ----
A saccade is a fast eye movement that allows the change of visual fixation from one object of interest to another. These movements are characterized by very high angular velocity peaks that can reach up to 1,000º/s, making them as one of the fastest neuromotor activities in the human body. Modeling such a complex movement remains a challenge. Saccadic eye movements can be defined by initial and landing points, duration, amplitude, and velocity profile. The landing point is important as it defines the new fixation region and, therefore, the region of interest of the viewer. Its prediction may reduce problems caused by display-update latency in gaze-contingent systems that make real-time changes in the display based on eye tracking. The main contribution of this work is to propose the use of state-of-the-art machine learning techniques (i.e., Recurrent Neural Networks) for saccade landing point prediction in real-world scenarios. My method was evaluated using 220,000 saccades from 75 subjects acquired during viewing video from Hollywood movies. The results obtained using our proposed methods outperform existing approaches with improvements of up to 40% error reduction. The results show that dynamic temporal relationships exploited by Recurrent Neural Networks can improve the performance of traditional Feed Forward Neural Networks   

Taylor series approach ----
Gaze-contingent displays have been widely used in vision research and virtual reality applications. Due to data transmission, image processing, and display preparation, the time delay between the eye tracker and the monitor update may lead to a misalignment between the eye position and the image manipulation during eye movements. I propose a method to reduce the misalignment using a Taylor series to predict the saccadic eye movement. The proposed method was evaluated using two large datasets including 219,335 human saccades (collected with an EyeLink 1000 system, median 3°, 95% range 1° to 32°) and 21,844 monkey saccades (collected with a scleral search coil, median 2°, 95% range 1° to 9°). When assuming a 10-ms time delay, the prediction of saccade trajectories using the proposed method could reduce the misalignment greater than two state-of-the-art methods. The average error was about 0.93° for human saccades and 0.26° for monkey saccades. Our results suggest that this proposed saccade prediction method will create more accurate gaze-contingent displays.
