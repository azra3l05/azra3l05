# 👋 Hi, I'm Gopinath Sekar — Data Engineer

![Visitors](https://visitor-badge.laobi.icu/badge?page_id=azra3l05&color=7aa2f7)

Building robust **data pipelines**, automating everything I reasonably can, and running a fleet of **self-hosted services** to keep my ops skills sharp. I care about clean engineering, observability, and secure, scalable **cloud-native** systems.

🌱 **Currently exploring:** agentic AI workflows & AI-assisted engineering

<table>
<tr>
<td valign="top" width="55%">

#### 🛠️ Data Engineering & Cloud
- **Snowflake** — procedures, SDKs, perf tuning, Liquibase CI/CD
- **dbt** — data modeling & testing on Snowflake
- **AWS** — S3, Lambda, SNS, IAM, Secrets Manager, CloudFormation
- **Apache Airflow** — ETL orchestration, Dockerized DAGs
- **SQL · Python** — analytics, data-quality checks, automation
- **GitHub Actions · Docker** — CI/CD & reproducible environments

#### 📊 Analytics & Front-End
- **Tableau** — trusted-ticket auth, parameter automation
- **Angular · Node.js** — Tableau embedding, Express APIs, JWT
- **Grafana · Graylog** — metrics & centralized logging

#### 🏠 Self-Hosted Homelab
- ~40 containerized services · Docker + Traefik + Authelia SSO
- Custom **observability dashboard** (SvelteKit + FastAPI)
- ZFS / BTRFS · scripted auto-updates · ops bots

</td>
<td valign="top" width="45%">

<img src="https://github-readme-stats.vercel.app/api?username=azra3l05&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub stats" />
<br/><br/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=azra3l05&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />
<br/><br/>
<img src="https://streak-stats.demolab.com/?user=azra3l05&theme=tokyonight&hide_border=true" alt="Streak" />

</td>
</tr>
</table>

#### 📌 Featured Project
**[fda-recall-dashboard](https://github.com/azra3l05/fda-recall-dashboard)** — an end-to-end **FDA drug-recall data pipeline & dashboard**: Airflow DAGs ingest and clean public FDA data → PostgreSQL → Superset visualizations. Dockerized. `Python · Airflow · PostgreSQL · Superset`

<details>
<summary>🏗️ <b>Homelab architecture</b> (click to expand)</summary>

```mermaid
flowchart LR
    NET([🌐 Internet]) --> TR[Traefik<br/>Reverse Proxy]
    TR --> AU[Authelia<br/>SSO + 2FA]
    AU --> APP[Web Apps]
    AU --> MON[Monitoring<br/>& Uptime]
    AU --> AUTO[Automation<br/>& Ops Bots]
    APP --> DB[(PostgreSQL<br/>Redis)]
    AUTO --> DB
    APP --> ST[(ZFS / BTRFS<br/>Storage)]
    MON --> ST
    AUTO --> ST
```

</details>

#### 🧰 Tools I Reach For

![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apache-airflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/Postgres-316192?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DD0031?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

#### ⚡ A Few Things About Me
- 🏠 I self-host almost everything — if it can run in a container, it probably is.
- 📈 Obsessed with metrics — if it can be graphed, it's going to Grafana.
- 🐧 Daily-drive Linux (Ubuntu / Alpine); love tinkering with ZFS & BTRFS.
- 🔐 Big on secure pipelines — encryption, secrets management, and IAM done right.
- 🎮 Occasional detour into gaming & retro consoles.

#### 🤝 Connect
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/gopinath-sekar)
