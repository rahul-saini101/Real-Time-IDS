# Real Time Intrusion Detection System

## Abstract
With the advent of new IEEE 802.11ax (WiFi 6) devices, enabling security is a priority. Since previous versions were found to have security vulnerabilities, to fix the most common security flaws, the WiFi Protected Access 3 (WPA3) got introduced. Although WPA3 is an improvement over its predecessor in terms of security, recently it was found that WPA3 has a few security vulnerabilities as well. In this paper, we have mentioned the previously known vulnerabilities in WPA3 and WPA2. In addition to that, we have created our own dataset based on WPA3 attacks (Section \ref{attacks}). We have proposed a two-stage solution for the detection of an intrusion in the network. The two-stage approach will help ease computational processing burden of an AP and WLAN Controller. First, AP will perform a lightweight simple operation for some duration (say 500ms) at certain time interval. Upon discovering any abnormality in the flow of traffic an ML-based solution at the controller will detect the type of attack. Our approach is to utilize resources on AP as well as the back-end controller with certain level of optimization. We have achieved over 99\% accuracy in attack detection using an ML-based solution. We have also publicly provided our code and dataset for the open-source research community, so that it can contribute for future research work.

The dataset used for the testing and training purpose is avaiable at [Link](https://drive.google.com/file/d/14eCNQxHj7kqBWkd4ZKI78V0EdkHL6PfT/view?usp=sharing)


## Cite Us
~~~
@misc{https://doi.org/10.48550/arxiv.2207.02489,
  doi = {10.48550/ARXIV.2207.02489},
  
  url = {https://arxiv.org/abs/2207.02489},
  
  author = {Saini, Rahul and Halder, Debajyoti and Baswade, Anand M.},
  
  keywords = {Cryptography and Security (cs.CR), Networking and Internet Architecture (cs.NI), FOS: Computer and information sciences, FOS: Computer and information sciences},
  
  title = {RIDS : Real-time Intrusion Detection System for WPA3 enabled Enterprise Networks},
  
  publisher = {arXiv},
  
  year = {2022},
  
  copyright = {Creative Commons Attribution Non Commercial No Derivatives 4.0 International}
}
~~~
