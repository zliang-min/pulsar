---
id: helm-install
title: Install Apache Pulsar using Helm
sidebar_label: "Install "
---

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';


Install Apache Pulsar on Kubernetes with the official Pulsar Helm chart.

## Requirements

To deploy Apache Pulsar on Kubernetes, the followings are required.

- kubectl 1.14 or higher, compatible with your cluster ([+/- 1 minor release from your cluster](https://kubernetes.io/docs/tasks/tools/install-kubectl/#before-you-begin))
- Helm v3 (3.0.2 or higher)
- A Kubernetes cluster, version 1.14 or higher

## Environment setup

Before deploying Pulsar, you need to prepare your environment.

### Tools

Install [`helm`](helm-tools.md) and [`kubectl`](helm-tools) on your computer.

## Cloud cluster preparation

To create and connect to the Kubernetes cluster, follow the instructions:

- [Google Kubernetes Engine](helm-prepare.md#google-kubernetes-engine)

## Pulsar deployment

Once the environment is set up and configuration is generated, you can now proceed to the [deployment of Pulsar](helm-deploy).

## Pulsar upgrade

To upgrade an existing Kubernetes installation, follow the [upgrade documentation](helm-upgrade).
