<h1 align="center">Muhammad Murtaz Amir Naqvi</h1>

<p align="center">
  <b>Senior Platform &amp; Cloud Engineer</b><br>
  Ten years building and operating cloud native production systems.<br>
  Currently running a distributed Splunk platform for a large enterprise endpoint estate,<br>
  and researching machine learning for insider threat detection.
</p>

<p align="center">
  <a href="https://linkedin.com/in/muhamamd-murtaz-amir-naqvi-a836278a">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:murtazamirnaqvi@gmail.com">
    <img src="https://img.shields.io/badge/Email-24292F?style=flat-square&logo=gmail&logoColor=white" alt="Email">
  </a>
  <img src="https://img.shields.io/badge/Newcastle%20upon%20Tyne,%20UK-24292F?style=flat-square&logo=googlemaps&logoColor=white" alt="Location">
  <img src="https://img.shields.io/badge/Open%20to-Platform%20%2F%20SRE%20%2F%20ML%20Security-2ea043?style=flat-square" alt="Open to">
</p>

---

### What I work on

I own platform workstreams end to end. That means the Ansible roles that provision the estate, the Kubernetes clusters the workloads run on, the CI/CD that builds and ships cross platform agents, and the Splunk and ELK layers that tell you when any of it is unhappy.

The other half is research. My MSc dissertation was on insider threat detection using behavioural biometrics, and I start a PhD at Northumbria in October 2026 on adaptive guardrail synthesis for agentic AI applications.

---

### Selected work

<!-- Add repo links where public. Closed source entries are listed without links on purpose. -->

| Project | What it is | Stack |
| --- | --- | --- |
| **AI Driven Insider Threat Detection** | XGBoost plus BiLSTM attention framework on the CERT dataset. AUPRC 0.984, precision 96.5%, recall 93%. MSc dissertation, currently being prepared for publication. | Python, PyTorch, XGBoost, CERT |
| **Encrypted Traffic Classification** | ML classification of encrypted network traffic from DPDK and nDPI capture, validated under high throughput with Pktgen and T-Rex. | XGBoost, DNN, DPDK, nDPI |
| **UXM Endpoint Monitoring Platform** | Distributed Splunk Enterprise platform for endpoint experience monitoring. HEC ingest architecture, search performance, dashboard and alerting layer. *Closed source.* | Splunk, SPL, Ansible, GKE |
| **UXM Agent Build &amp; Release Pipeline** | Multi stage CI/CD compiling and packaging monitoring agents for Windows (EXE, MSI), macOS (DMG) and Linux from a single source tree. *Closed source.* | GitLab CI, GitHub Actions, C++, InnoSetup |
| **Governed Self Service Operations** | Rundeck layer giving L1 support pre approved runbooks for cache flush, restarts and capacity actions without handing out infrastructure access. *Closed source.* | Rundeck, Ansible, Python |
| **Centralised Log Analytics Platform** | ELK platform onboarding Cisco Meraki and other sources into unified search for incident troubleshooting. *Closed source.* | Elasticsearch, Logstash, Kibana |
| **Android Malware Detection** | Static and dynamic feature extraction with supervised classification. MS thesis at NUST. | Python, scikit-learn |

---

### Experience

**Senior IT Consultant, Platform &amp; Cloud Infrastructure**  
`MCG A/S · Apr 2021 to Present · Remote, Denmark`
- Led Kubernetes adoption, deploying and managing Splunk on GKE via the Splunk Operator for container native lifecycle management
- Built modular Ansible roles provisioning Splunk, RabbitMQ and UXM services consistently across dev, stage and prod
- Provisioned cloud infrastructure with Pulumi and migrated workflows to Terraform for better change control and auditability
- Administered Splunk Enterprise and ELK for centralised log analytics and proactive anomaly detection in production

**Senior Network Programmer**  
`Bellstone Pvt. Ltd. · Dec 2019 to Mar 2021 · Lahore, Pakistan`
- Built AWS and GCP infrastructure for a scalable WebRTC communications platform with security first access controls
- Containerised the platform on EKS using Kubernetes deployment patterns for resilience and controlled rollouts
- Implemented AWS Global Accelerator for edge routing, cutting latency for international users

**Software Design Engineer II**  
`XFlow Research Inc. · May 2018 to Dec 2019 · Islamabad, Pakistan`
- Engineered on prem network security platforms for high performance traffic filtering at carrier scale
- Built a centralised site orchestration module with Python Flask APIs for remote site onboarding and control plane operations
- Served as SME for DPDK and KVM virtualisation, guiding packet processing design and mentoring on performance engineering

---

### Research &amp; education

| | | |
| --- | --- | --- |
| **PhD Computer Science** *(offer held, Oct 2026)* | Northumbria University | Adaptive Guardrail Synthesis for Agentic AI Applications |
| **MSc Advanced Computer Science** | Northumbria University | AI Driven Insider Threat Detection Using Behavioural Biometrics |
| **MS Computer Engineering** | NUST, Pakistan | Android Malware Detection Using Machine Learning |
| **BEng Computer Engineering** | Lancaster University, UK | |

---

### Toolbox

**Infrastructure as code &amp; orchestration**  
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Pulumi](https://img.shields.io/badge/Pulumi-8A3391?style=flat-square&logo=pulumi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![Rundeck](https://img.shields.io/badge/Rundeck-00A8E1?style=flat-square&logoColor=white)

**Cloud**  
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![KVM](https://img.shields.io/badge/KVM-CC0000?style=flat-square&logoColor=white)

**Observability**  
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)
![Elastic](https://img.shields.io/badge/Elastic%20Stack-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)

**CI/CD**  
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab%20CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![AWS CodePipeline](https://img.shields.io/badge/CodePipeline-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo%20CD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Languages**  
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**ML**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square&logoColor=white)
![DPDK](https://img.shields.io/badge/DPDK-0071C5?style=flat-square&logoColor=white)

---

### Currently

- **Building** endpoint experience monitoring at scale, from the C++ agent through to the Splunk dashboard
- **Researching** guardrails for agentic AI systems, ahead of a PhD start in October 2026
- **Learning** Kubernetes internals and deeper reliability engineering practice
- **Open to** collaboration on cloud native platforms, security tooling and ML driven detection

---

### Activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=mmurtaznaqvi&show_icons=true&hide_border=true&theme=github_dark&hide_title=true&include_all_commits=true&rank_icon=github" alt="GitHub stats">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mmurtaznaqvi&layout=compact&hide_border=true&theme=github_dark&langs_count=8&hide=html,css" alt="Top languages">
</p>
