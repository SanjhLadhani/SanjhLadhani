<!-- ═══════════════════════════════════ BANNER ═══════════════════════════════════ -->

<p align="center">
  <img src="https://raw.githubusercontent.com/SanjhLadhani/SanjhLadhani/main/banner.svg" width="100%" alt="Sanjh Ladhani — LLM Systems, RAG, Agentic AI" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=2800&pause=700&color=00F7FF&center=true&vCenter=true&width=900&height=50&lines=I+don%27t+just+build+models.;I+build+AI+systems+that+solve+messy%2C+real-world+problems.;10M%2B+records+%E2%86%92+structured+intelligence+with+LLMs;Agents+that+research%2C+verify+%26+act+%E2%80%94+never+guess;From+idea+%E2%86%92+prototype+%E2%86%92+production" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://sanjhladhani.netlify.app/"><img src="https://img.shields.io/badge/Portfolio-00F7FF?style=for-the-badge&logo=firefoxbrowser&logoColor=black" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/sanjh-ladhani-data-science"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://www.kaggle.com/sanjhladhani"><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle" /></a>
  <a href="https://x.com/SanjhLadhani"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
  <a href="mailto:sanjhladhani2020@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://sanjhladhani.netlify.app/Sanjh_ladhani_resume.pdf"><img src="https://img.shields.io/badge/Resume-FF5722?style=for-the-badge&logo=readdotcv&logoColor=white" alt="Resume" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-open_to_opportunities-2ea44f?style=flat-square&logo=statuspage&logoColor=white" alt="Open to opportunities" />
  <img src="https://img.shields.io/badge/now-AI%2FML_Engineer_%40_Tender247-8A2BE2?style=flat-square" alt="Current role" />
  <img src="https://img.shields.io/badge/based_in-Ahmedabad%2C_India-0A66C2?style=flat-square" alt="Location" />
  <img src="https://komarev.com/ghpvc/?username=SanjhLadhani&label=profile+views&color=00F7FF&style=flat-square" alt="Profile views" />
</p>

<!-- ═══════════════════════════════════ IMPACT ═══════════════════════════════════ -->

<table align="center">
  <tr>
    <td align="center" width="200"><h2>10M+</h2><sub><b>records processed</b><br/>LLM + rules pipelines</sub></td>
    <td align="center" width="200"><h2>28K+</h2><sub><b>companies enriched</b><br/>verified, source-tagged</sub></td>
    <td align="center" width="200"><h2>153K</h2><sub><b>products canonicalized</b><br/>self-growing entity maps</sub></td>
    <td align="center" width="200"><h2>70%</h2><sub><b>manual effort cut</b><br/>n8n automation</sub></td>
  </tr>
  <tr>
    <td align="center"><h2>25K+</h2><sub><b>images trained on</b><br/>YOLO / RF-DETR</sub></td>
    <td align="center"><h2>~35%</h2><sub><b>faster inference</b><br/>batching + pipeline tuning</sub></td>
    <td align="center"><h2>92%</h2><sub><b>helmet detection accuracy</b><br/>live, in production</sub></td>
    <td align="center"><h2>🥇</h2><sub><b>1st place · ARIC 2024–25</b><br/>oral presentation</sub></td>
  </tr>
</table>

<!-- ═══════════════════════════════════ ABOUT ═══════════════════════════════════ -->

## 👩‍💻 Who I Am

<img align="right" width="150" src="https://raw.githubusercontent.com/SanjhLadhani/SanjhLadhani/main/g9r1bfyqxdrmt0cxn8prpfcy9w.gif" alt="coding animation" />

I'm an **AI/ML Engineer & Data Scientist** who turns unstructured, messy information into systems that **understand, decide, and act**. My work sits at the intersection of **research, engineering, and automation** — LLM pipelines, RAG, agentic workflows, voice AI and real-time computer vision.

| | |
|---|---|
| 💼 **Now** | **AI/ML Engineer** @ **Tender247** (i-Sourcing Technologies) — LLM, RAG & automation pipelines · *Apr 2026 → Present* |
| 🧠 **Before** | **AI Intern** @ **Brainy Neurals** — computer vision & real-time inference on AWS · *Nov 2025 → Mar 2026* |
| 🎓 **Learning** | **MSc Data Science** @ Institute of Advanced Research (CGPA **9.4**) · **BCA** Gujarat University, *All-Time Ranker* (CGPA **8.94**) |
| 🏆 **Recognition** | 1st Place — ARIC 2024–25 · Prerna Award for Academic Excellence |

<br clear="right"/>

<!-- ═══════════════════════════════════ ARCHITECTURE ═══════════════════════════════════ -->

## 🧬 How I Build LLM Systems

The pattern behind my production pipelines — **the LLM interprets, deterministic rules anchor, and nothing is paid for twice.**

```mermaid
%%{init: {'theme':'dark','themeVariables':{'primaryColor':'#1a1a2e','primaryTextColor':'#e8f9ff','primaryBorderColor':'#00F7FF','lineColor':'#8A2BE2','tertiaryColor':'#0f0f1a'}}}%%
flowchart LR
    A["Messy input<br/>OCR tenders · typed company names"] --> B["Retrieval<br/>web search · grounded search<br/>MCA · GST registers"]
    B --> C["LLM extraction<br/>Gemini 2.5 Flash<br/>batched + context cached"]
    C --> D["Rule layer<br/>regex validation<br/>register cross-checks"]
    D --> E["Entity resolution<br/>many spellings → one canonical"]
    E --> F[("Cache + store<br/>PostgreSQL · SQLite")]
    F --> G["Verified output<br/>every field: source + confidence"]
    F -.->|"cleaned data"| H["QLoRA fine-tune<br/>Qwen, 4-bit"]
    H -.->|"cheap local inference"| C
```

<table>
  <tr>
    <td width="25%" valign="top"><b>🛡️ Verify, don't guess</b><br/><sub>Unverified values stay blank. Every field carries its source and confidence.</sub></td>
    <td width="25%" valign="top"><b>⚓ LLM + rules</b><br/><sub>The model does the interpreting; deterministic logic validates and anchors every output.</sub></td>
    <td width="25%" valign="top"><b>♻️ Never pay twice</b><br/><sub>Context caching, result caching and canonical maps keep cost and latency down.</sub></td>
    <td width="25%" valign="top"><b>🔬 Distill to local</b><br/><sub>Clean LLM output becomes training data for a fine-tuned model that runs locally.</sub></td>
  </tr>
</table>

<!-- ═══════════════════════════════════ PROJECTS ═══════════════════════════════════ -->

## 🚀 Featured Work

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>💊 Pharma Procurement Intelligence</h3>
      <sub><b>Gemini extraction → rules → canonicalization → QLoRA</b></sub><br/><br/>
      Turns OCR-corrupted GeM/NIC pharma tenders into clean, analysis-ready data. A ~44K-token domain-engineered prompt with batched parallel inference and context caching; regex rules ensure strengths are never invented. Self-growing maps (153K descriptions · 11K brands · 5K bidders) resolve every product, brand and firm to one canonical string.<br/><br/>
      🔬 Fine-tuned <b>Qwen with QLoRA</b> runs locally as a low-cost API alternative.<br/>
      📊 <b>10M+ records</b> · crash-resilient FastAPI + PostgreSQL + audit trail<br/><br/>
      <img src="https://img.shields.io/badge/Gemini_2.5_Flash-4285F4?style=flat-square" /> <img src="https://img.shields.io/badge/QLoRA-5C3EE8?style=flat-square" /> <img src="https://img.shields.io/badge/Qwen-615CED?style=flat-square" /> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" /> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
    </td>
    <td width="50%" valign="top">
      <h3>🏢 AI Company Intelligence Engine</h3>
      <sub><b>Company name in → verified profile out</b></sub><br/><br/>
      Researches across web search, Gemini grounded search, MCA register and GST sources to produce CIN, GST/PAN, directors, address, website, contact and status. Entity resolution maps many typed spellings to one company; register cross-checks validate the result.<br/><br/>
      ✅ Every field has a <b>source + confidence</b>; unverified stays blank.<br/>
      ♻️ Cached — no company is researched twice · <b>28K+ enriched</b><br/><br/><br/>
      <img src="https://img.shields.io/badge/Gemini-4285F4?style=flat-square" /> <img src="https://img.shields.io/badge/DeepInfra-2ea44f?style=flat-square" /> <img src="https://img.shields.io/badge/RAG-FF6F00?style=flat-square" /> <img src="https://img.shields.io/badge/Serper_/_Tavily-FF4B4B?style=flat-square" /> <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" /> <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>📞 AI Call Agent — n8n + Retell</h3>
      <sub><b>Production voice agent, fully automated end-to-end</b></sub><br/><br/>
      Inbound &amp; outbound calls with real-time conversational speech. Handles active/inactive user outreach, feedback collection and inquiry routing, with dynamic response logic, CRM updates and post-call data sync.<br/><br/>
      <img src="https://img.shields.io/badge/Retell_AI-000000?style=flat-square" /> <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white" /> <img src="https://img.shields.io/badge/Webhooks-FF6F00?style=flat-square" /> <img src="https://img.shields.io/badge/CRM_Sync-0A66C2?style=flat-square" />
    </td>
    <td width="50%" valign="top">
      <h3>🔗 n8n Lead-Gen Automation</h3>
      <sub><b>Capture → enrich → route</b></sub><br/><br/>
      No-code workflow with email, Google Sheets and CRM integrations that cut manual effort by <b>~70%</b>.<br/><br/>
      <h3>🗣️ SAYANK.AI — Voice Assistant</h3>
      <sub><b>Multi-modal AI assistant</b></sub><br/><br/>
      Speech recognition + TTS, NLP intent handling, live API integrations and a neural-inspired animated GUI.<br/><br/>
      <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white" /> <img src="https://img.shields.io/badge/NLP-4B8BBE?style=flat-square" /> <img src="https://img.shields.io/badge/TTS-7C3AED?style=flat-square" />
    </td>
  </tr>
</table>

<details>
<summary><b>👁️ Computer vision work (click to expand)</b></summary>
<br/>

| Project | What it does | Result |
|---|---|---|
| ⛑️ **SanjhSuraksha** | YOLOv8 PPE monitoring for open-cast mines from live video | **92% detection accuracy**, deployed |
| 🏀 **Basketball Detection & Tracking** | Player, jersey-number and action detection (RF-DETR + YOLOv8) | **mAP 0.62 → 0.78** on 25K+ images, **~35% faster** inference, on AWS EC2 + S3 |

</details>

<sub>🔎 More on my <a href="https://sanjhladhani.netlify.app/">portfolio</a> — emotion-based music &amp; book recommenders, an AES-256 steganography tool, and more.</sub>

<!-- ═══════════════════════════════════ STACK ═══════════════════════════════════ -->

## 🛠️ Arsenal

**🤖 LLMs · RAG · Agents**  
![Gemini](https://img.shields.io/badge/Gemini_2.5_Flash-4285F4?style=for-the-badge&logo=googlegemini&logoColor=white)
![LLMs](https://img.shields.io/badge/LLMs-412991?style=for-the-badge&logo=openai&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-FF6F00?style=for-the-badge)
![Agents](https://img.shields.io/badge/Agentic_AI-7C3AED?style=for-the-badge)
![QLoRA](https://img.shields.io/badge/QLoRA_%2F_PEFT-5C3EE8?style=for-the-badge)
![Qwen](https://img.shields.io/badge/Qwen-615CED?style=for-the-badge)
![Context Caching](https://img.shields.io/badge/Context_Caching-0A66C2?style=for-the-badge)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-00B8D4?style=for-the-badge)
![DeepInfra](https://img.shields.io/badge/DeepInfra-2ea44f?style=for-the-badge)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![Serper / Tavily](https://img.shields.io/badge/Serper_%2F_Tavily-FF4B4B?style=for-the-badge)
![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Entity Resolution](https://img.shields.io/badge/Entity_Resolution-4B8BBE?style=for-the-badge)

**⚙️ Automation · Voice AI · Document Intelligence**  
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Retell AI](https://img.shields.io/badge/Retell_AI-000000?style=for-the-badge)
![Webhooks](https://img.shields.io/badge/Webhooks-FF6F00?style=for-the-badge)
![OCR](https://img.shields.io/badge/OCR_%2F_Document_Parsing-3776AB?style=for-the-badge)

**👁️ Vision · ML · Data**  
![YOLOv8](https://img.shields.io/badge/YOLOv8-00B8D4?style=for-the-badge)
![RF-DETR](https://img.shields.io/badge/RF--DETR-5C3EE8?style=for-the-badge)
![NLP](https://img.shields.io/badge/NLP-4B8BBE?style=for-the-badge)
![CNN / RNN](https://img.shields.io/badge/CNN_%2F_RNN-000000?style=for-the-badge)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

**🧱 Core stack**

<p align="left">
  <img src="https://skillicons.dev/icons?i=python,cpp,java,c,mysql,postgres,mongodb,sqlite,tensorflow,sklearn,opencv,flask,fastapi,docker,aws,git,github,linux,anaconda,vscode&perline=10&theme=dark" alt="Core stack" />
</p>

<!-- ═══════════════════════════════════ NOW ═══════════════════════════════════ -->

## 🧠 Currently Building

```text
> agentic AI systems ........ LLM agents that research, verify and act
> RAG + LLM data pipelines .. structured intelligence from unstructured data, at scale
> AI calling systems ........ voice agents wired into automation workflows
> production ML pipelines ... from notebook to something that doesn't fall over
```

<!-- ═══════════════════════════════════ ACHIEVEMENTS ═══════════════════════════════════ -->

## 🏆 Recognition & Credentials

<table>
  <tr>
    <td valign="top" width="50%">
      🥇 <b>1st Place, Oral Presentation</b><br/><sub>Annual Research &amp; Innovation Conclave (ARIC) 2024–25</sub><br/><br/>
      🎖️ <b>Prerna Award</b><br/><sub>Academic Excellence — Special Category</sub><br/><br/>
      🏅 <b>All-Time Ranker</b><br/><sub>Gujarat University · CGPA 8.94</sub>
    </td>
    <td valign="top" width="50%">
      📜 <b>AI Data Engineer</b> — Reliance Foundation<br/>
      📜 <b>Deep Learning</b> — NVIDIA<br/>
      📜 <b>Introduction to Data Science</b> — Cisco Networking Academy<br/>
      📜 <b>Data Visualization</b> — Forage<br/>
      📜 <b>Emerging Technologies</b> — Code Unnati (SAP &amp; Edunet)
    </td>
  </tr>
</table>

<!-- ═══════════════════════════════════ FOOTER ═══════════════════════════════════ -->

## 🤝 Let's Build Something Real

<p align="center">
  <a href="https://www.linkedin.com/in/sanjh-ladhani-data-science"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://sanjhladhani.netlify.app/"><img src="https://img.shields.io/badge/Portfolio-00F7FF?style=for-the-badge&logo=firefoxbrowser&logoColor=black" alt="Portfolio" /></a>
  <a href="https://www.kaggle.com/sanjhladhani"><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle" /></a>
  <a href="https://x.com/SanjhLadhani"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
  <a href="mailto:sanjhladhani2020@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<p align="center"><i>Real-world AI — not just notebooks.</i> ⚡</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/SanjhLadhani/SanjhLadhani/main/footer.svg" width="100%" alt="Let's build something real" />
</p>
