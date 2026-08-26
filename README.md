# Awesome-High-Performance-Computing-Cloud

## Top High-Performance Computing (HPC) Cloud Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Cloud HPC, Elastic Cluster Provisioning, Scientific Computing & High-Performance Workloads*
**Last updated: August 2026**

This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **High-Performance Computing (HPC) Cloud**. These platforms enable organizations to provision, orchestrate, scale, monitor, and operate HPC clusters across public clouds, private infrastructure, hybrid environments, and specialized bare-metal systems.

**Examples** include Rescale, Azure CycleCloud, AWS ParallelCluster, Google Cloud HPC Toolkit, Nimbix, Altair One, Penguin Computing, UberCloud, Sabrewing HPC, and HPCNow!.

**Open-source emphasis**: This section is heavily expanded with open-source HPC cluster managers, schedulers, cloud-bursting frameworks, self-service portals, provisioning systems, infrastructure-as-code tools, and complete private-cloud/HPC management platforms. These projects can be combined to build self-hosted alternatives to commercial HPC-cloud platforms.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites or repositories.

## Table of Contents

* [SaaS/Hosted Platforms](#saashosted-platforms)
* [Open-Source GitHub Projects](#open-source-github-projects)
* [How to Contribute](#how-to-contribute)
* [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform | Description | Starting Pricing | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Rescale](https://rescale.com/)** | Full-stack HPC SaaS platform for engineering, simulation, AI/ML, and workflow automation across multiple clouds. | Starts at ~$0.04/core-hour for basic compute + Foundation platform tier | 5-day free trial with up to 500 core-hours / promotional compute credits upon evaluation request |
| **[Azure CycleCloud](https://azure.microsoft.com/products/cyclecloud/)** | Enterprise HPC cluster orchestration and scheduler management (Slurm, PBS Pro, LSF) on Microsoft Azure. | $0 for CycleCloud software; underlying Azure compute starts at $0.0104/hr (B1s VM) or $0.096/hr (D2s v5) | Azure Free Account: $200 credit for 30 days + 12 months free access to 750 hrs/month of B1s VMs + 55+ always-free services |
| **[AWS ParallelCluster](https://aws.amazon.com/hpc/parallelcluster/)** | AWS cluster deployment and management tool for dynamically scaling Slurm and batch HPC workloads. | $0 for ParallelCluster software; underlying AWS compute starts at $0.0104/hr (t3.micro) or $0.0416/hr (t3.medium) | AWS Free Tier: 750 hrs/month of t2.micro or t3.micro instances for 12 months + 5 GB S3 standard storage |
| **[Google Cloud HPC Toolkit](https://cloud.google.com/hpc-toolkit)** | Modular framework for deploying turnkey, repeatable HPC environments and Slurm clusters via Infrastructure-as-Code on GCP. | $0 for HPC Toolkit; underlying GCP compute starts at $0.0084/hr (e2-micro) or $0.0336/hr (e2-standard-2) | GCP Free Tier: $300 credit for 90 days + Always Free tier (1 non-preemptible `e2-micro` VM with 1 GB RAM & 30 GB standard disk/month) |
| **[Nimbix (JARVICE Cloud)](https://www.nimbix.net/)** | Accelerated HPC and AI cloud platform providing containerized simulation, processing, and visualization workflows. | Starts at $0.15/core-hour for CPU nodes; $0.49/GPU-hour for entry GPU instances | No perpetual free tier; 14-day evaluation pilot with 50–100 free core-hours upon request |
| **[Altair One](https://altair.com/altair-one)** | Cloud portal for CAE simulation, data analytics, and scalable HPC solver workloads powered by Altair Units. | Starts at ~$1,500/year for base Altair Units (AU) license pack (~$0.10–$0.50/AU-hour for cloud solver bursts) | 14-day free trial with full portal access to Altair simulation and modeling applications |
| **[Penguin Solutions (POD)](https://www.penguinsolutions.com/)** | HPC and AI bare-metal infrastructure provider offering on-demand clusters and managed computing environments. | Starts at ~$0.10/core-hour for bare-metal CPU compute nodes (~$1.50/GPU-hour for accelerated instances) | No perpetual free tier; 30-day proof-of-concept trial with 500–1,000 core-hours upon sales qualification |
| **[Simr (UberCloud)](https://www.ubercloud.com/)** | HPC cloud platform for running engineering simulations in containerized cloud environments across AWS, Azure, and GCP. | Starts at ~$125/user/month base platform subscription (or BYOC with cloud compute starting at ~$0.05/core-hr) | 30-day free trial for engineering teams with evaluation support and pre-configured simulation containers |
| **[Sabalcore / Sabrewing HPC](https://www.sabrewing.com/)** | Bare-metal scientific and engineering HPC cloud service with pre-installed technical computing applications. | $0.14/core-hour on-demand ($0.10/core-hour prepaid volume pricing) | Free trial with 1,000 free core-hours + 100 GB storage for 30 days upon sign-up |
| **[HPCNow!](https://www.hpcnow.com/)** | Specialized managed HPC cloud operations, cluster architecture, support, and optimization services. | Starts at ~$100/cluster-hour or ~$1,200/month for managed cluster operations + underlying cloud VM costs | No perpetual free tier; 14-day initial infrastructure assessment and proof-of-concept consultation trial |

### Other Strong Commercial / Hosted Options

| Platform | Description | Starting Pricing | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- |
| **[AWS Parallel Computing Service (AWS PCS)](https://aws.amazon.com/hpc/)** | Fully managed service for building and operating Slurm-based HPC clusters on AWS. | $0.007/hr (Small controller) + $0.0821/hr node management fee + underlying EC2 (starts at $0.0104/hr) | AWS Free Tier: 750 hrs/month of t3.micro for 12 months; AWS POC grants available up to $300+ |
| **[Google Cloud HPC](https://cloud.google.com/hpc)** | High-performance compute, networking, TPU/GPU infrastructure, and GCP Batch scheduler for scientific computing. | $0 for GCP Batch scheduler; compute instances start at $0.0084/hr (`e2-micro`) or $0.0336/hr (`e2-standard-2`) | $300 credit for 90 days + Always Free tier (1 `e2-micro` VM with 1 GB RAM & 30 GB standard persistent storage/month) |
| **[Azure HPC](https://azure.microsoft.com/solutions/high-performance-computing/)** | Cloud HPC infrastructure including HBv3/HBv4/HX instances, InfiniBand networking, and Azure Batch job scheduling. | $0 for Azure Batch scheduler; compute instances start at $0.0104/hr (B1s) or $0.096/hr (D2s v5) | $200 credit for 30 days + 12 months free access to 750 hrs/month of B1s VMs + 55+ always-free services |
| **[Oracle Cloud HPC](https://www.oracle.com/cloud/hpc/)** | High-performance bare-metal computing with ultra-low latency cluster networking for engineering simulations and AI. | Starts at $0.01/OCPU-hour (Ampere A1), $0.04/core-hour (standard x86), or $10.00/GPU-hour (NVIDIA H100) | Always Free tier: 4 OCPUs & 24 GB RAM (Ampere A1) + 2 AMD VMs (1/8 OCPU, 1 GB RAM each) + 200 GB block storage; plus $300 credit for 30 days |
| **[CoreWeave](https://www.coreweave.com/)** | Specialized GPU cloud provider for AI training, machine learning, and accelerated HPC simulations. | Starts at $0.06/vCPU-hour or $1.25/GPU-hour (NVIDIA L40), $2.70/GPU-hour (A100 80GB), $6.16/GPU-hour (H100 SXM5) | No perpetual free tier; Accelerator Program provides up to $10,000–$25,000 in GPU cloud credits for approved startups and researchers |
| **[Lambda (Lambda GPU Cloud)](https://lambdal.com/)** | Cloud GPU infrastructure with 1-click clusters for deep learning, AI modeling, and accelerated computing. | Starts at $0.50/GPU-hour (entry GPUs), $1.29/GPU-hour (A100 40GB/80GB), $2.49/GPU-hour (H100 PCIe) | No perpetual free tier; Lambda Research Grant provides up to $5,000 in compute credits for academic AI/HPC research |

## Open-Source GitHub Projects

* **[AWS ParallelCluster](https://github.com/aws/aws-parallelcluster)**
  Open-source HPC cluster deployment and management framework for AWS. It automates infrastructure provisioning, cluster configuration, scheduler setup, and elastic scaling.

* **[Google Cloud HPC Toolkit](https://github.com/GoogleCloudPlatform/hpc-toolkit)**
  Open-source infrastructure framework for creating repeatable HPC environments on Google Cloud, including compute, networking, storage, schedulers, and software stacks.

* **[Open OnDemand](https://github.com/OSC/ondemand)**
  Open-source browser-based HPC portal providing web terminals, file management, job submission, monitoring, and interactive applications such as Jupyter and RStudio.

* **[Slurm](https://github.com/SchedMD/slurm)**
  Industry-standard open-source workload manager and job scheduler for Linux clusters. Provides resource allocation, job scheduling, accounting, and cluster management.

* **[OpenHPC](https://github.com/openhpc/ohpc)**
  Community-driven collection of HPC packages, tools, libraries, and cluster-management components for constructing production HPC environments.

* **[Warewulf](https://github.com/warewulf/warewulf)**
  Open-source HPC cluster provisioning and management platform supporting large-scale stateless and container-based compute-node deployment.

* **[xCAT](https://github.com/xcat2/xcat-core)**
  Open-source infrastructure provisioning and management framework for HPC clusters, bare-metal servers, virtual machines, and data centers. It supports OS provisioning, hardware discovery, remote management, and cloud integration.

* **[OpenStack](https://github.com/openstack/openstack)**
  Open-source private-cloud infrastructure platform that can provide compute, networking, storage, and tenant management underneath self-hosted HPC clouds.

* **[Waldur](https://github.com/waldur/waldur-mastermind)**
  Open-source cloud and HPC management platform providing self-service provisioning, OpenStack and Slurm integration, accounting, billing, and resource management.

* **[ColdFront](https://github.com/ubccr/coldfront)**
  Open-source allocations-management platform for HPC centers, handling resource requests, allocations, users, projects, and integration with HPC systems.

* **[Open XDMoD](https://github.com/ubccr/xdmod)**
  Open-source HPC operational analytics and monitoring platform providing job, CPU, wait-time, wall-time, application, and infrastructure-performance metrics.

* **[StackHPC Slurm Appliance](https://github.com/stackhpc/ansible-slurm-appliance)**
  Open-source Ansible-based reference environment for deploying Slurm HPC clusters with OpenTofu, OpenHPC packages, shared storage, monitoring, accounting, and Open OnDemand.

* **[OpenTofu](https://github.com/opentofu/opentofu)**
  Open-source infrastructure-as-code engine useful for reproducible provisioning of HPC infrastructure across clouds and private environments.

* **[Terraform](https://github.com/hashicorp/terraform)**
  Infrastructure-as-code platform widely used for automating cloud HPC infrastructure, networking, storage, identity, and cluster resources.

* **[Ansible](https://github.com/ansible/ansible)**
  Open-source automation framework commonly used to configure HPC nodes, software environments, schedulers, storage, and cluster services.

* **[HTCondor](https://github.com/htcondor/htcondor)**
  Open-source high-throughput computing workload-management system suitable for distributed compute environments and opportunistic cloud resources.

* **[OpenPBS](https://github.com/openpbs/openpbs)**
  Open-source workload manager and scheduler descended from the PBS family and designed for HPC, cloud, and large-scale compute clusters.

* **[Flux](https://github.com/flux-framework/flux-core)**
  Modern open-source resource-management and scheduling framework designed for large-scale HPC systems and capable of hierarchical workload management.

* **[Kubernetes](https://github.com/kubernetes/kubernetes)**
  Open-source container orchestration platform increasingly used for GPU/HPC clusters, cloud-native scientific computing, batch workloads, and AI infrastructure.

* **[Kueue](https://github.com/kubernetes-sigs/kueue)**
  Kubernetes-native job queueing system designed to manage quotas, queues, priorities, and resource allocation for batch and AI workloads.

* **[Volcano](https://github.com/volcano-sh/volcano)**
  Kubernetes-native batch scheduler designed for HPC, AI, machine learning, and other high-performance workloads.

* **[SkyPilot](https://github.com/skypilot-org/skypilot)**
  Open-source framework for running AI and compute workloads across multiple clouds and Kubernetes clusters, with automated provisioning and cost-aware resource selection.

* **[Cloud-Hypervisor](https://github.com/cloud-hypervisor/cloud-hypervisor)**
  Open-source cloud-native virtual machine monitor useful for building specialized compute infrastructure and lightweight virtualized HPC environments.

### Additional Strong Open-Source Options

* **[OpenPBS](https://github.com/openpbs/openpbs)** for PBS-style HPC scheduling and workload management.
* **[HTCondor](https://github.com/htcondor/htcondor)** for high-throughput and distributed computing.
* **[Flux Framework](https://github.com/flux-framework/flux-core)** for next-generation HPC resource management.
* **[Kueue](https://github.com/kubernetes-sigs/kueue)** for Kubernetes batch scheduling and quota management.
* **[Volcano](https://github.com/volcano-sh/volcano)** for Kubernetes-native HPC and AI scheduling.
* **[OpenStack Magnum](https://github.com/openstack/magnum)** for container orchestration integrated with private cloud infrastructure.
* **[Prometheus](https://github.com/prometheus/prometheus)** for cluster and workload monitoring.
* **[Grafana](https://github.com/grafana/grafana)** for HPC infrastructure and job-performance dashboards.
* **[Lmod](https://github.com/TACC/Lmod)** for managing HPC software environments and module stacks.
* **[Spack](https://github.com/spack/spack)** for reproducible installation and management of HPC software stacks.
* **[EasyBuild](https://github.com/easybuilders/easybuild-framework)** for automated HPC software builds and deployment.
* **[Apptainer](https://github.com/apptainer/apptainer)** for secure, portable containers on HPC clusters.
* **[OpenMPI](https://github.com/open-mpi/ompi)** for distributed-memory parallel computing using MPI.
* **[MPICH](https://github.com/pmodels/mpich)** for high-performance MPI implementations.
* **[BeeGFS](https://github.com/ThinkParQ/beegfs)** for parallel file-system infrastructure.
* **[Lustre](https://github.com/lustre/lustre-release)** for large-scale parallel HPC storage.
* **[Ceph](https://github.com/ceph/ceph)** for scalable distributed storage that can underpin cloud/HPC environments.
* **[PyTorch](https://github.com/pytorch/pytorch)** for distributed GPU computing and large-scale machine-learning workloads.
* **[Ray](https://github.com/ray-project/ray)** for distributed computing and elastic execution of Python/AI workloads.
* **[Dask](https://github.com/dask/dask)** for parallel and distributed Python computation.

**Frameworks for building a self-hosted HPC Cloud**: A particularly strong open-source stack can combine **OpenStack + Slurm + Warewulf + Open OnDemand + ColdFront + Open XDMoD + Spack/Lmod + Apptainer + Prometheus/Grafana**, with **OpenTofu/Ansible** for infrastructure automation. This provides many of the architectural building blocks found in commercial HPC-cloud offerings. The Open OnDemand/ColdFront/Open XDMoD combination is explicitly used as an integrated open-source HPC-center toolset.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS, hosted, or open-source.
4. Prefer active projects with public source repositories for the Open-Source section.
5. Submit a PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

* This is a **community-curated list** — not exhaustive and not an endorsement.
* Some projects listed under the SaaS/Hosted section also publish open-source components or tooling; classification is based on their primary commercial delivery model.
* Cloud HPC costs can vary substantially based on compute instances, GPUs, interconnects, storage, data transfer, scheduler configuration, and workload utilization.
* Self-hosted HPC environments require appropriate expertise in Linux, networking, security, schedulers, parallel filesystems, and cluster operations.
* Always verify the current licensing terms of individual open-source projects before using them commercially.

---

**Made for researchers, engineers, AI/ML teams, universities, national laboratories, simulation teams, and HPC infrastructure engineers.**
Let's make high-performance computing more **elastic, reproducible, accessible, and open**.
