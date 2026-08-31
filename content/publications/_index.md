---
title: "Papers"
description: ""
---

# Patents
* **<p align="justify"><font color='#FA8072'>[Indian Patent] Method And System Facilitating Data Optimization In A Data Transmission Process </font>**\
**<u>Shubham Chaudhary</u>**, Aryan Taneja, Anjali Singh, Arani Bhattacharya, Mukulika Maity\
<font color="#3498DB"> Application Number: 202211028440 </font></p>
---

# Publications
[Google Scholar](https://scholar.google.com/citations?user=zjqLCUsAAAAJ&hl=en)

### 2026
---
* **<p align="justify"><font color="#FA8072">[PHD THESIS] Lightweight optimization strategies for modern video applications over wireless networks</font>**\
**<u>Shubham Chaudhary</u>**\
<button style=
        "background-color: #669900 ; color: white;" name="pdfbutton"
        onclick=" window.open('https://repository.iiitd.edu.in/xmlui/handle/123456789/2009', '_blank'); return false;">Thesis</button>
        <details><summary>Abstract</summary><p align="justify">
        The various video applications running over wireless networks face a common set of challenges, such as inconsistent bandwidth, high network variability, and sudden latency spikes. Considering such constraints, this thesis explores the possible strategies and design choices for developing data-intensive video applications such as real-time traffic surveillance, live video streaming, and cloud-assisted autonomous driving. Our focus is primarily on two techniques across three distinct video-streaming applications. The first technique is the intelligent use of tiled encoding available in modern video codecs, where the encoded video has independent rectangular spatial regions that can be manipulated in real time without re-encoding. The second technique is to develop data filtering strategies to minimize ingestion costs by pruning extraneous information. In traffic surveillance, cameras stream video to servers for computer vision algorithms, consuming significant bandwidth. To reduce bandwidth usage, we use tile sampling to select spatial regions of frames that contain only moving objects, since the rest of the frame mostly has static backgrounds, such as the sky and buildings. To select such tiles, we propose an adaptive tile selection algorithm that samples only tiles with moving objects by leveraging their correlation with tile bitrates. Our evaluations across different lighting, weather, and traffic conditions, both using benchmark videos and a live deployment, show improved accuracy, reduced bandwidth usage, and lower overhead than existing systems. For live streaming, we propose using the network interface of a nearby helper device to get an aggregated bandwidth. To stream videos, we design a tile-level aggregation strategy that partitions tiles into two subsets and schedules them independently across available network interfaces, based on their importance. We demonstrate, through extensive experiments, that such an aggregation strategy provides better QoE than conventional multipath strategies. Lastly, we address the high data ingestion cost in self-driving cars. Autonomous vehicles rely on compressed models whose accuracy degrades over time as the distribution of real-world test data changes, requiring frequent retraining on a server. This necessitates limiting the number of selected training frames to minimize the end-to-end delay in obtaining the retrained model without impairing post-training accuracy. We sample only the most useful frames and adaptively encode them into a video based on the network bandwidth. Our lightweight sampling strategy seamlessly integrates with the existing workflow, achieving superior accuracy while minimizing update delay compared to baseline strategies across different network conditions.</p>
        </details></p>

* **<p align="justify"><font color="#FA8072">[ACM TOMM] Tile-level Multipath Content-aware Live Video Streaming</font>**\
**<u>Shubham Chaudhary</u>**, Aruba Sood, Navneet Mishra, Keshav Gambhir, Arani Bhattacharya, Mukulika Maity\
<font color="#3498DB"> In the ACM Transactions on Multimedia Computing, Communications, and Applications (TOMM) </font>\
<button style=
        "background-color: #669900 ; color: white;" name="pdfbutton"
        onclick=" window.open('https://dl.acm.org/doi/10.1145/3833392', '_blank'); return false;">Paper</button>
        <details><summary>Abstract</summary><p align="justify">
        The growing popularity of live streaming applications even in remote areas underscores the need for a high-quality and seamless experience. However, live streaming is a bandwidth-hungry application that challenges the current cellular networks to maintain consistent bandwidth and latency. To address these shortcomings, we propose using the collaboration of multiple devices with their individual cellular networks to support live video streaming. Prior approaches on multipath streaming, however, lead to high end-to-end latencies due to head-of-line blocking when used with live video streaming. To mitigate this problem, we design a content-aware system COMPACT that splits the video into foreground and background using video tiles (independently encoded spatial blocks) and streams them over different paths. COMPACT depends on its scheduler, which exhaustively searches for the best quality based on network estimates. We implement and validate COMPACT on two transport protocols: SCTP and QUIC. We extensively evaluate our system using network traces while walking and traveling in a bus or car for three live streaming applications: online classes, live sports, and live news. For the online class, we find that compared to the single path, COMPACT manages to reduce the median stall and E2E lag by 70.6% and 28.57%, and the tail stall and lag by 83.9% and ≈ 80% on a bus trace. We note that COMPACT performs better than the baselines, even for live news and live sports. We further performed a live experiment to test COMPACT on an actual cellular network, and show that it works well in practice.</p>
        </details></p>

### 2025
---
<!-- * **<p align="justify"><font color="#FA8072">[BuildSys] Pipette: Adaptive Selection of Relevant Samples for Continual Learning in Autonomous Vehicles </font>**\
**<u>Shubham Chaudhary</u>**, Saket Anand, Aruna Balasubramanian, Arani Bhattacharya\
<font color="#3498DB"> In the Proceedings of the 12th ACM International Conference on Systems for Energy-Efficient Buildings, Cities, and Transportation (BuildSys'25) to be held in Golden, Colorado, USA. </font><font style="float:right">**(Submitted)**</font>
<!-- \ -->
<!-- <button style=
        "background-color: #669900 ; color: white;" name="pdfbutton"
        onclick=" window.open('https://dl.acm.org/doi/10.1145/3712676.3714451', '_blank'); return false;">Paper</button>
<button style=
        "background-color: #A569BD ; color: white;" name="codebutton"
        onclick=" window.open('https://github.com/shubhamchdhary/COMPACT', '_blank'); return false;">Code</button>
        <details>
        <summary>Abstract</summary><p align="justify">
        Add here</p>
        </details></p>  -->

* **<p align="justify"><font color="#FA8072">[MMSys] COMPACT: Content-aware Multipath Live Video Streaming for Online Classes using Video Tiles </font>**\
**<u>Shubham Chaudhary</u>**, Navneet Mishra, Keshav Gambhir, Tanmay Rajore, Arani Bhattacharya, Mukulika
Maity\
<font color="#3498DB"> In the Proceedings of the 16th ACM Multimedia Systems Conference (MMSys’25) held in Stellenbosch, South Africa. </font>\
<button style=
        "background-color: #669900 ; color: white;" name="pdfbutton"
        onclick=" window.open('https://dl.acm.org/doi/10.1145/3712676.3714451', '_blank'); return false;">Paper</button>
<button style=
        "background-color: #A569BD ; color: white;" name="codebutton"
        onclick=" window.open('https://github.com/shubhamchdhary/COMPACT', '_blank'); return false;">Code</button>
        <details>
        <summary>Abstract</summary><p align="justify">
        The growing popularity of live online classes, even in remote areas, stresses the need for a good and seamless quality of experience to enhance learning. However, these bandwidth-hungry applications challenge the current cellular networks to maintain consistent bandwidth and latency. In this work, we, therefore, propose using the collaboration of multiple devices with their individual cellular networks to support such live video streaming. We design a content-aware system COMPACT that splits video into foreground and background using video tiles (independently encoded spatial blocks) and streams them over different paths. COMPACT depends on its scheduler, which exhaustively searches for the best quality based on the network estimates. We extensively evaluate our system using network traces while walking and traveling on the bus or car. Compared to the single path, COMPACT manages to reduce the median stall and E2E lag by 70.6% and 28.57%, and the tail stall and lag by 83.9% and ≈ 80% on a bus trace. Furthermore, we performed a live experiment to test COMPACT on the actual cellular network.</p>
        </details></p>  

### 2024 

---
* **<p align="justify"><font color="#FA8072">[S3 @ MobiCom] Scalable and Sustainable Video Analytics on Edge using Sensor Clustering</font>**\
**<u>Shubham Chaudhary</u>**, Arani Bhattacharya, Saket Anand, Aruna Balasubramanian\
<font color="#3498DB"> In Proceedings of the 15th ACM Wireless of the Students, by the Students, and for the Students Workshop (S3) in conjuction with the 30th Annual International Conference on Mobile Computing and Networking (MobiCom'24) held in Washington, D.C., USA </font>\
<button style=
        "background-color: #669900 ; color: white;" name="pdfbutton"
        onclick=" window.open('https://dl.acm.org/doi/10.1145/3636534.3695902', '_blank'); return false;">Paper</button>
        <details> <summary>Abstract</summary><p align="justify">
        The proliferation of video analytics in applications like autonomous driving, traffic surveillance, and teleoperated vehicles requires on-premise (on edge) execution of deep learning models to meet latency requirements and curb bandwidth usage by limiting frequent offloading of inference tasks. However, constrained by the compute and power availability on the edge, a cheaper model is typically deployed. These shallower models have two major associated problems: 1) using the same model for all cameras/vehicles gives inconsistent accuracy, and 2) trained models are prone to data drift. In this work, we propose to address these problems using two strategies. The first strategy is to intelligently assign individual models to each camera/vehicle by clustering the ones with similar visual scenes to reduce the number of allocated models. Second, to circumvent the data drift, we retrain the model assigned to the cluster, which undergoes accuracy deviation.</p>
        </details></p>  


* **<p align="justify"><font color="#FA8072">[COMPASS] Network Architecture Search for Sustainable Traffic Surveillance</font>**\
**<u>Shubham Chaudhary</u>**, Arani Bhattacharya\
<font color="#3498DB"> Poster in Doctoral Consortium at the 7th ACM SIGCAS/SIGCHI Conference on Computing and Sustainable Societies (COMPASS'24) held in Delhi, India </font></p>

* **<p align="justify"><font color="#FA8072">[ATC] TileClipper: Lightweight Selection of Regions of Interest from Videos for Traffic
Surveillance </font>**\
**<u>Shubham Chaudhary</u>**, Aryan Taneja, Anjali Singh, Purbasha Roy, Sohum Sikdar, Mukulika Maity, Arani
Bhattacharya\
<font color="#3498DB"> In the Proceedings of the 2024 USENIX Annual Technical Conference (ATC'24) held in Santa Clara, CA, USA </font>\
<button style=
        "background-color: #669900 ; color: white;" name="pdfbutton"
        onclick=" window.open('https://www.usenix.org/conference/atc24/presentation/chaudhary', '_blank'); return false;">Paper & Slides</button>
<button style=
        "background-color: #ed3d17 ; color: white;" name="pdfbutton"
        onclick=" window.open('https://www.youtube.com/watch?v=ZFhBqa0bQIs', '_blank'); return false;">Video</button>
<button style=
        "background-color: #A569BD ; color: white;" name="codebutton"
        onclick=" window.open('https://github.com/shubhamchdhary/TileClipper', '_blank'); return false;">Code</button>
        <details> <summary>Abstract</summary>
    <p align="justify">With traffic surveillance increasingly used thousands of cameras on roads send video feeds to cloud servers to run computer vision algorithms, requiring high bandwidth. State-of-the-art techniques reduce the bandwidth requirement by either sending a  limited number of frames/pixels/regions or relying on re-encoding the important parts of the video. This imposes significant overhead on both the camera side and server side compute as re-encoding is expensive.  In this work, we propose TileClipper, a system that utilizes tile sampling, where a limited number of rectangular areas within the frames, known as tiles, are sent to the server. TileClipper selects the tiles adaptively by utilizing its correlation with the tile bitrates. We evaluate TileClipper on different datasets having 55 videos in total to show that, on average, our technique reduces approx.22% of data sent to the cloud while providing a detection accuracy of 92% with minimal calibration and compute compared to prior works. We show real-time tile filtering of TileClipper even on cheap edge devices like Raspberry Pi 4 and nVidia Jetson Nano. We further create a live deployment of TileClipper to show that it provides over 87% detection accuracy and over 55% bandwidth savings.</p>
    </details></p>
<!-- <br></br> -->

### 2023

---

* **<p align="justify"><font color="#FA8072">[COMSNETS] NATIVE: Network Aggregation based Tiled Live Video Streaming </font>**\
Keshav Gambhir, Tanmay Rajore, **<u>Shubham Chaudhary</u>**, Taral Jain, Avishi Gupta, Mukulika Maity, Arani
Bhattacharya\
<font color="#3498DB"> Demo Paper in Proceedings of International Conference on COMmunication Systems & NETworkS (COMSNETS'23) held in Bangalore, India </font>\
<button style=
        "background-color: #669900 ; color: white;" name="codebutton"
        onclick=" window.open('https://ieeexplore.ieee.org/abstract/document/10041371', '_blank'); return false;">Paper</button><details> <summary>Abstract</summary>    
    <p align="justify">The COVID-19 pandemic has forced most interactions to move to online space, starting from online lectures, conferences in hybrid mode, and work-from-home office works. Hence, it is essential for live video streaming to be reliable and provide a good quality of experience (QoE) to users. However, in large sections of the world, the cellular network is not reliable enough to be used for online participation in such events. To quantify this problem, we first measure the QoE in terms oflag, video resolution, and dropped calls on a popular video conferencing platform Google Meet over three different cellular ISPs in New Delhi, India. We observe significantly worse quality of experience metrics compared to a study recently performed in the US. To mitigate this problem, we propose NATIVE (Network Aggregation-based Tiled lIve Video strEaming), a system of aggregating the cellular network connectivity using a secondary or helper device in the vicinity trusted by the user. The implementation of NATIVE uses tiled encoding of video, where the video frames are divided into rectangular units known as tiles. All the tiles are divided into two subsets which are scheduled independently via the available network interfaces depending on its importance. The receiver device receives video segments from the two network paths and stitches back the tiles in them to play. We show the demo of NATIVE using two laptops and a cloud server where the server acts as a streamer
        </details></p>
<!-- <br></br> -->

### 2022

---

* **<p align="justify"><font color="#FA8072">[COMSNETS] VISTA: Fast and Efficient Traffic Surveillance by Tile Sampling </font>**\
**<u>Shubham Chaudhary</u>**, Aryan Taneja, Anjali Singh, Mukulika Maity, Arani Bhattacharya\
<font color="#3498DB"> In Proceedings of the Workshop on Last-mile Challenges and Standardization Opportunities in Smart Infrastructure (LastMileS) in conjunction with International Conference on COMmunication Systems & NETworkS (COMSNETS'22) held in Bangalore, India </font>\
<font color="ffa833">*Best Paper Award*</font></p>

<!-- [Google Scholar](https://scholar.google.com/citations?user=zjqLCUsAAAAJ&hl=en) -->

--- 

<!-- # Patents
* **<p align="justify"><font color='#FA8072'>[Indian Patent] Method And System Facilitating Data Optimization In A Data Transmission Process </font>**\
**<u>Shubham Chaudhary</u>**, Aryan Taneja, Anjali Singh, Arani Bhattacharya, Mukulika Maity\
<font color="#3498DB"> Application Number: 202211028440 </font></p> -->