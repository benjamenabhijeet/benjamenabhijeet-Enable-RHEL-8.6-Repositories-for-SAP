# benjamenabhijeet-Enable-RHEL-8.6-Repositories-for-SAP
Enable RHEL 8.6 Repositories for SAP with HA using Ansible playbook
📋 Overview
This Ansible playbook configures a RHEL 8.6 system by:

Setting the release version to 8.6

# Enabling all required repositories for SAP with High Availability (HA) solutions

✅ Prerequisites
✅ Target host must be a registered RHEL system

✅ Ensure passwordless SSH access from the Ansible control node

✅ Ansible must be installed on the control node

# This playbook performs:

subscription-manager release --set=8.6

Enables the following repos:

rhel-8-for-x86_64-baseos-rpms

rhel-8-for-x86_64-appstream-rpms

rhel-8-for-x86_64-sap-solutions-rpms

rhel-8-for-x86_64-highavailability-rpms

sap-netweaver-for-rhel-8-x86_64-rpms (optional)
![image alt](https://github.com/benjamenabhijeet/benjamenabhijeet-Enable-RHEL-8.6-Repositories-for-SAP/blob/aae4794badb0639cfa877800d209f4026f21fcdb/enable_repo_for_SAP_system.jpg)

