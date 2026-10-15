# Awesome-Web-Servers-Load-Balancers

## Top Workflow Orchestration Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Data Pipelines, Durable Execution, DAG Scheduling, ML Workflows & Business Process Orchestration*  

**Last updated: October 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Workflow Orchestration**. These systems define, schedule, retry, and observe multi-step jobs—ETL/ELT, ML training, microservice sagas, and long-running business processes.



**Examples** include Apache Airflow, Astronomer, Prefect, Dagster Cloud, AWS Step Functions, Temporal Cloud, Flyte, Kubeflow, Google Cloud Composer, Azure Data Factory, and **Dagster** (`dagster-io/dagster`)—an orchestration platform for data assets.



**Open-source emphasis**: Workflow orchestration is strongly open source. **Airflow**, **Dagster**, **Prefect**, **Temporal**, **Flyte**, and **Argo Workflows** power production data and application pipelines worldwide. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Astronomer, Google Cloud Composer, Amazon MWAA](https://www.astronomer.io/)**  

  Managed Apache Airflow offerings—hosted control planes, scaling, and cloud integrations for data teams.



- **[Prefect Cloud, Dagster+](https://www.prefect.io/)**  

  Managed platforms around modern Python-native orchestrators with hybrid execution and observability.



- **[Temporal Cloud, AWS Step Functions, Azure Data Factory](https://temporal.io/)**  

  Durable execution and cloud-native workflow services for application and integration orchestration.



- **[Flyte (Union.ai), Kubeflow-oriented managed offerings](https://flyte.org/)**  

  Hosted ML and data workflow platforms built on open orchestrators.



- **[Other managed workflow platforms](https://aws.amazon.com/step-functions/)**  

  Additional serverless and enterprise orchestration services.



## Open-Source GitHub Projects



- **[Apache Airflow](https://github.com/apache/airflow)**  

  Leading open-source platform to programmatically author, schedule, and monitor workflows as DAGs—industry standard for data engineering.



- **[Dagster](https://github.com/dagster-io/dagster)**  

  Open orchestration platform centered on data assets—software-defined assets, strong typing, and development-oriented tooling.



- **[Prefect](https://github.com/PrefectHQ/prefect)**  

  Open Python-native workflow orchestration—dynamic flows, hybrid execution, and a modern developer experience.



- **[Temporal](https://github.com/temporalio/temporal)**  

  Open durable execution engine—workflows as code with automatic retries, timers, and versioning for reliable distributed processes.



- **[Flyte](https://github.com/flyteorg/flyte)**  

  Open Kubernetes-native workflow orchestrator optimized for data and ML pipelines with strong reproducibility.



- **[Argo Workflows](https://github.com/argoproj/argo-workflows)**  

  Open container-native workflow engine for Kubernetes—DAGs and steps as CRDs.



- **[Kubeflow Pipelines](https://github.com/kubeflow/pipelines)**  

  Open ML workflow platform on Kubernetes—pipeline authoring, experiment tracking, and recurring runs.



- **[Luigi](https://github.com/spotify/luigi)**  

  Open Python pipeline framework from Spotify—dependency-aware batch workflows, still widely used.



- **[Tekton](https://github.com/tektoncd/pipeline)**  

  Open Kubernetes-native CI/CD and pipeline primitives often reused for general workflow steps.



- **[Cadence](https://github.com/cadence-workflow/cadence)**  

  Open workflow orchestration engine (Uber origin) related in design lineage to Temporal.



- **[Mage / Kestra / Windmill](https://github.com/mage-ai/mage-ai)**  

  Emerging open orchestrators focused on developer UX, hybrid pipelines, and automation.



### Additional Strong Open-Source Options



- **Data engineering DAGs**: Apache Airflow or Dagster.

- **Python-first dynamic flows**: Prefect.

- **Durable application workflows**: Temporal.

- **K8s-native / ML**: Flyte, Argo Workflows, Kubeflow Pipelines.

- **Composable stacks**: Orchestrator → object storage → warehouse/lake → observability (OpenTelemetry).

- Managed clouds reduce ops for the control plane; execution often still runs in your VPC with open workers.



**Frameworks for building custom systems**:  

**Airflow** or **Dagster** for data asset pipelines; **Prefect** for flexible Python flows; **Temporal** for long-running business logic; **Flyte** / **Argo** on Kubernetes for ML and container steps.  

Fully open workflow orchestration is production-standard across startups and large enterprises.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Workflow engines often hold credentials and can mutate production data. Apply least-privilege connections, secret management, and audit logging. Design tasks to be idempotent—retries will happen.

- Open-source orchestrators offer control and portability but require you to operate databases, queues, and workers. Managed platforms shift control-plane operations to the vendor. Neither replaces careful data contracts and failure handling.



---



**Made for data engineers, platform teams, and builders of reliable multi-step systems.**  

Let's expand open workflow orchestration while recognizing the managed convenience that hosted Airflow, Prefect, Dagster, and Temporal clouds deliver.
# Awesome-Web-Servers-Load-Balancers

# Top Web Servers & Load Balancers Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on L4/L7 Load Balancing, Traffic Distribution, High Availability, Health Checks & Application Delivery*  
**Last updated: October 2026**

This repository tracks notable **SaaS/cloud platforms** and **open-source projects** for **Web Servers & Load Balancers**. These systems distribute traffic across backends, perform health checks, terminate TLS, and keep applications available under load.

**Examples** include AWS ELB, Google Cloud Load Balancing, Azure Load Balancer, F5 BIG-IP, HAProxy Enterprise, NGINX Plus, Citrix ADC, Kemp LoadMaster, A10 Networks, Radware Alteon, and **Nginx** (`nginx/nginx`)—a high-performance load balancer, web server, and reverse proxy.

**Open-source emphasis**: Software load balancing is strongly open source. **Nginx**, **HAProxy**, **Envoy**, **Traefik**, **Caddy**, and **MetalLB** are production standards. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[AWS Elastic Load Balancing, Google Cloud Load Balancing, Azure Load Balancer](https://aws.amazon.com/elasticloadbalancing/)**  
  Managed L4/L7 load balancers integrated with each major public cloud—autoscaling, health checks, and global anycast options.

- **[F5 BIG-IP, Citrix ADC, A10, Radware Alteon, Kemp](https://www.f5.com/)**  
  Enterprise application delivery controllers (ADCs)—hardware and virtual appliances with advanced traffic policies and security.

- **[NGINX Plus, HAProxy Enterprise](https://www.nginx.com/)**  
  Commercial editions of leading open proxies with extra modules, support, and enterprise features.

- **[Other managed load-balancing services](https://cloud.google.com/load-balancing)**  
  Additional cloud and CDN-adjacent traffic distribution products.

## Open-Source GitHub Projects

### Core Load Balancers & Proxies

- **[Nginx](https://github.com/nginx/nginx)**  
  High-performance open load balancer, web server, and reverse proxy—layer 7 routing, upstreams, and the most widely deployed software LB/proxy on the internet.

- **[HAProxy](https://github.com/haproxy/haproxy)**  
  Open high-performance TCP/HTTP load balancer—precise L4/L7 control, stick tables, and exceptional reliability under heavy load.

- **[Envoy](https://github.com/envoyproxy/envoy)**  
  Open cloud-native proxy and load balancer—advanced L7 filters, observability, and the data-plane engine for many service meshes and gateways.

- **[Traefik](https://github.com/traefik/traefik)**  
  Open dynamic reverse proxy and load balancer with automatic service discovery for Kubernetes, Docker, and cloud-native apps.

- **[Caddy](https://github.com/caddyserver/caddy)**  
  Open web server and reverse proxy with automatic HTTPS—capable load balancing and modern defaults for smaller and mid-size deployments.

- **[SeeSaw](https://github.com/google/seesaw)**  
  Open Linux Virtual Server (LVS)-based load balancing platform from Google—anycast-friendly L4 balancing.

### Kubernetes & Cloud-Native Balancing

- **[MetalLB](https://github.com/metallb/metallb)**  
  Open load balancer for bare-metal Kubernetes clusters—BGP and L2 modes to expose services without a cloud LB.

- **[Kube-VIP](https://github.com/kube-vip/kube-vip)**  
  Open Kubernetes virtual IP and load-balancer solution for control plane and service HA on bare metal.

- **[Contour](https://github.com/projectcontour/contour)**  
  Open Kubernetes ingress controller built on Envoy—HTTP routing and load balancing as cluster ingress.

- **[Istio / service-mesh LBs](https://github.com/istio/istio)**  
  Open service mesh patterns that embed Envoy for sophisticated L7 traffic shifting and balancing.

### Additional Open Options

- **[Varnish](https://github.com/varnishcache/varnish-cache)**  
  Open HTTP accelerator often placed in front of origins—caching plus director-based backend selection.

- **[OpenResty](https://github.com/openresty/openresty)**  
  Nginx + LuaJIT for programmable load-balancing and gateway logic.

- **[Gobetween](https://github.com/yyyar/gobetween)**  
  Open modern L4 load balancer written in Go—simple and cloud-friendly.

- **[FATload / community LVS tools](https://github.com/search?q=LVS+load+balancer)**  
  Linux Virtual Server and related open L4 balancing stacks.

### Additional Strong Open-Source Options

- **General L7 software LB**: Nginx or HAProxy.
- **Cloud-native / K8s**: Traefik, Envoy, Contour, MetalLB.
- **Mesh-aware**: Envoy via Istio or standalone.
- **Composable stacks**: Cloud LB (ELB/GCLB) → Nginx/HAProxy/Envoy on nodes → apps; or pure open MetalLB + Ingress on bare metal.
- Hardware/commercial ADCs still lead for specialized ASICs, ultra-deep packet inspection, and vendor-supported compliance packages.

**Frameworks for building custom systems**:  
**Nginx** or **HAProxy** for classic software load balancing; **Envoy** / **Traefik** for dynamic cloud-native routing; **MetalLB** for bare-metal Kubernetes; cloud provider LBs when you want managed L4/L7 in public cloud.  
Fully open load-balancing stacks are production-proven at every scale.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Load balancers sit on the critical path. Misconfiguration can black-hole traffic or expose internal services. Use health checks, connection draining, and least-privilege admin access. Keep TLS and cipher configuration current.
- Open-source load balancers offer transparency and cost control. Managed cloud LBs and commercial ADCs shift capacity planning and support to the vendor. Neither replaces capacity testing and failure-mode design.

---

**Made for network engineers, SREs, and platform teams who keep traffic flowing.**  
Let's expand open load balancing while recognizing the global managed capacity that cloud and commercial ADC platforms deliver.
