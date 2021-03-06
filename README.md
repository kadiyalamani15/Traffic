# TRAFFIC  
  
### Problem Statement:
Analyzing Traffic video to extract vehicle count based on vehicle classification. Main focus: Analyzing the video, no matter what is the angle of the video.
  
#### Task 1:
How to classify vehicles  
  
#### Task 2:
Extract Vehicle Count
  
#### Task 3:
Vehicle count data as per lanes present in the video  
  
> Technology Used: Computer Vision (CV)  
> Mostly used Package: openCV  
> Skill Set required:
1. Image Processing  
2. Backend Development  
3. Frontend Development  
4. Cloud Deployment  


### Medium Articles  
1. [Vehicle Classification in Turning Movement Counts](https://medium.com/transportation-engineering-data-collection/vehicle-classification-in-turning-movement-counts-4ce6b59534fe)  
2. [Analyzing Issues in Vehicle Classification Solution](https://medium.com/@bhrigs/analyzing-issues-in-vehicle-classification-and-counting-solution-57f29a84ec9f)  
3. [Tutorial: Counting Road Traffic Capacity with OpenCV](https://medium.com/machine-learning-world/tutorial-counting-road-traffic-capacity-with-opencv-998580f1fbde)  
4. [Practical Image Process with OpenCV](https://towardsdatascience.com/practical-image-process-with-opencv-8405772c603e)  
5. [Detecting and Counting Objects with OpenCV](https://medium.com/analytics-vidhya/detecting-and-counting-objects-with-opencv-b0f59bc1e111)  
6. [Tutorial: Making Road Traffic Counting App based on Computer Vision and OpenCV](https://medium.com/machine-learning-world/tutorial-making-road-traffic-counting-app-based-on-computer-vision-and-opencv-166937911660)  
  
  
### Youtube Links  
1. [Classification and Specification of Vehicle](https://www.youtube.com/watch?v=MLR2wbmjRQE&feature=youtu.be)  
2. [vehicle counting and classification using image processing by opencv python](https://www.youtube.com/watch?v=ONgktXxGIJo) 
3. [Object tracking in video with OpenCV and Deep Learning](https://www.youtube.com/watch?v=19vaot75JCY)  
4. [Automated vehicle classification, tracking and speed estimation](https://youtu.be/MvPY1CBapE4)  
5. [Vehicle Counting and Classification](https://youtu.be/mcNPld9wsIo)  
6. [LANE VEHICLE COUNTING FROM A UAV](https://youtu.be/NmcIzqJK1-U)  
7. [TIC501 Pro: Reliable counting and classification of vehicles over several lanes - SICK AG](https://www.youtube.com/watch?v=uLsDljlwuak)  
8. [Counting and calculating the density of the Vehicles with OpenCV 4.0 Java](https://www.youtube.com/watch?v=92RTneVhRV4)   
9. [OpenCV Projects : Vehicle Classification OpenCV (python)](https://www.youtube.com/watch?v=cyNKepIPEP4)  
  
### Research Papers  
1. [Counting and CLassification of Highway Vehicles by Regression Analysis.pdf](https://github.com/kadiyalamani15/Traffic/blob/master/Traffic%20-%20Research%20Paper%20Project/07100903.pdf)  
2. [Video-Based Vehicle Counting Framework.pdf](https://github.com/kadiyalamani15/Traffic/blob/master/Traffic%20-%20Research%20Paper%20Project/08703814.pdf)  
3. [Robust Vehicle Counting with Severe Shadows and Occlusions.pdf](https://github.com/kadiyalamani15/Traffic/blob/master/Traffic%20-%20Research%20Paper%20Project/129780549.pdf)    
4. [Overview of Vehicle Detection and Classification.pdf](https://github.com/kadiyalamani15/Traffic/blob/master/Traffic%20-%20Research%20Paper%20Project/159127941.pdf)    
Vehicle detection and classification system can be used in the following applications:  
    * Transportation planning for traffic operation and pavement design (Avely et al., 2004). Differences in size, weight, and performance between light and heavy vehicle need to be considered during transportation planning.  
    * Vehicles’ data collection for safety evaluation purposes. Studies show high percentages of fatal accidents involved heavy vehicles (Avely et al., 2004).  
    * Road maintenance planning. Road wear is affected by weight of the vehicles and traffic flows (Hjort et al., 2008). Road with high traffic of heavy vehicles need to be maintained more frequently.    
    * Traffic management. Traffic congestion can be managed by allowing only light vehicles to travel on a particular road during peak hours.  

   A vehicle detection and classification system can be used by the road archi- tects. The system is able to provide the number of vehicles and their classes using a particular stretch of the road. Road wear and safety are affected by the number of vehicles and their classes using the road. A large number of vehicle using the road will cause the road to wear faster. Heavy vehicles will also accelerate road wear. Hence, road architects need to take these information into consideration during planning and design stages. A more durable pavement type can be chosen for road with a lot of heavy vehicles. More frequent road maintenance can also be planned.  
   
   Developing a Vehicle Detection and Classification System required three main components. There are detection algorithm, tracking and counting algorithm, and classification algorithm.  
   
   #### Vehicle Detection  
   There are many methods to detect vehicles. These methods can be categorized into intrusive and non-intrusive as described by Daubaras and Zilys (2012). An example of intrusive method is installation of inductive loop detector into the pavement surface. Non-intrusive methods can be further categorized into imaging and non-imaging. Examples of non-imaging methods include using infrared sensor, microwave radar, and ultrasonic sensors. On the other hand, imaging methods include any use of digital image camera. Imaging method is a more preferable method because this method cost the least among non-intrusive methods as reported by Sun et al. (2004).  

   #### Tracking And Counting
   Tracking of moving objects from video sequences are usually done by tracking blobs (Magee, 2004). Blobs are collections of pixels that are connected together in an image. Hence, contours found from vehicle detection algorithm in this project can be used to track moving vehicles. This is because basically contours define blobs. The following shows a simple tracking and counting algorithm:
    1. Capture current video sequences frame.
    2. Find all detected moving objects contours.
    3. Find nearest match of tracked object.
    4. If nearest match found, then update the tracked object. 5. Else create a new tracked object.
    6. Clean up tracked object list. Discard expired object.
    7. Increment vehicle count counter when a vehicle is detected.  
    
   #### Hardware and Software Used
   The vehicle detection and classification system consists of hardware and software components that process an input graphical signals such as video sequences from traffic surveillance camera into the number of vehicle and their type. The hardware required for this system includes a computer and a camera that are able to capture video sequences with at less 320x240 resolution at 25-30 frames per second (FPS). The software part of the system is developed using Microsoft Visual Studio with OpenCV library by IntelCorporation (2001).


5. [Feature Extraction Analysis, Techniques and Issues in Vehicle Types Recognition.pdf](https://github.com/kadiyalamani15/Traffic/blob/master/Traffic%20-%20Research%20Paper%20Project/188217040.pdf)  
6. [Moving Vehicle Detection for Measuring Traffic Count Using OpenCV.pdf](https://github.com/kadiyalamani15/Traffic/blob/master/Traffic%20-%20Research%20Paper%20Project/20131230030637936.pdf)  
7. [Vehicle Detection and Speed Estimation for Automated Traffic Surveillance Systems at Night time.pdf](https://github.com/kadiyalamani15/Traffic/blob/master/Traffic%20-%20Research%20Paper%20Project/212493711.pdf)  
8. [Vehicle counting system using optimized virtual loop method based on real time video.pdf](https://github.com/kadiyalamani15/Traffic/blob/master/Traffic%20-%20Research%20Paper%20Project/26779112.pdf)  
9. [Automated Vehicle counting and classification for traffic census.pdf](https://github.com/kadiyalamani15/Traffic/blob/master/Traffic%20-%20Research%20Paper%20Project/301109170.pdf)  
10. [Real-Time system based on feature extraction for vehicle detection and classification.pdf](https://github.com/kadiyalamani15/Traffic/blob/master/Traffic%20-%20Research%20Paper%20Project/5B1407617920-20Transport20and20Telecommunication20Journal5D20Real-Time20System20Based20on20Feature20Extraction20for20Vehicle20Detection20and20Classification.pdf)  
11. [Real-Time video surveillance system for traffic managmeent with background subtraction using codebook model and occlusion handling.pdf](https://github.com/kadiyalamani15/Traffic/blob/master/Traffic%20-%20Research%20Paper%20Project/5B1407617920-20Transport20and20Telecommunication20Journal5D20Real-Time20Video20Surveillance20System20for20Traffic20Management20with20Background20Subtraction20Using20Codebook20Model20and20Occlusion20Handling.pdf)  
12. [Automatic traffic surveillance using video tracking.pdf](https://github.com/kadiyalamani15/Traffic/blob/master/Traffic%20-%20Research%20Paper%20Project/82054378.pdf)  
13. [Vehicle classification framework: a comparative study.pdf](https://github.com/kadiyalamani15/Traffic/blob/master/Traffic%20-%20Research%20Paper%20Project/Ambardekar2014_Article_VehicleClassificationFramework.pdf)  
14. [Freight Analysis using YOLOv2.pdf](https://github.com/kadiyalamani15/Traffic/blob/master/Traffic%20-%20Research%20Paper%20Project/SSRN-id3420232.pdf)  
15. [A simple vehicle classification framework for wireless audio-sensor networks.pdf](https://github.com/kadiyalamani15/Traffic/blob/master/Traffic%20-%20Research%20Paper%20Project/httpwww_itl_waw_plczasopismajtit2008143.pdf)  
    Classification is naturally more challenging if there are multiple targets of various types (e.g., tanks, jeeps, other types of military vehicles, civilian vehicles, etc.). Furthermore, there may be a number of vehicles of the same type, e.g., tanks of a particular make. We define as classification the problem of identifying which class a vehicle belongs to. Identifying a particular vehicle goes one step further and is not within the scope of the current paper.  
16. [Fusion of Environmental Sension on PM 2.5 and Deep Learning on vehicle detecting for acquiring roadside PM 2.5 concentration Increments.pdf](https://github.com/kadiyalamani15/Traffic/blob/master/Traffic%20-%20Research%20Paper%20Project/sensors-20-04679.pdf)  
