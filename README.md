<!--
  ✦ SETUP NOTES (delete this comment whenever you like) ✦
  1. This repo must be named exactly  rmedagam06/rmedagam06  to show on your profile.
  2. Commit assets/bastani-pipeline.svg and .github/workflows/snake.yml too.
  3. The snake + pipeline images go live after the first Action run + push to main.
  4. Pin these repos on your profile: Kirona, wallpaper-diffusion, lob-simulator, llm-benchmark.
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:a855f7,50:d946ef,100:ec4899&height=200&section=header&text=Ronika%20Medagam&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=EE%20@%20Georgia%20Tech%20%C2%B7%20ML%20%C2%B7%20Trustworthy%20AI%20%C2%B7%20Security&descAlignY=60&descSize=18" width="100%" alt="banner"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=A855F7&center=true&vCenter=true&width=760&height=45&lines=Making+LLM+agents+provably+behave+%F0%9F%94%90;Building+ML+systems+from+scratch+%F0%9F%A7%A0;Research+that+ships+as+real+software+%F0%9F%9A%80;4.0+GPA+%C2%B7+AWS+AI+Practitioner+%C2%B7+Published+author" alt="typing subtitle"/>
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=rmedagam06&label=Profile+views&color=a855f7&style=flat" alt="views"/>
&nbsp;
<a href="https://www.linkedin.com/in/ronika-m-259b3b296"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin"/></a>
<a href="https://ronikas-webpage.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-a855f7?style=for-the-badge&logo=vercel&logoColor=white" alt="portfolio"/></a>
<a href="mailto:ronika05m@gmail.com"><img src="https://img.shields.io/badge/Email-ec4899?style=for-the-badge&logo=gmail&logoColor=white" alt="email"/></a>
<a href="https://pubmed.ncbi.nlm.nih.gov/40991854/"><img src="https://img.shields.io/badge/Published-PubMed-326599?style=for-the-badge&logo=pubmed&logoColor=white" alt="pubmed"/></a>

</div>

---

## <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30"> hey, I'm Ronika

I'm an Electrical Engineering student at **Georgia Tech** (4.0 GPA, minoring in CS & AI), and I spend most of my week bouncing between a formal-methods lab, a wet lab, and a pile of side projects. I like problems that sit on a seam: security work living inside ML systems, research that turns into software people actually run, math that has to survive contact with real data.

- 🔭 Right now I'm at **TRUSTML @ Penn** with Prof. Osbert Bastani, proving that AI agents stay inside the permissions they're given.
- 🧫 I also forecast waterborne pathogens with an XGBoost model at **Graham Lab @ GT**, using data I generate by hand in the wet lab.
- 🧠 On the side I build ML from scratch, ship full-stack products, and break things on purpose in a SOC lab.
- 🎓 I TA an intro-CS course, co-founded an education nonprofit, and once co-authored a rugby-research paper. Long story.
- 📫 Reach me at **ronika05m@gmail.com**.

---

## 🔬 Currently focused on — Bastani Lab (TRUSTML @ Penn)

When an LLM agent runs shell commands for you, what stops it from reading a file it was never meant to touch? My research answers that with proofs instead of vibes. I build a pipeline that takes an LLM-written access policy, hands it to a **cvc5 SMT solver** through **AWS Cedar**, and checks by formal equivalence whether the agent stays least-privilege across 89 TerminalBench tasks.

<div align="center">
  <img src="https://raw.githubusercontent.com/rmedagam06/rmedagam06/main/assets/bastani-pipeline.svg" width="90%" alt="Bastani Lab formal verification pipeline"/>
</div>

What I've built there so far:

- Wrote the automated verification pipeline (`cedar-policy-symcc` + cvc5) that scores every generated policy TP / FP / TN / FN against the privileges an agent truly used.
- Analyzed **12,000+ access traces** and tracked down an attribution bug that was misclassifying 9,900+ lines, cutting trace noise by **78%**.
- Wired Cedar policies into the `nono` AI sandbox so CLI agents run under conformal-security guardrails.
- Turned messy non-technical user workflows into structured prompt rules, then wrote the docs and adoption guides so other people could use it.

---

## 🧭 Other directions I'm pulling on

<table>
  <tr>
    <td width="50%" valign="top">

**🛡️ Security engineering**
<br/>Hardened a live mobile-security backend at **Jayson & Williams** (TLS/SSL, AES-256, RBAC, OWASP ZAP testing, SAST in CI). Built a SOC correlation engine and a Linux HIDS that scores threats and fires `iptables` blocks on its own.

  </td>
  <td width="50%" valign="top">

**🧠 ML from the ground up**
<br/>Coded a **latent diffusion model** from scratch in PyTorch (U-Net, CLIP cross-attention, DDIM, LoRA) and a platform that fine-tunes, quantizes, and ranks open-source LLMs by accuracy vs latency vs VRAM.

  </td>
  </tr>
  <tr>
  <td width="50%" valign="top">

**🌐 Full-stack products**
<br/>Shipped **Kirona**, a productivity PWA serving **536 users** with real-time cloud sync, a 6-model AI fallback cascade, and edge functions for timezone-aware push notifications.

  </td>
  <td width="50%" valign="top">

**📈 Quant & applied research**
<br/>Built an exchange matching engine with an Avellaneda-Stoikov market maker, forecast *Legionella* outbreaks with XGBoost, and mined 2,258 abstracts into a **peer-reviewed publication**.

  </td>
  </tr>
</table>

---

## 🧰 Tech I reach for

<div align="center">

**Languages**
<br/>
<img src="https://skillicons.dev/icons?i=python,java,ts,js,c" alt="languages"/>

**AI / ML**
<br/>
<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn" alt="ml"/>
<img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="hf"/>
<img src="https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge&logoColor=white" alt="xgboost"/>
<img src="https://img.shields.io/badge/PEFT%2FLoRA-EE4C2C?style=for-the-badge" alt="peft"/>
<img src="https://img.shields.io/badge/RAG-6f42c1?style=for-the-badge" alt="rag"/>

**Web & Backend**
<br/>
<img src="https://skillicons.dev/icons?i=nextjs,react,tailwind,fastapi" alt="web"/>

**Cloud & DevOps**
<br/>
<img src="https://skillicons.dev/icons?i=aws,docker,git,githubactions,linux" alt="cloud"/>
<img src="https://img.shields.io/badge/AWS%20Bedrock-232F3E?style=for-the-badge&logo=amazonaws&logoColor=FF9900" alt="bedrock"/>
<img src="https://img.shields.io/badge/AWS%20Cedar-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="cedar"/>

**Data & Caching**
<br/>
<img src="https://skillicons.dev/icons?i=postgres,supabase,sqlite,redis,elasticsearch" alt="data"/>

**Security & Detection**
<br/>
<img src="https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white" alt="splunk"/>
<img src="https://img.shields.io/badge/ELK%20Stack-005571?style=for-the-badge&logo=elastic&logoColor=white" alt="elk"/>
<img src="https://img.shields.io/badge/Suricata-EF3B2D?style=for-the-badge" alt="suricata"/>
<img src="https://img.shields.io/badge/Zeek-4B2E83?style=for-the-badge" alt="zeek"/>
<img src="https://img.shields.io/badge/Sigma-1B75BB?style=for-the-badge" alt="sigma"/>
<img src="https://img.shields.io/badge/MITRE%20ATT%26CK-C8102E?style=for-the-badge" alt="mitre"/>
<img src="https://img.shields.io/badge/cvc5%20SMT-2E7D32?style=for-the-badge" alt="cvc5"/>

</div>

---

## 🚀 Featured projects

| Project | What it does | Stack |
|---|---|---|
| **[Kirona](https://github.com/rmedagam06/Kirona)** · [live](https://kirona-five.vercel.app/) | Productivity PWA for 536 users: real-time sync, offline mode, a 6-model AI cascade with prompt-injection filters | `Next.js` `Supabase` `Redis` `Deno` |
| **[wallpaper-diffusion](https://github.com/rmedagam06/wallpaper-diffusion)** | Latent diffusion model built from scratch that turns text into 512×512 images, trained on a 4GB GPU | `PyTorch` |
| **[llm-benchmark](https://github.com/rmedagam06/llm-benchmark)** | Benchmarks open LLMs on MMLU, runs QLoRA sweeps, quantizes to GGUF, and auto-picks the best deploy config | `PEFT/TRL` `llama.cpp` `FastAPI` |
| **[lob-simulator](https://github.com/rmedagam06/lob-simulator)** | Exchange matching engine + Avellaneda-Stoikov market maker, with a live P&L dashboard and 56 tests | `Python` `Streamlit` |
| **[soc-investigation-sim](https://github.com/rmedagam06/soc-investigation-sim)** | Multi-source threat-correlation engine and a red-team kill-chain simulator in Docker | `ELK` `Suricata` `Zeek` |
| **[ids](https://github.com/rmedagam06/ids)** | Real-time Linux intrusion detection off auth logs, with GeoIP scoring and automatic firewall blocks | `Python` `Splunk` `ELK` |
| **[course-planner](https://github.com/rmedagam06/course-planner)** | Topological-sort scheduler that builds minimum-semester graduation plans from a degree map | `Next.js` `TypeScript` |

---

## 📊 By the numbers

<div align="center">
<img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=rmedagam06&theme=tokyonight&hide_border=true" alt="streak"/>


</div>

---

## 🐍 Watch the snake eat my contributions

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/rmedagam06/rmedagam06/output/snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/rmedagam06/rmedagam06/output/snake-light.svg"/>
    <img alt="contribution snake" src="https://raw.githubusercontent.com/rmedagam06/rmedagam06/output/snake-dark.svg"/>
  </picture>
</div>

---

<div align="center">

### Let's build something 🌸

<a href="https://www.linkedin.com/in/ronika-m-259b3b296"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin"/></a>
<a href="https://ronikas-webpage.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-a855f7?style=for-the-badge&logo=vercel&logoColor=white" alt="portfolio"/></a>
<a href="mailto:ronika05m@gmail.com"><img src="https://img.shields.io/badge/Email-ec4899?style=for-the-badge&logo=gmail&logoColor=white" alt="email"/></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:ec4899,50:d946ef,100:a855f7&height=120&section=footer" width="100%" alt="footer"/>

</div>
