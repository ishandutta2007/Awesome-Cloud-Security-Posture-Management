# Awesome-Cloud-Security-Posture-Management

## Top Cloud Security Posture Management (CSPM) Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Cloud Misconfiguration Detection, Compliance Benchmarks, Attack-Path Analysis, Multi-Cloud Posture & Continuous Security Assessment*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Security Posture Management (CSPM)**. These tools continuously assess cloud environments for misconfigurations, policy violations, compliance gaps, and attack paths across AWS, Azure, GCP, and Kubernetes.



**Examples** include Wiz, Lacework, Orca Security, Palo Alto Prisma Cloud, Tenable Cloud Security, Microsoft Defender for Cloud, Check Point CloudGuard, Trend Vision One, CrowdStrike Falcon Cloud, SentinelOne Singularity, Prisma Cloud, Rapid7 InsightCloudSec, Ermetic, SentinelOne Singularity Cloud, Aqua Security, Sysdig, Microsoft Defender CSPM, and CrowdStrike Falcon Cloud Security (the category leaders).



**Open-source emphasis**: CSPM has a mature open-source ecosystem. **Prowler**, **ScoutSuite**, **Cloud Custodian**, **Steampipe**, **Checkov**, and related tools provide strong multi-cloud auditing, policy-as-code, and compliance checks. This section heavily expands those projects.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Wiz](https://www.wiz.io/)**  

  Leading agentless CNAPP/CSPM platform with Security Graph attack-path analysis, fast time-to-value, and broad multi-cloud coverage.



- **[Lacework](https://www.lacework.com/)**  

  Cloud security platform (now part of broader Fortinet/FortiCNAPP portfolios in some contexts) focused on posture, runtime, and anomaly detection.



- **[Orca Security](https://orca.security/)**  

  Agentless SideScanning CNAPP/CSPM with strong vulnerability, malware, and compliance coverage across cloud workloads.



- **[Palo Alto Prisma Cloud](https://www.paloaltonetworks.com/prisma/cloud)**  

  Comprehensive Code-to-Cloud CNAPP with deep CSPM, CWPP, CIEM, and IaC security capabilities.



- **[Tenable Cloud Security](https://www.tenable.com/products/tenable-cloud-security)**  

  Cloud security posture and CNAPP offering (incorporating former Ermetic capabilities) for multi-cloud risk visibility.



- **[Microsoft Defender for Cloud](https://azure.microsoft.com/products/defender-for-cloud)**  

  Native Microsoft CSPM and CNAPP tightly integrated with Azure, hybrid, and multi-cloud workloads, with foundational free tiers.



- **[Check Point CloudGuard](https://www.checkpoint.com/cloudguard/)**  

  Cloud-native security platform covering posture management, network security, and workload protection.



- **[Trend Vision One](https://www.trendmicro.com/)**  

  Extended detection and response platform with cloud security posture and workload protection modules.



- **[CrowdStrike Falcon Cloud Security](https://www.crowdstrike.com/)**  

  Cloud security capabilities within the Falcon platform, including posture assessment and workload protection.



- **[SentinelOne Singularity Cloud](https://www.sentinelone.com/)**  

  Cloud security and CNAPP features within the Singularity platform for posture and runtime protection.



- **[Rapid7 InsightCloudSec](https://www.rapid7.com/products/insightcloudsec/)**  

  Cloud security posture management and compliance platform for multi-cloud environments.



- **[Aqua Security](https://www.aquasec.com/)**  

  Cloud-native security platform with CSPM, container, and Kubernetes security capabilities (also maintains open-source CloudSploit/Trivy lineage).



- **[Sysdig](https://sysdig.com/)**  

  Cloud and container security platform strong on runtime detection, Kubernetes, and posture management.



## Open-Source GitHub Projects

- **[Prowler](https://github.com/prowler-cloud/prowler)**  

  Leading open-source multi-cloud security assessment tool—CIS benchmarks and compliance checks across AWS, Azure, GCP, Kubernetes, and more (Apache 2.0).



- **[ScoutSuite](https://github.com/nccgroup/ScoutSuite)**  

  Open-source multi-cloud security auditing tool from NCC Group that produces clear HTML reports of posture findings.



- **[Cloud Custodian](https://github.com/cloud-custodian/cloud-custodian)**  

  Open-source rules engine for cloud security, cost, and governance—policy-as-code with real-time and scheduled enforcement across major clouds.



- **[Steampipe](https://github.com/turbot/steampipe)**  

  Open-source tool that turns cloud APIs into SQL tables—powerful for custom posture queries, compliance mods, and investigations.



- **[Checkov](https://github.com/bridgecrewio/checkov)**  

  Widely used open-source IaC security scanner (Terraform, CloudFormation, Kubernetes, etc.) with hundreds of built-in policies.



- **[CloudSploit](https://github.com/aquasecurity/cloudsploit)**  

  Open-source cloud misconfiguration scanner (Aqua) supporting AWS, Azure, GCP, and other providers.



- **[Trivy](https://github.com/aquasecurity/trivy)**  

  Popular open-source scanner for containers, IaC, and cloud configurations—unifies vulnerability and misconfiguration detection.



- **[kube-bench](https://github.com/aquasecurity/kube-bench)**  

  Open-source tool that checks whether Kubernetes clusters are deployed according to CIS Kubernetes Benchmarks.



- **[CloudQuery](https://github.com/cloudquery/cloudquery)**  

  Open-source cloud asset inventory and ETL tool useful for building custom CSPM-style analysis pipelines.



- **[Documentation and open CSPM playbooks](https://docs.prowler.com/)**  

  Guides for running continuous or scheduled open-source posture assessments and integrating results into SIEM/CI pipelines.



### Additional Strong Open-Source Options

- Starting with **Prowler** for fast, comprehensive multi-cloud and Kubernetes compliance audits.

- Adding **ScoutSuite** for human-readable assessment reports and **Cloud Custodian** for automated remediation/enforcement.

- Using **Checkov + Trivy** to shift security left into IaC and container pipelines.

- Leveraging **Steampipe** when teams prefer SQL-driven custom posture queries.

- Accepting that agentless attack-path graphs, continuous CNAPP correlation, automated prioritization, and enterprise support still favor commercial platforms (Wiz, Orca, Prisma Cloud, Defender for Cloud, etc.).

- Focusing open-source efforts on transparency, cost control, and pipeline-integrated guardrails.



**Frameworks for building custom systems**: Run Prowler/ScoutSuite on a schedule → store findings in a database or SIEM → enforce cleanup with Cloud Custodian → scan IaC with Checkov/Trivy in CI → query assets with Steampipe. Suitable for platform and security engineering teams. Many enterprises still adopt commercial CSPM/CNAPP for scale, attack-path context, and managed operations.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- CSPM tools influence production cloud security. Open-source deployments require proper credentials management, scheduling, and response processes. This list is not security or compliance advice.



---

**Made for cloud security engineers, platform teams, and open-source security advocates.**

Let's keep cloud posture visible, enforceable, and as open as practical.
