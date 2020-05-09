## Automated Pavement Distress Detection and Deterioration Analysis using Street View Map
Xu Lei1, Chenglong Liu2, Li Li1 and Guiping Wang  

**Reading Status:** Skimmed

### NSDB
#### Need
-  Detecting pavement distress require manual or semi-automated labor by trained technicials.  
-  Manual survey is labor-intensive and time-consuming.  
-  Subjectivity in survey process  
-  Need for well-trained personnel
#### Solution
-  Automate pavement distress detection using 2-RGB images with Deep Learning
-  Automate deterioration of distress given time
#### Differentiation
-  Can identify eight types of distresses
-  Dataset collected using Baidu API
-  Uses pre-trained Yolov3 for detection and identification
-  Uses three-level "GPS-Bounding box-SIFT" distress matching framework for tracking deterioration
#### Benefit
-  Yolov3 with high mAP of 88.3\% and AP of 80\%  
-  GPS records enabled producing a visualization map and plot of distresses through time
-  Baidu API is better than Google API for providing different views
#### Comments
-  Perspective is human-eye view perspective so measuring area of distress is not feasible
-  Explains well three different possible ways to detect pavement distress and highlights why use 2-RGB images instead
-  Excellent use of SIFT + RANSAC to track changes
-  Decision Tree for evaluating the distress deterioration at different times
-  Uses mean Euclidean distance (MEuD) and matching rate (MR) to determine whether the two distress are identical. 
