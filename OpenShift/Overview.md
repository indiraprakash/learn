## Containers
* Set of processes that are isolated from the system
* Isolated environment created using the OS internal features(cgroups,namespaces) is to minimize CPU and Memory overhead
* Quick and reusable deployments
## Podman
* A tool for managing containers and container images
*  Uses the image formate OCI (Open Container Initiative)
## Kubernetes
* Orchestrates and schedule containers for high availability
  * #### Challenges of container cluster architecture
  * Orchestration
  * Isolation
  * Scheduling
* #### Features
  * Service discovery and load balancing
  * Horizontal scaling
  * Self healing with health checks
  * Automated rollout and rollback
  * centralized configuration management using resource types(Secrets and ConfigMaps)
  * Operators
## Red Hat OpenShift Container Platform (RHOCP)
* is a set of moduler components and services built on top of Kubernetes Container Infrastructure
* #### Features
  * Integrated developer workflow
  * Routes (Exposing the services outside)
  * Metrics and logging
  * Unified UI
