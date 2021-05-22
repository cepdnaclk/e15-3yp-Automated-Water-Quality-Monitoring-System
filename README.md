---
layout: home
permalink: index.html
repository-name: e15-3yp-Automated-Water-Quality-Monitoring-System
title: Automated Water Quality Monitoring System
---

# Automated Water Quality Monitoring System

---

## Team
-  E/15/077, K.P.W.A.K.K. Dilhani, [e15077@eng.pdn.ac.lk](mailto:e15077@eng.pdn.ac.lk)
-  E/15/279, L.S.W.S. Premathilaka, [e15279@eng.pdn.ac.lk](mailto:e15279@eng.pdn.ac.lk)
-  E/15/211, S.A.I. Maduwanthi, [e15211@eng.pdn.ac.lk](mailto:e15211@eng.pdn.ac.lk)

## Table of Contents
1. [Introduction](#introduction)
2. [Solution Architecture](#solution-architecture )
3. [Hardware & Software Designs](#hardware-and-software-designs)
4. [Testing](#testing)
5. [Conclusion](#conclusion)
6. [Links](#links)

---

## Introduction


Fresh water is finite resource need for agriculture,industry and human existence. Therefore the quality of water is very important.The objective of this project is to develop automated water quality monitoring system by using continues measurements of pH and turbidity measurement.Normal process is water samples are normally collected at regular period and do the analysis and this ask for larger time consumption.But in this project we hope to offer fast and easy monitoring of pH and turbidity levels with IoT applications for continues maintenance of clean water.

### The process carried out water treatment plant.
![image](https://user-images.githubusercontent.com/73756777/119238107-29f25780-bb5e-11eb-9ca5-db925a0b96a8.png)



## Solution Architecture

![image](https://user-images.githubusercontent.com/73756777/119238122-49898000-bb5e-11eb-936d-2212a8bbe12a.png)

## Hardware and Software Designs

### Circuit Diagram
![image](https://user-images.githubusercontent.com/73756777/119238157-8190c300-bb5e-11eb-86ad-0982f5021e33.png)

### Flow Chart
![image](https://user-images.githubusercontent.com/73756777/119238187-aab15380-bb5e-11eb-896c-71e81c3c189f.png)

### Front-End Technologies
![image](https://user-images.githubusercontent.com/73756777/119238210-c9174f00-bb5e-11eb-955d-f00e4affb731.png)

### UI Design
![image](https://user-images.githubusercontent.com/73756777/119238216-d0d6f380-bb5e-11eb-8ddd-972a66ba64fc.png)

### Back-End Technologies
![image](https://user-images.githubusercontent.com/73756777/119238227-e2b89680-bb5e-11eb-96b6-d264d9119720.png)

### ER Diagran
![image](https://user-images.githubusercontent.com/73756777/119238231-e8ae7780-bb5e-11eb-91d1-479b19994ec6.png)


## Testing


Test Plan

Following are the test plan that is to be tested.

Integration Testing
Focus – pH sensor, web site
Inputs and expected output are like below.


PH <6.5 --> Alert 

PH  6.5 – 7. 5 --> Normal 

PH >7.5 --> Alert 


Assumption – temperature 25(C)


Testing Environment – wifi connection,pH sensor along with the embedded device and web interface
Testing Process - In our system we are designing it to give alert when the variation of pH and turbidity values occurred. We can give some sort of boundary values to the system and check whether it gives expected output to the clients.
Normally pH value of treated water should be in the range of 6.5 – 7.5.Then we are going to test our system using this case.
By using soap water ,normal water and leman water it can be tested.

 

Unit Testing

Test whether sensors are working properly.Test both pH and Turbidity sensors with known solutions to verify whether it gives expected values.
Focus – pH sensor
Inputs and expected outputs –pH value of water is going to be changed by using pH known chemical and expecting their exact pH values using our pH sensor


        2.2 – Vinegar
        10.5 - Milk of Magnesia
        14.0 - Sodium Hydroxide (NaOH)


Assumption – temperature 25(C) 
Testing Environment – pH sensor is needed

 Load Testing
Focus –whole system
Inputs – increase the number of nodes up to 30 nodes for the system using

dummy values
Expected output –system should operate properly as before
Assumption - temperature 25(C) 
Testing Environment – pH sensor ,Turbidy sensors,wifi connection and web site

## Conclusion

 Now we have completed  two nodes in the system. We can measure pH values and Turbidity values in real time of those two water treatment stages. But we still doing it in using two water samples(pure water and muddy water). And the Database also updating at the same time when sensor values are  updated. And when considering the web application,  the data can be retrieved easily. And tables in the web application also real-time updated with the database.

## Links  
- <a href = "https://github.com/cepdnaclk/e15-3yp-Automated-Water-Quality-Monitoring-System" target = "_blank"> Project Repository </a>
- <a href = "https://cepdnaclk.github.io/e15-3yp-Automated-Water-Quality-Monitoring-System/" target = "_blank">Project Page</a>
- <a href = "http://www.ce.pdn.ac.lk/" target = "_blank">Department of Computer Engineering</a>
- <a href = "https://eng.pdn.ac.lk/" target = "_blank">University of Peradeniya</a>


[//]: # (Please refer this to learn more about Markdown syntax)
[//]: # (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
