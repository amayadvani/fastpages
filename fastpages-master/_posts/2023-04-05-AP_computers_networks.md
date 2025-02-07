---
toc: true
comments: true
layout: base
title: Computers and Networks (Unit 4)
description: Add Definitions from Unit 4 Computer Systems and Network
---

## Requirements
> Work through College Board Unit 4... blog, add definitions, and pictures.  Be creative, for instance make a story of Computing and Networks that is related to your PBL experiences this year.


### How a Computer Works
> As we have learned, a computer needs aa program to do something smart.  The sequence of a program initiates a series of actions with the computers Central Processing Unit (CPU). This component is essentially a binary machine focussing on program instructions provided.  The CPU retrieives and stores the data it acts upon in Random Access Memory (RAM). Between the CPU, RAM, and Storage Devices a computer can work with many programs and large amounts of data.

List specification of your Computer, or Computers if working as Pair/Trio
- Processor GHz:
- Memory in GB:
- Storage in GB:
- OS:

Input devices: Input devices are used to enter information into a computer. Some examples of input devices include keyboards, mice, touchscreens, and microphones. Here's a picture of a keyboard:

keyboard

Output devices: Output devices are used to display or output information from a computer. Some examples of output devices include monitors, printers, and speakers. Here's a picture of a computer monitor:

monitor

Program File: A program file is a file that contains instructions that a computer can execute. Program files can have different extensions depending on the programming language they are written in. Here's a picture of a Python program file:

python program file

Program Code: Program code is the set of instructions that a computer program is made up of. Program code is written in a programming language and can be executed by a computer. Here's an example of some Python program code:

Processes: Processes are the programs and services that are currently running on a computer. Processes can be viewed and managed using a task manager or system monitor. Here's a picture of the Windows Task Manager showing some running processes:

windows task manager

Ports: Ports are used to connect devices to a computer. Different types of devices use different types of ports. Some common types of ports include USB, HDMI, and Ethernet. Here's a picture of some USB ports on a computer:

usb ports

Data File: A data file is a file that contains data that can be used by a computer program. Data files can have different formats depending on the type of data they contain. Here's a picture of a CSV data file:

csv data file

Inspect Running Code: Inspecting running code involves analyzing the state of a program while it is running. This can be done using debugging tools that allow you to step through the program and examine variables and data structures. Here's a picture of the PyCharm IDE with a program paused in the debugger:

pycharm debugger

Inspect Variables: Inspecting variables involves examining the values of variables in a program while it is running. This can be done using debugging tools that allow you to pause the program and view the current state of variables. Here's a picture of the PyCharm IDE with a program paused in the debugger showing the values of some variables:


![Computer Hardware]({{site.baseurl}}/images/cpu.jpeg)


### The Internet
> Watch/review College Board Daily Video for 4.1.1

- Essential Knowledge
    - A computing device is a physical artifact that can run a program. Some examples include computers, tablets, servers, routers, and smart sensors.
    - A computing system is a group of computing devices and programs working together for a common purpose.
    - A computer network is a group of interconnected computing devices capable of sending or receiving data.
    - A computer network is a type of computing system. 
    - A path between two computing devices on a computer network (a sender and a receiver) is a sequence of directly connected computing devices that begins at the sender and ends at the receiver.
    - Routing is the process of finding a path from sender to receiver.
    - The bandwidth of a computer network is the maximum amount of data that can be sent in a fixed amount of time.
    - Bandwidth is usually measured in bits per second

-Path: The path refers to the route that data takes from one point to another on a network. This can include multiple hops through different devices and networks. To analyze the path of a network connection, you can use the traceroute command in the Linux terminal.

Route: A route is a path that data takes from one network to another. A router is a device that is used to direct data along a specific route. To view the routes that your network is using, you can use the route command in the Linux terminal.

Computer System: A computer system is a collection of hardware and software that work together to perform specific tasks. This can include the central processing unit (CPU), memory, storage, and input/output devices.

Computer Device: A computer device is a physical component of a computer system, such as a keyboard, mouse, monitor, or printer.

Bandwidth: Bandwidth refers to the amount of data that can be transmitted over a network in a given amount of time. It is typically measured in bits per second (bps), kilobits per second (kbps), or megabits per second (Mbps). To measure the bandwidth of your network connection, you can use the speedtest-cli command in the Linux terminal.

Computer Network: A computer network is a collection of interconnected devices and systems that can communicate with each other to share information and resources. Networks can be local area networks (LANs), wide area networks (WANs), or the internet. To measure the latency of a network connection, you can use the ping command in the Linux terminal.

> Watch/review College Board Daily Video 4.1.2

- Complete True of False Questions

T
F
F
T
F
F
T



- Essential Knowledge
    - The internet is a computer network consisting of interconnected networks that use standardized, open (nonproprierary) communication protocols.
    - Access to the internet depends on the ability to connect a computing device to an internet connected device.
    - A protocol is an agreed-upon set of rules that specify the behavior of a system.
    - The protocols used in the internet are open, which allows users to easily connect additional computing devices to the internet.
    - Routing on the internet is usually dynamic; it is not specified in advance
    - The scalability of a system is the capacity for the system to change in size and scale to meet new demands.
    - The internet was designed to be scalable
    - Information is passed through the internet as a data stream. Data streams contain chunks of data, which are encapsulated in packets. 
    - Packets contain a chunk of data and metadata used for routing the packet between the origin and the destination on the internet, as well as for data reassembly.
    - Packets may arrive at the destination in order, out of order, or not at all
    - IP, TCP and UDP are common protocols used on the internet.
    - The world wide web is a system of linked pages, programs, and files.
    - HTTP is a protocol used by the world wide web
    - The world wide web uses the internet

- Go over AP videos, vocabulary, and essential knowledge.  Draw a diagram showing the internet and its many levels. A preferred diagram would using your knowledge of frontend, backend, deployment, etc.  Picture would highligh vocabulary by illustration. The below illustration have some ideas

![Full Stack]({{site.baseurl}}/images/fullstack.png)


- Often we draw pictures of machines communicating over the Internet with arrows.  However, the real communication goes through protocol layers and the machine and then is trasported of the network.   For College Board and future Computer Knowledge you should become familiar with the following ...

```
     User Machine  <---> Frontend Server <---> Backend Server
    +-----------+         +-----------+         +-----------+
    |  Browser  |         |  GH Page  |         |   Flask   |
    +-----------+    ^    +-----------+    ^    +-----------+
    |    HTTP   |    |    |    HTTP   |    |    |    HTTP   |
    +-----------+    |    +-----------+    |    +-----------+
    |    TCP    |    |    |    TCP    |    |    |    TCP    |   
    +-----------+    |    +-----------+    |    +-----------+
    |     IP    |    V    |     IP    |    V    |     IP    |
    +-----------+         +-----------+         +-----------+
    |  Network  |  <--->  |  Network  |  <--->  |  Network  |
    +-----------+         +-----------+         +-----------+
```

The "http" layer is an application layer protocol in the TCP/IP stack, used for ***communication between web browsers and web servers***. It is the protocol used for transmitting data over the World Wide Web.

The "transport" layer (TCP) is responsible for providing reliable data transfer between applications running on different hosts.  The TCP protocol segments the data into smaller ***chunks called "segments"***. Each segment contains a sequence number that identifies its position in the original stream of data, as well as other control information such as source and destination port numbers, and checksums for error detection.

The "ip" layer is responsible for packetizing data received from the TCP layer of the protocol stack, and then ***encapsulating the data into IP packets***. The IP packets are then sent to the lower layers of the protocol stack for transmission over the network.

The "network" layer is responsible for ***routing data packets between networks*** using the Internet Protocol (IP). This layer handles tasks such as packet addressing and routing, fragmentation and reassembly, and ***network congestion*** control.


### Fault Tolerance
> Watch both Daily videos for 4.2

- Complete the network activity, summarize your understanding of fault tolerance.


### Parallel and Distributed Computing
> Review previous lecture on Parallel Computing and watch Daily vidoe 4.3.  Think of ways to make something in you team project to utilize Cores more effectively.  Here are some thoughts to add to your story of Computers and Networks...

- What is naturally Distributed in Frontend/Backend archeticture?  

- Analyze this command in Docker: ```ENV GUNICORN_CMD_ARGS="--workers=1 --bind=0.0.0.0:8086"```.   Determine if there is options are options in this command for parallel computing within the server that runs python/gunicorn.  Here is an [article](https://medium.com/building-the-system/gunicorn-3-means-of-concurrency-efbb547674b7)


> Last week we discussed parallel computing on local machine.  There are many options.  Here is something to get parallel computing work with a tool called Ray.
- Review this [article](https://www.anyscale.com/blog/writing-your-first-distributed-python-application-with-ray)...  Can you get parallel code on images to work more effectively?  I have not tried Ray.

- Code example from ChatGPT using squares.  This might be more interesting if nums we generated to be a lot bigger.

```python
import ray

# define a simple function that takes a number and returns its square
def square(x):
    return x * x

# initialize Ray
ray.init()

# create a remote function that squares a list of numbers in parallel
@ray.remote
def square_list(nums):
    return [square(num) for num in nums]

# define a list of numbers to square
nums = [1, 2, 3, 4, 5]

# split the list into two parts
split_idx = len(nums) // 2
part1, part2 = nums[:split_idx], nums[split_idx:]

# call the remote function in parallel on the two parts
part1_result = square_list.remote(part1)
part2_result = square_list.remote(part2)

# get the results and combine them
result = ray.get(part1_result) + ray.get(part2_result)

# print the result
print(result)

```
