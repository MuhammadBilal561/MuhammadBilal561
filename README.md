<div align="center">

# Muhammad Bilal

Software engineer building AI-native systems that reason, act, and ship.

<img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&size=20&pause=1200&color=8B5CF6&center=true&vCenter=true&width=600&lines=The+model+proposes.+The+backend+decides.;Ground+truth+beats+confident+generation." alt="tagline" />

<a href="https://www.mohammadbilal.me/"><img src="https://skillicons.dev/icons?i=chrome" height="32"/></a>&nbsp;
<a href="https://www.linkedin.com/in/muhammadbilal561"><img src="https://skillicons.dev/icons?i=linkedin" height="32"/></a>&nbsp;
<a href="https://github.com/MuhammadBilal561"><img src="https://skillicons.dev/icons?i=github" height="32"/></a>&nbsp;
<a href="mailto:bilalrehan013@gmail.com"><img src="https://skillicons.dev/icons?i=gmail" height="32"/></a>

![Profile Views](https://komarev.com/ghpvc/?username=MuhammadBilal561&style=flat-square&color=8B5CF6&label=Profile+Views)

</div>

---

## The pattern behind everything I build

```mermaid
%%{init: {'theme':'base', 'themeVariables': {'primaryColor':'#1a1a2e','primaryTextColor':'#e2e8f0','primaryBorderColor':'#8b5cf6','lineColor':'#8b5cf6','background':'#0d1117'}}}%%
flowchart LR
    A(["🧠 LLM"]) -->|proposes an action| B{"🛡️ Backend validator"}
    B -->|permitted & within limits| C[("⚙️ Execute")]
    B -->|rejected| D["↩️ Explain why, no side effect"]
```

I don't trust a model with unrestricted access to a real system. Every project below is that same rule, applied to a different domain.

```mermaid
%%{init: {'theme':'base', 'themeVariables': {'primaryColor':'#1a1a2e','primaryTextColor':'#e2e8f0','primaryBorderColor':'#8b5cf6','lineColor':'#8b5cf6','background':'#0d1117'}}}%%
flowchart TD
    P(["propose → validate → execute"])
    P --> R["🏢 RelayOS — books a real calendar appointment"]
    P --> Bi["📄 Bidently — drafts a proposal grounded in real history"]
    P --> T["📈 TradeMind — executes a real paper trade"]
    P --> S["🧩 SocratIQ — reveals an answer only after a real mastery gate"]
```

`PLANTEA` sits underneath all of it — the full-stack foundation (auth, roles, data, mobile) the pattern above is built on top of.

---

## Projects

| | Problem | Boundary that makes it real, not a demo |
|---|---|---|
| **[RelayOS](https://github.com/MuhammadBilal561/RelayOS)** | Businesses lose leads because nobody replies fast enough | Every booking runs through a server-validated function — the AI can't touch the calendar directly |
| **[Bidently](https://github.com/MuhammadBilal561/Bidently)** | Tender responses take days and are easy to get wrong | Proposal drafts are grounded in the org's own past submissions, not generated from nothing |
| **[TradeMind](https://github.com/MuhammadBilal561/TradeMind)** | "Let the AI trade for me" is usually reckless | Risk checks sit between the agent's decision and the actual order — paper markets only |
| **[SocratIQ](https://github.com/MuhammadBilal561/SocratIQ)** | AI tutoring usually just gives the answer away | The solution is withheld until you've actually attempted it |
| **[PLANTEA](https://github.com/MuhammadBilal561/PLANTEA)** | Full-stack mobile marketplace, three real user roles | Buyers, sellers, and delivery riders — not a single-user CRUD demo |

### A closer look — RelayOS

```mermaid
%%{init: {'theme':'base', 'themeVariables': {'primaryColor':'#1a1a2e','primaryTextColor':'#e2e8f0','primaryBorderColor':'#8b5cf6','lineColor':'#8b5cf6','background':'#0d1117'}}}%%
flowchart LR
    U["💬 Customer message"] --> K["📚 Knowledge retrieval"]
    K --> Q["🎯 Lead qualification"]
    Q --> V{"🛡️ Calendar validator"}
    V -->|slot free, rules pass| B["📅 Real booking"]
    V -->|conflict or policy fail| H["🙋 Human handoff"]
    B --> H2["🙋 Confirmed handoff"]
```

---

## Stack

<div align="center">

![](https://skillicons.dev/icons?i=ts,js,react,nextjs,tailwind,nodejs,express,postgres,mongodb,mysql,supabase,sqlite,py,cpp,cs,git,github,docker,linux,vercel&perline=10)

</div>

**AI layer** — `LLM function-calling` `RAG` `pgvector` `Vector search` `Agentic workflows`
**Also using** — `React Native` `Drizzle` `CI/CD`
**Exploring next** — `Go` `Kubernetes` `GPU scheduling`

---

## Activity

<div align="center">

![Followers](https://img.shields.io/github/followers/MuhammadBilal561?style=flat-square&color=8B5CF6&label=Followers&logo=github&logoColor=white) ![Public Repos](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2FMuhammadBilal561&label=Repos&query=%24.public_repos&color=8B5CF6&style=flat-square)

<img src="https://github-readme-stats.vercel.app/api?username=MuhammadBilal561&show_icons=true&hide_border=true&bg_color=0D1117&title_color=8B5CF6&icon_color=8B5CF6&text_color=C9D1D9&cache_seconds=1800" height="165"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=MuhammadBilal561&hide_border=true&background=0D1117&ring=8B5CF6&fire=8B5CF6&currStreakLabel=8B5CF6&disable_animations=true" height="165"/>

</div>

---

<div align="center">

**build → validate → ship**

Open to internships & collaboration — [email](mailto:bilalrehan013@gmail.com) · [LinkedIn](https://www.linkedin.com/in/muhammadbilal561)

</div>
