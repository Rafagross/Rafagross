# Elvis Rafael Gross Cardero

**Cloud Operations Engineer** · AWS · GCP · Kubernetes · Terraform · Las Vegas, NV

I keep cloud infrastructure running: the monitoring that catches a problem before a user does, the least-privilege access path that removes the bastion host, the runbook that lets someone else fix it at 3 a.m. Seven years across AWS and GCP, most recently at enterprise scale in regulated gaming.

**Currently looking for** Cloud Operations, SRE, DevOps, or Platform Engineering roles — remote or hybrid. If you're hiring, the fastest way to judge my work is the repositories below. They're the real thing, not tutorials.

---

## Background

At **International Game Technology** I operated AWS infrastructure for gaming platforms serving millions of end users — EC2 and EKS fleets, CloudWatch observability, IAM boundaries, patching and backup under audit requirements. Regulated gaming means change control is real: nothing ships without a rollback path and a record of who approved it.

Before that, three years as a **Pre-Sales Cloud Engineer at CODESA**, a Google Cloud partner, architecting solutions for enterprise clients across Latin America — which is where I learned to explain an architecture to the people paying for it, not just the people building it.

I hold a **Nevada gaming license** and I'm certified in AWS, Google Cloud, and security fundamentals. CKA is in progress.

---

## Selected work

### [fraud-detection-aws-platform](https://github.com/Rafagross/fraud-detection-aws-platform)

Private EC2 operations without a bastion host: SSM Session Manager for access, VPC endpoints so traffic never leaves the AWS network, CloudWatch for observability, AWS Backup for recovery. Built around one question — how do you reach an instance that has no public IP and no inbound rule? Terraform.

### [eks-prometheus-grafana-runbook](https://github.com/Rafagross/eks-prometheus-grafana-runbook)

Production EKS with a Prometheus and Grafana observability stack: deployment steps, what to alert on, and what the dashboards are actually for.

### [container-runtime-runbooks-homelabs](https://github.com/Rafagross/container-runtime-runbooks-homelabs)

Container runtime configuration on Linux, written the way I'd want to find it during an incident — exact commands, expected output, and what it means when the output differs.

---

## Stack

| Area | Tools |
|------|-------|
| AWS | EC2, EKS, S3, RDS, IAM, VPC, CloudWatch, Systems Manager, Backup, Lambda |
| GCP | Compute Engine, GKE, Cloud Run, BigQuery, Cloud Monitoring |
| Kubernetes | cluster operations, workload troubleshooting, RBAC |
| Infrastructure as code | Terraform, Ansible |
| Observability | Prometheus, Grafana, CloudWatch |
| Scripting | Bash, Python |

---

## Certifications

AWS Certified SysOps Administrator · Google Cloud Professional Cloud Architect · Google Cloud Associate Cloud Engineer · CompTIA Cloud+ · ISC2 Certified in Cybersecurity · CKA (in progress)

Verify at [credly.com/users/rafa-gross](https://www.credly.com/users/rafa-gross)

---

## Homelab

A three-node Kubernetes cluster on Proxmox with Prometheus and Grafana, where I break things on purpose. Most of what ends up in the runbooks above was learned here first.

---

## Contact

[rafael-gross.com](https://rafael-gross.com) · [LinkedIn](https://www.linkedin.com/in/erafael-gross) · rafagross15@gmail.com
