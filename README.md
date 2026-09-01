<div align="center">

# Muhammad Bilal

Software engineer building AI-native systems that reason, act, and ship.

<img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&size=20&pause=1200&color=8B5CF6&center=true&vCenter=true&width=560&lines=The+model+proposes.+The+backend+decides." alt="tagline" />

<a href="https://www.mohammadbilal.me/"><img src="https://skillicons.dev/icons?i=chrome" height="32"/></a>&nbsp;
<a href="https://www.linkedin.com/in/muhammadbilal561"><img src="https://skillicons.dev/icons?i=linkedin" height="32"/></a>&nbsp;
<a href="https://github.com/MuhammadBilal561"><img src="https://skillicons.dev/icons?i=github" height="32"/></a>&nbsp;
<a href="mailto:bilalrehan013@gmail.com"><img src="https://skillicons.dev/icons?i=gmail" height="32"/></a>

</div>

---

## The pattern behind everything I build

```mermaid
flowchart LR
    A(["🧠 LLM"]):::model -->|proposes an action| B{"🛡️ Validator"}:::validator
    B -->|approved| C[("⚙️ Execute")]:::go
    B -->|rejected| D["↩️ Explain — no side effect"]:::stop

    classDef model fill:#8B5CF6,stroke:#6D28D9,color:#fff
    classDef validator fill:#1E1B4B,stroke:#8B5CF6,color:#C7D2FE
    classDef go fill:#0D1117,stroke:#8B5CF6,color:#8B5CF6
    classDef stop fill:#0D1117,stroke:#EF4444,color:#EF4444
```

I don't trust a model with unrestricted access to a real system. Every project below is that rule, applied to a different domain.

```mermaid
flowchart TD
    P(["propose → validate → execute"]):::core
    P --> R["🏢 RelayOS — books a real calendar slot"]:::proof
    P --> Bi["📄 Bidently — drafts from real proposal history"]:::proof
    P --> T["📈 TradeMind — executes a real paper trade"]:::proof
    P --> S["🧩 SocratIQ — unlocks an answer only after a real attempt"]:::proof

    classDef core fill:#8B5CF6,stroke:#6D28D9,color:#fff
    classDef proof fill:#0D1117,stroke:#8B5CF6,color:#C9D1D9
```

`PLANTEA` is the full-stack foundation underneath all of it — auth, roles, real data, mobile — the ground the pattern above stands on.

<details>
<summary><strong>Zoom in: how RelayOS actually enforces this, request by request</strong></summary>

```mermaid
sequenceDiagram
    participant V as Visitor
    participant W as Widget
    participant A as Agent (LLM)
    participant Val as Validator
    participant Cal as Google Calendar

    V->>W: "Book me Tuesday at 3pm"
    W->>A: forward message + context
    A->>Val: propose create_booking(slot)
    Val->>Cal: check_availability()
    Cal-->>Val: slot free
    Val->>Cal: create_booking()
    Cal-->>Val: confirmed
    Val-->>A: booking success
    A-->>W: "You're booked for Tuesday 3pm"
    W-->>V: confirmation shown
```

The agent is never allowed to call `create_booking` without a preceding `check_availability` in the same conversation — enforced in the system prompt and verifiable in the logged tool-call history, not just assumed.

</details>

---

## Projects

| | Problem | Boundary that makes it real, not a demo |
|---|---|---|
| **[TradeMind](https://github.com/MuhammadBilal561/TradeMind)** | "Let the AI trade for me" is usually reckless | Strict backend risk checks sit between the agent's decision and the order execution via Alpaca. |
| **[RelayOS](https://github.com/MuhammadBilal561/RelayOS)** | Businesses lose leads because nobody replies fast enough | Every booking runs through a server-validated function — the AI can't touch the calendar directly. |
| **[Bidently](https://github.com/MuhammadBilal561/Bidently)** | Tender responses take days and are easy to get wrong | Drafts are grounded purely in the org's own past submissions via RAG, not generated from nothing. |
| **[SocratIQ](https://github.com/MuhammadBilal561/SocratIQ)** | AI tutoring usually just hands you the answer | The solution stays hidden behind a mastery gate until the user has actually attempted it. |
| **[PLANTEA](https://github.com/MuhammadBilal561/PLANTEA)** | Full-stack mobile marketplace, three real user roles | Buyers, sellers, and delivery riders managing distinct workflows — not a single-user CRUD demo. |

---

## Stack & Current Focus

<div align="center">

![](https://skillicons.dev/icons?i=go,kubernetes,docker,linux,cpp,cs,ts,js,react,nextjs,tailwind,nodejs,express,postgres,mongodb,supabase,sqlite,git,github,vercel)

</div>

**The AI Layer:** `LLM function-calling` · `RAG` · `pgvector` · `Agentic workflows`

> [!NOTE]  
> **Currently focused on High-Concurrency Systems & Cloud-Native Infrastructure:**  
> Building a custom TCP Load Balancer in **Go** to deepen my understanding of network protocols and goroutines, while actively contributing to CNCF open-source projects like `Project-HAMi`.

---

<div align="center">

**build → validate → ship**

Open to internships & collaboration — [Email](mailto:bilalrehan013@gmail.com) · [LinkedIn](https://www.linkedin.com/in/muhammadbilal561)

</div>
