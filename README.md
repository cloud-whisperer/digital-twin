<p align="center">
  <img src="digital_twin_I_lc.jpg" alt="banner" width="100%">
</p>
<br> This serves as a PoC for a highly available, monolithic, hybrid data center.
<br>
<br>The argument is to advocate for the use of AWS services for non-core infrastructure, when permitted by 
<br>respective regulatory/compliance requirements. Whilst cloud-native network architectures are
<br>effective for certain use cases, such network architectures are not feasible for industries which
<br>require adherance to stringent workflows and documentation.
<br>
<br>Digital twins allow for predictive maintenance, provides insights into when and how assets should be
<br>upgraded or replaced, which adheres to the Cost Optimisation Pillar of the Well-Architected Framework.
<br>
<br><b>Source:</b> Digital Twin Technology: A Game-Changer for Asset Management in the Utilities Industry
<br>https://www.quinnox.com/blog/digital-twin-technology-a-game-changer-for-asset-management-in-the-utilities-industry/
<br><br>
## Table of Contents
<br> - [Digital twin project for the energy and power industry (PoC). ](#project-title-and-description)
<br> - [Tech Stack](#tech-stack)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

<br>Tech Stack #tech-stack
<br>
- **Azure**: Virtual Machines (VMs) for **Windows Server 2022**, **pfSense**, **Ubuntu**.
- **AWS**: **CloudWatch**, **Firehose**, **EventBridge**, **Lambda**, **S3**, **DataDog**, **New Relic**.
- **MySQL**: Primary database on **Azure**, backup on **Debian**.
- **VirtualBox**: For local hosting of **Debian** and **Ubuntu** VMs.
<br>

![Alt text](/images/update_26_Avril_lc_WATERMARKED_lc.jpg)

<br><b></b>Features</b>
<br>- Hybrid cloud architecture using Azure (heavy workloads) and AWS (logging, monitoring).
<br>- EventBridge for real-time alerts, remediation using Lambda.
<br>- Compliant with regulations like ISO 27001, SOC 2, GDPR.
<br>- Cost optimization by outsourcing non-critical infrastructure tasks to the cloud.
<br>- Digital Twin model for enhanced performance monitoring in the energy sector.
