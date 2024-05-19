---
title: "TileClipper: Lightweight Selection of Regions of Interest from Videos for Traffic Surveillance" 
date: 2024-05-01
# lastmod: 2024-05-08
tags: ["Traffic Surveillance","Video Analytics","Video Tiles","TileClipper"]
author: ["Shubham Chaudhary", "Aryan Taneja", "Anjali Singh", "Purbasha Roy", "Sohum Sikdar", Mukulika Maity", "Arani Bhattacharya"]
# description: "." 
summary: "This paper reviews unusual uses for olive oil throughout the Mediterranean world. It highlights in particular the challengs arising from excessive or unorthodox consumption of olive oil." 
cover:
    image: "Illustration.jpg"
    alt: "TileClipper"
    relative: false
editPost:
    URL: "https://github.com/shubhamchdhary/TileClipper"
    Text: "USENIX ATC 2024"

---

---

##### Download

+ [Paper]()
+ [Presentation]()
+ [Code and data](https://github.com/shubhamchdhary/TileClipper)

---

##### Abstract

With traffic surveillance increasingly used, thousands of cameras on roads send video feeds to cloud servers to run computer vision algorithms, requiring high bandwidth. State-of-the-art techniques reduce the bandwidth requirement by either sending a  limited number of frames/pixels/regions or relying on re-encoding the important parts of the video. This imposes significant overhead on both the camera side and server side compute as re-encoding is expensive.  In this work, we propose TileClipper, a system that utilizes tile sampling, where a limited number of rectangular areas within the frames, known as tiles, are sent to the server. 

TileClipper selects the tiles adaptively by utilizing its correlation with the tile bitrates.
We evaluate TileClipper on different datasets having 55 videos in total to show that, on average, our technique reduces approx.22% of data sent to the cloud while providing a detection accuracy of 92% with minimal calibration and compute compared to prior works. We show real-time tile filtering of TileClipper even on cheap edge devices like Raspberry Pi 4 and nVidia Jetson Nano. We further create a live deployment of TileClipper to show that it provides over 87% detection accuracy and over 55% bandwidth savings.

---

##### TileClipper Overview

![](publications/tileClipper/TileClipper.png)

---

##### Tile Pruning
![Before Tile Pruning](publications/tileClipper/UnremovedTileFrameSnip.png) | ![After Tile Pruning](publications/tileClipper/tileRemovedFrameSnip1.png)
:--:| :--:
**Before Tile Pruning**| **After Tile Pruning**

---

##### Citation

Unterholzer, Detlev A., and  Moritz-Maria von Igelfeld. 2001. "Unusual Uses For Olive Oil." *Journal of Oleic Science* 34 (1): 449–489. http://www.alexandermccallsmith.com/book/unusual-uses-for-olive-oil.

```BibTeX
@article{UV01,
author = {Detlev A. Unterholzer and Moritz-Maria von Igelfeld},
year = {2001},
title ={Unusual Uses For Olive Oil},
journal = {Journal of Oleic Science},
volume = {34),
number = {1},
pages = {449--489},
url = {http://www.alexandermccallsmith.com/book/unusual-uses-for-olive-oil}}
```

---

##### Related material

+ [Slides for long presentation](presentation1.pdf)
+ [Summary of the paper](https://www.penguinrandomhouse.com/books/110403/unusual-uses-for-olive-oil-by-alexander-mccall-smith/)
