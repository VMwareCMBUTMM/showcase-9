# Field Showcase - All Apps Organization - Blueprints

This repository section, located at `showcase-9/showcase-all-apps/cloudTemplates`, contains a collection of blueprints designed to demonstrate various deployment scenarios and functionalities within VMware Cloud Foundation Automation.
These blueprints are used in the field showcase environment and can be used as examples and starting points for users to understand and implement their own deployments.

# Contents
The cloudTemplates directory includes blueprint yaml files for use in VCF Automation:

* **Opencart K8s Application:** Template for deploying the Opencart shopping cart application in a VKS Cluster, along with a MySQL database in a VM Service machine.
* **Opencart VM Application:** Demostrates how its easy to create kubernetes backed vm's to run an Opencart Application on an Apache, and a MySQL VM.
* **Web Server:** Templates showcasing how to quickly get started prvisioning a Apache web server.

# Property Group
As part of this environment's goal to create environment-agnostic content that is easily shareable, we leverage a property group called `environment`.
The following are the `environment` constant property groups `string` variables.

| environment |  |  |
| :---- | :---- | :---- |
| Name | Type | Constant Value |
| domain | string | \<domain fqdn\> |
| ops\_a | string | \<ops instance fqdn\> |
| opscollector\_01a | string | \<ops collector IP\> |
| opslogs\_01a | string | \<ops logs IP\> |
| nameserver1 | string | \<nameserver 1 IP\> |
| nameserver2 | string | \<nameserver 2 IP\> |
| ubuntu1804 | string | vmi-\<id\> |
| www | string | \<webserver fqdn\> |


