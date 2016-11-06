# Overview
#### What is it?
This repository is a collection of instructions, compiled sources, and code used or created during my exploration of getting Spark jobs to run code on a GPU.
#### Motivation
I wanted to see if performance in Spark could be taken to the next level, particularly in CPU-bottlenecked use cases. The idea was that Spark would still handle all of the details of a distributed processing framework (monitoring, chunking of work, code serialization, etc.), and executors would utilize a GPU if available to improve processing speeds.
#### How does it work?
I used aparapi (a-parallel-API) provided by AMD to write java code that could run on a GPU. Apaparapi is an Java API that takes your java code and converts it to OpenCL code and runs that converted
# Installation
# Examples
# Misc.
#### Challenges/Considerations
#### Resources
