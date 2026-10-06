# Hi, I'm Diame 👋

My GitHub is used to document cloud security projects, networking labs, vulnerability analysis, technical write-ups and hands-on cybersecurity learning.

[LinkedIn](https://www.linkedin.com/in/diame-e/)

---

## Featured Projects

### [Cloud Infrastructure & Security Monitoring](https://github.com/oe1600/cloud-infrastructure-security-monitoring)

An AWS lab built to test the full path from a restricted API request to a security alert. Terraform provisioned the environment, and Python checks verified the deployed settings.

- **Infrastructure:** Private EC2 instance inside a VPC, with no public IPv4 address and no inbound or outbound security-group rules.
- **Storage and access:** S3 public access blocked, encryption and versioning enabled, and a reader role limited to the lab bucket.
- **Detection and alerting:** CloudTrail recorded a denied API request. CloudWatch detected the event and triggered an SNS email notification.
- **Validation:** All seven Python checks passed, covering storage protection, network rules and logging integration.
- **Lifecycle:** Terraform created 25 resources and removed all 25 after testing.

The denied request was a dry run, so it could not delete the VPC. The repository includes an architecture diagram and console evidence of the configuration, alarm history, email alert and validation results.

**Tools:** AWS EC2, S3, VPC, IAM, CloudTrail, CloudWatch, SNS, Terraform and Python.

[View project and screenshots →](https://github.com/oe1600/cloud-infrastructure-security-monitoring)

### [Multi-Cloud Security Misconfiguration Analysis](https://github.com/oe1600/multi-cloud-security-misconfiguration-analysis)

A practical investigation into how five cloud platforms identify and handle the same types of security mistakes: public storage, excessive permissions and unrestricted SSH access.

- **Coverage:** Separate test environments across AWS, Microsoft Azure, Google Cloud, Oracle Cloud Infrastructure and IBM Cloud.
- **Testing:** Three risk categories assessed on each platform, with configuration evidence recorded before and after remediation.
- **Detection:** Reviewed native findings and dashboards, including AWS IAM Access Analyzer, Microsoft Defender for Cloud, Google Security Command Center and IBM Workload Protection.
- **Remediation:** Removed public storage access, reduced excessive permissions and restricted exposed network rules.
- **Comparison:** Assessed detection visibility, reporting clarity and remediation guidance within the available free-tier and trial services.

Google Cloud gave the clearest overall visibility in the tested environments, while AWS showed strong storage exposure detection. Other scenarios required more manual review or depended on scan timing and enabled services. Results describe these tests, rather than a ranking of each provider's full security capabilities.

The repository includes a findings table, a Mermaid workflow and selected AWS console screenshots showing exposure detection and remediation.

**Focus:** Multi-cloud security, IAM, storage permissions, network exposure, native security tooling and remediation validation.

[View project and findings →](https://github.com/oe1600/multi-cloud-security-misconfiguration-analysis)

---

## 🛠️ Skills

### Cloud Platforms
AWS, Microsoft Azure, Google Cloud Platform, Oracle Cloud Infrastructure, IBM Cloud

### Cloud Security
IAM, RBAC, least privilege, cloud security posture management, CSPM concepts, public storage security, cloud misconfiguration testing, cloud hardening, remediation planning, security monitoring, secure cloud architecture, multi-cloud security comparison, shared responsibility model, security baseline reviews

### DevOps & Cloud Engineering
Terraform, infrastructure-as-code, Docker, Kubernetes fundamentals, Git, GitHub, GitHub Actions, CI/CD awareness, cloud resource deployment, environment configuration, configuration management, automation concepts, monitoring and alerting, deployment pipelines, cloud cost awareness, DevSecOps fundamentals

### AWS
EC2, S3, IAM, VPC, Security Groups, CloudWatch, CloudTrail awareness, IAM Access Analyzer, AWS Config awareness, AWS Security Hub awareness, GuardDuty awareness, public bucket exposure testing, least-privilege remediation

### Microsoft Azure
Azure Blob Storage, Azure RBAC, Microsoft Entra ID, Network Security Groups, Microsoft Defender for Cloud, Azure Monitor awareness, Azure Policy awareness, posture recommendations, identity and access review

### Google Cloud Platform
Cloud Storage, IAM, Firewall Rules, Security Command Center, cloud resource configuration, security findings, network exposure review, misconfiguration detection

### Oracle Cloud Infrastructure
Object Storage, IAM policies, compartments, groups, VCNs, Security Lists, Cloud Guard awareness, manual security review

### IBM Cloud
Cloud Object Storage, IAM access groups, access policies, security groups, Workload Protection, manual detection review

### IT Support & Endpoint Administration
Windows support, Microsoft 365, Active Directory, Microsoft Entra ID, Intune awareness, user account management, password resets, permissions, group policy awareness, endpoint troubleshooting, software installation, patching support, printer support, hardware troubleshooting, remote support, ticketing workflows, asset documentation

### Network Engineering
TCP/IP, DNS, DHCP, NAT, VLANs, OSPF, routing, switching, subnetting, firewalls, security groups, Network Security Groups, VPCs, VCNs, VPN awareness, network segmentation, packet analysis, open port exposure, Wireshark, Cisco IOS, Packet Tracer, Palo Alto firewall fundamentals

### Cybersecurity
Vulnerability assessment, risk analysis, access control review, misconfiguration detection, remediation validation, security monitoring, evidence collection, security reporting, incident response awareness, GDPR awareness, malware analysis fundamentals, penetration testing fundamentals, threat modelling awareness, security documentation

### Security Operations & Monitoring
Microsoft Defender for Cloud, Google Security Command Center, AWS IAM Access Analyzer, AWS Security Hub awareness, GuardDuty awareness, IBM Workload Protection, SIEM awareness, Microsoft Sentinel awareness, Splunk awareness, log analysis fundamentals, alert investigation, security dashboard review

### Scripting, Automation & Technical Tools
Python, PowerShell, Bash fundamentals, Linux, Windows Server, Docker, Terraform fundamentals, Git, GitHub, Markdown, command-line tools, VMware, VirtualBox

### Professional & Technical Communication
Technical documentation, project write-ups, screenshot-based evidence collection, cloud security reporting, risk explanation, troubleshooting, stakeholder communication, presentation skills, problem-solving, independent learning

---

## 📚 Certifications & Training

### Completed
- Google IT Support Certificate
- Google Foundations of Cybersecurity
- Mastercard Cybersecurity Job Simulation
- AWS Fundamentals of Machine Learning & AI
- Kali Linux Essential Training
- Python 3 — Codecademy

### In Progress
- CompTIA Security+
- AWS Certified Cloud Practitioner
- Cisco CCNA
- Cisco CyberOps Associate

---

## 🎯 Career Interests

I am currently interested in entry-level and graduate roles in:

- Cloud Security
- Cybersecurity
- IT Support
- Infrastructure Support
- Network Security
- Cloud Engineering
- DevOps / Cloud Infrastructure

---

## 📌 Current Focus

I am currently improving my practical skills in:

- Multi-cloud security
- IAM and least-privilege access control
- Cloud vulnerability detection
- Network security
- Security documentation
- Technical troubleshooting
- Infrastructure automation fundamentals
- Cloud monitoring and remediation
