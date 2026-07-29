# Hi, I'm Thiago Colen 👋

**AI Engineer | Agentic Systems (LangGraph/Deep Agents) & RAG | TypeScript, Anthropic Claude, AWS/Terraform | 15+ yrs Front-End Architecture**
📍 *São Paulo, Brasil*

[🌐 Blog](https://thiagocolen.github.io) | [💼 LinkedIn](https://linkedin.com/in/thiagocolen) | [📧 Contact Me](mailto:thiago.souzacolen@gmail.com)

---

## 🎯 About Me

AI Engineer building production-grade agentic systems — most recently **"Pinky and the Brain,"** a
cloud-native Deep Agent (LangGraph.js) grounded by a custom RAG pipeline. The service is deployed on
AWS (Lightsail, CloudFront) via Terraform, and exposed through the Agent Client Protocol, a REST/SSE
API, and a Model Context Protocol server — with a companion CLI (`patb-cli`) bridging it into the
Zed IDE.

That work sits on top of 15+ years as a Front-End Developer and Web Architect, most recently at
Santander/F1rst, where I built proprietary front-end and UI frameworks, led Micro Front-End and Web
Components architectures, and shipped AWS-hosted (S3, Lambda, API Gateway) static deployment
pipelines for large-scale applications.

* 🚀 Currently building: **[Pinky and the Brain](https://github.com/thiagocolen/pinky-and-the-brain)** — a cloud-native Deep Agent service, and its companion **[patb-cli](https://github.com/thiagocolen/patb-cli)** IDE/CLI bridge
* 🧠 Deep diving into: **Agentic Systems, Retrieval-Augmented Generation, Prompt Engineering, Anthropic Claude / LLM integration**

---

## 🛠️ Technical Stack

| Category | Technologies & Tools |
| :--- | :--- |
| **AI / Agents** | LangChain, LangGraph.js (Deep Agents), Anthropic Claude, Retrieval-Augmented Generation (BM25 + vector fusion), Model Context Protocol (MCP), Agent Client Protocol (ACP) |
| **Languages** | TypeScript, JavaScript, HTML5, CSS3 |
| **Front-End** | Angular, React, RxJS, Web Components, Micro Front-Ends, Module Federation, Tailwind CSS, Bootstrap |
| **Testing & Tooling** | Jest, Cypress, Playwright, Storybook, Jasmine, Karma, Vite, Webpack, Nx Monorepo |
| **Cloud & DevOps** | AWS (Lightsail, S3, Lambda, CloudFront, API Gateway), Terraform, Docker, GitHub Actions, SQLite |

---

## 🚀 Featured Project

### [Pinky and the Brain](https://github.com/thiagocolen/pinky-and-the-brain) — *Deep Agent Service & CLI*

* **The Scenario:** Wanted hands-on, production-grade experience with agentic AI beyond prototype
  scripts — grounded retrieval, cloud deployment, and real client integrations (IDE, REST, MCP).
* **The Challenge:** Build a cloud-native agent that teaches or writes about a fixed set of topics,
  grounding every answer in curated source material rather than model recall, and make it reachable
  from an IDE, a REST client, and an MCP client alike.
* **The Approach:** Built "The Brain," a single Deep Agent (`createDeepAgent` on LangGraph.js) with a
  persona, a guided conversation flow, and tools that always defer to a knowledge store for topics,
  subtopics, and source material. Implemented a RAG pipeline over ~5,166 pre-compiled knowledge
  chunks, combining BM25 with vector similarity via rank fusion. Deployed to AWS as Infrastructure-as-
  Code — a Lightsail container service behind CloudFront, provisioned and torn down with Terraform.
  Exposed the agent through four entrypoints: Agent Client Protocol (ACP) for IDEs, a REPL CLI, an
  Express REST API with SSE streaming, and a Model Context Protocol (MCP) server. Built `patb-cli`, a
  companion CLI/Zed bridge that streams runs in real time and downloads agent-written files as
  hash-verified artifacts to the user's own disk.
* **Impact & Outcomes:** Measured **0.900 recall@10** for the fused BM25 + vector retriever on a
  labelled query set, a large improvement over the 0.597 recall@10 of the substring matching it
  replaced. Shipped a fully IaC-deployed, cloud-hosted agent service (Docker + Terraform + Lightsail +
  CloudFront) rather than a local-only prototype. Delivered a working Zed IDE integration via the
  Agent Client Protocol, plus REST/SSE and MCP interfaces for non-IDE clients.
* **Technologies:** TypeScript, LangChain, LangGraph.js (Deep Agents), Anthropic Claude,
  Retrieval-Augmented Generation (RAG), BM25, Vector Embeddings, AWS Lightsail, AWS CloudFront, AWS
  S3, Terraform, Docker, Express, Server-Sent Events (SSE), Model Context Protocol (MCP), Agent
  Client Protocol (ACP), SQLite
* **Links:** [Repo](https://github.com/thiagocolen/pinky-and-the-brain) • [patb-cli](https://github.com/thiagocolen/patb-cli)

---

## 💼 Background

* **F1rst** — Web Architect (Nov 2023 – Feb 2026), Tech Lead (Jan 2022 – Oct 2023), Sr. Front-End
  Developer (Apr 2018 – Dec 2021)
* **Avanade** — Sr. Full Stack Developer (Jan 2017 – Apr 2018)
* **Natue** — Front-End Developer (Apr 2016 – Jan 2017)
* **TEx** — Front-End Developer (Oct 2014 – Nov 2015)

**Education:** MBA, Computer/Information Technology Administration and Management — FIAP (2020–2021)
· Bachelor's, Desenho Industrial com habilitação em Programação Visual — UNESP (2000–2005)

**Languages:** English (Intermediate/B2) · Portuguese (Fluent)

---

## 📈 Engineering Activity & Metrics

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=thiagocolen&show_icons=true&theme=dark&count_private=true" alt="GitHub Stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=thiagocolen&layout=compact&theme=dark" alt="Top Languages" />
</div>

---

<div align="center">
  <sub>Designed & engineered by Thiago Colen • Powered by Markdown & GitHub Actions</sub>
</div>
