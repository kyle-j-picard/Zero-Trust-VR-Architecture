# Zero Trust Architecture for Enterprise VR Headsets

This repository contains an architectural proposal and a technical deployment report for securing unmanaged Virtual Reality (VR) headsets in an enterprise remote work environment. 

As organizations deploy immersive IoT hardware like the Meta Quest Pro, these devices continuously process highly sensitive biometric and spatial telemetry. If connected directly to a corporate VPN without verification, they create a massive attack surface. This project outlines a comprehensive Zero Trust solution to remediate this vulnerability.

## Repository Contents

* **`Documentation/Zero_Trust_VR_Architectural_Proposal.pdf`**
  This document outlines the theoretical architecture, detailing the integration of strict Mobile Device Management (MDM) posture checks, a dedicated isolated VLAN, and mandatory TLS 1.3 encryption to protect mission-critical systems.

* **`Documentation/Zero_Trust_VR_Deployment_Report.pdf`**
  This document details the simulated technical rollout of the architecture. It covers real-world deployment challenges, such as fine-tuning Cisco VPN authentication timers to prevent dropped connections during health checks, configuring scalable log aggregation, and validating the 100% compliance rate.
