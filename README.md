# README - A-19 Domestic Assistant Robot Cognitive Architecture

## Overview

This project presents a **Cognitive Architecture** for the **A-19 Domestic Assistant Robot**, designed to assist elderly people with household tasks like cleaning and meal preparation. The architecture focuses on two key situations:
1. Deciding whether to prepare a complex or simple meal, potentially involving human interaction.
2. Handling fragile objects during cleaning by deciding to avoid them or seek user input.

## Components

### UML Diagrams
1. **Component Diagram**: Illustrates A-19's software architecture, highlighting **cloud-based components** for high-level decisions and **on-premises components** for real-time tasks.
2. **State Machine Diagram**: Describes the state transitions of the **Meal Preparation Module**, covering states like **Idle**, **Simple Preparation**, and **Request Human Input**.
3. **Activity Diagram**: Outlines the robot’s workflow, from sensing the environment to task execution and decision-making.


### Future Extensions
Complex Task Handling: Add more sophisticated task management where the robot can handle multi-step tasks that involve both cleaning and meal preparation.
Improved Human Interaction: Enhance natural language processing capabilities for more fluid interaction with the elderly person.
Adaptive Learning: Incorporate machine learning to allow A-19 to adapt its behavior based on past interactions and user feedback.

### Conclusion
This cognitive architecture ensures that A-19 can autonomously manage complex household tasks, interact with humans, and handle uncertain environments with minimal human intervention. By integrating cloud-based and on-premises components, A-19 can efficiently balance processing tasks and real-time actions, ensuring optimal performance in home assistance.

