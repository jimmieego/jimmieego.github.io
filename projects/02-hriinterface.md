---
layout: page
title: System of Human-Robot Interfaces for Emergency Response Teams
folder: projects
type: project
image: images/muri_ems.jpg
excerpt: This remote operator interface allows a single human supervisor to monitor and task multiple heterogeneous robots. Decreasing the robot to human ratio will be achieved by increasing the operator's awareness of the broad situation while still allowing him or her to interact with each robot at an individual level. To increase the operator's awareness, several interaction widgets have been designed to facilitate the tracking of objects that are no longer visible on the current main map view. These supplemental widgets are called the Halo and the Mini Map.
---

**Method**: Cognitive Task Analysis, Workflow Analysis, Wireframing, Prototyping  
**Tools**: Qt, Adobe Illustrator, Adobe Flash

##Introduction
This project was funded by the Office of Naval Research (ONR) and it is a Multidisciplinary University Research Initiative Program (MURI) partnered with researchers at MIT and Stanford.

My responsibility for implementing the UV Specialist interface included:  

* Generate interface and interaction specifications based on task analysis ([work sample](/assets/TaskAnalysisSample.pdf));  
* User interface and test application implementation using Qt;  
* Design and conduct usability test of the interface;  
* Qualitative and quantitative data analysis.  

##The UV(Unmanned Vehicle) Spelialist Interface
The UV specialist interface is a Qt-based application designed to improve remote operator (UV specialist) situation awareness, while maintaining a collection of tasks and robot teams during a CBRNE incident scenario. The application is composed of a collection of widgets (components) that provide diverse functionality and expandability. The primary interface widget is the map display (center of the Figure), which presents a portion of the response area. Unmanned vehicles (UVs), tasks, and task-specific information items (e.g., identified victims and hazards) are also displayed on the map. The UV specialist can zoom in on a map region using the mouse scroll wheel. From the zoomed view, the UV specialist may either use the scroll bars to navigate the map area or grab any portion of the map to drag it to the desired position (i.e., map panning). The task panel (far right side of the Figure) provides relevant information regarding the tasks created by the UV specialist, and the assignments and status of each UV. The bottom panel is the UV task creation panel, where the UV specialist selects the task type and inputs required information to create tasks (e.g., searching for victims, victim assessment, hazard sampling, bomb surveillance, etc.) that the UVs execute.  

The UV Specialist interface is integrated with the ONR MURI system and allows the user to specify high-level commands, such as search an area for victims, that are allocated by MIT's mixed-initiative tasker to MIT's ground or aerial robots. The MIT mixed-initiative tasker can also allocate tasks autonomously to robots and notify the remote operator of such allocations. A touch screen version of the UV Specialist interface has been integrated with Kansas State University's robotic team.  

A screenshot of the UV Specialist interface:
![Screenshot of the UV Specialist interface]({{ site.baseurl }}/{{ page.image }})

##Evaluation of a Geospatial Annotation Tool for UV(Unmanned Vehicle) Specialist Interface
Map-based interfaces have been developed to support collaborative control of unmanned vehicles (i.e., robots). Annotation on the map (or geospatial annotation) has been proposed as an effective way to support team collaboration; however, there is a lack of research focused on the design of geospatial annotation tools to promote usability and task performance. Two annotation tool designs were developed in this study. The annotation contents were directly anchored on the map in the first design, while in the second design annotations were summarized in a separate panel on the interface. Evaluation participants followed instructions from a simulated team leader and assigned unmanned vehicles to different tasks for two simulated scenarios that include searching for victims and collecting hazardous materials samples. The results demonstrate the potential of using geospatial annotations to enrich communication and support map-based unmanned vehicle control. Participants appreciated the direct location reference feature of the first design and had generally shorter response time, but felt that the second design provided better usability and lower task workload. These results suggest that the user experience depends on the manner of obtaining information from the annotation tools, and the integration of the tool with user's task flow and other interface components, such as the map display. The presented results can be used as a basis for designing geospatial annotation tools for team collaboration that better fit user needs and preferences.  

**First Design**: Individual annotations directly anchored on the map  
![First annotation tool design]({{ site.baseurl }}/images/Annotation_design1.png)

**Second Design**: Annotations summarized in a separate panel  
![First annotation tool design]({{ site.baseurl }}/images/Annotation_design2.png)

##Related publications
Zhang, T., and Adams, J. A. (2012). [Evaluation of a geospatial annotation tool for UV(Unmanned Vehicle) specialist interface](http://www.tandfonline.com/doi/abs/10.1080/10447318.2011.590122#.VaHD7ZNViko). *International Journal of Human-Computer Interaction*, 28(6), 361-372.