# Awesome-Chaos-Engineering-Platform

## Top Chaos Engineering Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Fault Injection, Resilience Testing, Controlled Failure Experiments, Game Days & Reliability Validation*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Chaos Engineering**. These systems deliberately inject failures (latency, resource stress, network partitions, pod kills, etc.) in a controlled way so teams can validate resilience and improve reliability before real incidents occur.



**Examples** include Gremlin, Steadybit, Harness Chaos Engineering, LitmusChaos Cloud, PowerfulSeal, Chaos Mesh, Azure Chaos Studio, AWS Fault Injection Simulator, ChaosSearch, and Netflix Chaos Monkey (the category leaders).



**Open-source emphasis**: Chaos engineering has an excellent open-source and CNCF ecosystem. **LitmusChaos**, **Chaos Mesh**, **Chaos Toolkit**, and related projects are widely used in production Kubernetes environments. This section heavily expands those options.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Gremlin](https://www.gremlin.com/)**  

  Leading commercial chaos engineering platform with safety controls, broad fault types, and enterprise governance for mixed cloud and Kubernetes estates.



- **[Steadybit](https://www.steadybit.com/)**  

  Commercial resilience and chaos platform focused on approachable experiments, extensibility, and optional self-hosting for compliance needs.



- **[Harness Chaos Engineering](https://www.harness.io/)**  

  Enterprise chaos offering built on LitmusChaos, providing a managed control plane, CI/CD integration, and Kubernetes-centric resilience testing.



- **[LitmusChaos Cloud / managed Litmus](https://litmuschaos.io/)**  

  Hosted or commercial paths around the open LitmusChaos platform for teams that want managed operations on top of the CNCF project.



- **[PowerfulSeal](https://github.com/powerfulseal/powerfulseal)**  

  Chaos tool originally focused on Kubernetes (also usable in commercial contexts)—pod and infrastructure disruption for resilience testing.



- **[Chaos Mesh](https://chaos-mesh.org/)**  

  CNCF open-source chaos engineering platform for Kubernetes (also available with commercial support options)—broad fault coverage via Kubernetes-native APIs.



- **[Azure Chaos Studio](https://azure.microsoft.com/products/chaos-studio)**  

  Azure-native fault injection service for controlled experiments against Azure resources with Azure RBAC and monitoring integration.



- **[AWS Fault Injection Simulator (FIS)](https://aws.amazon.com/fis/)**  

  AWS-native chaos and fault injection service for agentless experiments governed by IAM, tags, and CloudWatch.



- **[ChaosSearch and related analytics platforms](https://www.example.com/)**  

  Platforms that may combine search/analytics with operational or chaos-related use cases (verify current product focus).



- **[Netflix Chaos Monkey and related Netflix OSS](https://netflix.github.io/)**  

  Foundational chaos approach (Chaos Monkey) that popularized terminating instances in production to validate resilience; more of a pioneering tool than a full modern platform.



## Open-Source GitHub Projects

- **[LitmusChaos](https://github.com/litmuschaos/litmus)**  

  Leading CNCF incubating open-source chaos engineering platform for Kubernetes—ChaosCenter, ChaosHub experiment library, workflows, and controlled fault injection for SREs and developers.



- **[Chaos Mesh](https://github.com/chaos-mesh/chaos-mesh)**  

  CNCF incubating open-source chaos engineering platform for Kubernetes—pod, network, I/O, stress, time, and cloud-provider faults defined as Kubernetes custom resources.



- **[Chaos Toolkit](https://github.com/chaostoolkit/chaostoolkit)**  

  Open-source, extensible chaos engineering toolkit with a declarative experiment format and drivers for many platforms (Kubernetes, cloud, applications).



- **[PowerfulSeal](https://github.com/powerfulseal/powerfulseal)**  

  Open-source chaos tool for killing pods and disrupting Kubernetes clusters to test resilience.



- **[Chaos Monkey (Netflix OSS lineage)](https://github.com/Netflix/chaosmonkey)**  

  Classic open-source tool for randomly terminating instances in production to validate system resilience (historical foundation of the practice).



- **[chaosd](https://github.com/chaos-mesh/chaosd)**  

  Chaos engineering toolkit component related to Chaos Mesh for broader fault injection scenarios.



- **[Kube-monkey](https://github.com/asobti/kube-monkey)**  

  Open-source Chaos Monkey-style tool for randomly deleting Kubernetes pods.



- **[Toxiproxy](https://github.com/Shopify/toxiproxy)**  

  Open-source network proxy for simulating latency, bandwidth limits, and other network conditions during testing.



- **[Pumba](https://github.com/alexei-led/pumba)**  

  Open-source chaos testing tool for Docker containers (network, kill, pause, stress).



- **[Documentation and chaos open playbooks](https://litmuschaos.io/)**  

  Guides for running game days, writing hypotheses, and deploying LitmusChaos or Chaos Mesh safely in production-like environments.



### Additional Strong Open-Source Options

- Starting with **LitmusChaos** or **Chaos Mesh** for Kubernetes-native controlled experiments and experiment libraries.

- Using **Chaos Toolkit** when you need a flexible, multi-platform experiment definition approach.

- Adding network and container-level tools (Toxiproxy, Pumba) for targeted failure modes.

- Accepting that enterprise safety rails, multi-cloud breadth, polished governance, and managed support still favor commercial platforms (Gremlin, Steadybit, Harness) or cloud-native services (AWS FIS, Azure Chaos Studio).

- Focusing open-source efforts on Kubernetes-first environments, transparency, and cost-free continuous resilience testing.



**Frameworks for building custom systems**: Define steady-state hypotheses → run experiments with LitmusChaos or Chaos Mesh → observe impact via Prometheus/Grafana → automate in CI/CD → expand blast radius carefully. Suitable for platform and SRE teams. Many enterprises still adopt commercial chaos platforms for guardrails and reporting.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Chaos experiments can cause real outages if misconfigured. Always start with small blast radius, use safety controls, and obtain proper authorization. Open-source tools require careful operational practices. This list is not operational or SRE advice.



---

**Made for SREs, platform engineers, and open-source resilience advocates.**

Let's break things on purpose—safely, transparently, and as open as practical.
