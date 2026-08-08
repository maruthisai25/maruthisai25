## Sai Maruthi

Platform / SRE engineer. I build the infrastructure other people's software runs on — Kubernetes control planes in Go, Terraform landing zones, and, lately, LLM agents trusted with production access.

Currently at **Razorpay**, working on platform and reliability for regulated banking infrastructure: a Slack-native AI DevOps agent with scoped, fully audited production access; fleet-wide EKS upgrades delivered through GitOps; and SLO-driven observability.

### What I work on

- **Kubernetes internals** — custom CRDs and controllers built on controller-runtime, operators, CEL/admission validation
- **AI agents in production** — LLM agents and MCP servers with scoped RBAC, just-in-time permissions, human-in-the-loop approvals, and complete audit trails
- **Infrastructure as code** — Terraform landing zones, multi-region DR, GitOps delivery pipelines
- **Observability** — Prometheus, OpenTelemetry, multi-window SLO burn rates, incident response

### Projects

**[IncidentOS](https://github.com/maruthisai25/IncidentOS)** — Kubernetes reliability control plane
A Go operator with an `IncidentScenario` CRD that drives bounded fault injection through Chaos Mesh behind fail-closed Prometheus abort gates. Multi-window SLO burn rates, evidence-ranked root-cause analysis with provenance on every signal, policy-gated remediation, and generated postmortems.

**[modelops](https://github.com/maruthisai25/modelops)** — Gated model release platform
Quality, latency and cost gates in front of every model rollout, with canary traffic steps, automated rollback, fallback routing, Cosign artifact verification, and CRD/CEL validation live-tested on Kubernetes 1.34.

**[K-Query](https://github.com/maruthisai25/K_Query)** — Slack-native DevOps agent for Kubernetes
Private LLM inference, Qdrant vector search over runbooks and FAQs, and live kubectl + Prometheus queries behind a `/devops` slash command. Ships with production Kubernetes manifests: HPA, RBAC, NetworkPolicy, ServiceMonitor.

**[AWS Education Platform](https://github.com/maruthisai25/AWS_Health_App)** — Cloud-native platform, end-to-end in Terraform
Cognito authentication, AppSync + DynamoDB real-time chat, Elastic Transcoder video delivery, Aurora PostgreSQL, WAF/IAM/KMS, and CloudWatch/CloudTrail/X-Ray observability.

### Toolbox

`Go` &nbsp;`Python` &nbsp;`Kubernetes` &nbsp;`Terraform` &nbsp;`AWS` &nbsp;`GCP` &nbsp;`Prometheus` &nbsp;`OpenTelemetry` &nbsp;`Istio` &nbsp;`Karpenter` &nbsp;`Argo CD` &nbsp;`vLLM` &nbsp;`MCP`

---

<sub>AWS Certified Solutions Architect · Google Cloud Associate Cloud Engineer · HashiCorp Terraform Associate</sub>

<sub>[LinkedIn](https://linkedin.com/in/sai-maruthi)</sub>
