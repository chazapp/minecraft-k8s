# minecraft-k8s
A Kubernetes x Minecraft implementation

## Content
This repository contains the following stack for a Minecraft server:
  - itzg/minecraft-server base image
  - PaperMC server, with Geyser + Floodgate for Java/Bedrock interoperability
  - Prometheus metrics exporter

## Usage
Apply these files to your cluster, point your DNS to the LoadBalancer IP.
