# Awesome-Robotics-Devops

## Top Robotics DevOps Tools Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Fleet Observability, Incident Management & Edge Deployment*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Robotics DevOps**. These tools help robotics companies monitor fleets, manage incidents, deploy software updates, and coordinate robot operations at scale — bringing DevOps practices to the unique challenges of physical robot systems.



**Examples** include Foxglove, Formant, InOrbit, Cogniteam Nimbus, Robust AI, MOV.AI, Transitive Robotics, Tartan Sense, Polymath Robotics, and Apex.AI (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom fleet monitoring, and transparent robot observability — ideal for robotics companies prioritizing data ownership, developers building fleet infrastructure, and teams avoiding vendor lock-in.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Foxglove](https://foxglove.dev/)**  

  Visualization, observability, and data management platform purpose-built for robotics. Centralizes multimodal temporal datasets including time series, sensor logs, imagery, LiDAR/point clouds, and geospatial maps in a single integrated workspace. Supports real-time ROS/ROS 2 connections via bridges and WebSockets, with desktop apps for Linux, Windows, and macOS. Free tier includes 3 developer seats, 10 GB cloud storage, and 5 connected devices. Starting at $18/month for paid plans .



- **[Formant](https://formant.io/)**  

  Fleet observability and robot operations platform with comprehensive device management, incident management, and analytics. Features device configuration templates for bulk provisioning, group-based organization, multi-device video monitoring, custom alerting with threshold triggers, operator intervention requests (selection and labeling), and Formant Analytics for fleet uptime and incident rate reporting. Supports Slack, SMS, PagerDuty, and webhook notifications .



- **[InOrbit](https://www.inorbit.ai/)**  

  Cloud-based robot operations platform with fleet management, real-time analytics, and incident management. Features robot-agnostic agent with adaptive diagnostics, configurable dashboards, advanced teleoperation, and multi-map support. Data sampling modes include Regular (10-second intervals), Diff (on change), and Event (immediate). Compatible with ROS 1, ROS 2, and non-ROS robots through Edge SDK. Standard Edition is free to start with pay-as-you-go pricing based on monthly active robots .



- **[Cogniteam Nimbus](https://www.cogniteam.com/)**  

  Cloud robotics platform for fleet management and autonomous operations.



- **[Robust AI](https://www.robust.ai/)**  

  Cognitive robotics platform with fleet management capabilities.



- **[MOV.AI](https://www.mov.ai/)**  

  Robotics engine platform for AMR fleet management and orchestration.



- **[Transitive Robotics](https://transitiverobotics.com/)**  

  Open-source framework for full-stack robotics with hosted solution available. Provides WebRTC video streaming, remote teleoperation, and ROS tooling capabilities. Transitive 2.0 adds ClickHouse for time-series data storage, Grafana for visualization, and Alertmanager for custom alerting .



- **[Tartan Sense](https://www.tartansense.com/)**  

  Robotics platform for agricultural automation with fleet management.



- **[Polymath Robotics](https://www.polymathrobotics.com/)**  

  Autonomous vehicle software platform for industrial fleets.



- **[Apex.AI](https://www.apex.ai/)**  

  Safety-certified autonomous mobility software with fleet deployment tools.



## Open-Source GitHub Projects



- **[Transitive](https://github.com/transitiverobotics/transitive)**  

  Open-source framework for full-stack robotics with **fine-grained, namespaced access control**. Core concepts include full-stack packages (cross-device dependency management), real-time data synchronization with full-stack reactivity, and topic-based access control. Version 2.0 integrates ClickHouse for historic time-series data, Grafana for visualization, and Alertmanager for custom alerting. Includes free Health Monitoring capability with sparkline plots and 24-hour heartbeat visualization. Runs on Docker Compose with self-hosted deployment .



- **[Trillium](https://github.com/RobotnikAutomation/trillium)**  

  Free, open-source web-based robotics visualization and control application. Fork of Foxglove Studio v1.87.0 (last open-source release before Foxglove went proprietary). Features 40% smaller web app and 23% smaller desktop binaries compared to Lichtblick (another Foxglove fork). Available as web app, Docker container, or desktop installer for Linux and Windows. Extensions installable directly in browser or desktop app .



- **[OpenRobOps (ORO)](https://www.inorbit.ai/)**  

  InOrbit's open-source robot operations and fleet management layer, announced for full open-source release in 2026. Built on InOrbit's production-proven platform that has managed thousands of AMRs. Integrates natively with ROS on-device and Open RMF for coordination. Provides transparent architecture, observability, fleet control, and full data ownership. Aims to be the standard, self-hostable fleet manager for ROS developers .



- **[NexusOS](https://pypi.org/project/nexusos-robotics/)**  

  Universal OS and fleet middleware for heterogeneous robots, solving the "Tower of Babel" through zero-dependency hardware abstraction. Unifies multi-vendor fleets (mobile rovers, arms, quadrupeds, drones) under standardized messaging, control, and safety. Features asynchronous Python HAL plugin architecture (Serial, CAN, Modbus, ROS 2, MicroPython), Protobuf/WebSocket/gRPC transport, FastAPI cloud backend, and glassmorphic web dashboard with 2D pose trajectory and teleoperation. Docker Compose orchestration .



- **[Canonical Observability Stack (COS)](https://ubuntu.com/blog/roscon-2025)**  

  Fully open-source observability infrastructure for ROS 2 devices using Ubuntu. Combines Grafana, Prometheus, and Loki to provide unified monitoring for robotics fleets. Features device onboarding, automatic ros2bag uploads to self-hosted server, remote fleet monitoring, live ROS data access, Ubuntu system data and logs access, and event alerting (low battery, network loss). Demonstrated at ROSCon 2025 with Botmind fleet management integration .



- **[Lichtblick](https://github.com/lichtblick-suite/lichtblick)**  

  Another fork of Foxglove Studio maintained by BMW. Became the parent repo of Foxglove Studio forks when commit history was deleted. Provides visualization and data management for robotics development with larger binary sizes compared to Trillium (99 MB vs 76 MB for Linux .deb packages) .



### Additional Strong Open-Source Options



- **[Awesome Open Source Robots](https://github.com/stephane-caron/awesome-open-source-robots)** — Curated list of robots with open source software, hardware, and both. Includes arms, bipeds, quadrupeds, humanoids, drones, and mobile manipulators with license information .

- **[Awesome Robotics](https://github.com/ahundt/awesome-robotics)** — Curated list of robotics links and software libraries useful for robot development. 1,364 GitHub stars .

- **[Awesome Robot Descriptions](https://github.com/robot-descriptions/awesome-robot-descriptions)** — Curated list of robot descriptions (URDF, MJCF) with license and feature matrix for arms, bipeds, dual arms, drones, and end effectors .

- **ROS 2 Ecosystem** — Standard robot operating system providing middleware, tools, and libraries for fleet development.

- **Open RMF** — Open Robot Management Framework for multi-fleet coordination, integrated with OpenRobOps.



**Frameworks for building custom systems**: Combine **Transitive** for full-stack robotics with ClickHouse/Grafana/Alertmanager stack, **Trillium** for open-source Foxglove-compatible visualization, **NexusOS** for heterogeneous fleet abstraction, and **Canonical Observability Stack** for Ubuntu-based ROS 2 monitoring to build a complete self-hosted robotics DevOps platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Robotics DevOps tools must comply with safety regulations, data protection laws, and industry standards. Fleet operations require validation of monitoring and incident management workflows before production deployment.

- Self-hosted open-source solutions require proper infrastructure, security hardening, and ongoing maintenance.



---



**Made for robotics engineers, fleet operators, DevOps teams, and developers building robot operations platforms.**  

Let's make robotics DevOps more open, observable, and fleet-friendly.
