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

* **[Rescale](https://rescale.com/)**
  Full-stack HPC SaaS platform for engineering, scientific computing, simulation, AI/ML, and distributed workloads. Rescale provides cloud HPC orchestration, application environments, workflow automation, and access to multiple cloud infrastructures.

* **[Azure CycleCloud](https://azure.microsoft.com/products/cyclecloud/)**
  Enterprise HPC orchestration and management platform for Microsoft Azure, supporting schedulers such as Slurm, PBS Pro, LSF, Grid Engine, and HTCondor with automated cluster scaling.

* **[AWS ParallelCluster](https://aws.amazon.com/hpc/parallelcluster/)**
  Open-source cluster management tool from AWS for deploying and dynamically scaling HPC environments on AWS using schedulers such as Slurm and AWS Batch. Although the software is open source, it is included here because its primary role is provisioning HPC infrastructure as an AWS cloud service.

* **[Google Cloud HPC Toolkit](https://cloud.google.com/hpc-toolkit)**
  Google Cloud's open-source toolkit for creating repeatable, turnkey HPC clusters using infrastructure-as-code and established HPC best practices.

* **[Nimbix](https://www.nimbix.net/)**
  HPC cloud platform focused on accelerated computing, engineering simulation, AI, scientific workloads, and specialized compute infrastructure.

* **[Altair One](https://altair.com/altair-one)**
  Cloud-based engineering and HPC environment providing access to simulation, AI, data analytics, and distributed computing resources.

* **[Penguin Solutions](https://www.penguinsolutions.com/)**
  HPC and AI infrastructure provider offering cloud, hosted, bare-metal, and managed HPC environments for technical computing workloads.

* **[UberCloud](https://www.ubercloud.com/)**
  HPC cloud marketplace and ecosystem connecting technical-computing users with cloud HPC infrastructure, applications, and service providers.

* **[Sabrewing HPC](https://www.sabrewing.com/)**
  HPC-focused infrastructure and cloud-computing services for technical and scientific workloads.

* **[HPCNow!](https://www.hpcnow.com/)**
  HPC infrastructure and cloud services provider focused on deploying and operating high-performance computing environments.

### Other Strong Commercial / Hosted Options

* **[AWS HPC / AWS Parallel Computing Service](https://aws.amazon.com/hpc/)**
  AWS services for elastic HPC infrastructure, workload orchestration, networking, storage, and managed cluster environments.

* **[Google Cloud HPC](https://cloud.google.com/hpc)**
  Cloud HPC infrastructure built around high-performance compute, storage, networking, GPUs, and cluster orchestration.

* **[Azure HPC](https://azure.microsoft.com/solutions/high-performance-computing/)**
  Azure's collection of HPC compute, storage, networking, scheduler, and cluster-management services.

* **[Oracle Cloud HPC](https://www.oracle.com/cloud/hpc/)**
  HPC infrastructure and bare-metal compute designed for engineering, scientific, simulation, and compute-intensive workloads.

* **[CoreWeave](https://www.coreweave.com/)**
  GPU-focused cloud infrastructure increasingly used for large-scale AI/HPC workloads.

* **[Lambda](https://lambdal.com/)**
  GPU cloud and infrastructure provider supporting AI, machine learning, and high-performance accelerated workloads.

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
