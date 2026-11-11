<!-- ============ HEADER ============ -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:0d1117,40:00f5ff,100:7b2ff7&height=240&section=header&text=ABHILASH%20T.A&fontSize=62&fontColor=ffffff&animation=fadeIn&fontAlignY=40&desc=%E2%9A%A1%20CLOUD%20ENGINEER%20%7C%20AWS%20%7C%20DEVOPS%20%E2%9A%A1&descAlignY=62&descSize=18" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=800&color=00F5FF&center=true&vCenter=true&width=700&height=50&lines=%3E+Architecting+secure+AWS+infrastructure;%3E+Automating+everything+with+Python+%26+Bash;%3E+Shipping+with+Docker+%2B+Terraform+%2B+CI%2FCD;%3E+Open+to+Cloud+%2F+Junior+DevOps+roles" alt="typing"/>

<br/>

<a href="https://www.linkedin.com/in/abhilash-t-anthony-74a529260"><img src="https://img.shields.io/badge/LINKEDIN-00F5FF?style=for-the-badge&logo=linkedin&logoColor=0d1117&labelColor=0d1117"/></a>
<a href="mailto:Abhilashantony17@gmail.com"><img src="https://img.shields.io/badge/EMAIL-7B2FF7?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d1117"/></a>
<img src="https://img.shields.io/badge/STATUS-OPEN_TO_WORK-39FF14?style=for-the-badge&labelColor=0d1117"/>
<img src="https://img.shields.io/badge/LOCATION-MANGALORE_%7C_BANGALORE_%7C_REMOTE-FF00E5?style=for-the-badge&labelColor=0d1117"/>

</div>

<br/>

<!-- ============ TERMINAL ============ -->
```bash
abhilash@cloud:~$ whoami
> Cloud Engineer | BCA Graduate (2026) | AWS-focused builder

abhilash@cloud:~$ cat skills.conf
> cloud      = ["AWS", "VPC", "IAM", "S3", "EC2", "Lambda", "CloudFront"]
> devops     = ["Docker", "Terraform", "GitHub Actions", "CloudFormation"]
> scripting  = ["Python", "Bash", "Linux"]
> mindset    = "least-privilege, automate-everything, build-in-public"

abhilash@cloud:~$ cat mission.txt
> Build, secure and automate cloud infrastructure.
> Learn fast. Ship real AWS projects.

abhilash@cloud:~$ status --now
> [OK] Seeking Cloud Engineer / Junior DevOps opportunities
```

<br/>

<!-- ============ TECH STACK ============ -->
<h2 align="center">⚙️ TECH ARSENAL</h2>

<div align="center">

<img src="https://skillicons.dev/icons?i=aws,docker,terraform,githubactions,python,bash,linux,nginx,git,github&theme=dark&perline=10" />
<br/><br/>
<img src="https://skillicons.dev/icons?i=react,nodejs,mongodb,firebase,apache&theme=dark&perline=10" />

</div>

<br/>

<div align="center">

| 🌩️ DOMAIN | ⚡ TECHNOLOGIES |
|:---|:---|
| **Compute** | EC2 · Auto Scaling · ELB · Elastic Beanstalk · Lambda |
| **Networking** | VPC · NAT/IGW · NACLs · Security Groups · Peering · Transit Gateway · Route 53 · CloudFront |
| **Storage** | S3 · EBS · EFS · AWS Backup |
| **Security** | IAM · STS · KMS · ACM · GuardDuty · Inspector · Organizations |
| **Monitoring** | CloudWatch · CloudTrail · Systems Manager |
| **Integration** | EventBridge · SNS · SQS · SES |
| **Databases** | RDS · DynamoDB · MongoDB |

</div>

<br/>

<!-- ============ ARCHITECTURE ============ -->
<h2 align="center">🛰️ FEATURED ARCHITECTURE</h2>
<p align="center"><i>Custom VPC: public/private tiers with bastion + NAT</i></p>

```mermaid
flowchart TB
    Internet((🌐 Internet)) --> IGW[Internet Gateway]
    IGW --> PUB
    subgraph VPC["☁️ Custom VPC"]
        subgraph PUB["Public Subnets (Web Tier) x2 AZ"]
            BASTION[🛡️ Bastion Host]
            NAT[NAT Gateway]
        end
        subgraph PRIV["Private Subnets (App Tier) x2 AZ"]
            APP1[EC2 App 1]
            APP2[EC2 App 2]
        end
        BASTION -- SSH --> APP1
        BASTION -- SSH --> APP2
        APP1 -. updates .-> NAT
        APP2 -. updates .-> NAT
    end
    NAT --> IGW
```

<br/>

<!-- ============ PROJECTS ============ -->
<h2 align="center">🚀 MISSION LOG: PROJECTS</h2>

<table align="center">
<tr>
<td width="50%" valign="top">

### 🌐 Custom VPC Architecture
2 public + 2 private subnets across 2 AZs. Bastion host access, NAT Gateway, NACLs and VPC peering.

![](https://img.shields.io/badge/VPC-00F5FF?style=flat-square&labelColor=0d1117)
![](https://img.shields.io/badge/EC2-00F5FF?style=flat-square&labelColor=0d1117)
![](https://img.shields.io/badge/NAT-00F5FF?style=flat-square&labelColor=0d1117)
![](https://img.shields.io/badge/NACL-00F5FF?style=flat-square&labelColor=0d1117)

</td>
<td width="50%" valign="top">

### 🔐 Secure Static Website
S3 hosting with least-privilege bucket policy, versioning, CORS, CloudFront, ACM HTTPS and Route 53 custom domain.

![](https://img.shields.io/badge/S3-7B2FF7?style=flat-square&labelColor=0d1117)
![](https://img.shields.io/badge/CloudFront-7B2FF7?style=flat-square&labelColor=0d1117)
![](https://img.shields.io/badge/ACM-7B2FF7?style=flat-square&labelColor=0d1117)
![](https://img.shields.io/badge/Route53-7B2FF7?style=flat-square&labelColor=0d1117)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛡️ IAM Security Lab
Least-privilege policies, root hardening with MFA, cross-account access using STS temporary credentials.

![](https://img.shields.io/badge/IAM-FF00E5?style=flat-square&labelColor=0d1117)
![](https://img.shields.io/badge/MFA-FF00E5?style=flat-square&labelColor=0d1117)
![](https://img.shields.io/badge/STS-FF00E5?style=flat-square&labelColor=0d1117)

</td>
<td width="50%" valign="top">

### ⚡ Serverless EC2 Scheduler
Lambda + EventBridge to automatically start/stop EC2 on a schedule. Scoped execution role, CloudWatch Logs monitoring.

![](https://img.shields.io/badge/Lambda-39FF14?style=flat-square&labelColor=0d1117)
![](https://img.shields.io/badge/EventBridge-39FF14?style=flat-square&labelColor=0d1117)
![](https://img.shields.io/badge/CloudWatch-39FF14?style=flat-square&labelColor=0d1117)

</td>
</tr>
</table>

<div align="center">

### 📦 Elastic Beanstalk Deployment
Sample app on managed environments with scaling and load balancing.

</div>

<br/>

<!-- ============ CURRENTLY ============ -->
<h2 align="center">🔭 CURRENT FOCUS</h2>

<div align="center">

`🏗️ Terraform IaC` &nbsp; `🐳 Dockerised apps` &nbsp; `🔁 GitHub Actions CI/CD` &nbsp; `☁️ More real-world AWS builds`

</div>

<br/>

<!-- ============ FOOTER ============ -->
<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=16&duration=4000&pause=1000&color=7B2FF7&center=true&vCenter=true&width=500&lines=Let's+build+something+in+the+cloud+%E2%98%81%EF%B8%8F" alt="footer typing"/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7b2ff7,60:00f5ff,100:0d1117&height=120&section=footer" width="100%"/>

</div>
