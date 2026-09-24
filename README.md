<!-- ==================== HEADER BANNER ==================== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=270&color=0:0B1220,30:102A56,60:0078D4,100:50E6FF&text=AZURE%20DATA%20ENGINEER&fontSize=48&fontAlignY=36&fontColor=FFFFFF&font=Montserrat&animation=fadeIn&desc=%E2%98%81%EF%B8%8F%20Microsoft%20Certified%3A%20AZ-104%20%C2%B7%20DP-900%20%C2%B7%20AI-900&descAlignY=58&descSize=20&descColor=FFFFFF" width="100%"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=50E6FF&center=true&vCenter=true&width=800&lines=Hi+%F0%9F%91%8B+I'm+M+Reddappa+Yadav;Azure+Data+Engineer+%40+EY+GDS;Source+%E2%86%92+Lake+%E2%86%92+Transform+%E2%86%92+Analytics;Lakehouse+%7C+PySpark+%7C+ADF+%7C+Databricks;Exploring+GenAI+%26+Agentic+AI+on+Enterprise+Data" alt="Typing SVG" />
</p>

<!-- ==================== CERTIFICATION BADGES ==================== -->
<p align="center">
  <img src="https://img.shields.io/badge/%F0%9F%8F%86%20AZ--104-Azure%20Administrator%20Associate-0078D4?style=for-the-badge&logo=microsoft&logoColor=white"/>
  <img src="https://img.shields.io/badge/%F0%9F%8F%86%20DP--900-Azure%20Data%20Fundamentals-00B7C3?style=for-the-badge&logo=microsoft&logoColor=white"/>
  <img src="https://img.shields.io/badge/%F0%9F%8F%86%20AI--900-Azure%20AI%20Fundamentals-7B2FF7?style=for-the-badge&logo=microsoft&logoColor=white"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Role-Azure%20Data%20Engineer-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
  <img src="https://img.shields.io/badge/Experience-4%2B%20Years-FF6F00?style=for-the-badge&logo=databricks&logoColor=white"/>
  <img src="https://img.shields.io/badge/Location-Bangalore%2C%20India-E91E63?style=for-the-badge&logo=googlemaps&logoColor=white"/>
  <img src="https://img.shields.io/badge/Open%20to-Opportunities-2EA44F?style=for-the-badge&logo=handshake&logoColor=white"/>
</p>

---

<!-- ==================== ABOUT ==================== -->
<table>
<tr>
<td width="60%" valign="top">

## 👨‍💻 Professional Summary

I'm **M Reddappa Yadav**, an **Azure Data Engineer with 4+ years of experience** building cloud-based data solutions, currently at **EY GDS, Bangalore**.

I design reliable data platforms that move data from **source ➜ lake ➜ transformation ➜ analytics**, with a focus on pipelines that are **scalable, observable, and cost-aware**.

🔹 `Data Engineering` · `Lakehouse` · `ETL/ELT` · `Distributed Processing`

🚀 I'm also expanding into **Generative AI and Agentic AI**, particularly where AI can work with **enterprise data**.

</td>
<td width="40%" valign="top">

### ⚡ Profile Snapshot

| | |
|---|---|
| 🎯 **Role** | `Azure Data Engineer` |
| ⏳ **Experience** | `4+ Years` |
| ☁️ **Cloud** | `Microsoft Azure` |
| 🏗️ **Data** | `Big Data / Lakehouse` |
| ⚙️ **Processing** | `PySpark / Spark` |
| 🤖 **AI** | `GenAI / RAG / Agents` |
| 🏆 **Certified** | `AZ-104 · DP-900 · AI-900` |

</td>
</tr>
</table>

---

<!-- ==================== AZURE ARCHITECTURE ==================== -->
## ☁️ Azure Data Platform I Build

```mermaid
flowchart LR
    subgraph SRC["📥 DATA SOURCES"]
        S1["🗄️ Databases<br/>SQL · Oracle"]
        S2["🌐 REST APIs"]
        S3["📁 Files<br/>CSV · JSON · Parquet"]
    end

    subgraph ING["⚙️ INGEST"]
        ADF["🔄 Azure Data Factory<br/>Pipelines · Triggers"]
    end

    subgraph LAKE["🏞️ AZURE DATA LAKE STORAGE GEN2"]
        BR["🥉 BRONZE<br/>Raw"]
        SI["🥈 SILVER<br/>Cleansed · Delta"]
        GO["🥇 GOLD<br/>Curated"]
    end

    subgraph PROC["⚡ TRANSFORM"]
        DBX["🔥 Azure Databricks<br/>PySpark · Delta Lake"]
    end

    subgraph SERVE["📊 SERVE"]
        SYN["🏢 Azure Synapse"]
        PBI["📈 Power BI"]
    end

    subgraph GENAI["🤖 GENAI"]
        RAG["🧠 RAG · Agents<br/>on Enterprise Data"]
    end

    S1 --> ADF
    S2 --> ADF
    S3 --> ADF
    ADF --> BR
    BR --> DBX
    DBX --> SI
    SI --> GO
    GO --> SYN
    SYN --> PBI
    SI -.-> RAG

    style SRC fill:#0B1220,stroke:#50E6FF,stroke-width:2px,color:#FFFFFF
    style ING fill:#0B1220,stroke:#0078D4,stroke-width:2px,color:#FFFFFF
    style LAKE fill:#0B1220,stroke:#FFB900,stroke-width:2px,color:#FFFFFF
    style PROC fill:#0B1220,stroke:#FF3621,stroke-width:2px,color:#FFFFFF
    style SERVE fill:#0B1220,stroke:#F2C811,stroke-width:2px,color:#FFFFFF
    style GENAI fill:#0B1220,stroke:#B146C2,stroke-width:2px,color:#FFFFFF

    style S1 fill:#102A56,stroke:#50E6FF,color:#FFFFFF
    style S2 fill:#102A56,stroke:#50E6FF,color:#FFFFFF
    style S3 fill:#102A56,stroke:#50E6FF,color:#FFFFFF
    style ADF fill:#0078D4,stroke:#FFFFFF,color:#FFFFFF
    style BR fill:#B5651D,stroke:#FFFFFF,color:#FFFFFF
    style SI fill:#8A97A8,stroke:#FFFFFF,color:#000000
    style GO fill:#FFB900,stroke:#FFFFFF,color:#000000
    style DBX fill:#FF3621,stroke:#FFFFFF,color:#FFFFFF
    style SYN fill:#00B7C3,stroke:#FFFFFF,color:#000000
    style PBI fill:#F2C811,stroke:#FFFFFF,color:#000000
    style RAG fill:#B146C2,stroke:#FFFFFF,color:#FFFFFF
```

<p align="center">
  <img src="https://img.shields.io/badge/Bronze-Raw%20Data-B5651D?style=flat-square"/>
  <img src="https://img.shields.io/badge/Silver-Cleansed%20%26%20Validated-8A97A8?style=flat-square"/>
  <img src="https://img.shields.io/badge/Gold-Business%20Ready-FFB900?style=flat-square"/>
  <img src="https://img.shields.io/badge/Architecture-Medallion%20Lakehouse-0078D4?style=flat-square"/>
</p>

---

<!-- ==================== TECH STACK ==================== -->
## 🛠️ Azure Tech Stack

<table>
<tr>
<td width="25%" align="center"><h4>🔄 Ingestion & Orchestration</h4></td>
<td>
  <img src="https://img.shields.io/badge/Azure%20Data%20Factory-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pipelines-50E6FF?style=for-the-badge&logoColor=black&labelColor=0B1220"/>
  <img src="https://img.shields.io/badge/Triggers-00B7C3?style=for-the-badge"/>
</td>
</tr>
<tr>
<td align="center"><h4>🏞️ Storage & Lakehouse</h4></td>
<td>
  <img src="https://img.shields.io/badge/ADLS%20Gen2-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
  <img src="https://img.shields.io/badge/Delta%20Lake-00ADD4?style=for-the-badge&logo=delta&logoColor=white"/>
  <img src="https://img.shields.io/badge/Medallion%20Architecture-FFB900?style=for-the-badge&logoColor=black"/>
</td>
</tr>
<tr>
<td align="center"><h4>⚡ Processing</h4></td>
<td>
  <img src="https://img.shields.io/badge/Azure%20Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white"/>
  <img src="https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white"/>
</td>
</tr>
<tr>
<td align="center"><h4>📊 Analytics & Serving</h4></td>
<td>
  <img src="https://img.shields.io/badge/Azure%20Synapse-00B7C3?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
</td>
</tr>
<tr>
<td align="center"><h4>🔐 Cloud Administration</h4></td>
<td>
  <img src="https://img.shields.io/badge/Azure%20Administration-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
  <img src="https://img.shields.io/badge/Azure%20AD%20%2F%20RBAC-5E5E5E?style=for-the-badge&logo=microsoft&logoColor=white"/>
  <img src="https://img.shields.io/badge/Monitoring-107C10?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
</td>
</tr>
<tr>
<td align="center"><h4>🤖 Generative AI</h4></td>
<td>
  <img src="https://img.shields.io/badge/GenAI-B146C2?style=for-the-badge&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/RAG-7B2FF7?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Agentic%20AI-E91E63?style=for-the-badge"/>
</td>
</tr>
<tr>
<td align="center"><h4>🧰 Dev Tools</h4></td>
<td>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</td>
</tr>
</table>

---

<!-- ==================== EXPERIENCE ==================== -->
## 💼 Professional Journey

| 📅 Period | 🏢 Company | 🎯 Role | ☁️ Focus |
|:---|:---|:---|:---|
| **Apr 2026 ➜ Present** | **EY GDS**, Bangalore | Azure Data Engineer | Enterprise data platforms on Azure |
| **Jul 2023 ➜ Apr 2026** | **CGI** | Software Engineer, Azure Data Engineering | ADF · Databricks · PySpark · Delta Lake |
| **Jul 2022 ➜ Jun 2023** | **CGI** | Associate Software Engineer, Azure Cloud Administration | Azure administration and operations |

<p align="center">
  <img src="https://img.shields.io/badge/Education-B.Sc.%20Computer%20Science-102A56?style=for-the-badge&logo=googlescholar&logoColor=white"/>
  <img src="https://img.shields.io/badge/Sri%20Venkateshwara%20University-Tirupati-0078D4?style=for-the-badge"/>
</p>

---

<!-- ==================== PRINCIPLES ==================== -->
## 🎯 What I Bring to a Team

<table>
<tr>
<td align="center" width="25%">🔐<br/><b>Reliability</b><br/><sub>Idempotent, restartable pipelines with clear failure handling</sub></td>
<td align="center" width="25%">⚡<br/><b>Performance</b><br/><sub>Partitioning and optimized Spark jobs</sub></td>
<td align="center" width="25%">🧪<br/><b>Quality</b><br/><sub>Validation and data-quality checks at every
