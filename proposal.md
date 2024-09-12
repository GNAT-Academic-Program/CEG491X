# Project Title: 
Ada-Centered Flexible SoC Prototyping Board for Embedded Systems Development

## CEG 491X : Capstone Project

## Proposal
Submitted by: Olivier Henley    
IP: No    
Submitted to Professor/TA:     
Date Submitted: 2024-09-01    
Date Received:    
Reviewed by:    
Approved/Disapproved:   
Signature:   
Date:   
Comments:   

## Project Description
This project aims to develop a flexible SoC prototyping board focused on supporting Ada development in embedded systems. The board will feature a range of critical components, including high IO availability, Persistent RAM, HyperRAM, DDR memory, and cost-effective FPGAs (e.g., Artix7). It will also include multiple voltage rails, configurable clocks, and IO multiplexing for flexible pin routing.

The project will ensure compatibility with open-source tools (e.g., Yosys) for FPGA bitstream creation and develop an infrastructure for SoC deployment, utilizing Ada’s package manager to streamline the process. It is important to note that the project will primarily focus on packaging existing, functioning open-source IPs, meaning students are not expected to implement complex IPs such as MCU cores.

Simple extension boards will be designed to demonstrate the board's capabilities, with thorough documentation provided, including templates for the EDA of extensions and a pinout sharing system.

## Project Goals
- Develop the SoCs Prototyping Board: Focus on delivering a cost-effective and highly flexible platform for Ada-based embedded development.
- Create SoC Deployment Infrastructure: Implement an open-source infrastructure for FPGA development, with a focus on Ada integration.
- Design and Document Extension Boards: Create and document simple extension boards to demonstrate and expand the platform’s capabilities.
- Showcase a Working Example: Deploy a RISC-V SoC with Ada firmware as a reference implementation to demonstrate the board’s full potential.

## Functional Requirements
- A flexible SoCs prototyping board featuring high IO availability, HyperRAM, DDR memory, FPGA (ECP5/Artix7), multiple voltage rails, and configurable clocks.
- Infrastructure to support FPGA bitstream creation using open-source tools.
- Support for Ada’s package manager for SoC deployment.


## Non-Functional Requirements
- Modularity: Design should allow seamless integration with extension boards.
- Documentation: Comprehensive documentation, including pinouts, design templates, and user guidelines.
- Cost-Effectiveness: Prioritize components that deliver high performance at a reasonable cost.


## Hardware and Software Architecture (Draft)
- Hardware Components: The main SoCs prototyping board includes an Artix7 FPGA, HyperRAM, Persistent RAM, DDR memory, multiple voltage rails, and configurable clocks.
- Extension Boards: Simple, detachable boards to expand capabilities.
- Software Components: Support for Ada firmware deployment, with the SoC deployment infrastructure utilizing open-source tools and Ada’s package manager.

(A detailed diagram of the architecture will be attached in the formal submission)

## Work Breakdown Structure (WBS)

### Board Development:
- Design SoCs prototyping board layout.
- Select essential components (FPGA, memory, IO).
- Develop power and clock management.

### Extension Board Design:
- Brainstorming features and form factors.
- Designing simple extension boards for demonstration.

### SoC Deployment Infrastructure:
- Integrate open-source tools for bitstream creation.
- Implement support for Ada package manager.

### Documentation:
- Pinout and template documentation for extension boards.
- Create user manuals and setup guides.

### Demonstration and Testing:
- Implement a RISC-V SoC running Ada firmware.
- Showcase the capabilities with extension boards.

(A detailed WBS chart will be attached in the formal submission)

## Gantt Chart (Draft)
The Gantt chart will illustrate the timeline for each phase of the project:

- Phase 1: Initial Design and Component Selection (Weeks 1-4)
- Phase 2: Board Layout and Prototyping (Weeks 5-10)
- Phase 3: SoC Deployment Infrastructure (Weeks 11-15)
- Phase 4: Documentation and Final Testing (Weeks 16-20)
(A detailed Gantt chart will be attached in the formal submission)

## Personal/Professional Expectations

From this project, I expect to gain deeper experience in FPGA design, SoC architecture, and embedded systems development with a focus on Ada programming. Professionally, I hope to enhance my skills in designing flexible hardware platforms, while personally, I aim to develop better teamwork and project management skills by collaborating with peers on an advanced, real-world system.

## Project Implementation Phase
SCRUMS and SPRINTS
The project will follow SCRUM methodology to ensure effective progress and agile responses to challenges. Each SCRUM will involve:

- Sprint Planning: At the start of each sprint, we will outline the goals for that cycle.
- Daily SCRUM Meetings: Daily check-ins to discuss progress and identify blockers.
- Sprint Review: At the end of each sprint, we will review accomplishments and adjust the plan for the next sprint.
- The first SCRUM will focus on setting up the board layout, selecting components, and establishing a clear architecture for the SoC prototyping board.

## Specifications and Formal Requirements
- High IO Availability: The board must support multiple IO interfaces and allow flexible pin routing.
- Component Integration: The board must integrate HyperRAM, DDR memory, ECP5/Artix7 FPGA, and support multiple voltage rails.
- FPGA Toolchain Support: Ensure compatibility with open-source tools like Yosys, Nextpnr, and LiteX for FPGA bitstream creation.
- SoC Deployment: Implement a deployment process that supports Ada’s package manager for managing SoC and firmware deployment.
- Extension Boards: Simple and modular extension boards must be designed and thoroughly documented.

## Architecture and Subsystem Components
The architecture consists of:

- Core Board: FPGA, memory components, and power management systems.
- SoC Infrastructure: Firmware deployment tools, Ada support.
- Extension Modules: Expansion boards that interface with the main SoC board.
- Each subsystem will be designed and integrated independently to allow maximum flexibility during development and testing.

## Work Breakdown Structure (WBS) and Group Tasks
Group Member 1: Focus on FPGA design, ensuring the board’s compatibility with the selected components and tools.
Group Member 2: Handle the extension board design and the documentation of standard connections.
Group Member 3: Implement the SoC infrastructure, integrating Ada’s package manager and open-source tools.
Group Member 4: Oversee documentation, including templates and pinout sharing systems, and assist with the RISC-V SoC demonstration.