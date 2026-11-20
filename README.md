# cloud-architecture-playground

A hands-on catalog of cloud architectures, from a single VM to multi-region active-active, AI agent
platforms and sovereign cloud. 217 architectures across 20 categories. Each one is explained
once and implemented on AWS, Azure and GCP with Terraform, Pulumi (Go) and the native IaC of each
cloud (CloudFormation, Bicep, Infrastructure Manager). 1,953 implementation folders in total, each
with its own documentation.

## How this repo works

Every architecture (categories 01 to 20) has this layout. The cloud-neutral README is written once;
each of the nine implementation folders holds one implementation.

```
<category>/<NN-architecture-name>/
├── README.md                 cloud-neutral explanation
├── diagrams/
├── aws/
│   ├── README.md
│   ├── terraform/
│   ├── pulumi/
│   └── cloudformation/
├── azure/
│   ├── README.md
│   ├── terraform/
│   ├── pulumi/
│   └── bicep/
└── gcp/
    ├── README.md
    ├── terraform/
    ├── pulumi/
    └── infra-manager/
```

## IaC tools

| Cloud | Folder 1   | Folder 2 | Folder 3 (native IaC) |
|-------|------------|----------|-----------------------|
| AWS   | terraform  | pulumi   | cloudformation        |
| Azure | terraform  | pulumi   | bicep                 |
| GCP   | terraform  | pulumi   | infra-manager         |

Pulumi is always written in Go. Infrastructure Manager is Google's managed Terraform service and
replaces the discontinued Deployment Manager; it runs Terraform HCL.

## Legends

**Level:** 🟢 Beginner | 🟡 Intermediate | 🔴 Advanced | 🔵 Expert

**Tier (suggested study order only; every architecture gets all nine implementations):**
★ Core: study first | ◆ Standard: study after the core ones | ○ Specialized: study when the topic becomes relevant

**Status:** ⬜ Not started | 🟨 Code written | ✅ Validated (fmt, validate/plan or equivalent, linters pass) | 🚀 Deployed and destroyed successfully

## Service mapping quick reference

| Capability              | AWS                         | Azure                          | GCP                            |
|-------------------------|-----------------------------|--------------------------------|--------------------------------|
| Virtual machines        | EC2                         | Virtual Machines               | Compute Engine                 |
| VM autoscaling          | Auto Scaling Groups         | VM Scale Sets                  | Managed Instance Groups        |
| Load balancing          | ELB (ALB/NLB)               | Load Balancer / App Gateway    | Cloud Load Balancing           |
| Object storage          | S3                          | Blob Storage                   | Cloud Storage                  |
| CDN                     | CloudFront                  | Front Door                     | Cloud CDN                      |
| Managed Kubernetes      | EKS                         | AKS                            | GKE                            |
| Serverless functions    | Lambda                      | Azure Functions                | Cloud Run functions            |
| Serverless containers   | Fargate / App Runner        | Container Apps                 | Cloud Run                      |
| Queue                   | SQS                         | Service Bus                    | Cloud Tasks / Pub/Sub          |
| Pub/Sub and events      | SNS / EventBridge           | Event Grid                     | Pub/Sub / Eventarc             |
| Streaming               | Kinesis / MSK               | Event Hubs                     | Pub/Sub / Managed Kafka        |
| Relational database     | RDS / Aurora                | Azure SQL / Database for PG    | Cloud SQL / AlloyDB            |
| NoSQL                   | DynamoDB                    | Cosmos DB                      | Firestore / Bigtable           |
| Cache                   | ElastiCache                 | Azure Managed Redis            | Memorystore                    |
| Data warehouse          | Redshift                    | Synapse / Fabric               | BigQuery                       |
| Identity and access     | IAM / IAM Identity Center   | Entra ID / Azure RBAC          | Cloud IAM                      |
| Secrets                 | Secrets Manager             | Key Vault                      | Secret Manager                 |
| Org governance          | Organizations + SCP         | Management Groups + Policy     | Resource Manager + Org Policy  |
| DNS                     | Route 53                    | Azure DNS                      | Cloud DNS                      |
| Private connectivity    | PrivateLink                 | Private Endpoint               | Private Service Connect        |
| Network hub             | Transit Gateway / Cloud WAN | Virtual WAN                    | Network Connectivity Center    |
| Native IaC              | CloudFormation              | Bicep                          | Infrastructure Manager         |

## Categories

| Category | Level | Summary |
|----------|-------|---------|
| [00-foundations](00-foundations/) | 🟢 | Documentation only: how to use the repo, IaC compared, service mapping, failure domains, shared responsibility, Well-Architected, cost discipline, naming, C4 diagrams. |
| [01-compute-and-hosting-basics](01-compute-and-hosting-basics/) | 🟢 | Single VMs, load-balanced fleets, PaaS, batch and desktop hosting: the simplest ways to run code in the cloud. |
| [02-network-foundations](02-network-foundations/) | 🟢🟡🔴 | VPC/VNet design, egress, hubs, hybrid connectivity, DNS and segmentation. |
| [03-landing-zones-and-governance](03-landing-zones-and-governance/) | 🟡🔴 | Account/subscription/project hierarchy, guardrails, logging, identity and cost governance for multi-account estates. |
| [04-application-architectures](04-application-architectures/) | 🟢🟡🔴 | Classic and modern application shapes: monoliths, n-tier, SPAs, microservices, multi-tenant SaaS and modernization. |
| [05-serverless](05-serverless/) | 🟢🟡🔴 | Functions, serverless containers, workflows and event-driven serverless building blocks. |
| [06-containers-and-kubernetes](06-containers-and-kubernetes/) | 🟡🔴 | Managed container services and Kubernetes on each cloud: clusters, ingress, scaling, tenancy, GitOps and platforms. |
| [07-event-driven-and-messaging](07-event-driven-and-messaging/) | 🟡🔴 | Queues, pub/sub, event buses, streaming and the distributed-transaction patterns built on them. |
| [08-data-and-analytics](08-data-and-analytics/) | 🟡🔴 | ETL, lakes, warehouses, lakehouses, streaming analytics, search and data governance. |
| [09-databases-and-persistence](09-databases-and-persistence/) | 🟡🔴 | Managed relational and NoSQL databases, caching, replication, migration, backup and global data. |
| [10-resilience-and-disaster-recovery](10-resilience-and-disaster-recovery/) | 🟡🔴🔵 | Multi-AZ and multi-region designs, DR strategies, progressive delivery and advanced resilience patterns. |
| [11-security-architectures](11-security-architectures/) | 🟡🔴🔵 | Edge protection, zero trust, secrets, workload identity, monitoring, supply chain and compliance baselines. |
| [12-hybrid-and-multicloud](12-hybrid-and-multicloud/) | 🔴🔵 | Migration, hybrid identity, on-prem extension, multicloud, repatriation and sovereign cloud. |
| [13-cicd-and-platform-engineering](13-cicd-and-platform-engineering/) | 🟡🔴 | Pipelines, IaC delivery, environment promotion, GitOps, registries, runners and developer portals. |
| [14-observability-and-operations](14-observability-and-operations/) | 🟡🔴 | Logging, metrics, tracing, FinOps visibility, fleet management, drift detection and incident response. |
| [15-ai-ml-architectures](15-ai-ml-architectures/) | 🟡🔴🔵 | RAG, training, serving, inference, LLM gateways, vector search, agents and AI governance. |
| [16-integration-and-api](16-integration-and-api/) | 🟡🔴 | API gateways, B2B integration, throttling, developer portals, federation and iPaaS. |
| [17-iot-edge-and-media](17-iot-edge-and-media/) | 🔴🔵 | CDN, IoT ingestion, video, transcoding, edge compute, digital twins, gaming and ad tech. |
| [18-industry-reference-architectures](18-industry-reference-architectures/) | 🔴🔵 | End-to-end reference architectures for e-commerce, SaaS, fintech, healthcare, government and more. |
| [19-cost-and-sustainability](19-cost-and-sustainability/) | 🟡🔴 | Spot fleets, scheduling, Arm compute, storage tiering, commitments and carbon-aware design. |
| [20-emerging-and-new](20-emerging-and-new/) | 🔵 | Living category: new patterns and platform shifts such as AI agent landing zones, sovereignty, confidential AI and post-quantum readiness. |

## Recommended order

Suggested, not a schedule.

```
Phase 1:  00 → 01 → 02 → 03                  (foundations, compute, network, landing zones)
Phase 2:  04 → 05 → 09 → 07                  (apps, serverless, databases, messaging)
Phase 3:  06 → 10 → 11                       (containers, resilience, security)
Phase 4:  13 → 14 → 08                       (CI/CD, observability, data)
Phase 5:  12 → 16 → 17 → 19                  (hybrid, integration, IoT/media, cost)
Phase 6:  15 → 18 → 20                       (AI/ML, industry references, emerging)

Inside every category, study the ★ architectures first, then ◆, then ○.
```

## Progress tracking

[STATUS.md](STATUS.md) is the main progress tracker: one table per category with one row per
architecture and nine status cells (⬜ 🟨 ✅ 🚀, see the legend above), one per implementation.

## Companion repositories

This repo shows HOW each architecture is built on each cloud. The deeper theory lives elsewhere:
Kubernetes tools: `k8s-playground`. Networking protocols: `networking-playground`.
Distributed systems theory: `distributed-systems-playground`. Caching: `cache-playground`.
Secrets management: `secrets-playground`. Storage: `storage-playground`.
Authentication: `auth-playground`. Security: `cyber-ops-lab`.
Isolation and virtualization: `compute-isolation-playground`.

## Recommended resources

- [AWS Architecture Center](https://aws.amazon.com/architecture/)
- [AWS Well-Architected Framework](https://aws.amazon.com/architecture/well-architected/)
- [Azure Architecture Center](https://learn.microsoft.com/en-us/azure/architecture/)
- [Azure Well-Architected Framework](https://learn.microsoft.com/en-us/azure/well-architected/)
- [Google Cloud Architecture Center](https://cloud.google.com/architecture)
- [Google Cloud Well-Architected Framework](https://cloud.google.com/architecture/framework)
- [Terraform Registry](https://registry.terraform.io/)
- [Pulumi Go documentation](https://www.pulumi.com/docs/iac/languages-sdks/go/)
- [AWS CloudFormation documentation](https://docs.aws.amazon.com/cloudformation/)
- [Azure Bicep documentation](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/)
- [Google Infrastructure Manager documentation](https://cloud.google.com/infrastructure-manager/docs)
- [C4 model](https://c4model.com/)

## 20 - Emerging & New

This is a living category. New architecture patterns, platform shifts and service launches
get added here as new folders with the full nine-implementation layout.
Particularly active in 2026: AI agent landing zones, digital sovereignty, confidential AI
and post-quantum readiness.
