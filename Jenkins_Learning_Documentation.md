# Jenkins CI/CD Documentation Report  

A detailed guide to understanding and implementing Continuous Integration and Continuous Delivery using Jenkins.

---

## Table of Contents
1. [Overview of Jenkins](#overview-of-jenkins)  
2. [System Requirements](#system-requirements)  
3. [Installing Jenkins](#installing-jenkins)  
4. [Jenkins Dashboard Overview](#jenkins-dashboard-overview)  
5. [Creating and Managing Jobs](#creating-and-managing-jobs)  
6. [Understanding Pipelines](#understanding-pipelines)  
7. [Build Triggers and Automation](#build-triggers-and-automation)  
8. [Project Dependencies (Upstream & Downstream)](#project-dependencies-upstream--downstream)  
9. [Best Practices](#best-practices)  
10. [Common Errors and Solutions](#common-errors-and-solutions)  
11. [Advanced CI/CD Workflow](#advanced-cicd-workflow)  
12. [References](#references)  

---

## Overview of Jenkins  

### What is Jenkins?

Jenkins is an open-source automation server used to automate building, testing, and deploying software applications. It plays a major role in DevOps by enabling Continuous Integration (CI) and Continuous Delivery (CD).

### Why Use Jenkins?

- Automates repetitive development tasks  
- Detects errors early in the development cycle  
- Integrates with Git, Docker, Maven, and other tools  
- Supports thousands of plugins  
- Works on Windows, Linux, and macOS  

---

## System Requirements  

Before installing Jenkins, ensure the following:

- Java (JDK 11 or later) installed  
- Minimum 2GB RAM (Recommended: 4GB+)  
- Web browser (Chrome or Firefox)  
- Git installed (for version control integration)  

---

## Installing Jenkins  

### Step 1: Install Java  

Check Java installation:

```bash
java -version
