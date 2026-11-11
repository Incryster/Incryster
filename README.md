<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,2,24&height=220&section=header&text=ABHILASH%20T.A&fontSize=62&fontColor=E8F4FF&fontAlignY=38&desc=CLOUD%20ENGINEER%20%E2%97%86%20AWS%20%E2%97%86%20DEVOPS&descSize=18&descAlignY=60&animation=fadeIn" width="100%" alt="Abhilash T.A header" />

<a href="https://github.com/Incryster"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=2600&pause=1200&color=00F5FF&center=true&vCenter=true&width=640&height=40&lines=Architecting+secure+AWS+infrastructure;Automating+everything+with+Python+%26+Bash;Shipping+with+Docker+%2B+Terraform+%2B+CI%2FCD;Open+to+Cloud+%2F+Junior+DevOps+roles" alt="Typing intro" /></a>

<br/>

![Status](https://img.shields.io/badge/STATUS-OPEN__TO__WORK-39FF14?style=for-the-badge&labelColor=060a14)
![BCA](https://img.shields.io/badge/BCA-CLASS%20OF%202026-00F5FF?style=for-the-badge&labelColor=060a14)
![AWS](https://img.shields.io/badge/AWS-FOCUSED%20BUILDER-7B2FF7?style=for-the-badge&labelColor=060a14)
![Location](https://img.shields.io/badge/MANGALORE%20%C2%B7%20BANGALORE%20%C2%B7%20REMOTE-FF00E5?style=for-the-badge&labelColor=060a14)

<br/>

[![Email](https://img.shields.io/badge/%F0%9F%93%A7_EMAIL_ME-00F5FF?style=for-the-badge&labelColor=060a14)](mailto:Abhilashantony17@gmail.com?subject=Let%27s%20build%20in%20the%20cloud)
[![LinkedIn](https://img.shields.io/badge/in_%C2%B7_LINKEDIN-7B2FF7?style=for-the-badge&labelColor=060a14)](https://www.linkedin.com/in/abhilash-t-anthony-74a529260)
[![Hire](https://img.shields.io/badge/HIRE_ME_%E2%9A%A1-FF00E5?style=for-the-badge&labelColor=060a14)](mailto:Abhilashantony17@gmail.com?subject=Opportunity%20for%20Abhilash%20%E2%80%94%20Cloud%20%2F%20DevOps)

<br/>

| `5+` | `15+` | `7` | `∞` |
|:---:|:---:|:---:|:---:|
| **CLOUD BUILDS** | **TOOLS DEPLOYED** | **AWS DOMAINS** | **AUTOMATE-EVERYTHING** |

</div>

---

## `01 // SYSTEM SHELL` &nbsp;→&nbsp; INTERACTIVE TERMINAL

```bash
abhilash@cloud:~$ whoami
Cloud Engineer | BCA Graduate (2026) | AWS-focused builder

abhilash@cloud:~$ cat skills.conf
cloud      = ["AWS","VPC","IAM","S3","EC2","Lambda","CloudFront"]
devops     = ["Docker","Terraform","GitHub Actions","CloudFormation"]
scripting  = ["Python","Bash","Linux"]
mindset    = "least-privilege, automate-everything, build-in-public"

abhilash@cloud:~$ cat mission.txt
Build, secure and automate cloud infrastructure.
Learn fast. Ship real AWS projects.

abhilash@cloud:~$ status --now
[OK] Seeking Cloud Engineer / Junior DevOps opportunities

abhilash@cloud:~$ sudo hire-me
[sudo] password for recruiter: ********
ACCESS GRANTED ✔ — recruiter fast-track unlocked
Priority channel established. Response time < 24h:
→ Abhilashantony17@gmail.com
```

---

## `02 // TECH ARSENAL` &nbsp;→&nbsp; WEAPONS OF CHOICE

<div align="center">

<img src="https://skillicons.dev/icons?i=aws,docker,terraform,githubactions,python,bash,linux,nginx,git,github,react,nodejs,mongodb,firebase,apache&perline=8" alt="Tech stack icons" />

</div>

| Tool | Category | Tool | Category | Tool | Category |
|:--|:--|:--|:--|:--|:--|
| **AWS** | CLOUD | **Docker** | DEVOPS | **Terraform** | IaC |
| **GitHub Actions** | CI/CD | **Python** | LANG | **Bash** | SCRIPT |
| **Linux** | OS | **Nginx** | SERVER | **Apache** | SERVER |
| **Git** | VCS | **GitHub** | VCS | **React** | WEB |
| **Node.js** | RUNTIME | **MongoDB** | DB | **Firebase** | BAAS |

### `02.1 // CAPABILITY MATRIX` &nbsp;→&nbsp; AWS DOMAIN COVERAGE

| Domain | Services | Count |
|:--|:--|:--:|
| ⚡ **COMPUTE** | `EC2` `Auto Scaling` `ELB` `Elastic Beanstalk` `Lambda` | 5 |
| 📡 **NETWORKING** | `VPC` `NAT/IGW` `NACLs` `Security Groups` `Peering` `Transit Gateway` `Route 53` `CloudFront` | 8 |
| 💾 **STORAGE** | `S3` `EBS` `EFS` `AWS Backup` | 4 |
| 🛡 **SECURITY** | `IAM` `STS` `KMS` `ACM` `GuardDuty` `Inspector` `Organizations` | 7 |
| 📈 **MONITORING** | `CloudWatch` `CloudTrail` `Systems Manager` | 3 |
| 🔗 **INTEGRATION** | `EventBridge` `SNS` `SQS` `SES` | 4 |
| 🗄 **DATABASES** | `RDS` `DynamoDB` `MongoDB` | 3 |

---

## `03 // FEATURED BLUEPRINT` &nbsp;→&nbsp; CUSTOM VPC ARCHITECTURE

> Public / private tiers across 2 AZs with a bastion jump host and NAT egress. `10.0.0.0/16` · 4 subnets · defense in depth with NACLs + Security Groups.

```mermaid
flowchart TB
    NET(["🌐 INTERNET"])
    IGW["⇅ IGW<br/>internet gateway"]
    subgraph VPC["☁ CUSTOM VPC · 10.0.0.0/16"]
        direction LR
        subgraph PUB["PUBLIC SUBNETS · WEB TIER ×2 AZ"]
            BAS["🛡 BASTION<br/>SSH jump host · AZ-a"]
            NAT["🔀 NAT GW<br/>egress only · AZ-a"]
        end
        subgraph PRIV["PRIVATE SUBNETS · APP TIER ×2 AZ"]
            APP1["⚙ EC2 APP 1<br/>10.0.3.0/24 · AZ-a"]
            APP2["⚙ EC2 APP 2<br/>10.0.4.0/24 · AZ-b"]
        end
    end
    NET -->|inbound| IGW
    IGW -->|inbound| BAS
    BAS -->|"SSH :22"| APP1
    BAS -->|"SSH :22"| APP2
    APP1 -.->|pkg updates| NAT
    APP2 -.->|pkg updates| NAT
    NAT ==>|egress| IGW

    classDef cyan fill:#0a1326,stroke:#00F5FF,color:#E8F4FF;
    classDef violet fill:#0a1326,stroke:#7B2FF7,color:#E8F4FF;
    class NET,IGW,BAS,NAT cyan;
    class APP1,APP2 violet;
```

**Traffic layers:** 🔵 Inbound · 🟣 SSH · 🟢 Updates · 🟠 Egress

<details>
<summary><b>NODE INTEL</b> — click to expand</summary>

| Node | Intel |
|:--|:--|
| **INTERNET / EDGE** | User traffic resolves via Route 53 and enters the VPC through the Internet Gateway. Nothing reaches private tiers directly. |
| **INTERNET GATEWAY** | Horizontally scaled, redundant VPC edge component. The public route table points `0.0.0.0/0` here. |
| **BASTION HOST** | Hardened SSH jump box in the public subnet. Security Group allows `:22` only from a trusted CIDR — the single door into private instances. |
| **NAT GATEWAY** | Lets private instances reach the internet for package updates. Outbound-only: the internet cannot initiate connections back in. |
| **EC2 · APP 1** | Private subnet, AZ-a, no public IP. Reachable only via the bastion; egress flows through the NAT Gateway. |
| **EC2 · APP 2** | Private subnet, AZ-b, no public IP. Multi-AZ placement keeps the app tier resilient to a single-AZ failure. |

</details>

---

## `04 // MISSION LOG` &nbsp;→&nbsp; DEPLOYED PROJECTS

> Real AWS builds, shipped in public. Open a mission file for architecture notes and deploy logs.

### 🌐 LOG 001 — Custom VPC Architecture &nbsp; ![DEPLOYED](https://img.shields.io/badge/DEPLOYED-00F5FF?style=flat-square&labelColor=060a14)
2 public + 2 private subnets across 2 Availability Zones. Bastion host access, NAT Gateway egress, layered NACLs and VPC peering — a production-shaped network built from scratch.

`VPC` `EC2` `NAT` `NACL` `PEERING`

<details>
<summary><b>OPEN MISSION FILE →</b></summary>

- ▸ 4 subnets across ap-south-1a / 1b with clean CIDR plan
- ▸ Bastion-only SSH into private tier — no public IPs on apps
- ▸ NACLs + Security Groups for defense in depth
- ▸ VPC peering with correctly scoped route tables

```bash
$ terraform apply -auto-approve
…
Apply complete! Resources: 18 added, 0 changed, 0 destroyed.
Outputs: vpc_id = vpc-0f27a… · subnets = 4 · azs = ap-south-1a/1b
```
</details>

### 🔐 LOG 002 — Secure Static Website &nbsp; ![LIVE](https://img.shields.io/badge/LIVE-7B2FF7?style=flat-square&labelColor=060a14)
S3 hosting locked behind a least-privilege bucket policy, fronted by CloudFront with ACM HTTPS and a Route 53 custom domain. Versioning and CORS configured for safe rollbacks.

`S3` `CLOUDFRONT` `ACM` `ROUTE 53`

<details>
<summary><b>OPEN MISSION FILE →</b></summary>

- ▸ Bucket fully private — CloudFront Origin Access Control only
- ▸ Versioning enabled for instant rollback
- ▸ HTTPS everywhere via ACM certificate + redirect policy
- ▸ Custom domain aliased through Route 53

```bash
$ aws s3 sync ./dist s3://at-static-site --delete
upload: 42 files · 1.8 MB
$ aws cloudfront create-invalidation --paths "/*"
Invalidation I3K9… Completed · HTTPS ✓ · OAC ✓
```
</details>

### 🛡 LOG 003 — IAM Security Lab &nbsp; ![HARDENED](https://img.shields.io/badge/HARDENED-FF00E5?style=flat-square&labelColor=060a14)
A least-privilege playground: scoped policies, root account hardening with MFA, and cross-account access using STS temporary credentials instead of long-lived keys.

`IAM` `MFA` `STS`

<details>
<summary><b>OPEN MISSION FILE →</b></summary>

- ▸ Root account locked down with hardware-grade MFA hygiene
- ▸ Policies written and verified with the IAM policy simulator
- ▸ Cross-account role assumption via STS — credentials expire in 1h
- ▸ Zero wildcard admin policies in the final state

```bash
$ aws sts assume-role --role-arn arn:aws:iam::2211…:role/CrossAccountAudit
Credentials: ASIA… · Expiration: +1h
Access Analyzer: 0 unused permissions · MFA: enforced ✓
```
</details>

### ⚡ LOG 004 — Serverless EC2 Scheduler &nbsp; ![AUTOMATED](https://img.shields.io/badge/AUTOMATED-39FF14?style=flat-square&labelColor=060a14)
Lambda + EventBridge automatically start and stop EC2 instances on a schedule — cutting off-hours compute cost with a scoped execution role and full CloudWatch observability.

`LAMBDA` `EVENTBRIDGE` `CLOUDWATCH`

<details>
<summary><b>OPEN MISSION FILE →</b></summary>

- ▸ Cron rules for office-hours start / evening stop
- ▸ Execution role scoped to specific instance ARNs only
- ▸ Every run logged and metric-tracked in CloudWatch
- ▸ Zero servers to babysit — fully event-driven

```bash
[EventBridge] cron(0 19 * * ? *) → lambda:ec2-scheduler
[λ] stopped 4 instances · duration 412ms · role: scoped ✓
[CloudWatch] OffHoursSaved ↑ · alarm state: OK
```
</details>

### 📦 LOG 005 — Elastic Beanstalk Deployment &nbsp; ![GREEN](https://img.shields.io/badge/GREEN-FFB020?style=flat-square&labelColor=060a14)
Sample application running on managed Beanstalk environments with auto scaling, load balancing, health monitoring and rolling deployments — platform power without the boilerplate.

`BEANSTALK` `ELB` `AUTO SCALING`

<details>
<summary><b>OPEN MISSION FILE →</b></summary>

- ▸ Managed environment with ALB + Auto Scaling group
- ▸ Rolling deploys with automatic health gating
- ▸ Environment health dashboards and event stream
- ▸ Config-as-code via saved configuration templates

```bash
$ eb deploy production-env
INFO: Environment health has transitioned to Green.
INFO: Rolling update complete · 2/2 instances InService ✓
```
</details>

---

## `05 // ACTIVE OPERATIONS` &nbsp;→&nbsp; CURRENT FOCUS

> What's on the workbench right now — tracked like missions, shipped like products.

| | Operation | Progress |
|:--:|:--|:--|
| 🏗 | **Terraform IaC**<br/>Modular VPC + EC2 stacks, remote state, workspaces and clean variable design. | ![72%](https://img.shields.io/badge/72%25-00F5FF?style=for-the-badge&labelColor=060a14) |
| 🐳 | **Dockerised Apps**<br/>Multi-stage builds, compose workflows, slim images and registry pushes. | ![65%](https://img.shields.io/badge/65%25-4DA6FF?style=for-the-badge&labelColor=060a14) |
| 🔁 | **GitHub Actions CI/CD**<br/>Lint → build → push → deploy pipelines with OIDC federation into AWS. | ![58%](https://img.shields.io/badge/58%25-FF00E5?style=for-the-badge&labelColor=060a14) |
| ☁ | **Real-World AWS Builds**<br/>One production-grade architecture shipped every fortnight. Build in public. | ![84%](https://img.shields.io/badge/84%25-39FF14?style=for-the-badge&labelColor=060a14) |

---

## `06 // UPLINK` &nbsp;→&nbsp; OPEN CHANNEL

<div align="center">

### ● TRANSMISSION READY — RESPONSE &lt; 24H
## Let's build something in the cloud ☁️

Seeking **Cloud Engineer / Junior DevOps** roles. If you're building on AWS — or want to — my inbox is the fastest route to me.

[![Email](https://img.shields.io/badge/%F0%9F%93%A7_Abhilashantony17%40gmail.com-00F5FF?style=for-the-badge&labelColor=060a14)](mailto:Abhilashantony17@gmail.com?subject=Cloud%20%2F%20DevOps%20opportunity)
[![LinkedIn](https://img.shields.io/badge/in_%C2%B7_CONNECT_ON_LINKEDIN-FF00E5?style=for-the-badge&labelColor=060a14)](https://www.linkedin.com/in/abhilash-t-anthony-74a529260)

![Mangalore](https://img.shields.io/badge/%F0%9F%93%8D_MANGALORE-00F5FF?style=flat-square&labelColor=060a14)
![Bangalore](https://img.shields.io/badge/%F0%9F%93%8D_BANGALORE-7B2FF7?style=flat-square&labelColor=060a14)
![Remote](https://img.shields.io/badge/%F0%9F%8C%8D_REMOTE-FF00E5?style=flat-square&labelColor=060a14)
![Open](https://img.shields.io/badge/OPEN__TO__WORK-39FF14?style=flat-square&labelColor=060a14)

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,2,24&height=120&section=footer" width="100%" alt="footer wave" />

`BUILD v2.0.26 · REGION ap-south-1 · ALL SYSTEMS OPERATIONAL`

**© 2026 ABHILASH T.A — BUILT IN PUBLIC · DEPLOYED WITH ⚡ · LEAST-PRIVILEGE EVERYTHING**

</div>
