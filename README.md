# RH Summit Connect 2022 ZTP Edge Demo

## Overview
A collection of resources used to provision Single Node Openshift (SNO) with the Zero Touch Provisioning (ZTP) method on RHACM.

ZTP is based on a hub/spoke hierarchy to organize the hub cluster and the managed SNOs. Therefore,
the repository manifests necessary to run a basic demo are organized in two main folders:
- **hub**: this folder contains all the necessary manifests to configure the RHACM hub.
- **spoke**: this folder contains all the necessary manifests to reconcile machine discovery and provisioning with the Assisted Installer and Metal3 and trigger the OpenShift installation with Hive.

### Additional folders
The **subscription** folder contains all the manifests to orchestrate the provisioning using RHACM subscriptions using a GitOps approach.  
The **utils** folder contains extra utils to configure the host (for example Ansible automations to install and configure Sushy Tools).

## Quickstart
TODO

## Authors
Gianni Salinetti - gsalinet@redhat.com  
Nicolo' Amato - namato@redhat.com  

