**<h2 style="text-align:center;">Deploying Openshift on IBM Cloud Power Virtual Servers</h2>**
<!-- # Table of Contents -->

- [Introduction](#introduction)
- [Automation Host Prerequisites](#automation-host-prerequisites)
- [PowerVS Prerequisites](#powervs-prerequisites)
- [OCP Install](#ocp-install)
- [Contributing](#contributing)


## Introduction

[PowerVS](https://github.com/ocp-power-automation/ocp4-upi-powervs) contains Terraform templates to help deployment of OpenShift Container Platform (OCP) 4.x on [IBM® Power Systems™ Virtual Server on IBM Cloud](https://www.ibm.com/cloud/power-virtual-server).

This project leverages the helpernode [ansible playbook](https://github.com/RedHatOfficial/ocp4-helpernode) internally for OCP deployment on IBM Power Systems Virtual Servers (PowerVS).

> <i class="fa fa-exclamation" style="color:red;"></i> *For bugs/enhancement requests etc. please open a GitHub issue.*

For general PowerVS usage instructions please refer to the following links:

- [Getting started with IBM Power Systems Virtual Servers](https://cloud.ibm.com/docs/power-iaas?topic=power-iaas-getting-started) 
- [Multi-cloud on IBM Power Systems](https://www.youtube.com/watch?v=RywSfXT_LLs) [youtube video]
- [PowerVS in IBM Cloud](https://www.youtube.com/playlist?list=PLVrJaTKVPbKM_9HU8fm4QsklgzLGUwFpv) [youtube video]


> <i class="fa fa-info-circle" style="color:blue;"></i> *This branch must be used with latest OCP pre-release versions only. For stable releases please checkout specific release branches - {release-4.5, release-4.6 ...} and follow the docs.*


## Automation Host Prerequisites

The automation needs to run from a system with internet access. This could be your laptop or a VM with public internet connectivity. This automation code have been tested on the following Operating Systems:
- Mac OSX (Darwin)
- Linux (x86_64)
- Windows 10

Follow the [guide](https://github.com/ocp-power-automation/ocp4-upi-powervs/blob/master/docs/automation_host_prereqs.md) to complete the prerequisites.

## PowerVS Prerequisites

Follow the [guide](https://github.com/ocp-power-automation/ocp4-upi-powervs/blob/master/docs/ocp_prereqs_powervs.md) to complete the PowerVS prerequisites.

## OCP Install

Follow the [quickstart](https://github.com/ocp-power-automation/ocp4-upi-powervs/blob/master/docs/quickstart.md) guide for OCP installation on PowerVS.


## Contributing
Please see the [contributing doc](https://github.com/ocp-power-automation/ocp4-upi-powervs/blob/master/CONTRIBUTING.md) for more details.
PRs are most welcome !!
