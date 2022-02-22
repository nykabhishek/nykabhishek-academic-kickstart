---
title: Infrastructure Enabled Autonomy (IEA)
summary: "The objective of this project was to develop a distributed intelligence architecture for Connected Autonomous Vehicles (CAV) by offloading core computational functionalities to the infrastructure. I set up the Vehicle-to-Infrastructure (V2I) and Infrastructure-to-Infrastructure (I2I) communication network using DSRC and built software stacks on smart infrastructures for object detection, tracking, semantic segmentation, and localization. Further, I calibrated the cameras and sensor systems using OpenCV and developed SLAM capabilities for RSUs by fusing IMU, camera, GPS/RTK, and odometry data using estimation filters (like Monte-Carlo and Extended Kalman Filters (EKF)) for autonomous navigation of a Lincoln MKZ vehicle."
tags:
- Autonomous Vehicles
- Computer Vision
- Deep Learning
- Sensor Fusion
date: "2017-08-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by Autonomous Systems Laboratory
  focal_point: Smart

links:
- icon: ieee
  icon_pack: ai
  name: Publication
  url: https://ieeexplore.ieee.org/abstract/document/8916896
- icon: arxiv
  icon_pack: ai
  name: Article
  url: https://arxiv.org/abs/1802.01787
- icon: linkedin
  icon_pack: fab
  name: Follow
  url: https://www.linkedin.com/in/nykabhishek/
url_code: ""
url_pdf: ""
url_slides: ""
url_video: "https://www.youtube.com/watch?v=jC9_wJNKgvk"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

<p>
    <b>Location:</b> <a href="https://rellis.tamus.edu/" target="_blank">The Rellis campus</a>, Texas A&M University - College Station, TX
    <b>Collaborators:</b> <a href="https://cast.tamu.edu/" target="_blank">CAST Program</a>
</p>

<h4> <b>Videos:</b> </h4>
<p>
    <iframe width="720" height="405" src="https://www.youtube.com/embed/s4xNCPnUPRg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>
<p>
    <iframe width="720" height="405" src="https://www.youtube.com/embed/eOoPIvJhj3k" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>
<p>
    <iframe width="720" height="405" src="https://www.youtube.com/embed/iMSxPE9c2QQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>
<p>
    <iframe width="720" height="405" src="https://www.youtube.com/embed/7MCkzDjaPPY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>
<p>
    <iframe width="720" height="405" src="https://www.youtube.com/embed/X9t4WEsonf0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>

<p style="text-align:justify;">
    <b>Abstract:</b>
    IEA is a new paradigm in Autonomous Vehicle technology that looks at offloading the core computational capabilities of awareness generation and path planning from the vehicle out onto Smart Roadside Units equipped with various sensors. Through this distributed setup IEA provides a solution of shared liabilities by transferring the primary responsibility of localization from vehicle to infrastructure which in-turn enables of greater situational awareness of the area under the purview of IEA. IEA architecture is deployed on specific sections of roads or special traffic corridors by installing Road-Side Units (RSU) on either side of the road. These RSUs are fitted with multi-sensor smart packs (MSSP) containing sensors required for localizing vehicles. These MSSPs monitor the vehicles in the section of the roads under the purview of IEA and aid in generating the situational awareness which can be transmitted to the vehicles subscribing to this information. 
    <br>
    <br>
    MSSP includes several sensors that carry-out specific individual tasks and as a whole aid in generating the localization information. For example, cameras installed on the RSUs as a part of the MSSP are used to monitor traffic by identifying and locating all the objects of interest in the traffic corridor. MSSPs are installed with special SmartConnect devices, whose function is to establish wireless connectivity between MSSPs and the vehicles subscribing to its information and thus enabling transmission of information necessary for its localization. The SmartConnect devices are communication medium agnostic and modular so that they can be easily substituted by newer technologies.
</p>

<p>
    <b>Referances:</b>
    <ol start="1">
        <li>Nayak, A., Chour, K., Marr, T., Ravipati, D., Dey, S., Gautam, A., ... & Rathinam, S. (2018). A distributed hybrid hardware-in-the-loop simulation framework for infrastructure enabled autonomy. arXiv preprint arXiv:1802.01787.</li>
        <li>Ravipati, D., Chour, K., Nayak, A., Marr, T., Dey, S., Gautam, A., ... & Swaminathan, G. (2019, October). Vision Based Localization for Infrastructure Enabled Autonomy. In 2019 IEEE Intelligent Transportation Systems Conference (ITSC) (pp. 1638-1643). IEEE.</li>
        <li>Gopalswamy, S., & Rathinam, S. (2018, June). Infrastructure enabled autonomy: A distributed intelligence architecture for autonomous vehicles. In 2018 IEEE Intelligent Vehicles Symposium (IV) (pp. 986-992). IEEE.</li>
    </ol>
</p>
