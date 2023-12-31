# Autonomous_Navigation_ADAS

Demo Video:
Link1: Autonomous Vehicle ADAS Demo: https://youtu.be/-ZuUbB1JMvE  (Adaptive Cruise Control & Adaptive Steering Assist with gradual acceleration)


Link2: LiDAR localization view : https://youtu.be/a_JywLREhbo



Link3: Deployment of autonomous vehicle in IIT Hyderabad, India campus: https://www.linkedin.com/posts/tihan-iit-hyderabad_tihan-iithyderabad-innovatewithtihan-activity-7112009566434803712-SKUz?utm_source=share&utm_medium=member_ios


# The work is submitted in IEEE Transaction on Consumer Electronics. The corresponding code will be published soon after the publication of the paper.


The Code for LiDAR based autonomous Navigation including Adaptive Cruise control and Adaptive steering assist is coming soon. The complete Navigation stack includes:

1) Mapping Package: To create a map of an environment using LiDAR point cloud data and the map is stored in PCD file.
2) Localization Package: To localize the vehicle in real time by matching the input LiDAR point cloud on pcd (map) file, to determine its position and orientation. 
3) Obstacle detection Package: To detect all the obstacles in the region of interest and determine the distance of obstacle from the autonomous Vehicle.
4) Navigation Package: To navigate the autonomous vehicle with the synergistic control of adaptive cruise control and adaptive steering assist by integrating obstacle detection on LiDAR map based navigation.
