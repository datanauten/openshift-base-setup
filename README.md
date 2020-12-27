# OpenShift Base Setup

This repository contains basic OpenShift setup files which I apply to our OpenShift cluster after installation.
These files are monitored by ArgoCD to ensure the cluster configuration is always in line with this repository. Any live changes to the cluster will be overwritten 
by ArgoCD.

## Components

### Operators
Each installation consists of a minimal set of operators wich are required for cluster operations. Additional operators can be installed on each cluster. This directory contains the installation files for the required operators.

### ArgoCD
The cluster configuration will be managed and monitored by ArgoCD. This directory contains the necessary files to deploy and configure ArgoCD in such a way, that it automatically fulfills its role.
Any live changes to the cluster will be overwritten by ArgoCD immediately. No mercy!

### Cluster Monitoring
This directory contains the monitoring configuration. Additionally to the configuration of the cluster monitoring operator itself, it also contains the alertmanager configuration as well as custom alerts.

### Authentication


### Authorization


### Network Policies


### Basic Project Configuration


### Cert Manager


### Sealed Secrets


### Cluster Backup

