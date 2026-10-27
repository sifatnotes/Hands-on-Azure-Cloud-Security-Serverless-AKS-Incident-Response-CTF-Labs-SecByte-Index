# Hands-on-Azure-Cloud-Security-Serverless-AKS-Incident-Response-CTF-Labs-SecByte-Index
A comprehensive collection of practical cybersecurity CTF labs covering Microsoft Azure security, cloud incident response, serverless security (Logic Apps, Azure Functions), Azure Kubernetes Service (AKS), Entra ID RBAC, Azure Sentinel, Defender for Cloud, and cloud supply chain defense.
# Azure Cloud Security, Serverless & Incident Response CTF Lab Collection

Welcome to the **Azure Cloud Security, Serverless & Incident Response CTF Lab Collection**. This repository provides an organized, searchable catalog of practical cybersecurity labs and Capture The Flag (CTF) challenges hosted on Learn SecByte.

This catalog covers end-to-end Microsoft Azure security disciplines, including Entra ID RBAC governance, policy compliance, serverless application security (Azure Functions and Logic Apps), Azure Kubernetes Service (AKS) identity defense, secure container registries (ACR), and SOC operations with Microsoft Sentinel and Defender for Cloud.

---

## Lab Collection Index

### 1. Azure Identity, Governance & Security Posture
* **Azure RBAC: From Roles to Real-World Access Control**  
  *Lab Link:* [https://learn.secbyte.org/ctf/azure-rbac-from-roles-to-real-world-access-control](https://learn.secbyte.org/ctf/azure-rbac-from-roles-to-real-world-access-control)  
  *Focus:* Auditing custom vs. built-in RBAC roles, principle of least privilege, role assignment scope, and preventing privilege escalation paths.

* **Azure Policy: Governance, Compliance, and Control**  
  *Lab Link:* [https://learn.secbyte.org/ctf/azure-policy-governance-compliance-control](https://learn.secbyte.org/ctf/azure-policy-governance-compliance-control)  
  *Focus:* Writing and enforcing custom Azure Policy definitions, initiative assignments, compliance auditing, and automated remediation tasks.

* **Microsoft Defender for Cloud: Secure Posture & Threat Detection**  
  *Lab Link:* [https://learn.secbyte.org/ctf/microsoft-defender-for-cloud-secure-posture-threat-detection](https://learn.secbyte.org/ctf/microsoft-defender-for-cloud-secure-posture-threat-detection)  
  *Focus:* Evaluating Cloud Security Posture Management (CSPM), regulatory compliance dashboards, agentless scanning, and security recommendation enforcement.

### 2. Azure Serverless, Containers & Cloud Supply Chain
* **Azure Functions Security: Serverless Attack and Defense Lab**  
  *Lab Link:* [https://learn.secbyte.org/ctf/azure-functions-security-serverless-attack-and-defense-lab](https://learn.secbyte.org/ctf/azure-functions-security-serverless-attack-and-defense-lab)  
  *Focus:* Analyzing HTTP trigger vulnerabilities, function keys management, managed identity assignment, and serverless runtime breakouts.

* **Azure Logic Apps Security: Abuse and Defense**  
  *Lab Link:* [https://learn.secbyte.org/ctf/azure-logic-apps-security-abuse-and-defense](https://learn.secbyte.org/ctf/azure-logic-apps-security-abuse-and-defense)  
  *Focus:* Investigating HTTP endpoint triggers, API connection abuse, unauthorized workflow execution, and securing workflow secrets.

* **Azure Container Registry: Secure Supply Chain Essentials**  
  *Lab Link:* [https://learn.secbyte.org/ctf/azure-container-registry-secure-supply-chain-essentials](https://learn.secbyte.org/ctf/azure-container-registry-secure-supply-chain-essentials)  
  *Focus:* Enforcing ACR vulnerability scanning, content trust (Notary image signing), private endpoint isolation, and access token restriction.

* **Azure Kubernetes Service: Identity Exposure & Cluster Security**  
  *Lab Link:* [https://learn.secbyte.org/ctf/azure-kubernetes-service-identity-exposure-cluster-security](https://learn.secbyte.org/ctf/azure-kubernetes-service-identity-exposure-cluster-security)  
  *Focus:* Workload ID integration, auditing pod identity exposure, securing API server access, and mitigating cluster-to-tenant lateral movement.

### 3. Azure Telemetry, Threat Detection & Incident Response
* **Azure Security Assessment: From Tenant Recon to Incident Response**  
  *Lab Link:* [https://learn.secbyte.org/ctf/azure-security-assessment-from-tenant-recon-to-incident-resp](https://learn.secbyte.org/ctf/azure-security-assessment-from-tenant-recon-to-incident-resp)  
  *Focus:* Executing full-tenant security audits, tenant recon, misconfiguration identification, and full incident response workflows.

* **Azure Monitor Deep Dive: Visibility, Investigation, Detection**  
  *Lab Link:* [https://learn.secbyte.org/ctf/azure-monitor-deep-dive-visibility-investigation-detection-e](https://learn.secbyte.org/ctf/azure-monitor-deep-dive-visibility-investigation-detection-e)  
  *Focus:* Writing advanced Log Analytics KQL queries, configuring Diagnostic Settings, workbook creation, and setting metric alerts.

* **Azure Incident Response: Cloud Log Triage to Containment**  
  *Lab Link:* [https://learn.secbyte.org/ctf/azure-incident-response-cloud-log-triage-to-containment](https://learn.secbyte.org/ctf/azure-incident-response-cloud-log-triage-to-containment)  
  *Focus:* Analyzing Activity Logs, Entra ID Sign-in logs, host containment, token revocation, and isolating compromised Azure resources.

* **Azure Sentinel: Cloud Threat Detection and Incident Response**  
  *Lab Link:* [https://learn.secbyte.org/ctf/azure-sentinel-cloud-threat-detection-and-incident-response](https://learn.secbyte.org/ctf/azure-sentinel-cloud-threat-detection-and-incident-response)  
  *Focus:* Authoring KQL scheduled analytics rules, Sentinel incident triage, automated logic app playbooks, and threat investigation maps.

* **Azure Defender: Cloud Threat Detection & Response**  
  *Lab Link:* [https://learn.secbyte.org/ctf/azure-defender-cloud-threat-detection-response](https://learn.secbyte.org/ctf/azure-defender-cloud-threat-detection-response)  
  *Focus:* Triaging Defender for Resource Provider alerts (Servers, Key Vault, Storage), behavioral anomaly detection, and workload defense.

---

## Learning Path

### Path A: Azure Cloud Security Engineer & Governance Lead
1. **Governance & Access:** Start with [Azure RBAC](https://learn.secbyte.org/ctf/azure-rbac-from-roles-to-real-world-access-control), [Azure Policy](https://learn.secbyte.org/ctf/azure-policy-governance-compliance-control), and [Microsoft Defender for Cloud](https://learn.secbyte.org/ctf/microsoft-defender-for-cloud-secure-posture-threat-detection).
2. **Serverless & Containers:** Hardened workloads via [Azure Functions Security](https://learn.secbyte.org/ctf/azure-functions-security-serverless-attack-and-defense-lab), [Azure Logic Apps Security](https://learn.secbyte.org/ctf/azure-logic-apps-security-abuse-and-defense), [Azure Container Registry](https://learn.secbyte.org/ctf/azure-container-registry-secure-supply-chain-essentials), and [Azure Kubernetes Service](https://learn.secbyte.org/ctf/azure-kubernetes-service-identity-exposure-cluster-security).

### Path B: Azure SOC Analyst & Incident Responder
1. **Auditing & Telemetry:** Master investigation using [Azure Monitor Deep Dive](https://learn.secbyte.org/ctf/azure-monitor-deep-dive-visibility-investigation-detection-e) and [Azure Security Assessment](https://learn.secbyte.org/ctf/azure-security-assessment-from-tenant-recon-to-incident-resp).
2. **Threat Detection & Containment:** Execute response playbooks via [Azure Sentinel](https://learn.secbyte.org/ctf/azure-sentinel-cloud-threat-detection-and-incident-response), [Azure Defender](https://learn.secbyte.org/ctf/azure-defender-cloud-threat-detection-response), and [Azure Incident Response](https://learn.secbyte.org/ctf/azure-incident-response-cloud-log-triage-to-containment).

---

## How to Use the Labs

1. Select a practice scenario from the **Lab Collection Index**.
2. Click the corresponding link to open the exercise directly on Learn SecByte.
3. Review scenario topology, instruction details, and target goals.
4. Complete security checks, investigate cloud telemetry, or remediate tenant misconfigurations to capture flags.

---

## Target Audience

* **Cloud Security Engineers:** Implement robust governance policies, secure serverless deployments, and harden container supply chains in Azure.
* **SOC Analysts & Incident Responders:** Analyze Azure audit logs, construct KQL queries, and contain active cloud threats.
* **Penetration Testers & Red Teams:** Discover serverless attack vectors, AKS identity exposures, and cloud privilege escalation paths.
* **Cybersecurity Students:** Acquire practical, hands-on enterprise Azure defense experience.

---

## Disclaimer

All lab links provided in this repository direct to official, interactive training environments hosted on Learn SecByte. These exercises are provided strictly for educational purposes, defensive skill building, and authorized research. Unapproved testing against external cloud tenants is strictly prohibited.
