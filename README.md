# Awesome IT Operations [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools, scripts, frameworks, and resources for IT operations, infrastructure management, and enterprise technology.

Covering identity and access management, endpoint management, cloud infrastructure, security, observability, automation, cost optimization, and more.

---

## Contents

- [Identity & Access Management](#identity--access-management)
- [Endpoint Management](#endpoint-management)
- [Cloud Infrastructure](#cloud-infrastructure)
- [Security & Compliance](#security--compliance)
- [Observability](#observability)
- [Automation & Scripting](#automation--scripting)
- [Cost Optimization](#cost-optimization)
- [Internal Tooling](#internal-tooling)
- [Vendor Management](#vendor-management)
- [Learning & Reference](#learning--reference)
- [Contributing](#contributing)
- [License](#license)

---

## Identity & Access Management

- [Microsoft Entra ID (Azure AD)](https://entra.microsoft.com/) — Cloud identity and access management platform with Conditional Access, MFA, and SSO.
- [Keycloak](https://www.keycloak.org/) — Open-source identity and access management with SSO, OIDC, and SAML support.
- [SCIM2](https://github.com/PingIdentity/scim2) — Java library for building SCIM 2.0 provisioning clients and servers.
- [saml-chrome-panel](https://chrome.google.com/webstore/detail/saml-chrome-panel/paijfdbeoenhembfhkhllainmocckace) — Chrome extension for viewing and debugging SAML assertions in the browser.
- [OIDC Debugger](https://oidcdebugger.com/) — Free tool for testing and debugging OpenID Connect authentication flows.
- [Microsoft Graph Explorer](https://developer.microsoft.com/en-us/graph/graph-explorer) — Interactive tool for testing Microsoft Graph API calls against Entra ID and M365.
- [Casdoor](https://casdoor.org/) — Open-source SSO/IAM platform supporting OAuth 2.0, OIDC, SAML, LDAP, and SCIM.
- [python-msgraph](https://github.com/microsoftgraph/msgraph-sdk-python) — Official Microsoft Graph SDK for Python, useful for automating Entra ID operations.
- [Dex](https://dexidp.io/) — Federated OIDC identity provider that proxies to multiple upstream IdPs.
- [Authentik](https://goauthentik.io/) — Open-source identity provider with flows, policies, and outpost-based reverse proxy.
- [Conditional Access Documenter](https://github.com/merill/ConditionalAccessDocumenter) — Exports and visualizes Entra ID Conditional Access policies for review and auditing.
- [jwt.io](https://jwt.io/) — Decode, verify, and generate JWTs for debugging OIDC and OAuth token flows.
- [Opal](https://www.opal.dev/) — Automated access management platform for just-in-time privilege escalation and access reviews.

## Endpoint Management

- [Jamf Pro](https://www.jamf.com/products/jamf-pro/) — Enterprise Apple device management for macOS, iOS, iPadOS, and tvOS.
- [Microsoft Intune](https://www.microsoft.com/en-us/security/business/microsoft-intune) — Cloud-based endpoint management for Windows, macOS, iOS, and Android.
- [osquery](https://osquery.io/) — SQL-based endpoint visibility tool for querying OS state across your fleet.
- [Nudge](https://github.com/macadmins/nudge) — macOS application that encourages users to update their OS with customizable deferral policies.
- [CIS-CAT Pro](https://www.cisecurity.org/cybersecurity-tools/cis-cat-pro) — Automated compliance assessment against CIS Benchmarks for endpoints and servers.
- [Installapplications](https://github.com/macadmins/installapplications) — Bootstrap package for automated macOS DEP/ADE enrollment workflows.
- [MicroMDM](https://micromdm.io/) — Open-source MDM server for Apple devices, useful for testing and small deployments.
- [IntuneWinAppUtil](https://github.com/microsoft/Microsoft-Win32-Content-Prep-Tool) — Microsoft tool for packaging Win32 apps into .intunewin format for Intune deployment.
- [Puppet](https://puppet.com/) — Configuration management for enforcing endpoint and server state at scale.
- [swiftDialog](https://github.com/swiftDialog/swiftDialog) — macOS admin tool for creating dialogs and notifications in Jamf workflows.
- [Santa](https://santa.dev/) — Binary allowlisting/blocklisting system for macOS, created by Google.
- [SOFA](https://sofa.macadmins.io/) — macOS and iOS update feed that tracks latest OS releases, CVEs, and actively exploited vulnerabilities.
- [Zentral](https://zentral.io/) — Open-source endpoint monitoring and response platform for macOS and Linux.

## Cloud Infrastructure

- [Terraform](https://www.terraform.io/) — Industry-standard Infrastructure as Code tool for provisioning across AWS, GCP, Azure, and more.
- [OpenTofu](https://opentofu.org/) — Open-source fork of Terraform, community-driven and MPL-licensed.
- [tflint](https://github.com/terraform-linters/tflint) — Pluggable Terraform linter that catches errors and enforces best practices before apply.
- [Checkov](https://www.checkov.io/) — Static analysis tool for scanning IaC (Terraform, CloudFormation, Kubernetes) for misconfigurations.
- [Infracost](https://www.infracost.io/) — Shows cloud cost estimates for Terraform changes directly in pull requests.
- [Terragrunt](https://terragrunt.gruntwork.io/) — Thin wrapper for Terraform that provides DRY configurations and remote state management.
- [Pulumi](https://www.pulumi.com/) — Infrastructure as Code using general-purpose languages (Python, TypeScript, Go, C#).
- [Cloud Custodian](https://cloudcustodian.io/) — Rules engine for cloud resource management, cost optimization, and compliance enforcement.
- [Komiser](https://github.com/tailwarden/komiser) — Open-source cloud resource inspector and cost dashboard for multi-cloud environments.
- [Crossplane](https://www.crossplane.io/) — Kubernetes-native infrastructure provisioning using custom resource definitions.
- [Spacelift](https://spacelift.io/) — Collaborative IaC management platform with policy-as-code, drift detection, and RBAC.
- [env0](https://www.env0.com/) — Self-service infrastructure platform with Terraform automation, cost tracking, and governance.
- [Pike](https://github.com/JamesWoolfenden/pike) — Automatically generates IAM policies from Terraform code by scanning resource requirements.

## Security & Compliance

- [Microsoft Sentinel](https://azure.microsoft.com/en-us/products/microsoft-sentinel/) — Cloud-native SIEM and SOAR built on Azure Log Analytics for security event correlation.
- [Wazuh](https://wazuh.com/) — Open-source security monitoring platform providing SIEM, XDR, and compliance capabilities.
- [Prowler](https://prowler.pro/) — AWS and Azure security assessment tool aligned with CIS, PCI-DSS, HIPAA, and GDPR.
- [ScoutSuite](https://github.com/nccgroup/ScoutSuite) — Multi-cloud security auditing tool covering AWS, GCP, Azure, and Oracle Cloud.
- [Trivy](https://trivy.dev/) — Comprehensive vulnerability scanner for containers, filesystems, git repos, and IaC.
- [Falco](https://falco.org/) — Cloud-native runtime security tool that detects anomalous behavior in containers and hosts.
- [TheHive](https://thehive-project.org/) — Open-source incident response platform for security teams with case management and automation.
- [MITRE ATT&CK Navigator](https://mitre-attack.github.io/attack-navigator/) — Web tool for annotating and visualizing ATT&CK coverage against adversary techniques.
- [Graylog](https://graylog.org/) — Centralized log management and SIEM with alerting, dashboards, and search.
- [Velociraptor](https://docs.velociraptor.app/) — Endpoint forensics and incident response tool for collecting artifacts at scale.
- [CrowdStrike Falcon](https://www.crowdstrike.com/) — Endpoint detection and response (EDR) platform with threat intelligence and managed hunting.
- [HashiCorp Vault](https://www.vaultproject.io/) — Secrets management for storing, accessing, and rotating credentials, certificates, and API keys.
- [Drata](https://drata.com/) — Automated compliance platform for SOC 2, ISO 27001, HIPAA, and GDPR readiness.

## Observability

- [Prometheus](https://prometheus.io/) — Open-source metrics collection and alerting toolkit, the de facto standard for Kubernetes monitoring.
- [Grafana](https://grafana.com/) — Open-source visualization and dashboarding platform for metrics, logs, and traces.
- [Datadog](https://www.datadoghq.com/) — Full-stack observability platform with APM, infrastructure monitoring, log management, and RUM.
- [Loki](https://grafana.com/oss/loki/) — Log aggregation system by Grafana Labs, designed to work seamlessly with Prometheus and Grafana.
- [OpenTelemetry](https://opentelemetry.io/) — Vendor-neutral standard for collecting distributed traces, metrics, and logs.
- [Jaeger](https://www.jaegertracing.io/) — Open-source distributed tracing system for monitoring microservice architectures.
- [PagerDuty](https://www.pagerduty.com/) — Incident management and on-call scheduling platform for operations teams.
- [Alertmanager](https://prometheus.io/docs/alerting/latest/alertmanager/) — Handles alerts from Prometheus with deduplication, grouping, routing, and silencing.
- [Uptime Kuma](https://github.com/louislam/uptime-kuma) — Self-hosted monitoring tool with a clean UI for HTTP, TCP, DNS, and other uptime checks.
- [Vector](https://vector.dev/) — High-performance observability data pipeline for collecting, transforming, and routing logs and metrics.
- [Thanos](https://thanos.io/) — Highly available Prometheus setup with long-term storage, global query view, and downsampling.
- [Elastic Stack (ELK)](https://www.elastic.co/elastic-stack) — Elasticsearch, Logstash, and Kibana for search, log aggregation, and visualization at scale.
- [Sentry](https://sentry.io/) — Application error tracking and performance monitoring with stack traces and release health.
- [Netdata](https://www.netdata.cloud/) — Real-time infrastructure monitoring with per-second granularity and zero-configuration agents.

## Automation & Scripting

- [Ansible](https://www.ansible.com/) — Agentless automation platform for configuration management, app deployment, and orchestration.
- [Rundeck](https://www.rundeck.com/) — Self-service operations automation with job scheduling, RBAC, and audit logging.
- [n8n](https://n8n.io/) — Fair-code workflow automation tool with a visual editor and 200+ integrations.
- [Task](https://taskfile.dev/) — Modern task runner written in Go, simpler alternative to Make with YAML-based configuration.
- [Just](https://github.com/casey/just) — Command runner that replaces Makefiles with a simpler, more readable syntax.
- [Chef Infra](https://www.chef.io/) — Configuration management using Ruby-based recipes for infrastructure automation at scale.
- [SaltStack](https://saltproject.io/) — Event-driven automation and configuration management with remote execution.
- [Ofelia](https://github.com/mcuadros/ofelia) — Docker-native job scheduler as a replacement for cron in containerized environments.
- [Temporal](https://temporal.io/) — Durable execution framework for building reliable workflows and long-running processes.
- [PowerShell](https://github.com/PowerShell/PowerShell) — Cross-platform automation framework and scripting language, essential for Windows and Azure management.
- [xonsh](https://xon.sh/) — Python-powered shell that blends Bash-like syntax with Python for scripting.
- [Fabric](https://www.fabfile.org/) — Python library for streamlining SSH-based application deployment and system administration.
- [Semaphore](https://github.com/semaphoreui/semaphore) — Open-source web UI for running Ansible playbooks with inventory management and scheduling.

## Cost Optimization

- [Infracost](https://www.infracost.io/) — Cloud cost estimates for Terraform in pull requests, enabling shift-left cost awareness.
- [Komiser](https://github.com/tailwarden/komiser) — Open-source cloud cost inspector with multi-cloud resource and spend visibility.
- [Cloud Custodian](https://cloudcustodian.io/) — Policy-as-code engine for managing cloud resources, enforcing tagging, and automating cleanup.
- [Kubecost](https://www.kubecost.com/) — Real-time Kubernetes cost monitoring and allocation by namespace, deployment, and label.
- [FinOps Foundation](https://www.finops.org/) — Community, frameworks, and best practices for cloud financial management.
- [AWS Cost Explorer](https://aws.amazon.com/aws-cost-management/aws-cost-explorer/) — Native AWS tool for visualizing, analyzing, and forecasting cloud spend.
- [GCP Billing Reports](https://cloud.google.com/billing/docs/reports) — Built-in GCP cost analysis with filtering by project, service, SKU, and label.
- [Vantage](https://www.vantage.sh/) — Multi-cloud cost transparency platform with per-resource cost tracking and reporting.
- [Spot.io (by NetApp)](https://spot.io/) — Automated cloud infrastructure optimization using spot/preemptible instances and autoscaling.
- [Usage.ai](https://usage.ai/) — Automated AWS Reserved Instance and Savings Plan purchasing for cost reduction.
- [Zylo](https://zylo.com/) — SaaS management platform for license optimization, renewal tracking, and spend visibility.
- [Apptio Cloudability](https://www.apptio.com/products/cloudability/) — Enterprise FinOps platform for multi-cloud cost allocation, optimization, and governance.
- [OpenCost](https://www.opencost.io/) — CNCF project for real-time Kubernetes cost monitoring, the open-source core behind Kubecost.

## Internal Tooling

- [Retool](https://retool.com/) — Low-code platform for building internal tools with drag-and-drop components and API integrations.
- [Appsmith](https://www.appsmith.com/) — Open-source framework for building internal dashboards, admin panels, and CRUD apps.
- [Budibase](https://budibase.com/) — Open-source low-code platform for creating internal tools with built-in database and automation.
- [Backstage](https://backstage.io/) — Open-source developer portal by Spotify for managing services, docs, and infrastructure.
- [Kong Gateway](https://konghq.com/) — Cloud-native API gateway for managing, securing, and observing API traffic.
- [Windmill](https://www.windmill.dev/) — Open-source workflow engine and internal tool builder with scripts in Python, TypeScript, Go, and SQL.
- [Airplane](https://www.airplane.dev/) — Platform for building internal tools as code with tasks, views, and workflows.
- [Directus](https://directus.io/) — Open-source headless CMS and data platform with a real-time API and admin dashboard.
- [ToolJet](https://www.tooljet.com/) — Open-source low-code platform for building and deploying internal tools with visual app builder.
- [Port](https://www.getport.io/) — Internal developer portal for cataloging services, resources, and workflows with self-service actions.
- [Apache APISIX](https://apisix.apache.org/) — Cloud-native API gateway with dynamic routing, load balancing, and plugin extensibility.
- [Grafana OnCall](https://grafana.com/oss/oncall/) — Open-source on-call management with escalation chains, schedules, and ChatOps integration.

## Vendor Management

- [Zylo](https://zylo.com/) — SaaS management platform for discovering, optimizing, and governing software spend.
- [Productiv](https://productiv.com/) — SaaS intelligence platform that provides app usage analytics for license optimization.
- [Vendr](https://www.vendr.com/) — SaaS buying and renewal platform with negotiation support and benchmarked pricing data.
- [Zluri](https://www.zluri.com/) — SaaS management and identity governance platform with automated access reviews and workflows.
- [Torii](https://www.toriihq.com/) — SaaS management platform with automated discovery, workflow automation, and license optimization.
- [BetterCloud](https://www.bettercloud.com/) — SaaS operations platform for managing, securing, and automating SaaS application environments.
- [NPI](https://www.npi-financial.com/) — Technology procurement optimization with license advisory and vendor negotiation support.
- [Cledara](https://www.cledara.com/) — SaaS spend management with virtual cards, automated tracking, and approval workflows.
- [Ironclad](https://ironcladapp.com/) — Contract lifecycle management platform for drafting, negotiating, and storing agreements.
- [Juro](https://juro.com/) — AI-enabled contract management for in-browser creation, negotiation, and analysis.
- [Vertice](https://www.vertice.one/) — SaaS and cloud purchasing platform with AI-powered pricing benchmarks and renewal management.

## Learning & Reference

### Certifications

- [Microsoft SC-300](https://learn.microsoft.com/en-us/credentials/certifications/identity-and-access-administrator/) — Microsoft Identity and Access Administrator certification.
- [HashiCorp Terraform Associate](https://www.hashicorp.com/certification/terraform-associate) — Foundational certification for Terraform concepts and IaC workflows.
- [AWS Solutions Architect Associate](https://aws.amazon.com/certification/certified-solutions-architect-associate/) — Core AWS architecture, compute, storage, networking, and security.
- [Google Cloud Professional Cloud Architect](https://cloud.google.com/learn/certification/cloud-architect) — GCP architecture design, implementation, and management.
- [FinOps Certified Practitioner](https://learn.finops.org/) — Cloud financial management certification from the FinOps Foundation.
- [CompTIA Security+](https://www.comptia.org/certifications/security) — Foundational cybersecurity certification covering operations and risk management.

### Blogs & Newsletters

- [MacAdmins Blog](https://www.macadmins.io/) — Community hub for Apple enterprise administration with resources, tools, and Slack.
- [The Cloud Girl](https://thecloudgirl.dev/) — Visual sketchnotes and explanations for Azure and cloud concepts.
- [Last Week in AWS](https://www.lastweekinaws.com/) — Snarky, informative weekly newsletter covering AWS news, launches, and cost pitfalls.
- [tl;dr sec](https://tldrsec.com/) — Curated newsletter summarizing the latest in application and cloud security.
- [Merill Fernando's Blog](https://merill.net/) — Deep dives on Entra ID, Conditional Access, and Microsoft Graph.

### Podcasts

- [Screaming in the Cloud](https://www.lastweekinaws.com/podcast/screaming-in-the-cloud/) — Conversations about AWS, cloud architecture, and the business of cloud.
- [Cloud Security Podcast by Google](https://cloud.withgoogle.com/cloudsecurity/podcast/) — Weekly discussions on cloud security from the Google Cloud security team.
- [The Mac Admins Podcast](https://podcast.macadmins.io/) — Weekly podcast covering Apple enterprise administration and the Mac admin community.

### Conferences

- [MacAdmins at Penn State](https://macadmins.psu.edu/) — Premier annual conference for Apple IT administrators.
- [KubeCon + CloudNativeCon](https://www.cncf.io/kubecon-cloudnativecon-events/) — The flagship CNCF event for Kubernetes and cloud-native technologies.
- [FinOps X](https://x.finops.org/) — Annual summit for cloud financial management practitioners.

### Books

- [The Phoenix Project](https://itrevolution.com/the-phoenix-project/) — Novel about IT operations, DevOps, and the business value of technology.
- [Site Reliability Engineering](https://sre.google/sre-book/table-of-contents/) — Free online book from Google on SRE principles and practices.
- [Terraform: Up & Running](https://www.terraformupandrunning.com/) — Practical guide to writing production-grade Infrastructure as Code.

---

## Contributing

Contributions are welcome. Please read the [contribution guidelines](https://github.com/sindresorhus/awesome/blob/main/contributing.md) first, then open a pull request.

General rules:

- One tool per line, formatted as `[Name](URL) — Description.`
- Keep descriptions concise and objective (no marketing language).
- Tools should be actively maintained and relevant to IT operations.
- Check for duplicates before adding.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Athanasius Wahbah](mailto:wahbah@me.com) has waived all copyright and related or neighboring rights to this work.
