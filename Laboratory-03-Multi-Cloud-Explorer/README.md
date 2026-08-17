# Laboratory Activity 3: Multi-Cloud Explorer

This folder contains my research, comparisons, and recommendations for AWS, Microsoft Azure, and Google Cloud Platform (GCP) as part of Mission 3: Become a Multi-Cloud Explorer.

## Contents
- aws-research.md
- azure-research.md
- gcp-research.md
- cloud-platform-comparison.md
- client-recommendations.md
- reflection.md
- screenshots/
## Checkpoint 7: Linux to Cloud Migration

If this Ubuntu Linux server (running on KillerCoda) were migrated to the cloud, it could be hosted using the following equivalent services:

- **AWS:** Amazon EC2 (Elastic Compute Cloud) with an Ubuntu AMI, sized based on the CPU and memory specs gathered from the terminal (`lscpu`, `free -h`), and EBS (Elastic Block Store) for the disk storage shown by `df -h`.
- **Azure:** Azure Virtual Machines using an Ubuntu image, matched to a VM size with equivalent vCPU and RAM, paired with Azure Managed Disks for storage.
- **GCP:** Compute Engine using an Ubuntu-based VM instance, sized according to the same CPU/memory requirements, with Persistent Disk for storage.

All three platforms offer virtual machine services that can replicate this Linux environment's specifications (OS, CPU, memory, and disk space) in the cloud.
