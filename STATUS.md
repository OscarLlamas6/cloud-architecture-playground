# Implementation status

## Legend
- ⬜ Not started
- 🟨 Code written
- ✅ Validated (fmt, validate/plan or equivalent, linters pass)
- 🚀 Deployed and destroyed successfully

Tier: ★ Core, ◆ Standard, ○ Specialized (suggested study order only).

## 01-compute-and-hosting-basics 🟢

| Architecture | Tier | AWS TF | AWS Pulumi | AWS CFN | Azure TF | Azure Pulumi | Azure Bicep | GCP TF | GCP Pulumi | GCP InfraMgr |
|---|---|---|---|---|---|---|---|---|---|---|
| [01-single-vm](01-compute-and-hosting-basics/01-single-vm/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [02-vm-with-managed-database](01-compute-and-hosting-basics/02-vm-with-managed-database/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [03-static-site-object-storage-cdn](01-compute-and-hosting-basics/03-static-site-object-storage-cdn/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [04-load-balanced-autoscaling-vms](01-compute-and-hosting-basics/04-load-balanced-autoscaling-vms/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [05-paas-web-app](01-compute-and-hosting-basics/05-paas-web-app/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [06-bastion-and-secure-admin-access](01-compute-and-hosting-basics/06-bastion-and-secure-admin-access/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [07-batch-compute-on-spot](01-compute-and-hosting-basics/07-batch-compute-on-spot/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [08-hpc-cluster](01-compute-and-hosting-basics/08-hpc-cluster/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [09-vdi-remote-desktop](01-compute-and-hosting-basics/09-vdi-remote-desktop/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |

## 02-network-foundations 🟢🟡🔴

| Architecture | Tier | AWS TF | AWS Pulumi | AWS CFN | Azure TF | Azure Pulumi | Azure Bicep | GCP TF | GCP Pulumi | GCP InfraMgr |
|---|---|---|---|---|---|---|---|---|---|---|
| [01-single-vpc-public-private-subnets](02-network-foundations/01-single-vpc-public-private-subnets/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [02-multi-az-network](02-network-foundations/02-multi-az-network/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [03-nat-and-egress-patterns](02-network-foundations/03-nat-and-egress-patterns/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [04-hub-and-spoke](02-network-foundations/04-hub-and-spoke/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [05-transit-gateway-cloud-wan-hub](02-network-foundations/05-transit-gateway-cloud-wan-hub/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [06-peering-mesh](02-network-foundations/06-peering-mesh/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [07-private-connectivity-to-managed-services](02-network-foundations/07-private-connectivity-to-managed-services/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [08-site-to-site-vpn](02-network-foundations/08-site-to-site-vpn/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [09-dedicated-interconnect](02-network-foundations/09-dedicated-interconnect/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [10-centralized-egress-inspection](02-network-foundations/10-centralized-egress-inspection/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [11-centralized-ingress-waf-lb](02-network-foundations/11-centralized-ingress-waf-lb/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [12-hybrid-dns-resolution](02-network-foundations/12-hybrid-dns-resolution/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [13-ipv6-dual-stack](02-network-foundations/13-ipv6-dual-stack/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [14-network-microsegmentation](02-network-foundations/14-network-microsegmentation/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [15-multi-region-network-backbone](02-network-foundations/15-multi-region-network-backbone/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |

## 03-landing-zones-and-governance 🟡🔴

| Architecture | Tier | AWS TF | AWS Pulumi | AWS CFN | Azure TF | Azure Pulumi | Azure Bicep | GCP TF | GCP Pulumi | GCP InfraMgr |
|---|---|---|---|---|---|---|---|---|---|---|
| [01-account-subscription-project-hierarchy](03-landing-zones-and-governance/01-account-subscription-project-hierarchy/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [02-guardrails-scp-azure-policy-org-policy](03-landing-zones-and-governance/02-guardrails-scp-azure-policy-org-policy/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [03-centralized-logging-and-audit](03-landing-zones-and-governance/03-centralized-logging-and-audit/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [04-identity-federation-sso](03-landing-zones-and-governance/04-identity-federation-sso/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [05-account-vending-factory](03-landing-zones-and-governance/05-account-vending-factory/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [06-network-hub-in-landing-zone](03-landing-zones-and-governance/06-network-hub-in-landing-zone/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [07-security-tooling-account](03-landing-zones-and-governance/07-security-tooling-account/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [08-budgets-and-cost-guardrails](03-landing-zones-and-governance/08-budgets-and-cost-guardrails/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [09-break-glass-access](03-landing-zones-and-governance/09-break-glass-access/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [10-sandbox-environments](03-landing-zones-and-governance/10-sandbox-environments/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [11-policy-as-code-pipeline](03-landing-zones-and-governance/11-policy-as-code-pipeline/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [12-landing-zone-for-msps](03-landing-zones-and-governance/12-landing-zone-for-msps/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |

## 04-application-architectures 🟢🟡🔴

| Architecture | Tier | AWS TF | AWS Pulumi | AWS CFN | Azure TF | Azure Pulumi | Azure Bicep | GCP TF | GCP Pulumi | GCP InfraMgr |
|---|---|---|---|---|---|---|---|---|---|---|
| [01-monolith-on-vms](04-application-architectures/01-monolith-on-vms/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [02-three-tier-web-app](04-application-architectures/02-three-tier-web-app/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [03-n-tier-with-internal-services](04-application-architectures/03-n-tier-with-internal-services/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [04-spa-plus-api](04-application-architectures/04-spa-plus-api/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [05-ssr-web-app](04-application-architectures/05-ssr-web-app/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [06-modular-monolith](04-application-architectures/06-modular-monolith/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [07-microservices-on-containers](04-application-architectures/07-microservices-on-containers/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [08-bff-pattern](04-application-architectures/08-bff-pattern/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [09-multi-tenant-saas-silo-pool-bridge](04-application-architectures/09-multi-tenant-saas-silo-pool-bridge/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [10-realtime-websocket-app](04-application-architectures/10-realtime-websocket-app/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [11-api-gateway-fronted-backend](04-application-architectures/11-api-gateway-fronted-backend/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [12-strangler-fig-modernization](04-application-architectures/12-strangler-fig-modernization/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |

## 05-serverless 🟢🟡🔴

| Architecture | Tier | AWS TF | AWS Pulumi | AWS CFN | Azure TF | Azure Pulumi | Azure Bicep | GCP TF | GCP Pulumi | GCP InfraMgr |
|---|---|---|---|---|---|---|---|---|---|---|
| [01-function-plus-api](05-serverless/01-function-plus-api/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [02-serverless-web-app](05-serverless/02-serverless-web-app/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [03-event-driven-function-pipeline](05-serverless/03-event-driven-function-pipeline/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [04-workflow-orchestration](05-serverless/04-workflow-orchestration/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [05-serverless-containers](05-serverless/05-serverless-containers/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [06-fan-out-fan-in](05-serverless/06-fan-out-fan-in/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [07-scheduled-jobs](05-serverless/07-scheduled-jobs/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [08-webhook-receiver](05-serverless/08-webhook-receiver/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [09-serverless-data-pipeline](05-serverless/09-serverless-data-pipeline/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [10-edge-functions](05-serverless/10-edge-functions/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [11-serverless-graphql](05-serverless/11-serverless-graphql/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |

## 06-containers-and-kubernetes 🟡🔴

| Architecture | Tier | AWS TF | AWS Pulumi | AWS CFN | Azure TF | Azure Pulumi | Azure Bicep | GCP TF | GCP Pulumi | GCP InfraMgr |
|---|---|---|---|---|---|---|---|---|---|---|
| [01-managed-container-service](06-containers-and-kubernetes/01-managed-container-service/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [02-managed-kubernetes-baseline](06-containers-and-kubernetes/02-managed-kubernetes-baseline/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [03-private-kubernetes-cluster](06-containers-and-kubernetes/03-private-kubernetes-cluster/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [04-ingress-and-gateway-api](06-containers-and-kubernetes/04-ingress-and-gateway-api/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [05-node-autoscaling](06-containers-and-kubernetes/05-node-autoscaling/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [06-spot-preemptible-node-pools](06-containers-and-kubernetes/06-spot-preemptible-node-pools/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [07-kubernetes-multi-tenancy](06-containers-and-kubernetes/07-kubernetes-multi-tenancy/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [08-gitops-platform](06-containers-and-kubernetes/08-gitops-platform/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [09-multi-cluster-and-fleet](06-containers-and-kubernetes/09-multi-cluster-and-fleet/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [10-service-mesh-on-managed-k8s](06-containers-and-kubernetes/10-service-mesh-on-managed-k8s/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [11-batch-and-ml-on-kubernetes](06-containers-and-kubernetes/11-batch-and-ml-on-kubernetes/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [12-internal-developer-platform](06-containers-and-kubernetes/12-internal-developer-platform/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |

## 07-event-driven-and-messaging 🟡🔴

| Architecture | Tier | AWS TF | AWS Pulumi | AWS CFN | Azure TF | Azure Pulumi | Azure Bicep | GCP TF | GCP Pulumi | GCP InfraMgr |
|---|---|---|---|---|---|---|---|---|---|---|
| [01-queue-based-load-leveling](07-event-driven-and-messaging/01-queue-based-load-leveling/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [02-pub-sub-fan-out](07-event-driven-and-messaging/02-pub-sub-fan-out/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [03-event-bus-routing](07-event-driven-and-messaging/03-event-bus-routing/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [04-dead-letter-and-retry](07-event-driven-and-messaging/04-dead-letter-and-retry/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [05-competing-consumers](07-event-driven-and-messaging/05-competing-consumers/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [06-streaming-ingestion](07-event-driven-and-messaging/06-streaming-ingestion/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [07-event-sourcing-cqrs](07-event-driven-and-messaging/07-event-sourcing-cqrs/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [08-saga-orchestration](07-event-driven-and-messaging/08-saga-orchestration/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [09-transactional-outbox-cdc](07-event-driven-and-messaging/09-transactional-outbox-cdc/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [10-claim-check](07-event-driven-and-messaging/10-claim-check/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [11-managed-kafka](07-event-driven-and-messaging/11-managed-kafka/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [12-exactly-once-pipeline](07-event-driven-and-messaging/12-exactly-once-pipeline/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |

## 08-data-and-analytics 🟡🔴

| Architecture | Tier | AWS TF | AWS Pulumi | AWS CFN | Azure TF | Azure Pulumi | Azure Bicep | GCP TF | GCP Pulumi | GCP InfraMgr |
|---|---|---|---|---|---|---|---|---|---|---|
| [01-batch-etl-pipeline](08-data-and-analytics/01-batch-etl-pipeline/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [02-data-lake](08-data-and-analytics/02-data-lake/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [03-data-warehouse](08-data-and-analytics/03-data-warehouse/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [04-lakehouse](08-data-and-analytics/04-lakehouse/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [05-medallion-architecture](08-data-and-analytics/05-medallion-architecture/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [06-streaming-analytics](08-data-and-analytics/06-streaming-analytics/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [07-cdc-to-warehouse](08-data-and-analytics/07-cdc-to-warehouse/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [08-search-architecture](08-data-and-analytics/08-search-architecture/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [09-lambda-and-kappa](08-data-and-analytics/09-lambda-and-kappa/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [10-data-mesh](08-data-and-analytics/10-data-mesh/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [11-time-series-store](08-data-and-analytics/11-time-series-store/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [12-data-governance-catalog](08-data-and-analytics/12-data-governance-catalog/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [13-bi-and-dashboards](08-data-and-analytics/13-bi-and-dashboards/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |

## 09-databases-and-persistence 🟡🔴

| Architecture | Tier | AWS TF | AWS Pulumi | AWS CFN | Azure TF | Azure Pulumi | Azure Bicep | GCP TF | GCP Pulumi | GCP InfraMgr |
|---|---|---|---|---|---|---|---|---|---|---|
| [01-managed-relational-multi-az](09-databases-and-persistence/01-managed-relational-multi-az/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [02-read-replicas](09-databases-and-persistence/02-read-replicas/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [03-nosql-key-value](09-databases-and-persistence/03-nosql-key-value/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [04-managed-cache-layer](09-databases-and-persistence/04-managed-cache-layer/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [05-cross-region-replica](09-databases-and-persistence/05-cross-region-replica/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [06-polyglot-persistence](09-databases-and-persistence/06-polyglot-persistence/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [07-database-migration](09-databases-and-persistence/07-database-migration/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [08-backup-pitr-and-archive](09-databases-and-persistence/08-backup-pitr-and-archive/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [09-global-database](09-databases-and-persistence/09-global-database/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [10-database-per-service](09-databases-and-persistence/10-database-per-service/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [11-sharded-database](09-databases-and-persistence/11-sharded-database/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [12-serverless-database](09-databases-and-persistence/12-serverless-database/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |

## 10-resilience-and-disaster-recovery 🟡🔴🔵

| Architecture | Tier | AWS TF | AWS Pulumi | AWS CFN | Azure TF | Azure Pulumi | Azure Bicep | GCP TF | GCP Pulumi | GCP InfraMgr |
|---|---|---|---|---|---|---|---|---|---|---|
| [01-multi-az-active-active](10-resilience-and-disaster-recovery/01-multi-az-active-active/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [02-backup-and-restore-dr](10-resilience-and-disaster-recovery/02-backup-and-restore-dr/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [03-multi-region-active-passive](10-resilience-and-disaster-recovery/03-multi-region-active-passive/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [04-blue-green-deployments](10-resilience-and-disaster-recovery/04-blue-green-deployments/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [05-pilot-light-dr](10-resilience-and-disaster-recovery/05-pilot-light-dr/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [06-warm-standby-dr](10-resilience-and-disaster-recovery/06-warm-standby-dr/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [07-global-load-balancing-failover](10-resilience-and-disaster-recovery/07-global-load-balancing-failover/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [08-canary-and-progressive-delivery](10-resilience-and-disaster-recovery/08-canary-and-progressive-delivery/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [09-multi-region-active-active](10-resilience-and-disaster-recovery/09-multi-region-active-active/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [10-cell-based-architecture](10-resilience-and-disaster-recovery/10-cell-based-architecture/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [11-shuffle-sharding-bulkheads](10-resilience-and-disaster-recovery/11-shuffle-sharding-bulkheads/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [12-chaos-engineering-platform](10-resilience-and-disaster-recovery/12-chaos-engineering-platform/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [13-static-stability](10-resilience-and-disaster-recovery/13-static-stability/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |

## 11-security-architectures 🟡🔴🔵

| Architecture | Tier | AWS TF | AWS Pulumi | AWS CFN | Azure TF | Azure Pulumi | Azure Bicep | GCP TF | GCP Pulumi | GCP InfraMgr |
|---|---|---|---|---|---|---|---|---|---|---|
| [01-edge-protection-waf-ddos](11-security-architectures/01-edge-protection-waf-ddos/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [02-zero-trust-access](11-security-architectures/02-zero-trust-access/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [03-secrets-and-key-management](11-security-architectures/03-secrets-and-key-management/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [04-workload-identity](11-security-architectures/04-workload-identity/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [05-private-only-architecture](11-security-architectures/05-private-only-architecture/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [06-security-monitoring-siem-pipeline](11-security-architectures/06-security-monitoring-siem-pipeline/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [07-centralized-firewall-inspection](11-security-architectures/07-centralized-firewall-inspection/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [08-pki-and-private-ca](11-security-architectures/08-pki-and-private-ca/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [09-secure-cicd-supply-chain](11-security-architectures/09-secure-cicd-supply-chain/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [10-cspm-compliance-automation](11-security-architectures/10-cspm-compliance-automation/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [11-data-perimeter](11-security-architectures/11-data-perimeter/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [12-tenant-isolation](11-security-architectures/12-tenant-isolation/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [13-confidential-computing](11-security-architectures/13-confidential-computing/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [14-pci-hipaa-baseline](11-security-architectures/14-pci-hipaa-baseline/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |

## 12-hybrid-and-multicloud 🔴🔵

| Architecture | Tier | AWS TF | AWS Pulumi | AWS CFN | Azure TF | Azure Pulumi | Azure Bicep | GCP TF | GCP Pulumi | GCP InfraMgr |
|---|---|---|---|---|---|---|---|---|---|---|
| [01-lift-and-shift-migration](12-hybrid-and-multicloud/01-lift-and-shift-migration/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [02-hybrid-identity](12-hybrid-and-multicloud/02-hybrid-identity/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [03-replatform-and-refactor-migration](12-hybrid-and-multicloud/03-replatform-and-refactor-migration/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [04-cross-cloud-data-replication](12-hybrid-and-multicloud/04-cross-cloud-data-replication/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [05-on-prem-extension-outposts-arc-gdc](12-hybrid-and-multicloud/05-on-prem-extension-outposts-arc-gdc/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [06-cloud-bursting](12-hybrid-and-multicloud/06-cloud-bursting/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [07-multicloud-active-passive](12-hybrid-and-multicloud/07-multicloud-active-passive/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [08-multicloud-networking](12-hybrid-and-multicloud/08-multicloud-networking/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [09-portable-kubernetes](12-hybrid-and-multicloud/09-portable-kubernetes/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [10-cloud-exit-and-repatriation](12-hybrid-and-multicloud/10-cloud-exit-and-repatriation/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [11-sovereign-cloud](12-hybrid-and-multicloud/11-sovereign-cloud/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |

## 13-cicd-and-platform-engineering 🟡🔴

| Architecture | Tier | AWS TF | AWS Pulumi | AWS CFN | Azure TF | Azure Pulumi | Azure Bicep | GCP TF | GCP Pulumi | GCP InfraMgr |
|---|---|---|---|---|---|---|---|---|---|---|
| [01-basic-cicd-pipeline](13-cicd-and-platform-engineering/01-basic-cicd-pipeline/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [02-iac-pipeline-plan-apply](13-cicd-and-platform-engineering/02-iac-pipeline-plan-apply/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [03-multi-environment-promotion](13-cicd-and-platform-engineering/03-multi-environment-promotion/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [04-gitops-delivery](13-cicd-and-platform-engineering/04-gitops-delivery/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [05-ephemeral-preview-environments](13-cicd-and-platform-engineering/05-ephemeral-preview-environments/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [06-artifact-and-container-registry](13-cicd-and-platform-engineering/06-artifact-and-container-registry/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [07-self-hosted-runners](13-cicd-and-platform-engineering/07-self-hosted-runners/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [08-policy-as-code-gates](13-cicd-and-platform-engineering/08-policy-as-code-gates/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [09-feature-flags-and-config](13-cicd-and-platform-engineering/09-feature-flags-and-config/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [10-internal-developer-portal](13-cicd-and-platform-engineering/10-internal-developer-portal/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |

## 14-observability-and-operations 🟡🔴

| Architecture | Tier | AWS TF | AWS Pulumi | AWS CFN | Azure TF | Azure Pulumi | Azure Bicep | GCP TF | GCP Pulumi | GCP InfraMgr |
|---|---|---|---|---|---|---|---|---|---|---|
| [01-centralized-logging](14-observability-and-operations/01-centralized-logging/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [02-metrics-and-alerting](14-observability-and-operations/02-metrics-and-alerting/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [03-distributed-tracing-otel](14-observability-and-operations/03-distributed-tracing-otel/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [04-finops-cost-visibility](14-observability-and-operations/04-finops-cost-visibility/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [05-patch-and-fleet-management](14-observability-and-operations/05-patch-and-fleet-management/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [06-config-drift-detection](14-observability-and-operations/06-config-drift-detection/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [07-audit-and-compliance-logging](14-observability-and-operations/07-audit-and-compliance-logging/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [08-slo-based-alerting](14-observability-and-operations/08-slo-based-alerting/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [09-incident-response-automation](14-observability-and-operations/09-incident-response-automation/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |

## 15-ai-ml-architectures 🟡🔴🔵

| Architecture | Tier | AWS TF | AWS Pulumi | AWS CFN | Azure TF | Azure Pulumi | Azure Bicep | GCP TF | GCP Pulumi | GCP InfraMgr |
|---|---|---|---|---|---|---|---|---|---|---|
| [01-rag-architecture](15-ai-ml-architectures/01-rag-architecture/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [02-ml-training-pipeline](15-ai-ml-architectures/02-ml-training-pipeline/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [03-real-time-model-serving](15-ai-ml-architectures/03-real-time-model-serving/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [04-batch-inference](15-ai-ml-architectures/04-batch-inference/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [05-llm-gateway](15-ai-ml-architectures/05-llm-gateway/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [06-vector-search](15-ai-ml-architectures/06-vector-search/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [07-agent-platform](15-ai-ml-architectures/07-agent-platform/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [08-mlops-pipeline](15-ai-ml-architectures/08-mlops-pipeline/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [09-gpu-training-cluster](15-ai-ml-architectures/09-gpu-training-cluster/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [10-fine-tuning-pipeline](15-ai-ml-architectures/10-fine-tuning-pipeline/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [11-ai-landing-zone-governance](15-ai-ml-architectures/11-ai-landing-zone-governance/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [12-semantic-cache-and-guardrails](15-ai-ml-architectures/12-semantic-cache-and-guardrails/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |

## 16-integration-and-api 🟡🔴

| Architecture | Tier | AWS TF | AWS Pulumi | AWS CFN | Azure TF | Azure Pulumi | Azure Bicep | GCP TF | GCP Pulumi | GCP InfraMgr |
|---|---|---|---|---|---|---|---|---|---|---|
| [01-api-gateway-patterns](16-integration-and-api/01-api-gateway-patterns/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [02-managed-sftp-b2b-integration](16-integration-and-api/02-managed-sftp-b2b-integration/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [03-partner-api-throttling](16-integration-and-api/03-partner-api-throttling/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [04-api-management-developer-portal](16-integration-and-api/04-api-management-developer-portal/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [05-graphql-federation](16-integration-and-api/05-graphql-federation/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [06-esb-replacement](16-integration-and-api/06-esb-replacement/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [07-workflow-automation-ipaas](16-integration-and-api/07-workflow-automation-ipaas/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |

## 17-iot-edge-and-media 🔴🔵

| Architecture | Tier | AWS TF | AWS Pulumi | AWS CFN | Azure TF | Azure Pulumi | Azure Bicep | GCP TF | GCP Pulumi | GCP InfraMgr |
|---|---|---|---|---|---|---|---|---|---|---|
| [01-global-content-delivery-cdn](17-iot-edge-and-media/01-global-content-delivery-cdn/) | ★ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [02-iot-ingestion-pipeline](17-iot-edge-and-media/02-iot-ingestion-pipeline/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [03-video-on-demand](17-iot-edge-and-media/03-video-on-demand/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [04-media-transcoding-pipeline](17-iot-edge-and-media/04-media-transcoding-pipeline/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [05-edge-compute](17-iot-edge-and-media/05-edge-compute/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [06-digital-twin](17-iot-edge-and-media/06-digital-twin/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [07-live-streaming](17-iot-edge-and-media/07-live-streaming/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [08-gaming-backend](17-iot-edge-and-media/08-gaming-backend/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [09-real-time-bidding-adtech](17-iot-edge-and-media/09-real-time-bidding-adtech/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |

## 18-industry-reference-architectures 🔴🔵

| Architecture | Tier | AWS TF | AWS Pulumi | AWS CFN | Azure TF | Azure Pulumi | Azure Bicep | GCP TF | GCP Pulumi | GCP InfraMgr |
|---|---|---|---|---|---|---|---|---|---|---|
| [01-ecommerce-platform](18-industry-reference-architectures/01-ecommerce-platform/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [02-saas-multi-tenant-platform](18-industry-reference-architectures/02-saas-multi-tenant-platform/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [03-payments-fintech](18-industry-reference-architectures/03-payments-fintech/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [04-healthcare-hipaa](18-industry-reference-architectures/04-healthcare-hipaa/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [05-banking-core-modernization](18-industry-reference-architectures/05-banking-core-modernization/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [06-government-sovereign](18-industry-reference-architectures/06-government-sovereign/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [07-logistics-and-tracking](18-industry-reference-architectures/07-logistics-and-tracking/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [08-streaming-media-platform](18-industry-reference-architectures/08-streaming-media-platform/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [09-social-feed-at-scale](18-industry-reference-architectures/09-social-feed-at-scale/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [10-ride-hailing-geospatial](18-industry-reference-architectures/10-ride-hailing-geospatial/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |

## 19-cost-and-sustainability 🟡🔴

| Architecture | Tier | AWS TF | AWS Pulumi | AWS CFN | Azure TF | Azure Pulumi | Azure Bicep | GCP TF | GCP Pulumi | GCP InfraMgr |
|---|---|---|---|---|---|---|---|---|---|---|
| [01-spot-and-preemptible-fleets](19-cost-and-sustainability/01-spot-and-preemptible-fleets/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [02-scheduled-start-stop](19-cost-and-sustainability/02-scheduled-start-stop/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [03-arm-based-compute](19-cost-and-sustainability/03-arm-based-compute/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [04-storage-tiering-lifecycle](19-cost-and-sustainability/04-storage-tiering-lifecycle/) | ◆ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [05-rightsizing-and-commitments](19-cost-and-sustainability/05-rightsizing-and-commitments/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [06-serverless-vs-container-cost-model](19-cost-and-sustainability/06-serverless-vs-container-cost-model/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [07-carbon-aware-workloads](19-cost-and-sustainability/07-carbon-aware-workloads/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |

## 20-emerging-and-new 🔵

| Architecture | Tier | AWS TF | AWS Pulumi | AWS CFN | Azure TF | Azure Pulumi | Azure Bicep | GCP TF | GCP Pulumi | GCP InfraMgr |
|---|---|---|---|---|---|---|---|---|---|---|
| [01-ai-agent-landing-zone](20-emerging-and-new/01-ai-agent-landing-zone/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [02-digital-sovereignty](20-emerging-and-new/02-digital-sovereignty/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [03-confidential-ai](20-emerging-and-new/03-confidential-ai/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [04-wasm-on-cloud](20-emerging-and-new/04-wasm-on-cloud/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [05-platform-engineering-with-agents](20-emerging-and-new/05-platform-engineering-with-agents/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [06-post-quantum-ready](20-emerging-and-new/06-post-quantum-ready/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |
| [07-placeholder-new-topic](20-emerging-and-new/07-placeholder-new-topic/) | ○ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ |

## Totals

| Status | Count |
|--------|-------|
| ⬜ Not started | 1,953 |
| 🟨 Code written | 0 |
| ✅ Validated | 0 |
| 🚀 Deployed and destroyed | 0 |
| **Total implementations** | **1,953** |
