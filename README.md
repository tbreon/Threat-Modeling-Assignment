# Threat Modeling Assignment

## Overview
This repository contains the initial setup for the **Threat Modeling Assignment**. The goal is to design a **data flow diagram (DFD)** and perform a **threat analysis** using the **STRIDE model** for a sample web application.

## Application Description
The sample web application performs the following:
1. Presents a login page for username and password entry.
2. Uses an open source authentication component to validate credentials against a database.
3. Displays a “message of the day” (MOTD) to authenticated users.
4. Allows users to submit comments on the MOTD, which are stored in the database.

## Tools Used
- **ThreatDragon** – used to create the data flow diagram and identify threats.
- **GitHub** – used to host and version-control the repository.
- **STRIDE Model** – used to categorize and analyze potential security threats.

## Objectives
- Create a complete DFD representing the application architecture.
- Identify at least five threats using the STRIDE model:
  - **S**poofing  
  - **T**ampering  
  - **R**epudiation  
  - **I**nformation Disclosure  
  - **D**enial of Service  
  - **E**levation of Privilege
- Evaluate how the open source authentication component introduces additional risks.
- Recommend one appropriate action for a specific threat:
  - Mitigate, Accept, Transfer, Inform, or Do Nothing.

## Deliverables
- Screenshot of the completed data flow diagram.
- 750–1,000 word threat analysis paper describing:
  - The DFD
  - Identified threats and their STRIDE categories
  - Impacts of the open source component
  - Recommended threat mitigation or handling approach
- All references formatted in **APA 7th edition** style.

## Author
**Travis Breon**  
Grand Canyon University – MSSE Program  
Course: Advanced Software Security
