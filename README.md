# BarPath_Tracking
![Image](https://pic4.zhimg.com/v2-f991d9567a65c74ada7cf19c8f2d43b0_b.jpg)

![Image](https://pic4.zhimg.com/v2-221a1c9d7f34c2fbeb045041760b9804_b.jpg)      
_Take my favourite weightlifter Lu XiaoJun as an example_    
---   
## Description  
        
There are 9 different trackers you can choose to track the barbell path,including BOOSTING,MIL,KCF,TLD, MEDIANFLOW, GOTURN, Dlib_Tracker, CamShift and Template_Matching.Not only the barbell path,you can also use these trackers to track other object,like a car or anything else.The following are some of the comparison results.    

<img src="Result/avg_fps.svg">      
      
<img src="Result/fps.svg">      
      

## Requirements   
     
* OpenCV3
* dlib
* numpy
    
## Start Tracking    
Firstly You need to create a bounding box around the bar(or the obeject) to be tracked.Click the left mouse button to select the bounding box.Then press <kbd>Enter</kbd> to start the tracking.If you want to close the video,just press <kbd>Esc</kbd>.    


