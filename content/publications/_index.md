---
title: "Papers"
description: ""
---

# Publications

### 2024 

---
* **<font color="#FA8072">[S3 @ MobiCom] Scalable and Sustainable Video Analytics on Edge using Sensor Clustering</font>**\
**<u>Shubham Chaudhary</u>**, Arani Bhattacharya, Saket Anand, Aruna Balasubramanian\
<font color="#3498DB"> In Proceedings of the 15th ACM Wireless of the Students, by the Students, and for the Students Workshop (S3) in conjuction with the 30th Annual International Conference on Mobile Computing and Networking (MobiCom'24) to be held in Washington, D.C., USA </font><font style="float:right">**(Accepted)**</font><details> <summary>Abstract</summary><p align="justify">
        The proliferation of video analytics in applications like autonomous driving, traffic surveillance, and teleoperated vehicles requires on-premise (on edge) execution of deep learning models to meet latency requirements and curb bandwidth usage by limiting frequent offloading of inference tasks. However, constrained by the compute and power availability on the edge, a cheaper model is typically deployed. These shallower models have two major associated problems: 1) using the same model for all cameras/vehicles gives inconsistent accuracy, and 2) trained models are prone to data drift. In this work, we propose to address these problems using two strategies. The first strategy is to intelligently assign individual models to each camera/vehicle by clustering the ones with similar visual scenes to reduce the number of allocated models. Second, to circumvent the data drift, we retrain the model assigned to the cluster, which undergoes accuracy deviation.</p>
    </details>  


* **<font color="#FA8072">[COMPASS] Network Architecture Search for Sustainable Traffic Surveillance</font>**\
**<u>Shubham Chaudhary</u>**, Arani Bhattacharya\
<font color="#3498DB"> Poster in Doctoral Consortium at the 7th ACM SIGCAS/SIGCHI Conference on Computing and Sustainable Societies (COMPASS'24) held in Delhi, India </font><font style="float:right">**(Accepted)**</font>

* **<font color="#FA8072">[MM] COMPACT: Content-aware Multipath Live Video Streaming for Online Classes using Video Tiles </font>**\
**<u>Shubham Chaudhary</u>**, Navneet Mishra, Keshav Gambhir, Tanmay Rajore, Arani Bhattacharya, Mukulika
Maity\
<font color="#3498DB"> In the Proceedings of the 32nd ACM International Conference on Multimedia (MM'24) to be held in Melbourne, Australia </font><font style="float:right">**(Submitted)**</font>
<!-- <button style=
        "background-color: #82E0AA ; color: white;" name="pdfbutton"
        onclick="http://www.google.com">PDF</button>
<button style=
        "background-color: #F5B041 ; color: white;" name="pptbutton"
        onclick="http://www.google.com">PPT</button>
<button style=
        "background-color: #A569BD ; color: white;" name="codebutton"
        onclick="http://www.google.com">CODE</button>
        <details> <summary>Abstract</summary>
    |  | 
    | -------- |
    <p align="justify">
        This is the content of the collapsible section. You can include any Markdown-formatted text, lists, or code here.</p>
        </details>     -->
<!-- <br></br> -->

* **<font color="#FA8072">[ATC] TileClipper: Lightweight Selection of Regions of Interest from Videos for Traffic
Surveillance </font>**\
**<u>Shubham Chaudhary</u>**, Aryan Taneja, Anjali Singh, Purbasha Roy, Sohum Sikdar, Mukulika Maity, Arani
Bhattacharya\
<font color="#3498DB"> In the Proceedings of the 2024 USENIX Annual Technical Conference (ATC'24) held in Santa Clara, CA, USA </font>\
<button style=
        "background-color: #669900 ; color: white;" name="pdfbutton"
        onclick=" window.open('https://www.usenix.org/conference/atc24/presentation/chaudhary', '_blank'); return false;">Paper & Slides</button>
<button style=
        "background-color: #A569BD ; color: white;" name="codebutton"
        onclick=" window.open('https://github.com/shubhamchdhary/TileClipper', '_blank'); return false;">CODE</button><font style="float:right">**(Accepted)**</font>
        <details> <summary>Abstract</summary>
    <p align="justify">With traffic surveillance increasingly used thousands of cameras on roads send video feeds to cloud servers to run computer vision algorithms, requiring high bandwidth. State-of-the-art techniques reduce the bandwidth requirement by either sending a  limited number of frames/pixels/regions or relying on re-encoding the important parts of the video. This imposes significant overhead on both the camera side and server side compute as re-encoding is expensive.  In this work, we propose TileClipper, a system that utilizes tile sampling, where a limited number of rectangular areas within the frames, known as tiles, are sent to the server. TileClipper selects the tiles adaptively by utilizing its correlation with the tile bitrates. We evaluate TileClipper on different datasets having 55 videos in total to show that, on average, our technique reduces approx.22% of data sent to the cloud while providing a detection accuracy of 92% with minimal calibration and compute compared to prior works. We show real-time tile filtering of TileClipper even on cheap edge devices like Raspberry Pi 4 and nVidia Jetson Nano. We further create a live deployment of TileClipper to show that it provides over 87% detection accuracy and over 55% bandwidth savings.</p>
    </details>  
<!-- <br></br> -->

### 2023

---

* **<font color="#FA8072">[COMSNETS] NATIVE: Network Aggregation based Tiled Live Video Streaming </font>**\
Keshav Gambhir, Tanmay Rajore, **<u>Shubham Chaudhary</u>**, Taral Jain, Avishi Gupta, Mukulika Maity, Arani
Bhattacharya\
<font color="#3498DB"> Demo Paper in Proceedings of International Conference on COMmunication Systems & NETworkS (COMSNETS'23) held in Bangalore, India </font><font style="float:right">**(Published)**</font>\
<button style=
        "background-color: #669900 ; color: white;" name="codebutton"
        onclick=" window.open('https://ieeexplore.ieee.org/abstract/document/10041371', '_blank'); return false;">Paper</button><details> <summary>Abstract</summary>    
    <p align="justify">The COVID-19 pandemic has forced most interactions to move to online space, starting from online lectures, conferences in hybrid mode, and work-from-home office works. Hence, it is essential for live video streaming to be reliable and provide a good quality of experience (QoE) to users. However, in large sections of the world, the cellular network is not reliable enough to be used for online participation in such events. To quantify this problem, we first measure the QoE in terms oflag, video resolution, and dropped calls on a popular video conferencing platform Google Meet over three different cellular ISPs in New Delhi, India. We observe significantly worse quality of experience metrics compared to a study recently performed in the US. To mitigate this problem, we propose NATIVE (Network Aggregation-based Tiled lIve Video strEaming), a system of aggregating the cellular network connectivity using a secondary or helper device in the vicinity trusted by the user. The implementation of NATIVE uses tiled encoding of video, where the video frames are divided into rectangular units known as tiles. All the tiles are divided into two subsets which are scheduled independently via the available network interfaces depending on its importance. The receiver device receives video segments from the two network paths and stitches back the tiles in them to play. We show the demo of NATIVE using two laptops and a cloud server where the server acts as a streamer
        </details>
<!-- <br></br> -->

### 2022

---

* **<font color="#FA8072">[COMSNETS] VISTA: Fast and Efficient Traffic Surveillance by Tile Sampling </font>**\
**<u>Shubham Chaudhary</u>**, Aryan Taneja, Anjali Singh, Mukulika Maity, Arani Bhattacharya\
<font color="#3498DB"> In Proceedings of the Workshop on Last-mile Challenges and Standardization Opportunities in Smart Infrastructure (LastMileS) in conjunction with International Conference on COMmunication Systems & NETworkS (COMSNETS'22) held in Bangalore, India </font><font style="float:right">**(Accepted)**</font>\
<font color="ffa833">*Best Paper Award*</font>

[Google Scholar](https://scholar.google.com/citations?user=zjqLCUsAAAAJ&hl=en)

--- 

# Patents
* **<font color='#FA8072'>[Indian Patent] Method And System Facilitating Data Optimization In A Data Transmission Process </font>**\
**<u>Shubham Chaudhary</u>**, Aryan Taneja, Anjali Singh, Arani Bhattacharya, Mukulika Maity\
<font color="#3498DB"> Application Number: 202211028440 </font>