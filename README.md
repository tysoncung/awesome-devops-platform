# Awesome DevOps Platform Engineering [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome DevOps Platform Engineering tools, practices, and resources for building modern cloud-native infrastructure and developer platforms

Platform Engineering is the discipline of designing and building toolchains and workflows that enable self-service capabilities for software engineering organizations in the cloud-native era. This list focuses on tools and practices that help teams build Internal Developer Platforms (IDPs), implement GitOps, and create golden paths for developers.

## Contents

- [Platform Engineering Fundamentals](#platform-engineering-fundamentals)
- [Internal Developer Platforms (IDPs)](#internal-developer-platforms-idps)
- [Developer Portals](#developer-portals)
- [GitOps Tools](#gitops-tools)
- [Platform Orchestration](#platform-orchestration)
- [Infrastructure as Code](#infrastructure-as-code)
- [Cloud Development Kits](#cloud-development-kits)
- [Service Mesh & Networking](#service-mesh--networking)
- [Progressive Delivery](#progressive-delivery)
- [Observability Platforms](#observability-platforms)
- [Security & Compliance](#security--compliance)
- [Cost Management](#cost-management)
- [Multi-Cloud & Hybrid](#multi-cloud--hybrid)
- [Developer Experience Tools](#developer-experience-tools)
- [Platform Templates & Blueprints](#platform-templates--blueprints)
- [Learning Resources](#learning-resources)
- [Communities](#communities)

## Platform Engineering Fundamentals

### Books & Guides
- [Platform Engineering on AWS](https://www.oreilly.com/library/view/platform-engineering-on/9781098141578/) - Building robust cloud platforms using AWS services
- [Team Topologies](https://teamtopologies.com/) - Organizing business and technology teams for fast flow
- [Platform Engineering Fundamentals](https://platformengineering.org/fundamentals) - Certification program and comprehensive guide
- [Internal Developer Platforms Guide](https://internaldeveloperplatform.org/) - Comprehensive resource on building IDPs

### Articles & Papers
- [What is Platform Engineering?](https://platformengineering.org/blog/what-is-platform-engineering) - Definition and principles
- [Platform Engineering Blog](https://platformengineering.org/blog) - Latest articles and industry insights
- [Platform Tooling Landscape](https://platformengineering.org/platform-tooling) - Guide to choosing the right tools for your IDP

## Internal Developer Platforms (IDPs)

### Open Source Platforms
- [Backstage](https://backstage.io/) - Open platform for building developer portals, created by Spotify
- [Humanitec Platform Orchestrator](https://humanitec.com/) - Dynamic Internal Developer Platform orchestrator
- [Kratix](https://kratix.io/) - Framework for building platforms using Kubernetes
- [Otomi](https://otomi.io/) - Self-hosted PaaS for Kubernetes
- [KubeVela](https://kubevela.io/) - Application delivery platform based on OAM
- [Gimlet](https://gimlet.io/) - Application deployment platform with GitOps
- [Qovery](https://www.qovery.com/) - Platform to deploy applications on AWS, GCP, Azure
- [mogenius](https://mogenius.com/) - Virtual DevOps platform

### Commercial Platforms
- [Port](https://www.getport.io/) - Developer portal with self-service actions
- [Cortex](https://www.cortex.io/) - Internal developer portal with service catalog
- [Configure8](https://www.configure8.io/) - Developer portal and service catalog
- [OpsLevel](https://www.opslevel.com/) - Service catalog and developer portal

## Developer Portals

### Service Catalogs
- [Backstage Software Catalog](https://backstage.io/docs/features/software-catalog/) - Centralized system model
- [Port Service Catalog](https://www.getport.io/product/service-catalog) - Comprehensive service registry
- [ServiceNow Service Catalog](https://www.servicenow.com/) - Enterprise service management

### Documentation Platforms
- [Docusaurus](https://docusaurus.io/) - Easy to maintain documentation websites
- [MkDocs](https://www.mkdocs.org/) - Project documentation with Markdown
- [ReadMe](https://readme.com/) - Interactive developer hubs
- [Stoplight](https://stoplight.io/) - API design and documentation platform

## GitOps Tools

### GitOps Operators
- [ArgoCD](https://argoproj.github.io/cd/) - Declarative GitOps CD for Kubernetes
- [Flux](https://fluxcd.io/) - GitOps toolkit for Kubernetes
- [Fleet](https://fleet.rancher.io/) - GitOps at scale for Kubernetes
- [Weave GitOps](https://www.weave.works/product/gitops/) - Enterprise GitOps platform

### GitOps Frameworks
- [Crossplane](https://crossplane.io/) - Cloud native control planes
- [Config Sync](https://cloud.google.com/anthos/config-management/docs/config-sync) - Google's GitOps for Kubernetes
- [Kustomize](https://kustomize.io/) - Kubernetes native configuration management
- [Helm](https://helm.sh/) - Package manager for Kubernetes

## Platform Orchestration

### Workflow Orchestration
- [Temporal](https://temporal.io/) - Workflow orchestration platform
- [Argo Workflows](https://argoproj.github.io/workflows/) - Container-native workflow engine
- [Apache Airflow](https://airflow.apache.org/) - Platform to programmatically author workflows
- [Prefect](https://www.prefect.io/) - Modern workflow orchestration
- [Dagster](https://dagster.io/) - Data orchestrator for machine learning

### Resource Orchestration
- [Kubernetes](https://kubernetes.io/) - Container orchestration platform
- [Nomad](https://www.nomadproject.io/) - Simple and flexible workload orchestrator
- [Docker Swarm](https://docs.docker.com/engine/swarm/) - Container orchestration built into Docker
- [Apache Mesos](https://mesos.apache.org/) - Distributed systems kernel

## Infrastructure as Code

### Provisioning Tools
- [Terraform](https://www.terraform.io/) - Infrastructure as code software tool
- [OpenTofu](https://opentofu.org/) - Open-source Terraform fork
- [Pulumi](https://www.pulumi.com/) - Infrastructure as code using programming languages
- [Ansible](https://www.ansible.com/) - Automation platform
- [Terragrunt](https://terragrunt.gruntwork.io/) - Terraform wrapper for DRY configurations
- [Terramate](https://terramate.io/) - Terraform orchestration and code generation

### Policy as Code
- [Open Policy Agent](https://www.openpolicyagent.org/) - Policy engine for cloud native environments
- [Kyverno](https://kyverno.io/) - Kubernetes native policy management
- [Polaris](https://www.fairwinds.com/polaris) - Validation of Kubernetes best practices
- [Conftest](https://www.conftest.dev/) - Write tests against structured configuration data
- [Checkov](https://www.checkov.io/) - Static analysis for infrastructure as code

## Cloud Development Kits

### Multi-Cloud CDKs
- [AWS CDK](https://aws.amazon.com/cdk/) - Cloud Development Kit for AWS
- [Azure Bicep](https://github.com/Azure/bicep) - DSL for deploying Azure resources
- [Google Cloud Deployment Manager](https://cloud.google.com/deployment-manager) - Infrastructure deployment service
- [Pulumi CDK](https://www.pulumi.com/docs/intro/concepts/programming-model/) - Multi-cloud infrastructure as code
- [CDKTF](https://developer.hashicorp.com/terraform/cdktf) - CDK for Terraform

### Kubernetes CDKs
- [CDK8s](https://cdk8s.io/) - Define Kubernetes applications using code
- [Kubernetes Operators](https://kubernetes.io/docs/concepts/extend-kubernetes/operator/) - Application-specific controllers
- [Kubebuilder](https://kubebuilder.io/) - SDK for building Kubernetes APIs

## Service Mesh & Networking

### Service Mesh Platforms
- [Istio](https://istio.io/) - Connect, secure, control, and observe services
- [Linkerd](https://linkerd.io/) - Ultralight, security-first service mesh
- [Consul](https://www.consul.io/) - Service mesh and service discovery
- [Cilium](https://cilium.io/) - eBPF-based networking, observability, and security
- [Kuma](https://kuma.io/) - Universal service mesh

### API Gateways
- [Kong](https://konghq.com/) - Cloud-native API gateway
- [Traefik](https://traefik.io/) - Modern HTTP reverse proxy and load balancer
- [NGINX](https://www.nginx.com/) - Web server and reverse proxy
- [Envoy](https://www.envoyproxy.io/) - Cloud-native high-performance edge/middle/service proxy
- [Tyk](https://tyk.io/) - API gateway and management platform

## Progressive Delivery

### Feature Flags
- [LaunchDarkly](https://launchdarkly.com/) - Feature management platform
- [Unleash](https://www.getunleash.io/) - Open source feature toggle service
- [Flagsmith](https://flagsmith.com/) - Open source feature flag platform
- [Split](https://www.split.io/) - Feature delivery platform
- [Flipt](https://flipt.io/) - Self-hosted feature flag application

### Canary Deployment
- [Flagger](https://flagger.app/) - Progressive delivery Kubernetes operator
- [Argo Rollouts](https://argoproj.github.io/rollouts/) - Progressive delivery for Kubernetes
- [Spinnaker](https://spinnaker.io/) - Multi-cloud continuous delivery platform
- [Keptn](https://keptn.sh/) - Event-based control plane for continuous delivery

## Observability Platforms

### Metrics & Monitoring
- [Prometheus](https://prometheus.io/) - Monitoring system and time series database
- [Grafana](https://grafana.com/) - Multi-platform analytics and monitoring
- [Datadog](https://www.datadoghq.com/) - Monitoring and security platform
- [New Relic](https://newrelic.com/) - Observability platform
- [Thanos](https://thanos.io/) - Highly available Prometheus setup

### Distributed Tracing
- [Jaeger](https://www.jaegertracing.io/) - Distributed tracing platform
- [Zipkin](https://zipkin.io/) - Distributed tracing system
- [Tempo](https://grafana.com/oss/tempo/) - High-volume distributed tracing backend
- [AWS X-Ray](https://aws.amazon.com/xray/) - Distributed tracing for AWS
- [Google Cloud Trace](https://cloud.google.com/trace) - Distributed tracing for GCP

### Logging
- [Elastic Stack (ELK)](https://www.elastic.co/elastic-stack/) - Search, analyze, and visualize logs
- [Loki](https://grafana.com/oss/loki/) - Log aggregation system by Grafana
- [Fluentd](https://www.fluentd.org/) - Unified logging layer
- [Vector](https://vector.dev/) - High-performance observability data pipeline
- [Fluent Bit](https://fluentbit.io/) - Fast and lightweight log processor

## Security & Compliance

### Security Scanning
- [Snyk](https://snyk.io/) - Developer security platform
- [Aqua Security](https://www.aquasec.com/) - Cloud native security platform
- [Sysdig](https://sysdig.com/) - Secure DevOps platform
- [Twistlock/Prisma Cloud](https://www.paloaltonetworks.com/prisma/cloud) - Cloud security platform
- [Falco](https://falco.org/) - Runtime security for containers and Kubernetes

### Secrets Management
- [HashiCorp Vault](https://www.vaultproject.io/) - Secrets and encryption management
- [AWS Secrets Manager](https://aws.amazon.com/secrets-manager/) - Secrets management for AWS
- [Azure Key Vault](https://azure.microsoft.com/en-us/services/key-vault/) - Secrets management for Azure
- [Sealed Secrets](https://sealed-secrets.netlify.app/) - Kubernetes controller for sealed secrets
- [External Secrets Operator](https://external-secrets.io/) - Integrate external secret management systems

### Compliance Tools
- [CloudQuery](https://www.cloudquery.io/) - Cloud asset inventory
- [Steampipe](https://steampipe.io/) - Query cloud infrastructure using SQL
- [Cloud Custodian](https://cloudcustodian.io/) - Rules engine for cloud security and governance
- [Prowler](https://github.com/prowler-cloud/prowler) - Security assessment tool for AWS and Azure

## Cost Management

### Cost Optimization
- [Infracost](https://www.infracost.io/) - Cloud cost estimates for Terraform
- [Kubecost](https://www.kubecost.com/) - Kubernetes cost monitoring and optimization
- [CloudHealth](https://www.cloudhealthtech.com/) - Cloud management platform
- [Spot.io](https://spot.io/) - Cloud cost optimization
- [CAST AI](https://cast.ai/) - Kubernetes cost optimization platform

### FinOps Tools
- [OpenCost](https://www.opencost.io/) - Open source Kubernetes cost monitoring
- [Cloud Custodian](https://cloudcustodian.io/) - Cloud governance and cost optimization
- [Vantage](https://www.vantage.sh/) - Cloud cost transparency platform
- [CloudZero](https://www.cloudzero.com/) - Cloud cost intelligence platform

## Multi-Cloud & Hybrid

### Multi-Cloud Management
- [Anthos](https://cloud.google.com/anthos) - Multi-cloud application platform
- [Azure Arc](https://azure.microsoft.com/en-us/services/azure-arc/) - Multi-cloud and edge management
- [AWS Outposts](https://aws.amazon.com/outposts/) - AWS infrastructure on-premises
- [Rancher](https://rancher.com/) - Multi-cluster Kubernetes management
- [VMware Tanzu](https://tanzu.vmware.com/) - Multi-cloud application platform

### Cloud Abstraction
- [Apache Libcloud](https://libcloud.apache.org/) - Python library for cloud providers
- [Fog](https://github.com/fog/fog) - Ruby cloud services library
- [Pkgcloud](https://github.com/pkgcloud/pkgcloud) - Node.js cloud abstraction library
- [Apache jclouds](https://jclouds.apache.org/) - Java multi-cloud toolkit

## Developer Experience Tools

### Development Environments
- [GitHub Codespaces](https://github.com/features/codespaces) - Cloud development environments
- [Gitpod](https://www.gitpod.io/) - Cloud development environments
- [DevPod](https://devpod.sh/) - Client-only tool for dev environments
- [Coder](https://coder.com/) - Self-hosted cloud development environments
- [Eclipse Che](https://www.eclipse.org/che/) - Kubernetes-native IDE

### CLI Tools
- [GitHub CLI](https://cli.github.com/) - GitHub from the command line
- [kubectl](https://kubernetes.io/docs/reference/kubectl/) - Kubernetes command-line tool
- [k9s](https://k9scli.io/) - Terminal UI for Kubernetes
- [Lens](https://k8slens.dev/) - Kubernetes IDE
- [Teleport](https://goteleport.com/) - Secure access to infrastructure

### Local Development
- [Tilt](https://tilt.dev/) - Multi-service dev environment for Kubernetes
- [Skaffold](https://skaffold.dev/) - Workflow for building and deploying to Kubernetes
- [Garden](https://garden.io/) - Development orchestrator for Kubernetes
- [DevSpace](https://www.devspace.sh/) - Developer tool for Kubernetes
- [Telepresence](https://www.telepresence.io/) - Local development against remote Kubernetes

## Platform Templates & Blueprints

### Reference Architectures
- [AWS Well-Architected Framework](https://aws.amazon.com/architecture/well-architected/) - Best practices for cloud architectures
- [Azure Architecture Center](https://docs.microsoft.com/en-us/azure/architecture/) - Azure reference architectures
- [Google Cloud Architecture Framework](https://cloud.google.com/architecture/framework) - GCP best practices
- [CNCF Cloud Native Trail Map](https://github.com/cncf/trailmap) - Path to cloud native adoption

### Starter Kits
- [Projen](https://projen.io/) - Project generator for modern applications
- [Yeoman](https://yeoman.io/) - Scaffolding tool for modern web apps
- [Cookiecutter](https://cookiecutter.io/) - Project templates for any language
- [Backstage Software Templates](https://backstage.io/docs/features/software-templates/) - Scaffolding for services

### Platform Examples
- [Internal Developer Platform Examples](https://internaldeveloperplatform.org/) - Reference architectures and examples
- [Kubernetes Examples](https://github.com/kubernetes/examples) - Kubernetes application examples
- [AWS CDK Examples](https://github.com/aws-samples/aws-cdk-examples) - CDK code examples
- [Terraform Examples](https://github.com/hashicorp/terraform-guides) - Terraform patterns and practices

## Learning Resources

### Courses & Certifications
- [Platform Engineering University](https://platformengineering.org/courses) - Comprehensive platform engineering courses
- [Platform Engineering Certified Practitioner](https://platformengineering.org/fundamentals) - Official certification program
- [CNCF Certifications](https://www.cncf.io/certification/) - Cloud native certifications
- [AWS Certifications](https://aws.amazon.com/certification/) - AWS cloud certifications
- [DevOps Institute Certifications](https://www.devopsinstitute.com/) - DevOps certifications

### Tutorials & Labs
- [Katacoda](https://www.katacoda.com/) - Interactive learning platform
- [KillerCoda](https://killercoda.com/) - Hands-on cloud native scenarios
- [Play with Kubernetes](https://labs.play-with-k8s.com/) - Kubernetes playground
- [Instruqt](https://instruqt.com/) - Hands-on virtual IT labs

### Podcasts
- [Platform Engineering Podcast](https://podcast.platformengineering.org/) - Insights from platform engineering leaders
- [Kubernetes Podcast](https://kubernetespodcast.com/) - Weekly news and interviews
- [DevOps Paradox](https://www.devopsparadox.com/) - DevOps discussions
- [The POPCAST](https://popcast-d9f7b6dc.simplecast.com/) - Platform engineering stories

### YouTube Channels
- [Platform Engineering](https://www.youtube.com/@PlatformEngineering) - Platform engineering content
- [CNCF](https://www.youtube.com/@cncf) - Cloud Native Computing Foundation
- [DevOps Toolkit](https://www.youtube.com/@DevOpsToolkit) - Viktor Farcic's DevOps content
- [TechWorld with Nana](https://www.youtube.com/@TechWorldwithNana) - DevOps tutorials

## Communities

### Organizations
- [Platform Engineering Community](https://platformengineering.org/) - Global platform engineering community
- [CNCF (Cloud Native Computing Foundation)](https://www.cncf.io/) - Cloud native ecosystem
- [DevOps Institute](https://www.devopsinstitute.com/) - DevOps community and education
- [SRE Community](https://sre.google/) - Site Reliability Engineering community

### Conferences
- [PlatformCon](https://platformcon.com/) - Platform engineering conference
- [KubeCon + CloudNativeCon](https://www.cncf.io/kubecon-cloudnativecon-events/) - Cloud native conference
- [DevOps Enterprise Summit](https://events.itrevolution.com/) - Enterprise DevOps conference
- [SREcon](https://www.usenix.org/conferences/byname/srecon) - Site reliability engineering conference

### Slack Communities
- [Platform Engineering Slack](https://platformengineering.org/slack) - Platform engineering discussions
- [Kubernetes Slack](https://kubernetes.slack.com/) - Kubernetes community
- [DevOps Chat](https://devopschat.co/) - DevOps professionals community
- [SRE Community Slack](https://sre-community.slack.com/) - SRE discussions

### Forums & Discussion
- [r/platformengineering](https://www.reddit.com/r/platformengineering/) - Platform engineering subreddit
- [r/devops](https://www.reddit.com/r/devops/) - DevOps subreddit
- [Stack Overflow DevOps](https://stackoverflow.com/questions/tagged/devops) - Q&A for DevOps
- [DevOps.com](https://devops.com/) - DevOps news and articles

## Contributing

Your contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.