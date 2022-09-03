---
title:  "How To Create An University Networking System In Cisco Packet Tracer"
mathjax: true
layout: post
---

### CREATING A UNIVERSITY NETWORK SYSTEM IN CISCO PACKET TRACER
# How To Create An University Networking System In Cisco Packet Tracer
## You can create a university network system in Cisco Packet Tracer

<figure style="text-align: center;">
    <img src="https://miro.medium.com/max/564/0*NNpAgg8uuvUnm3kK.jpg"
         alt="BounCet">
</figure>

Hello, today I and my friends tell you how to create a networking system in Cisco Packet Tracer.

Note: This is our CET 314 homework and this is a group project. Our group’s name is Cetgiller.

**Before reading the article;**

It is assumed that you know Cisco Packet Tracer.

**Content**

Part 1- General Information About The System

Part 2- Working With Cisco Packet Tracer

Part 3- Sending Message or Ping In Cisco Packet Tracer

## Part 1- General Information About The System
Group member;

Ali Eren Kayhan
Bengisu Kaya
Ege Eroğlu
Enes Sucu
Numan Kaya

<figure style="text-align: center;">
    <img src="https://miro.medium.com/max/394/0*xGf-H43Zmtgaaz-p"
         alt="BounCet">
</figure>



First, you need to know what the system must have, and what you have

- **Company Name:** Gezi school’s campuses
- **The number of campuses:** 4
- **The number of students:** 1150
- **The number of teachers:** 64
- **The number of workers:** ≌ 40
- **The number of desktops:** ≌ 250
- **The number of classrooms:** ≌ 24
- **The number of labs:** ≌ 5
- **Total of cabling in the current system: 1400 meters**
- **They want internet access with an average of 300 kbit/s.**
- **Every campus and buildings have the same network speed.**
- **Moreover, you should clarify your plan.**

1. Business Objectives

**a. What does the company do?**

Giving education to the next generations.

**b. Why do they think they need a network?**

To access more information and resources, communicate with each other (especially during the Pandemic) and also others (teachers from other schools), giving lessons on some platforms like Zoom and so on.

**c. What divisions/departments would be impacted by the network?**

The network would positively impact every department and division, especially if they deal with computers.

**2. Future Growth**

**a. What is the projected growth of the company?**

Thanks to networking designed by us, they have a chance to give better and more qualified education to students, and graduating more successful and qualified students from the school means more and more students want to be part of this. In other words, students become more willing to study in our schools. Therefore, the school will become like Bogazici university, which means becoming a top-ranking school because a better network and better education’s conditions make the school a target school for those students who want to improve themselves.

**b. Are new divisions/departments planned to be developed in the near future?**

Yes. Technology changes day by day and there are new areas. Therefore, to catch the trends in the working area there should be new departments and the current departments should be improved.

**c. Where does the company see itself in one year? Five years?**

In one year, the school should be in the top fifty schools in the ranking. In five years, the school should be in the top twenty schools in the ranking.

**3. User/Group Requirements**

**a. How will the network impact and improve user performance?**

Users have access to a limitless source, the internet. Therefore, they can use this limitless source to improve themselves.

**b. How will the network allow users to grow within their current roles?**

Thanks to networking designed by us, they can find better instructional materials to give students to educate them better and more qualified.

**c. What type and amount of resources must be available to each group?**

They should have equal access to the internet.

**4. Security**

**a. What are the levels of security within the company?**

There should be 4 security levels. Like this;

![0_DtSAuuZzdRfVYVWG](https://user-images.githubusercontent.com/32596425/188285932-28d2d193-679b-4692-9939-4d0c92786cc4.png)


For P1, everyone on the campus has access. For P2, not everyone can have access. Only students, teachers and workers, and IT team members have access. For P3, teachers and workers have access. For P4, only workers have access.

**b. Are there different levels of security when dealing with outside sources?**

Yes. The security should be like this;

![0_hBX3GzsHplnIStNE](https://user-images.githubusercontent.com/32596425/188286009-cd819743-09b6-4a56-9821-ea3819044d2a.png)

**c. What is the physical security in the company?**

The school’s servers are in a room and the room is only accessible by personnel who has high-level access.

**5. Fault Tolerance**

**a. If the company had a major network failure, what would the impact be?**

If the school had a major network failure, the system wouldn’t stop because we use mesh topology. Every point in the mesh topology is, directly and indirectly, connected to each other. Therefore, if there would be a problem in a line between 2 points, they continue to transmit data over other points. Data transfer does not pause in a mesh topology.

![0_MfRMNFadLLJzSMyW](https://user-images.githubusercontent.com/32596425/188286026-0d85d136-4c18-4def-826e-ca37687306f1.png)

**b. How fast does the network need to be repaired in the event of a failure?**

As soon as possible because education continues.

**c. How critical is fault tolerance and redundancy for this network?**

Since we are using the mesh topology, our fault tolerance and redundancy are not very critical. In case of any systematic problem, network traffic will not be interrupted because all points in the system are connected to each other. In case of any device failure, the settings can be backed up and transferred to the new device as it is. Since we are using the mesh topology and considering our economy, we did not want to use the point-to-point pair cable laying method for network traffic redundancy. We believe that we can continue the network traffic smoothly, thanks to the requirements and provides of the mesh topology.

**6. Existing Network Architecture**

**a. Does the company have an existing network?**

Yes, they have. However, they have a lot of complaints lately that they are slow and break down just when you need it.

**b. Can that network be successfully upgraded or retained?**

To answer this question, we need to know the current network exactly and we need the answers to these questions.

- What type of line do they use in the current network?
- What is the design of the current network?
- What parts of the current network should improve?

The number of questions can be more.

**c. What would be the impact of replacing the legacy network?**

If we change the legacy network completely, the price increases but we will have a better network. If we change some parts of the legacy network, the price is not as expensive as changing the legacy network completely but the quality is not the same, which means it would be better than the old but not better than a completely new network.

**7. Management**

**a. How much time and resource management is necessary to maintain the network?**

This changes according to whether we use a completely new network or changing some parts of the legacy network. Secondly, we need more time and resources to manage it.

**b. What level of network management does the company expect?**

![0_tYLDJtbB7HprTxw1](https://user-images.githubusercontent.com/32596425/188286070-9fa8af02-3aa2-4633-8338-a5b1c549f5ec.png)

![0_MaSXnKDy0IGFGK0q](https://user-images.githubusercontent.com/32596425/188286077-a10218a1-301c-4f86-85ac-f969cd9e89e8.png)

![0_hAtx0O9RBDdnjoGX](https://user-images.githubusercontent.com/32596425/188286080-c3cb533b-0088-4e9a-a6d8-2db198295e69.png)

![0_KU-ZmxY8bVZdpXz_](https://user-images.githubusercontent.com/32596425/188286088-8a3792bf-9f27-4557-aab3-39a7240a2f40.png)

![0_ww1b_81wfQG8Pvc4](https://user-images.githubusercontent.com/32596425/188286089-2e3e55d3-42c2-4a85-8cbd-8e7f5a7acabc.png)

![0_iFmAXsPs0XICuaLN](https://user-images.githubusercontent.com/32596425/188286093-44f225bc-2d1e-45ea-b4a4-f78c9307e74b.png)

This is the detailed plan about our network design.

![0_bNSr_UxffsUigoGo](https://user-images.githubusercontent.com/32596425/188286098-060b5bc6-22bf-4157-9db9-7b76179242ce.png)

They want a system where all computers and other devices will be on the same LAN, but all campuses network traffic will remain local, and all users can use it at the same speed. We consider WAN and LAN and BYOT in networking and different design styles of networking, like mesh and point-to-point, while we are creating the network.

The North campus has three buildings. Two of them are 5 floor-buildings and the other one has 3 floors. The distance between buildings is 25 meters.

This campus has 6 classes, 2 labs, 6 executive offices, and 3 connection rooms, which is the room where the server and router are in and only personnel who have high-level access can enter the room. We use mesh style for this campus. On this campus, there are 60 computers, 14 access pointers,3 switches, and 1 router. We don’t want to use a hub because we can keep a MAC address with a switch and this makes progression faster, which the customer wants.

East and West campuses have the same design. Each of them has 7 classes and 1 lab which has 20 desktops. There are 4 executive offices and 4 connection rooms. On each campus, there are 62 computers, 34 access pointers, 8 switches, and 2 routers. We use mesh style for this campus.

The last campus is the South campus and has two buildings which are 4 floors. The distance between buildings is 30 meters. It has 4 classes and 1 lab. There are 40 desktops in the lab. Also, there are 17 access points, 2 switches, and 1 router. We use point to point style for this campus but we also connect them with each other because we want to continue to share data even if there is a problem in the line that connects each building.

First of all, we decided to use Mesh Topology between campuses because, in case of problems in the line between 2 campuses or buildings, they can continue to share data with each other. But we use both mesh and point-to-point style design networks for buildings on the campuses.

Then, to ensure every building has the same quality of internet we use a router for one building in each campus to get internet from a modem under the Firewall and as customers demand, we use access points to enable them to connect the wireless technology. We also add a phone line in some buildings, mentioning also examples of floor plans. We will use 320 meters of the 1400 meters of cabling for the connection between the buildings and the rest for the connection between the floors. We prefer switches for some floors especially on the labs floors because it is enough for the required internet access speed and cheaper than a router.

To provide users with a better network we use a cable between campuses and buildings because when they use cable, the duty of cable is one thing, however, if we would use wireless technology, its duty is more than one, therefore, the internet speed would not be good. We also use their old cable system and in some parts, we use both fiber cables to provide faster access and CAT6 cable to provide internet access with an average of 300 kbit/s and also their cable to decrease the cost.

We assume that 70 percent of 1254 people will use the internet actively at the same time,

(1254*70) /100 = 877.8,

Each user is connected to the internet with 2 devices,

877.8 * 2 = 1755 devices at the same time,

Each user’s bandwidth: 10Mbps

The total bandwidth of our Internet provided by ISP:300 Mbps

Contention Ratio = 1755* 10 : 300 = 58.5:1 = 59:1

Therefore, with a contention ratio of 59:1 on a 300 Mbps internet,

we guarantee 300 Mbps/59 = 5,084745762711864 ≈ 5,1 Mbps (640 KB/s) speed.

## Part 2- Working With Cisco Packet TracerFirst, let’s see the final work.**

![0_HYN4jlTfyuzbct9R](https://user-images.githubusercontent.com/32596425/188286127-2696c39f-6295-43e6-a82a-caeff801698d.gif)

First, let’s see the final work.

These images belong to our 4 main campuses. To create this, there are several steps.

![0_ezJhwHCbxSiS_Lqv](https://user-images.githubusercontent.com/32596425/188286130-f9f410a1-a77a-4eb1-80da-df4c09a338bd.png)

![0_9LLoIyeHkMY8MyYy](https://user-images.githubusercontent.com/32596425/188286144-1a1495d7-4b84-4aef-ae5e-6aeb2ba13443.png)

![0_TI41CyiJyk3Mv_bi](https://user-images.githubusercontent.com/32596425/188286147-e31d7d35-7d6f-4abe-a0be-908c8563e051.png)

![0_B2c8Aa4-t7_cNV9E](https://user-images.githubusercontent.com/32596425/188286151-41f5c158-34e0-4991-bcfc-581b7de085c1.png)

![0_KAFmZEPqgU4UQEBo](https://user-images.githubusercontent.com/32596425/188286155-d885bade-e7af-4b3b-8d7e-ed3234f06720.png)

1.You should select your devices and their places.
2.You should connect them correctly. I advise you to use an automatic connection if you don’t know which cable you should use.
3.You use a cable computer to switch, or an access point to switch or switch to switch. However, when you connect the switch to the router, you should do some settings.
4.First, you should use the correct port in your router. Your router should be like in the “physical” part;

![0_kbEpGPVSU8Zv8YHi](https://user-images.githubusercontent.com/32596425/188286175-84d3a316-1782-48d3-8be7-63a2f595aab4.png)

![0_dBvssbWfBWNBacMQ](https://user-images.githubusercontent.com/32596425/188286176-ae701a69-a02f-4f63-aff9-4e44fdb25a0c.png)

These ports are for connection between the switch to the router.

![0_--fFbWgFkbYkNFNR](https://user-images.githubusercontent.com/32596425/188286183-2adf1117-627d-488a-8e9b-64877937ffc2.png)

These ports are for connection between router to router. We use a console connection and it needs this port and serial cable.

Then, you should go “config” part in your router. You should select the interface that you use. In our case, we use gigabit ethernet for connection between switch and router. It is necessary to give an IP address and click on **“Port status”**. You do this process how many switches you use. Then, you should go back to your computer that is connected with a switch or access pointer. Go config and give IP address. You can give the IP address by changing the last number of the router's IP address.

**DO NOT USE THE SAME IP ADDRESS OR 0.**

Then, do the same operation with other devices on a campus. If you want to use a server or modem, you should prefer to use gigabit ethernet to give an IP address.

After finishing one campus and doing the same operation on the other campus, it is time to connect each campus.

![0_1ZsNueiduuF_pWdB](https://user-images.githubusercontent.com/32596425/188286196-af5be5a9-ddcb-4ddd-b696-a2c0e6a8c14b.gif)

You use a serial cable to connect each campus. Go your any router and go “config” part. Here we use static routing. To do this, you should go to the interface and select one of the serial ports which you use. You give an IP address to them but you should use like 11.0.0.1 (the last “1” representing the north campus). You should give a number according to a system.

Our system is ordered campus, devices and gives the user devices this number but at the and changes the last one. What this means is, that your user device’s number can be like North PC 15122 IP address. Each number represents campus and devices to reach the user devices.

After you give an IP address to serials, you should go RIP in Routing. You enter every serial and router IP address here but the last number must be 0. After that, go static.

Network = Router IP address that you want to reach

Mask = Under the Router IP address that you want to reach^

Next Hop = Router serial’ IP address that you want to reach

**It is important that you must connect the serial cable to the same number port. If you connect serial 0/0/0 port, you should connect serial 0/0/0 in another router.**

You do this operation for every router. Then you can send a ping.

**Important Note= When you send a first-time message, you see “failed” but if you try it again you see “successful”. Every time your first message will be like that.**

## Part 3- Sending Message or Ping In Cisco Packet Tracer

You can send a message with click this icon;

![0_ZoUjkMUajcTSy3ks](https://user-images.githubusercontent.com/32596425/188286209-12e0c6c2-477b-4e05-aa77-310062a3d8b3.png)

You select the 2 devices. The first device is for sending messages and the second one is for receiving it.

Or you can write it in the command prompt. First, select your devices one for sending and one for receiving. You should know the device’s IP address that you send a ping to. Go to the device that you send ping and select the “desktop” part. Then click “command prompt”. Write ping IP address (for receiving computer) and click enter.

![0_o4PQ37Z3m22d79gx](https://user-images.githubusercontent.com/32596425/188286214-abb8b0ba-1d7c-42fe-98e0-b9476ac4df14.gif)

Thank you for reading our project

Cetgiller

It is originally published at https://alierenkayhanbouncet.blogspot.com/

If you like the article, please like and share this article. I will appreciate it a lot. To learn more about my works and me, you can visit <a href="https://alierenkayhan.github.io/">my website</a> and follow my channels.

Reference
- https://security.berkeley.edu/education-awareness/what-your-role-protecting-berkeley-campus-data
- https://www.scnsoft.com/blog/3-levels-corporate-network-security
- https://www.fool.com/the-blueprint/network-diagram/
- CET 314 lesson
- https://giphy.com/
