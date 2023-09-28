+++
showonlyimage = false
draft = false
image = "projects/threads.png"
date = "2021-05-23T10:16:56+01:00"
title = "Discovering C++ header dependencies"
weight = 8
+++

A multi-threaded solution to find dependencies in C++ files.
<!--more-->

> [View code on GitHub](https://github.com/jovanneste/Discover-Dependencies)

---

#### Description
Build a simple single-threaded solution to iteratively seach C++ files, searching for dependencies to include in header files. Significantly improved the speed through a multi-threaded approach.  

#### Multi-threaded solution
To ensure thread-safety, I created two structs with correct locks and synchronization mechanisms in place. These measures were essential to prevent race conditions and maintain the integrity of data shared between multiple threads, allowing for smooth and efficient execution of the multi-threaded solution. The **discoverdependencies.cpp** creates the correct number of threads and calls the process function for each thread.

---


