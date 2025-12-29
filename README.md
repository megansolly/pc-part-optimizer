# PC-Part-Optimizer

## Overview
The **PC Part Optimizer** is a PC part picker and optimization model that generates a complete, high-performance gaming PC build based on user-defined preferences. Given a **budget**, **color preference**, and **RGB preference**, the model selects the *best possible combination of compatible components* while maximizing overall system performance.

The optimizer removes the need for extensive manual research by automatically producing a full list of parts that a user can purchase to build a powerful and well-balanced gaming PC.

## Group Project & My Contribution
This project was completed as part of a team. My contributions included:

- Assisting in creating the optimization model that selects the best PC components
- Writing and testing the Jupyter Notebook code
- Assisting with data collection and performance evaluation of components

---

## Motivation
As PC gaming continues to grow in popularity, more gamers are choosing to build their own PCs as a **cost-effective way to achieve high performance**. However, selecting the right components presents several challenges:

- Comparing performance across hundreds of parts  
- Staying within budget  
- Ensuring part compatibility  
- Matching aesthetic preferences (color and RGB)  

This project was created to **eliminate the complexity and time-consuming research** typically required when building a custom PC. The PC Part Optimizer streamlines the decision-making process by intelligently selecting components that offer the best performance while respecting user constraints.

---

## Objective
The primary objective of the model is to:

> **Maximize overall PC performance while conforming to user-provided constraints.**

Performance is derived from **individual component performance metrics**, which are combined to evaluate and optimize the total system performance.

---

## Selected Components
The optimizer selects the following PC components:

- **GPU (Graphics Processing Unit)**
- **CPU (Central Processing Unit)**
- **Motherboard**
- **RAM**
- **Storage**
- **Case**
- **CPU Cooler**
- **Power Supply**
- **Case Fans**

All selected parts are:
- Compatible with one another  
- Within the user’s budget  
- Aligned with aesthetic preferences (color & RGB)  

---

## User Inputs
The model accepts the following inputs:

- **Budget** – Maximum total cost of the PC
- **Color Preference** – Desired component color theme
- **RGB Preference** – RGB-enabled components (yes/no)

---

## Output
The optimizer produces:
- A **complete list of PC components** ready for purchase
- A configuration designed to deliver **maximum gaming performance**
- A system that meets **budgetary, aesthetic, and compatibility constraints**

This output allows users to confidently build a high-performing gaming PC without needing deep hardware expertise.

---

## Key Features
- Automated PC part selection  
- Performance-driven optimization  
- Budget-aware decision making  
- Compatibility-safe configurations  
- Customizable aesthetics (color & RGB)  

---

## Use Case
This project is ideal for:
- Gamers building their first PC  
- Enthusiasts seeking optimal performance per dollar  
- Users overwhelmed by part compatibility and comparisons  

---

## Future Improvements
Potential enhancements include:
- Support for different use cases (streaming, productivity, workstation)
- Real-time pricing updates
- Expanded aesthetic customization
- Web-based user interface

---

## Disclaimer
This project is intended as a decision-support tool. Final purchasing decisions should account for availability, pricing fluctuations, and user-specific requirements.
