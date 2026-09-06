# Day 03 - Virtualization, Containers & Cloud Computing

## Virtualization

* Learned why using a separate physical server for every application can be inefficient.
* Learned that virtualization allows multiple virtual machines to run on the same physical hardware.
* Learned that a hypervisor manages virtual machines and allows them to operate independently.

### Hypervisor Types

* **Type 1:** Runs directly on physical hardware.
* **Type 2:** Runs on top of an existing operating system.

My Ubuntu virtual machine in VMware Workstation is an example of a Type 2 virtualization setup.

## Containers

* Learned that a container is a lightweight, isolated environment used to run an application and its required components.
* Unlike a virtual machine, a container does not require a complete operating system of its own.
* Containers use the host system's kernel.

### Container Images

* Learned that a container image is a pre-packed template used to create containers.
* An image can be used to create multiple containers.

## Cloud Computing

* Learned that cloud computing allows applications to use computing resources over the internet instead of relying on a single physical machine.
* Learned that cloud services can make applications easier to scale and access.

### Cloud Benefits

* **Scalability:** Resources can be increased or decreased depending on demand.
* **On-demand self-service:** Resources can be created when needed.
* **Pay only for what you use:** Costs are based on resource usage.
* **High availability:** Applications can continue running even if part of the system fails.
* **Global access:** Services can be accessed from different locations.

## Cloud Service Models

### IaaS - Infrastructure as a Service

The provider manages the physical hardware, while the customer manages the operating system and applications.

### PaaS - Platform as a Service

The provider manages the infrastructure and operating system, while the customer focuses mainly on the application.

### SaaS - Software as a Service

The provider manages everything and the user simply uses the complete application, such as Gmail or Zoom.
