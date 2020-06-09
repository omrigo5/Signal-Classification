# Signal-Classification
This work was prepared as a final project of a course completed in the Weizmann Institute of Science during my PhD studies: Practical Deep Learning for Science” by Prof. Eilam Gross.  
Goal: Demonstrate remote optical eavesdroping.  
Such a model could be useful for recording a meeting which takes place in an isolated building for example. One can record the vibrations of the windows (or any other nearby object) and reconstruct the audio signal.
![](https://github.com/omrigo5/Signal-Classification/blob/master/objective.jpg)
There are several challeges in executing this goal:  
-	Audio frequencies varies between 20 Hz to 20,000 Hz, which requires very fast sampling rate ( 20,000 Hz signals correspond to sampling of 50μs) with "tons" of data to record 
-	Probably low SNR (Signal to Noise ratio) 
-	An unknown transmission of the window and setup
![](https://github.com/omrigo5/Signal-Classification/blob/master/Lock-in.png?raw=true)
