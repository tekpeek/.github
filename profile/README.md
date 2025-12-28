# Systems Engineering & Cloud-Native Experiments

**TekPeek** serves as an archive for experiments in distributed systems, automation, and cloud-native infrastructure. This organization houses projects focused on Kubernetes operators, microservices architecture, and Linux system utilities.

## Core Methodology

The projects within this organization adhere to the following engineering principles:

- **Microservices Architecture**: decoupled services with defined API contracts.
- **Observability**: integrating logging and monitoring for operational visibility.

## Project Initiatives

| Project | Architecture & Function | Technology Stack |
| :--- | :--- | :--- |
| **[StockFlow](https://github.com/TekPeek/StockFlow)** | A strictly coupled set of microservices deployed on Kubernetes for real-time stock analysis. Processes market data streams to generate algorithmic trading signals. | **Python, Kubernetes, Docker, Microservices** |
| **[Kubesnap](https://github.com/TekPeek/Kubesnap)** | A lightweight utility for namespace-level observability. Captures and aggregates pod logs, persistently archiving snapshots to S3-compatible object storage. | **Python, Shell, AWS S3 / Object Storage** |

## Technical Stack

Tools and technologies utilized across TekPeek repositories:

- **Orchestration**: Kubernetes, Docker Compose
- **Languages**: Python, Bash/Shell
- **Infrastructure**: Linux (Kernel/Filesystem interactions), CI/CD Pipelines
- **Storage**: Object Storage (S3 Standard)

## Maintainer

Maintained by **[Avinash S](https://github.com/AvinashSubhash)** as a continuous portfolio of systems engineering work.
