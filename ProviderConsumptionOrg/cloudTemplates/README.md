# Field Showcase - Provider Consumption Organization - Blueprints

This repository section, located at `showcase-9/ProviderConsumptionOrg/cloudTemplates`, contains a collection of blueprints designed to demonstrate the blueprint sharing functionality within VMware Cloud Foundation Automation.
These blueprints are used in the field showcase environment and can be used as examples and starting points for users to understand and implement their own deployments.

# Contents
The cloudTemplates directory includes blueprint yaml files for use in VCF Automation:

* **Microsoft Windows Server:** Deploys Windows Server with inputs driving the image selection and sysprep setting the workgroup and password.
* **Ubuntu Linux Server:** Deploys a Ubuntu server with inputs for image selection along with cloud-init to configure a user and install our telegraf and logs agents.

# Property Group
Since these blueprints are shared between organizations, property groups cannot be leveraged.
