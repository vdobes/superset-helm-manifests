# Superset Helm Manifests

This repository contains example Kubernetes manifest files generated from the Superset Helm chart. 
These manifests serve as a reference for deploying Apache Superset, a modern data exploration and visualization platform, on your Kubernetes cluster.

## Overview

[Apache Superset](https://superset.apache.org/) is an open-source data exploration and visualization platform designed for business intelligence. 
While the official deployment method uses the Helm chart, this repository provides an alternative approach by using raw Kubernetes manifests generated from the Helm chart.

## Getting Started

### Prerequisites

- A running Kubernetes cluster.
- `kubectl` installed and configured to interact with your cluster.
- Helm installed for managing Kubernetes applications (for generating manifests).

### Example Deployment

   ```bash
   git clone https://github.com/vdobes/superset-helm-manifests.git
   cd superset-helm-manifests
   kubectl apply -f ./superset-helm-manifests
