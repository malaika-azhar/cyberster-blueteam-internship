![Status](https://img.shields.io/badge/status-in%20progress-yellow) ![Track](https://img.shields.io/badge/track-Blue%20Team-blue) ![Phase](https://img.shields.io/badge/phase-1%20of%204-lightgrey)

# Week 1 — SOC Foundations and Lab Setup

Part of the [Cyberster Blue Team Internship](../README.md).

## Overview

This week builds the lab environment used for the rest of Phase One — networking fundamentals, a 3-VM VirtualBox lab, Wazuh SIEM installation, agent deployment, and a first pass at alert triage.

## Hardware Note

My laptop (4GB RAM, AMD A6-7310) falls short of the spec needed to run all 3 VMs simultaneously as originally planned. After raising this with Cyberster support and my mentor, an interim setup was approved: using my host Windows machine as the Wazuh agent instead of a separate Windows VM, and running Ubuntu Server / Kali Linux one at a time rather than together, until a RAM upgrade is complete. This is noted in the relevant day folders below.

## Day-by-Day Status

| Day | Topic | Status |
|---|---|---|
| [Day 1](./Day-1-Networking-Fundamentals/) | Networking Fundamentals for SOC | ✅ Complete |
| [Day 2](./Day-2-VirtualBox-Lab-Setup/) | VirtualBox Lab Setup | 🔲 Pending |
| [Day 3](./Day-3-Wazuh-Manager-Installation/) | Wazuh Manager Installation (part 1) | 🔲 Pending |
| [Day 4](./Day-4-Wazuh-Manager-Installation/) | Wazuh Manager Installation (part 2) | 🔲 Pending |
| [Day 5](./Day-5-Wazuh-Agent-Deployment/) | Wazuh Agent Deployment (part 1) | 🔲 Pending |
| [Day 6](./Day-6-Wazuh-Agent-Deployment/) | Wazuh Agent Deployment (part 2) | 🔲 Pending |
| [Day 7](./Day-7-Dashboard-Navigation-Alert-Triage/) | Dashboard Navigation & Alert Triage | 🔲 Pending |

## What I'll Be Able to Explain by End of Week 1

- How log data moves from an endpoint, through a SIEM manager, into an indexer, and onto an analyst's dashboard
- Why a security lab runs isolated from the main network, and why that doesn't block internet access when needed
- How to read and triage SOC alerts using rule levels, frequency, and context — not severity alone
