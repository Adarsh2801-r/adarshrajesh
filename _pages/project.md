---
layout: splash
title: My Projects
permalink: /projects/
date: 2020-03-27T11:48:41+1:00
header:
  overlay_image: /assets/images/cover-image.png
  overlay_filter: 0.6

feature_row1:
   - image_path: /assets/images/malloc.png
     alt: "Dynamic Memory Allocator ( Malloc Lab )"
     title: "Dynamic Memory Allocator ( Malloc Lab )"
     excerpt: "Designed and implemented a dynamic memory allocator in C supporting malloc, calloc, realloc, and free operations. Optimized heap utilization to 73% with 8000 KOPS throughput using first-fit allocation and LIFO block management on segregated free lists."
   - image_path: /assets/images/proxy.jpg
     title: "Tiny Proxy Web Server ( Proxy Lab )"
     excerpt: "Implemented a concurrent web proxy server in C that forwards HTTP requests from clients to end servers and relays responses back, gaining hands-on experience with sockets, concurrency, and network programming."
   - image_path: /assets/images/shell.jpg
     title: "Tiny Unix Shell (Tsh Lab)"
     excerpt: "Implemented a miniature Unix shell supporting built-in job control (fg, bg, jobs, quit), execution of standard Linux commands, and Unix I/O redirection. Gained hands-on experience with process creation & termination, signal handling, and file descriptors, building a deeper understanding of OS internals and systems programming."
feature_row2:
  - image_path: /assets/images/jdk_upgrade.png
    alt: "JDK upgrade"
    title: "JDK upgrade for GC optimization"
    excerpt: "Upgrade the JDK version of a distributed NoSQL database - Apache Cassandra to optimize Java garbage collection"
    url: "https://github.com/Adarsh2801-r/Cassandra-JDK-Upgrade---Nutanix-Internship-Project-/blob/main/PS2%20report.pdf"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/3d_reconstruction.png
    title: "3D volume reconstruction from 2D free-hand ultrasound scans"
    excerpt: "Deep learning models to estimate relative spatial position co-ordinates to re-construct 3D trajectory"
    url: "https://github.com/Adarsh2801-r/3d-Reconstruction-of-UltraSound-Scans"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/Image_caption.png
    alt: "Image captioning"
    title: "Image Caption Generation"
    excerpt: "Encoder-decoder transformer model for image-to-text generation"
    url: "https://github.com/Adarsh2801-r/image_captioning"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/defect_prediction.png
    alt: "Defect Prediction"
    title: "Software Defect Prediction"
    excerpt: 'Improve developer productivity by localizing software bugs in large Java repositories using ML techniques'
    url: "https://github.com/Adarsh2801-r/Software-Defect-Prediction-Research"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/AI-bot.png
    alt: "AI-bot"
    title: "ENiGMA : AI ChatBot"
    excerpt: 'Real-time data retrieval and enhanced recommendations through keyword matching and intent recognition.'
    url: "https://github.com/Adarsh2801-r/AI---ChatBot"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/info-retrieval.jpg
    alt: "Info-Retrieve"
    title: "Document Retrieval Search Engine"
    excerpt: 'Document retrieval system with advanced Boolean query processing, including support for wildcards and spelling correction.'
    url: "https://github.com/Adarsh2801-r/Boolean-Information-retrieval-model"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/Astar.png
    alt: "A*"
    title: "Shortest Path using A*"
    excerpt: 'Implementation of A* algorithm to trace the shortest path between source and destination adresses on the map'
    url: "https://github.com/Adarsh2801-r/Shortest-path-using-ASTAR---GMAPS"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row5:
  - image_path: /assets/images/compiler.webp
    alt: "Compiler"
    title: "Compiler 'Parlance'"
    excerpt: 'Compiler for Custom Language'
    url: "https://github.com/Adarsh2801-r/Compiler-Construction"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/LMS.jpg
    alt: "LMS"
    title: "Library Management System"
    excerpt: "Desktop based application to manage library operations"
    url: "https://github.com/Adarsh2801-r/Library-Management-System"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/TrackTrigger.png
    alt: "TT"
    title: "Track 'n' Trigger"
    excerpt: "Android Application to track daily tasks and meetings"
    url: "https://github.com/Adarsh2801-r/Track_and_Trigger"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

<h2>Graduate Projects (Carnegie Mellon University) </h2>
{% include feature_row id="feature_row1" %}

<h2>Industry Projects</h2>
{% include feature_row id="feature_row2" %}

<h2>Research Projects</h2>
{% include feature_row id="feature_row3" type="left" %}

<h2>Undergraduate Projects (BITS Pilani) </h2>
{% include feature_row id="feature_row4" %}

{% include feature_row id="feature_row5" %} 