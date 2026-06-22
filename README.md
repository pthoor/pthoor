<h1 align="center">Pierre Thoor 🕵️</h1>
<p align="center"><strong>Senior Cloud Security Architect · Microsoft Security MVP · MDO Champion</strong></p>

<p align="center">
  <a href="https://thoor.tech">Blog</a> ·
  <a href="https://thoor.tech/detections/">Detections</a> ·
  <a href="https://sessionize.com/pierre-thoor">Talks</a> ·
  <a href="https://github.com/pthoor/Fylgyr">Fylgyr</a> ·
  <a href="https://www.linkedin.com/in/pierrethoor/">LinkedIn</a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1200&width=720&lines=Defender+XDR+%7C+Sentinel+%7C+Azure+Security+Architecture;Detection+Engineering+%7C+Threat+Hunting+%7C+GitHub+Supply+Chain+Security;Attack+to+understand.+Understand+to+detect.+Detect+to+automate." alt="Typing intro" />
</p>

<p align="center">
  <a href="https://visitorbadge.io"><img src="https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fpthoor%2Fpthoor&labelColor=%232ccce4&countColor=%23555555" alt="Visitors" /></a>
</p>

---

## ⚡ About Me

I design and run cloud security at enterprise scale — across large, multi-region Azure hub-and-spoke environments. My focus is practical security outcomes: stronger detections, lower noise, resilient architecture, and measurable risk reduction.

- **Role:** Senior Cloud Security Architect at [Onevinn AB](https://www.onevinn.com), Sweden
- **Recognition:** Microsoft Security MVP · MDO Champion
- **Author:** *[Microsoft Defender for Identity in Depth](https://www.packtpub.com/en-us/product/microsoft-defender-for-identity-in-depth-9781835082850)* (Packt, 2024)
- **Community:** Co-authored a four-part guide to securing Microsoft Teams with the Microsoft Defender for Office 365 product team — published on [Microsoft Tech Community](https://techcommunity.microsoft.com/blog/microsoftdefenderforoffice365blog/safeguarding-microsoft-teams-with-microsoft-defender-for-office-365/4464086) with a companion [YouTube series](https://www.youtube.com/playlist?list=PLmAptfqzxVEUnmX3No1ZCCpU96Y9A-6PE)

---

## 🎯 Expertise

| Area | What I deliver |
|---|---|
| **Microsoft Defender XDR** | Detection engineering and threat-led hardening across MDO, MDE, and identity signals. |
| **Microsoft Sentinel** | Data strategy, DCR/DCT filtering, table tiering, retention design, and cost-aware analytics at scale. |
| **Detection Engineering** | KQL detections built from first principles and mapped to MITRE ATT&CK — see my [public detection library](https://thoor.tech/detections/). |
| **Azure Security Architecture** | Secure landing zones, network control planes (AVNM, Firewall, Private Link), and policy-as-code governance. |
| **GitHub Supply Chain Security** | GHAS posture reviews, Actions hardening, app/OAuth governance, and signed-commit controls. |

---

## 🛠️ Tech Stack

**Detection & SecOps**

![Microsoft Defender XDR](https://img.shields.io/badge/Microsoft%20Defender%20XDR-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![Microsoft Sentinel](https://img.shields.io/badge/Microsoft%20Sentinel-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![KQL](https://img.shields.io/badge/KQL-512BD4?style=flat-square&logo=microsoft&logoColor=white)
![Defender for Cloud](https://img.shields.io/badge/Defender%20for%20Cloud-0078D4?style=flat-square&logo=microsoft&logoColor=white)

**Azure Security & Network**

![Azure Policy](https://img.shields.io/badge/Azure%20Policy-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Azure Firewall](https://img.shields.io/badge/Azure%20Firewall-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![AVNM](https://img.shields.io/badge/Azure%20Virtual%20Network%20Manager-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

**IaC & Automation**

![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Bicep](https://img.shields.io/badge/Bicep-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**GitHub Security**

![GitHub Enterprise](https://img.shields.io/badge/GitHub%20Enterprise-24292F?style=flat-square&logo=github&logoColor=white)
![GitHub Advanced Security](https://img.shields.io/badge/GitHub%20Advanced%20Security-24292F?style=flat-square&logo=github&logoColor=white)

---

## 📊 KQL Profile Snapshot

```kql
datatable(Attribute: string, Value: string)
[
    "Role",        "Senior Cloud Security Architect @ Onevinn AB",
    "Status",      "Microsoft Security MVP · MDO Champion · Author",
    "Location",    "Sweden",
    "Focus",       "Defender XDR · Sentinel · Threat Hunting · Azure Security · GitHub Supply Chain",
    "OpenSource",  "Fylgyr · MET · DMARC for Defender XDR",
    "Philosophy",  "Attack to understand. Understand to detect. Detect to automate.",
]
| project Attribute, Value
```

---

## 🧩 High-impact projects

| Project | Value |
|---|---|
| [**Fylgyr**](https://github.com/pthoor/Fylgyr) | PowerShell toolkit for GitHub supply-chain security audits — commit-signing, GitHub App/OAuth security, and campaign-driven detections (e.g., the Miasma worm). |
| [**MET**](https://github.com/pthoor/MET) | Opinionated Microsoft 365 security assessor for Defender for Office 365, EOP, and Teams controls, with a self-contained HTML report. |
| [**DMARC for Defender XDR**](https://github.com/pthoor/DMARC-for-Defender-XDR) | Turns DMARC aggregate reports into SOC-ready telemetry for Defender XDR — Azure serverless ingestion plus hunting and custom detections for spoofing, policy abuse, and sender drift. |
| [**Detection library**](https://thoor.tech/detections/) | Published KQL detections for Defender for Office 365 and Teams, mapped to MITRE ATT&CK. |

---

## 🗒️ Latest from thoor.tech

<!-- blog-post-list:start -->
- 🛰️ [**Azure Default Outbound Access Retirement: What It Actually Means (and What It Doesn't)**](https://thoor.tech/Azure-Default-Outbound-Access-Retirement/) — what the retirement means for your workloads and how to prepare.
- 🛡️ [Configure Defender for Cloud workload protections with Azure Policy](https://thoor.tech/DefenderforCloud-Workload-Protection-With-Azure-Policy/)
- 💸 [Demystifying Microsoft Defender for Cloud and Defender CSPM cost](https://thoor.tech/Demystifying-MDC-and-CSPM-cost/)
- ⚙️ [Deploy and destroy Copilot for Security with Bicep and GitHub Actions](https://thoor.tech/Copilot-for-Security-deploy-and-destroy/)

Browse by topic: [Sentinel](https://thoor.tech/topics/sentinel/) · [Defender XDR](https://thoor.tech/topics/defender/) · [Azure Networking](https://thoor.tech/topics/networking/) · [GitHub Security](https://thoor.tech/topics/github/) · [IaC & Automation](https://thoor.tech/topics/iac/)
<!-- blog-post-list:end -->

---

## 📘 Book

**[Microsoft Defender for Identity in Depth](https://www.packtpub.com/en-us/product/microsoft-defender-for-identity-in-depth-9781835082850)** (Packt, 2024)
An exhaustive guide to ITDR, breach prevention, and cyberattack response with Microsoft Defender for Identity in complex hybrid AD environments.

---

## 🎤 Speaking

I speak at community events and conferences about Defender XDR, Sentinel architecture, threat hunting, and GitHub supply-chain security.

Recent & upcoming: **Experts Live Denmark** (Copenhagen 2025 & 2026) · **NIC** (Norway) · **Teamsdagen** → [full catalog on Sessionize](https://sessionize.com/pierre-thoor)

---

## 📈 GitHub stats

![](https://github-readme-stats.vercel.app/api?username=pthoor&show_icons=true)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=pthoor&layout=compact&text_color=daf7dc&bg_color=151515&hide=css,html,php)](https://github.com/pthoor/github-readme-stats)

---

## 🎓 Certifications & Badges [@Credly](https://www.credly.com/users/pierre-thoor/badges?sort=-state_updated_at&page=1)
<details>
<summary>Show latest Credly badges</summary>

<!--START_SECTION:badges-->
[![Experts Live Denmark 2025 - Speaker](https://images.credly.com/size/110x110/images/8d25e84c-8208-4a61-b58b-432d044f2208/blob)](http://www.credly.com/badges/e193a254-8ed1-4a28-a29c-0a4ecfef7c31)
[![2024 Microsoft Most Valuable Professional (MVP)](https://images.credly.com/size/110x110/images/9e9359a4-fe7e-4e02-8eb0-6c2b7947345a/image.png)](http://www.credly.com/badges/9b10d702-679c-425b-9faf-98658c50db0c)
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
[![Microsoft Sentinel Black Belt](https://images.credly.com/size/110x110/images/23d9f8d7-d662-4b93-b1b2-2fbe5b9e06e7/CREDLY_Microsoft_Sentinel_Black_Belt_V1.png)](http://www.credly.com/badges/28b47cc0-a5be-41c3-95a3-1237917fc633)
[![L3 Microsoft Sentinel Influencer](https://images.credly.com/size/110x110/images/41b63430-ded3-4d19-994c-494e91821d3d/CREDLY_Microsoft_Cloud_Security_Digital_Badges_Sentinel_Influencer.png)](http://www.credly.com/badges/97ae9753-b447-47b1-9bb7-57efdda4a245)
[![AZ-305: Designing Microsoft Azure Infrastructure Solutions](https://images.credly.com/size/110x110/images/9d7dc4c0-5681-41fc-b96b-26e9157786d7/image.png)](http://www.credly.com/badges/b88638fe-e44a-475e-96eb-5814aa271fd6)
<!--END_SECTION:badges-->

[View all badges on Credly](https://www.credly.com/users/pierre-thoor/badges?sort=-state_updated_at&page=1)
</details>

---

## 🤝 Connect

[![MVP Badge](https://img.shields.io/badge/-Microsoft%20MVP-blue?style=flat-square&logo=Microsoft&logoColor=white)](https://mvp.microsoft.com/en-us/PublicProfile/5004683)
[![Twitter Badge](https://img.shields.io/twitter/follow/PierreThoor?style=social)](https://twitter.com/PierreThoor)
[![Linkedin Badge](https://img.shields.io/badge/-PierreThoor-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/pierrethoor/)](https://www.linkedin.com/in/pierrethoor/)
[![GitHub followers](https://img.shields.io/github/followers/pthoor?label=Follow&style=social)](https://github.com/pthoor/?tab=follow)
[![Bluesky](https://img.shields.io/badge/-pierrethoor.bsky.social-blue?style=flat-square&logo=bluesky&logoColor=white)](https://bsky.app/profile/pierrethoor.bsky.social)
