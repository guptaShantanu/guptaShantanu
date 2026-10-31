<p align="center">
  <img src="./assets/header.svg" alt="Terminal intro: Shantanu Gupta, Full-stack & AI Engineer, Senior Manager Tech at Eureka Forbes" width="100%" />
</p>

<p align="center">
  <a href="https://YOUR-PORTFOLIO-URL"><img src="https://img.shields.io/badge/⌘_portfolio-live-4f7cff?style=for-the-badge&labelColor=0b1020" alt="Portfolio" /></a>
  <a href="https://YOUR-PORTFOLIO-URL"><img src="https://img.shields.io/badge/ask_my_AI-online-4ade80?style=for-the-badge&labelColor=0b1020" alt="Ask my AI" /></a>
  <a href="https://www.linkedin.com/in/YOUR-LINKEDIN"><img src="https://img.shields.io/badge/linkedin-connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0b1020" alt="LinkedIn" /></a>
  <a href="mailto:officialshantanugupta08@gmail.com"><img src="https://img.shields.io/badge/email-ping-c084fc?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0b1020" alt="Email" /></a>
</p>

> [!NOTE]
> **`status: architecting AI systems @ Eureka Forbes`**: LLMs with retrieval, tools and agents, shipped inside the evals, guardrails and cost limits that production needs.

<br/>

## `⚡ system.profile`

```yaml
engineer:
  name: Shantanu Gupta
  location: Bangalore, IN
  current: Senior Manager, Tech @ Eureka Forbes
  runs_as: [Solution Architect, AI Solution Architect, Team Lead]

throughput:
  experience: 7+ years
  products_to_production: 10+
  users_served: 1M+
  enterprise_brands: 6+

operating_principles:
  - one owner across every layer, so nothing breaks at the hand-offs
  - models that ship, not demos
  - measure it before users see it
```

<br/>

## `🧬 architecture`

<p align="center">
  <img src="./assets/stack.svg" alt="Request lifecycle: Frontend, Backend, Database and AI, all owned by one engineer" width="100%" />
</p>

<br/>

## `🛰️ ship_pipeline`

```mermaid
flowchart LR
    A([💡 Idea]):::io --> B[🎨 Design]:::fe
    B --> C[📱 Flutter · Next.js]:::fe
    C --> D[⚙️ Node.js · gRPC]:::be
    D --> E[(🗄️ Postgres · Mongo · Vectors)]:::db
    E --> F{{🧠 LLM + RAG + Agents}}:::ai
    F --> G[🧪 Evals & Guardrails]:::ai
    G --> H([🚀 Production]):::io

    classDef io fill:#0b1020,stroke:#4ade80,color:#e2e8f0,stroke-width:2px
    classDef fe fill:#0b1020,stroke:#22d3ee,color:#e2e8f0
    classDef be fill:#0b1020,stroke:#60a5fa,color:#e2e8f0
    classDef db fill:#0b1020,stroke:#a78bfa,color:#e2e8f0
    classDef ai fill:#0b1020,stroke:#f0abfc,color:#e2e8f0
```

<br/>

## `🧰 toolchain`

<table>
  <tr>
    <td width="130"><code>client</code></td>
    <td><img src="https://skillicons.dev/icons?i=flutter,dart,nextjs,react,ts,kotlin,androidstudio&theme=dark" alt="Flutter, Dart, Next.js, React, TypeScript, Kotlin, Android" /></td>
  </tr>
  <tr>
    <td><code>services</code></td>
    <td><img src="https://skillicons.dev/icons?i=nodejs,ts,gcp,firebase,docker,vercel&theme=dark" alt="Node.js, TypeScript, Google Cloud, Firebase, Docker, Vercel" /></td>
  </tr>
  <tr>
    <td><code>state</code></td>
    <td><img src="https://skillicons.dev/icons?i=postgres,mongodb,mysql&theme=dark" alt="PostgreSQL, MongoDB, MySQL" /></td>
  </tr>
  <tr>
    <td><code>intelligence</code></td>
    <td>
      <img src="https://img.shields.io/badge/LLMs-0b1020?style=for-the-badge&logo=openai&logoColor=f0abfc" alt="LLMs" />
      <img src="https://img.shields.io/badge/RAG-0b1020?style=for-the-badge&logo=databricks&logoColor=f0abfc" alt="RAG" />
      <img src="https://img.shields.io/badge/Agents-0b1020?style=for-the-badge&logo=robotframework&logoColor=f0abfc" alt="Agents" />
      <img src="https://img.shields.io/badge/LangGraph-0b1020?style=for-the-badge&logo=langchain&logoColor=f0abfc" alt="LangGraph" />
      <img src="https://img.shields.io/badge/MCP-0b1020?style=for-the-badge&logo=anthropic&logoColor=f0abfc" alt="MCP" />
      <img src="https://img.shields.io/badge/pgvector-0b1020?style=for-the-badge&logo=postgresql&logoColor=f0abfc" alt="pgvector" />
      <img src="https://img.shields.io/badge/Evals-0b1020?style=for-the-badge&logo=checkmarx&logoColor=f0abfc" alt="Evals" />
      <img src="https://img.shields.io/badge/Claude-0b1020?style=for-the-badge&logo=anthropic&logoColor=f0abfc" alt="Claude" />
      <img src="https://img.shields.io/badge/Gemini-0b1020?style=for-the-badge&logo=googlegemini&logoColor=f0abfc" alt="Gemini" />
      <img src="https://img.shields.io/badge/Python-0b1020?style=for-the-badge&logo=python&logoColor=f0abfc" alt="Python" />
    </td>
  </tr>
</table>

<br/>

## `🚀 deployments`

| | service | what it does | stack |
| :-: | :-- | :-- | :-- |
| ![](https://img.shields.io/badge/PROD-4ade80?style=flat-square) | **Aquaguard Apps** · Eureka Forbes | Customer, technician & IoT apps for Aquaguard purifiers | `Flutter` `Bloc` `IoT` |
| ![](https://img.shields.io/badge/PROD-4ade80?style=flat-square) | **NWORX** · Designs In Change | Learning & leadership platform with a micro-frontend design studio | `Flutter` `Firebase` |
| ![](https://img.shields.io/badge/PROD-4ade80?style=flat-square) | **Assessment Platform** | Secure 360° assessment, engagement, reporting & analytics | `Flutter` `Firebase` |
| ![](https://img.shields.io/badge/1M_USERS-60a5fa?style=flat-square) | **Yellowbacks** · Qart Fashion | Backend scaled and benchmarked for a million users | `Node.js` `Caching` |
| ![](https://img.shields.io/badge/GCP-a78bfa?style=flat-square) | **Glyde Rides** | Vehicle-rental backend: live data + geo + transactions | `Node.js` `TS` `MongoDB` `PostgreSQL` |
| ![](https://img.shields.io/badge/SOLO-f0abfc?style=flat-square) | **Mr. Klean** | User app, admin portal & delivery app, end to end | `Flutter` `Node.js` |

<sub>→ full case studies, architecture decisions and an AI that answers from my profile: <b><a href="https://YOUR-PORTFOLIO-URL/projects">portfolio/projects</a></b></sub>

<br/>

## `📡 telemetry`

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=guptaShantanu&show_icons=true&hide_border=true&bg_color=0b1020&title_color=7dd3fc&icon_color=c084fc&text_color=cbd5e1&ring_color=4f7cff&include_all_commits=true&count_private=true&custom_title=runtime.stats" alt="GitHub stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=guptaShantanu&layout=compact&hide_border=true&bg_color=0b1020&title_color=7dd3fc&text_color=cbd5e1&langs_count=6&custom_title=languages.compiled" alt="Top languages" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=guptaShantanu&bg_color=0b1020&color=94a3b8&line=4f7cff&point=c084fc&area=true&area_color=4f7cff&hide_border=true&radius=12&title_color=7dd3fc&custom_title=commit.signal" alt="Contribution activity graph" width="100%" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/guptaShantanu/guptaShantanu/output/snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/guptaShantanu/guptaShantanu/output/snake.svg" />
    <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/guptaShantanu/guptaShantanu/output/snake.svg" width="100%" />
  </picture>
</p>

<br/>

## `📜 git log --career`

<details>
<summary><b>expand commit history</b></summary>
<br/>

```diff
+ HEAD → main   Senior Manager, Tech · Eureka Forbes
                solution architect · AI solution architect · team lead

+ a7f3e21       Lead App Engineer · Eureka Forbes            (Oct 2023)
                customer, technician & IoT apps; led hybrid mobile team

+ 5c19b0d       Senior Software Engineer · Designs In Change (Dec 2021 – Aug 2023)
                NWORX + Assessment on Flutter micro-frontends

+ 9e04d7a       Software Developer · Qart Fashion            (Sep 2019 – Nov 2021)
                QVenue, QStream; Yellowbacks backend → 1M users

+ 2b8c6f4       Software Developer · Glyde Rides             (Sep 2018 – Sep 2019)
                rental backend on GCP: MongoDB + PostgreSQL

+ 0d1e2a9       Intern · UrbanRider                          (Apr 2018 – Jul 2018)
                full app on Flutter + Firebase

! init          B.Tech, Information Technology · PSIT        (CGPA 8.3)
```

</details>

<br/>

<div align="center">

```console
$ ./connect --problem "your product"
→ routing to the right layer … frontend ✓ backend ✓ database ✓ ai ✓
→ one engineer assigned. response time: fast.
```

<a href="mailto:officialshantanugupta08@gmail.com"><img src="https://img.shields.io/badge/▶_bring_me_a_problem-4f7cff?style=for-the-badge&labelColor=0b1020" alt="Bring me a problem" /></a>

</div>
