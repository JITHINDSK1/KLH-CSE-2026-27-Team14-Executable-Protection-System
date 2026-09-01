# Executable Protection System

## Team Information
- **Team ID:** 14
- **Academic Year:** 2026-27
- **Branch:** CSE

### Team Members
- G. Jithin Reddy (2520030508) - GitHub: @JITHINDSK1
- B. Himavanth Sai Ganesh (2520030429)
- G. Cheran Tej Reddy (2520030466)

### Supervisor
- Y Harika Devi

## Abstract
Executable Protection System is a Linux-based Operating Systems project that demonstrates how the operating system protects executable files while they are being executed. In a multitasking environment, allowing another process to modify an executable that is currently running may result in corrupted or inconsistent program execution. This project addresses the problem by demonstrating the behavior of write operations on an active executable file and observing the response of the Linux kernel.

The project focuses on key Operating Systems and system programming concepts such as process creation, process execution, file handling, system calls, error handling, and executable file protection. System calls such as fork(), exec(), open(), write(), and close() can be used to create and execute a sample program and attempt to modify its executable while it is running. The project also uses errno to identify errors returned by the kernel and strace to observe the relevant system calls.

The proposed solution consists of a Linux-based application in C, where a sample executable is created and executed while another process attempts to modify it. The expected outcome is a functional demonstration of how Linux handles modification attempts on active executable files, providing practical understanding of file protection, system calls, error handling, and kernel-level operating system behavior. The project also strengthens system programming skills and demonstrates how Linux maintains safe and consistent execution of programs.

## Setup and Execution Instructions
*Instructions to be added.*

## Current Phase Status
- **Phase:** Initial Setup
