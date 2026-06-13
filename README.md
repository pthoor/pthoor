# Pierre Thoor 🕵️

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&width=600&lines=Senior+Cloud+Security+Architect;Microsoft+Security+MVP+%7C+MDO+Champion;Detection+%7C+Sentinel+%7C+Azure+%7C+GitHub+Security)](https://git.io/typing-svg)

[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fpthoor%2Fpthoor&labelColor=%232ccce4&countColor=%23555555)](https://visitorbadge.io)

**Senior Cloud Security Architect · [Onevinn AB](https://www.onevinn.com) · Sweden**

I architect and operate security at enterprise scale — currently across a 700+ subscription, multi-region Azure hub-and-spoke environment. My work covers the full stack: Microsoft Defender XDR, Sentinel logging strategy, threat hunting and detection engineering, Azure security architecture, and GitHub supply chain defense.

Microsoft Security MVP and MDO Champion. Author of *[Microsoft Defender for Identity in Depth](https://www.packtpub.com/en-us/product/microsoft-defender-for-identity-in-depth-9781835089125)* (Packt, 2024). I build open-source security tooling, write at [thoor.tech](https://thoor.tech), and co-run the *From Commit to Compromise* purple team webinar series.

-----

## 🔍 Focus Areas

**🛡️ Microsoft Defender XDR & Email Security**  
Designing and operating Defender XDR at enterprise scale across MDO, MDE, and Defender for Cloud. MDO Champion with deep focus on email threat defense — phishing, BEC, and domain spoofing — backed by the open-source DMARC Analyzer Azure project and hands-on DMARC/DKIM/SPF implementation at scale.

**📊 Microsoft Sentinel & Logging Strategy**  
Architecting Sentinel deployments with the data strategy first: analytics tier vs. Sentinel Data Lake, DCR/DCT transformation filters, retention and regulatory alignment, and cost optimization at scale. Experienced in designing Azure-wide logging strategy across 700+ subscription environments — from log source fit guidance to compliance retention mapping.

**🎯 Threat Hunting & Detection Engineering**  
Writing KQL detection and hunting queries grounded in real attack behavior. Focused on converting threat intelligence, purple team findings, and named campaign indicators into durable, low-noise detections across endpoint, identity, network, and supply chain.

**🟣 Purple Team / Adversary Simulation**  
Running structured purple team exercises that connect attack chains to detections. Co-host of the *From Commit to Compromise* webinar series — covering end-to-end attack scenarios from Azure and GitHub misconfigurations to post-exploitation, with full runbooks, deployment scripts, and Sentinel detection coverage for each scenario.

**🏗️ Azure Security Architecture**  
Designing security into Azure landing zones at enterprise scale: hub-and-spoke topology, AVNM, Azure Firewall policy, Private Endpoints, NSG governance with Security Admin Rules, ExpressRoute boundary control, and Azure Policy enforcement. Embedded across a 700+ subscription multi-region production environment.

**🔗 GitHub & Supply Chain Security**  
Auditing and hardening GitHub Enterprise environments: GHAS posture, Actions supply chain risk, app and OAuth permission governance, and signed commits enforcement. Author of Fylgyr — a PowerShell module purpose-built for GitHub supply chain security auditing, covering named campaigns including Miasma.

-----

## 🔨 Open Source

| Project | What it does |
|---|---|
| [**Fylgyr**](https://github.com/pthoor/Fylgyr) | PowerShell module for GitHub supply chain security auditing. Detects compromised Actions, suspicious app and OAuth configurations, and GHAS posture drift. Published on PSGallery. |
| [**MAST**](https://github.com/pthoor/MAST) | M365 Assessor for Security & Teams. Opinionated posture assessment across Microsoft Defender for Office 365, Exchange Online Protection, and Teams security configurations. |
| [**DMARC Analyzer Azure**](https://github.com/pthoor/DMARC-Analyzer-Azure) | Managed DMARC monitoring solution built on Azure. Ingests aggregate and forensic reports into Log Analytics and surfaces insights via Azure Workbook. |

-----

## 📖 Book

**[Microsoft Defender for Identity in Depth](https://www.packtpub.com/en-us/product/microsoft-defender-for-identity-in-depth-9781835089125)**  
Packt Publishing · 2024

A practical guide to deploying, configuring, and operating Microsoft Defender for Identity across complex on-premises and hybrid Active Directory environments — from initial sensor deployment to advanced detection tuning.

-----

## ✍️ Writing & Research

**Blog — [thoor.tech](https://thoor.tech)**  
I write about what I encounter in production: Azure security architecture, Microsoft Sentinel cost and logging strategy, Microsoft Defender XDR, GitHub supply chain security, KQL detection patterns, and Bicep-driven security automation.

**KQL Hunting Queries — [MS_Sentinel](https://github.com/pthoor/MS_Sentinel) · [Sentinel-Queries](https://github.com/pthoor/Sentinel-Queries)**  
Detection and hunting queries for Microsoft Sentinel covering identity, network, endpoint, and supply chain threat scenarios.

-----

## 🎤 Speaking

I present on Azure security architecture, detection engineering, Microsoft Defender XDR, and GitHub supply chain security at community events and conferences.

Recent and upcoming: **Experts Live**, **NIC** → [Full session list on Sessionize](https://sessionize.com/pierre-thoor)

-----

## 📊 Stack

```kql
Pierre Thoor
| where Title == 'Senior Cloud Security Architect'
  and Status == 'Microsoft Security MVP | MDO Champion'
| project
    Company = 'Onevinn AB',
    Country = 'Sweden',
    Book = 'Microsoft Defender for Identity in Depth (Packt 2024)',
    OpenSource = dynamic(['Fylgyr', 'MAST', 'DMARC Analyzer Azure']),
    Focus = 'XDR · Sentinel · Logging strategy · Threat hunting · Azure · GitHub supply chain',
    Blog = 'https://thoor.tech',
    Speaks = dynamic(['Experts Live', 'NIC'])
```

-----

## 🗒️ Latest from thoor.tech
<!-- blog-post-list:start -->
## Thoor.tech

[Read more](https://github.com/pthoor/pthoor/blob/main)

> Last updated: Saturday, May 3, 2025 at 12:28:36 AM
>
> Showing 5 of 10 posts.

[![Deploy and destroy Copilot for Security with Bicep and GitHub Actions](https://raw.githubusercontent.com/pthoor/pthoor/main/blog-posts/Thoor.tech/Deploy_and_destroy_Copilot_for_Security_with_Bicep_and_GitHub_Actions.svg)](https://github.com/pthoor/pthoor/blob/main/Copilot-for-Security-deploy-and-destroy)
[![Configure Defender for Cloud workload protections with Azure Policy](https://raw.githubusercontent.com/pthoor/pthoor/main/blog-posts/Thoor.tech/Configure_Defender_for_Cloud_workload_protections_with_Azure_Policy.svg)](https://github.com/pthoor/pthoor/blob/main/DefenderforCloud-Workload-Protection-With-Azure-Policy)
[![Demystifying Microsoft Defender for Cloud and Defender CSPM cost](https://raw.githubusercontent.com/pthoor/pthoor/main/blog-posts/Thoor.tech/Demystifying_Microsoft_Defender_for_Cloud_and_Defender_CSPM_cost.svg)](https://github.com/pthoor/pthoor/blob/main/Demystifying-MDC-and-CSPM-cost)
[![New Patch Management tool in the cloud - Azure Update Manager (AUM) is now GA](https://raw.githubusercontent.com/pthoor/pthoor/main/blog-posts/Thoor.tech/New_Patch_Management_tool_in_the_cloud_-_Azure_Update_Manager_(AUM)_is_now_GA.svg)](https://github.com/pthoor/pthoor/blob/main/Azure-Update-Manager-Costs)
[![Windows Server 2012/2012 R2 - End of support, what to do with Security Updates?](https://raw.githubusercontent.com/pthoor/pthoor/main/blog-posts/Thoor.tech/Windows_Server_2012_2012_R2_-_End_of_support__what_to_do_with_Security_Updates_.svg)](https://github.com/pthoor/pthoor/blob/main/Windows-Server-2012-ESU)
<!-- blog-post-list:end -->

-----

## 📈 GitHub Stats

![](https://github-readme-stats.vercel.app/api?username=pthoor&show_icons=true)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=pthoor&layout=compact&text_color=daf7dc&bg_color=151515&hide=css,html,php)](https://github.com/pthoor/github-readme-stats)

-----

## 🎓 Certifications & Badges [@Credly](https://www.credly.com/users/pierre-thoor/badges?sort=-state_updated_at&page=1)
<!--START_SECTION:badges-->
[![Experts Live Denmark 2025 - Speaker](https://images.credly.com/size/110x110/images/8d25e84c-8208-4a61-b58b-432d044f2208/blob)](http://www.credly.com/badges/e193a254-8ed1-4a28-a29c-0a4ecfef7c31)
[![2024 Microsoft Most Valuable Professional (MVP)](https://images.credly.com/size/110x110/images/9e9359a4-fe7e-4e02-8eb0-6c2b79473345a/image.png)](http://www.credly.com/badges/9b10d702-679c-425b-9faf-98658c50db0c)
[![GitHub Actions](https://images.credly.com/size/110x110/images/89efc3e7-842b-4790-b09b-9ea5efc71ec3/image.png)](http://www.credly.com/badges/09aa6592-fa75-4070-a484-3fb73c84561a)
[![Microsoft Security Immersion Completion Badge](https://images.credly.com/size/110x110/images/693308cf-f47f-41c0-8e71-0f28e4bc6a52/image.png)](http://www.credly.com/badges/7235876c-a64e-4857-90e6-842c0ec02e53)
[![New rank: Special Detective Agent](https://images.credly.com/size/110x110/images/b096f449-fce1-42d7-be93-e6e1e32e171b/image.png)](http://www.credly.com/badges/871e2a10-01fc-4c8e-82d4-f7665d4b409e)
[![New rank: Principal Detective](https://images.credly.com/size/110x110/images/8db7e105-c19e-4df8-87a4-ed1d5ccbc32b/image.png)](http://www.credly.com/badges/83e55150-1041-4d57-a375-9a8f240f0263)
[![New Rank: Kusto Senior Detective II](https://images.credly.com/size/110x110/images/2fb50859-656e-4390-b4ca-88bc2b619867/image.png)](http://www.credly.com/badges/4c8dff8f-a40f-42f8-a932-e5067fee5937)
[![2023 Microsoft Most Valuable Professional (MVP)](https://images.credly.com/size/110x110/images/5c687ffb-7ab6-4fd5-bf8c-14f0178acd21/image.png)](http://www.credly.com/badges/c3313322-21ff-417b-9190-fd3722c1fb96)
[![New Rank: Senior Kusto Detective](https://images.credly.com/size/110x110/images/79b22d1d-cb2d-471e-add7-bbe2e1672f61/image.png)](http://www.credly.com/badges/1fe2a960-c4cf-4335-9ad1-8bafca524d76)
[![New Rank: Kusto Detective III](https://images.credly.com/size/110x110/images/27c40e7b-98b2-4312-b52c-4454f6c90c52/image.png)](http://www.credly.com/badges/ea1579c4-8842-4827-8565-9e80068949fa)
[![New Rank: Kusto Detective II](https://images.credly.com/size/110x110/images/8fc10fee-7b05-4b86-8504-01abf614bcac/image.png)](http://www.credly.com/badges/23be7287-38d4-4f97-886e-0ce6b971ce25)
[![Cloud Security Rockstar Team](https://images.credly.com/size/110x110/images/4ae7bb2a-33ea-43c6-a76a-0b67f2ad12ec/image.png)](http://www.credly.com/badges/3bb3054d-f375-4db8-ab55-e9622200a8a3)
[![New Rank: Kusto Detective I](https://images.credly.com/size/110x110/images/304d7409-3dd5-40b6-ab20-88d3ec012eb1/image.png)](http://www.credly.com/badges/df9d0586-e639-40bc-9284-a0e7164a9c0e)
[![New Kusto Detective!](https://images.credly.com/size/110x110/images/1e07abc3-dc08-4320-af38-43824afc659d/image.png)](http://www.credly.com/badges/3d79d28b-4c21-42ca-8578-bac788f914c7)
[![Cloud Security Product Influencer](https://images.credly.com/size/110x110/images/0c1eb2a2-25d8-411d-b195-d0c88cf3a3c5/image.png)](http://www.credly.com/badges/087196bf-179c-4035-aa90-063b14dc336b)
[![GitHub Advanced Security](https://images.credly.com/size/110x110/images/c9ed294b-f8ac-48fa-a8c3-96dab1f110f2/image.png)](http://www.credly.com/badges/28412719-c3d8-4a73-86ef-bea9eb470ffb)
[![Cloud Security Product Champion](https://images.credly.com/size/110x110/images/7941cf3f-4295-4553-a57f-f0abf155d24e/image.png)](http://www.credly.com/badges/a729e668-aeb6-4bcd-936c-66fb8d5ce12d)
[![Microsoft Certified Trainer 2023-2024](https://images.credly.com/size/110x110/images/fd6bb2af-2f05-4d9b-a23e-39f8e309a82d/image.png)](http://www.credly.com/badges/3479f01e-13d6-4008-a5af-decb5e9fec18)
[![Kusto Detective Agency - Complete](https://images.credly.com/size/110x110/images/6726e724-5ce8-477e-93f5-6b39d6933273/image.png)](http://www.credly.com/badges/8c8f51b7-e1ba-4213-9f9b-0c16cafe5ceb)
[![SC-100: Microsoft Cybersecurity Architect](https://images.credly.com/size/110x110/images/c34a6df4-c7bd-461b-ac12-deab18ab6804/image.png)](http://www.credly.com/badges/0f483b27-8670-415f-9bed-a8edbbb88b47)
[![Microsoft Certified: Cybersecurity Architect Expert](https://images.credly.com/size/110x110/images/0ba22331-acf9-4e8a-8ce3-b4cc3d376040/image.png)](http://www.credly.com/badges/25c0d45f-17cf-47ff-afe1-117a45308c1e)
[![Microsoft Certified: Azure Network Engineer Associate](https://images.credly.com/size/110x110/images/c3a2e51d-7984-48cc-a4cb-88d4e848703b/azure-network-engineer-associate-600x600.png)](http://www.credly.com/badges/e21d4882-93a7-499d-837d-d0979a63c4f0)
[![Microsoft Certified: Security, Compliance, and Identity Fundamentals](https://images.credly.com/size/110x110/images/fc1352af-87fa-4947-ba54-398a0e63322e/security-compliance-and-identity-fundamentals-600x600.png)](http://www.credly.com/badges/1df6d5bc-db65-4a41-b797-e5aef213fc99)
[![Microsoft Sentinel Black Belt](https://images.credly.com/size/110x110/images/23d9f8d7-d662-4b93-b1b2-2fbe5b9e06e7/CREDLY_Microsoft_Sentinel_Black_Belt_V1.png)](http://www.credly.com/badges/28b47cc0-a5be-41c3-95a3-1237917fc633)
[![L3 Microsoft Sentinel Influencer](https://images.credly.com/size/110x110/images/41b63430-ded3-4d19-994c-494e91821d3d/CREDLY_Microsoft_Cloud_Security_Digital_Badges_Sentinel_Influencer.png)](http://www.credly.com/badges/97ae9753-b447-47b1-9bb7-57efdda4a245)
[![AZ-305: Designing Microsoft Azure Infrastructure Solutions](https://images.credly.com/size/110x110/images/9d7dc4c0-5681-41fc-b96b-26e9157786d7/image.png)](http://www.credly.com/badges/b88638fe-e44a-475e-96eb-5814aa271fd6)
<!--END_SECTION:badges-->

-----

## 🔔 Connect

[![MVP Badge](https://img.shields.io/badge/-Microsoft%20MVP-blue?style=flat-square&logo=Microsoft&logoColor=white)](https://mvp.microsoft.com/en-us/PublicProfile/5004683) [![Twitter Badge](https://img.shields.io/twitter/follow/PierreThoor?style=social)](https://twitter.com/PierreThoor) [![Linkedin Badge](https://img.shields.io/badge/-PierreThoor-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/pierrethoor/)](https://www.linkedin.com/in/pierrethoor/) [![GitHub followers](https://img.shields.io/github/followers/pthoor?label=Follow&style=social)](https://github.com/pthoor/?tab=follow) [![Bluesky](https://img.shields.io/badge/-pierrethoor.bsky.social-blue?style=flat-square&logo=bluesky&logoColor=white)](https://bsky.app/profile/pierrethoor.bsky.social)
