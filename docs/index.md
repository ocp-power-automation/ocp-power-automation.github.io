# Deploying OpenShift on IBM Power Systems

This Github organization is home to Infrastructure as Code (IaC) patterns to help deploy OpenShift on IBM Power Systems. Terraform is used to create the infrastructure and ansible playbooks are used to deploy and customize OpenShift. The following diagram shows the high level overview of the IaC pattern:

![Automation Architecture](https://github.com/ktania46/image/blob/main/OCPPowerAutomationArchDiag.png?raw=true)

## Contents:

- [Deploying OpenShift on IBM Cloud Power Virtual Servers](powervs.md)
     - Introduction 
     - Automation Host Prerequisites 
     - PowerVS Prerequisites 
     - OCP Install </br>
&nbsp;
- [Deploying OpenShift on KVM](ocp_kvm.md)
     - Introduction 
     - Prerequisites
     - Image and VM Requirements 
     - OCP Install </br>
&nbsp;
- [Deploying OpenShift on PowerVM managed via PowerVC ](powervm.md)
     - Introduction 
     - Prerequisites 
     - Image and LPAR Requirements 
     - OCP Install </br>
&nbsp;

