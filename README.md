# Play-with-K3S-and-Golang (PKG)
A playground for learning and practicing basic Cloud&amp;Edge computing concepts using K3S and GoLang

This document introduce the perspectives of this project, you may also [rush into the playground directly](./docs/00.index.md)

## Objectives
What we are going to do along the way till foreseeable future is, trying to understand 

+ ### the practical aspects of 
   1. generating an arbitrary network of computing units which heterogeneously distributed in location and resource capabilities using different kinds of virtual machines
   1. dynamically tuning of
      - network bandwidths between any nodes
      - network conditions between any nodes
      - node healthy status
      - disk mount/unmount status of any node
      - resource allocation, e.g., quota of CPU, Memory, Disk.
   1. provisioning a single job on computing unit in the network
   1. adjusting runtime resource limitation of that job provisioned in the step above
   1. scaling a provision across a subset of the network
   1. recursively provisioning a job across a subset of the network
   1. scheduling a queue of jobs on the network
   1. dynamically provisioning, scaling, scheduling a queue of unexpectable jobs on the network with arbitrary SLO expectations

* ### the quantitative analysis of
   1. the overhead of 
       - cold start
       - provisioning
       - scaling
   1. the efficiency of resource utilization: overload or under utilized
   1. tail-latency of a single job
   1. tail-latency of a queue of jobs
   1. data throughout
   1. energy consumption
   1. all above under arbitrary disturbances of the network
      - network bandwidth/condition
      - node fail
      - disk fail of node
      - memory/cpu capacity change of node

+ ### comparisons of 
   1. scheduling models
   1. provisioning models

## Levels to conquer

* #### Level 1: Setup the virtual machine playground, with the ability of tuning resources and reporting resource utilization

* #### Level 2: Setup the  K3S and GoLang development env and CI tools for testing

* #### Level 3: Dynamically provisioning and scheduling jobs across the network

* #### Level 4: Unrevealed yet
