# fixation_filter
A fixation filter for Gazepoint GP3 HD eyetracker

The fixation logic follows the dispersion rule, if the recorded gaze points are within 1 degree gaze angle and it lasts for 100ms it is considered as one fixation. 

The Gazepoint GP3 HD fixation filter cannot discern micro-saccades and it leads to problems such as recording a 10 second long fixation as below. 

![fixdur](https://user-images.githubusercontent.com/64123849/235407115-8e432609-6f9b-4c3f-8e50-5858332f0f7e.png)

Fixation Duration Recorded with Gazepoint GP3 HD


![fixdur2](https://user-images.githubusercontent.com/64123849/235407244-8fbec020-8213-41b3-b7d8-14c3e2564899.png)

Fixation Duration Filtered with this filter. 
