# ROKS Production Deployment Guide
There are 4 proposed topologies depending on the dedploymment requirements, choose the one that adapts better to your needs.

ROKS-split-1:

![Target Architecture](./images/IBM_VPC_ROKS_split-1.jpg)

ROKS-split-2:

![Target Architecture](./images/IBM_VPC_ROKS_split-2.jpg)

ROKS-split-3:

![Target Architecture](./images/IBM_VPC_ROKS_split-3.jpg)

ROKS-split-4:

![Target Architecture](./images/IBM_VPC_ROKS_split-4.jpg)


This guide divides in 4 parts:

- Set up the VPC in IBM Cloud
- Create the VPN gateway to secure connect to te VPC
- Deploy the cluster. 4 Topologies recommended
- Deploy the GitOps strategy