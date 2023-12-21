# Job Scheduling System

## Introduction
This repository contains a job scheduling system implemented in Python using matplotlib for visualization. The system simulates the allocation of tasks to worker nodes based on various scheduling policies, such as First Come First Serve (FCFS), Shortest Job First (SJF), and Shortest Duration Job First (SDJF). The system tracks and plots the CPU and memory utilization of the worker nodes over time.

## Table of Contents
- Introduction
- Implementation Details
- Usage
- Scheduling Policies
- Plots

## Introduction
The job scheduling system is designed to allocate tasks to a pool of 128 worker nodes based on different scheduling policies. The tasks are read from the 'JobArrival.txt' file, containing information about job arrival times, memory requirements, CPU requirements, and execution times.

## Implementation Details
- Worker Nodes: The system simulates 128 worker nodes, each having 24 cores and 64 units of memory.
- Scheduling Policies: The implemented scheduling policies include FCFS, SJF, and SDJF.
- Task Allocation: Jobs are allocated to worker nodes based on available resources and the selected scheduling policy.
- Utilization Tracking: The system tracks and plots daily and hourly CPU and memory utilization of the worker nodes.

## Usage
1. Ensure you have Python installed on your machine.
2. Run the script by executing the following command in the terminal:

   ```bash
   python job_scheduler.py
