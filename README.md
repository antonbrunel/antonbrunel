
<h1 align="center">Anton Brunel</h1>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img
      src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=24&pause=1000&color=33B2EA&center=true&vCenter=true&width=820&lines=AI-powered+product+builder;Web+apps+%2B+automation+%2B+UX;Turning+ideas+into+real+products;Shipping+fast+with+AI+tools"
      alt="Typing SVG"
    />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Product-Builder-black?style=for-the-badge" />
  <img src="https://img.shields.io/badge/AI-Assisted%20Development-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Vegan-Low%20Carbon-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Made%20in-France-blue?style=for-the-badge" />
</p>

---





# About

I build **real web products using AI-generated code**, then make them **actually operable** in production.

I can't call myself a developer. I am a **Product Builder**. My value doesn't lie in the lines of code, but in orchestrating intelligence to solve business problems.


<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=react,ts,tailwind,nextjs,vite,nodejs,supabase,postgres,replit,vscode,figma,postman,vercel&perline=13" alt="My Skills" />
  </a>
</p>


• **UX Architecture** | From first scroll to conversion.  
• **Business Funnels** | Turning traffic into leads and revenue.  
• **Data Orchestration** | Managing flows between UI, AI, and DB.  
• **Automation** | Deleting manual tasks with n8n pipelines.  
• **AI Integration** | Not just a chatbot, but a core feature.  
• **Rapid Iteration** | From idea to live product in days, not months.

🥬 **Carbon offset strategy** : Using a lot of AI... so I’m **vegan to balance my energy karma (not even joking).**

---





# Products Architecture
### How the system actually works

```mermaid
graph TD
    %% Nodes
    User((User / Voice Interface)) --> UI[React 19 / Tailwind]
    UI -- "API Events" --> Edge{Vercel Edge / Deno}
    Edge -- "Prompt / Audio" --> AI[Gemini Live / OpenAI]
    Edge -- "Payload" --> Automation[n8n Workflow]
    Automation -- "Store" --> DB[(Supabase / Postgres)]
    Automation -- "External" --> Actions[Stripe / Mail / Webhooks]

    %% Styling
    style UI fill:#33B2EA,stroke:#fff,stroke-width:2px,color:#fff
    style AI fill:#f9f,stroke:#fff,stroke-width:2px
    style DB fill:#3ecf8e,stroke:#fff,stroke-width:2px,color:#fff
    style Automation fill:#ff6d5a,stroke:#fff,stroke-width:2px,color:#fff

```

---





# Operating Infrastructure

Building is only 50% of the job. I ensure the product is **live, scalable, and monitored.**

| Layer | Provider | Core Role | Ecosystem Status |
| --- | --- | --- | --- |
| **Intelligence** | `Gemini / Claude` | Reasoning & Voice Interaction | Optimized & Latency-ready |
| **Logic & Flows** | `n8n / Node.js` | Business Rules & Orchestration | Automated & Error-handled |
| **Database** | `Supabase / RAG` | Real-time Data & RLS Security | Persistent, AI friendly & Secure |
| **Runtime** | `Vercel / Deno` | Serverless Execution | Edge-deployed |
| **PWA / UX** | `Vite / React` | Responsive Interface | Operational |

---





# Stack & Infrastructure

### AI Tools

<p>
<img src="https://img.shields.io/badge/OpenAI-ChatGPT-black?style=for-the-badge&logo=openai"/>
<img src="https://img.shields.io/badge/Google-Gemini-blue?style=for-the-badge&logo=google"/>
<img src="https://img.shields.io/badge/Anthropic-Claude-orange?style=for-the-badge"/>
<img src="https://img.shields.io/badge/DeepSeek-AI-purple?style=for-the-badge"/>
<img src="https://img.shields.io/badge/OpenAI-Codex-black?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Windsurf-AI-blue?style=for-the-badge"/>
</p>

---





### Ops & Infrastructure

<p>
<img src="https://img.shields.io/badge/Supabase-Database-green?style=for-the-badge&logo=supabase"/>
<img src="https://img.shields.io/badge/n8n-Automation-orange?style=for-the-badge&logo=n8n"/>
<img src="https://img.shields.io/badge/Vercel-Deployment-black?style=for-the-badge&logo=vercel"/>
<img src="https://img.shields.io/badge/Zeabur-Hosting-blue?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Render-Cloud-purple?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Cloudflare-Edge-orange?style=for-the-badge&logo=cloudflare"/>
<img src="https://img.shields.io/badge/OVH-Infra-blue?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Google%20Cloud-Platform-blue?style=for-the-badge&logo=googlecloud"/>
</p>

---





# Tech Stack Details

### Frontend Engineering

* **Core:** React 18/19, TypeScript, Vite, SPA architecture.
* **UI System:** Tailwind CSS, shadcn/ui, Radix UI, Framer Motion.
* **State & Data:** TanStack React Query, Context API, Zod validation, React Hook Form.

### AI & Voice Integration

* **Engines:** Gemini Live API (real-time voice streaming), OpenAI APIs, Claude.
* **Architecture:** Prompt engineering, AI guardrails, Contextual interaction design.
* **Audio:** Web Audio API, PCM processing, AudioContext.

### Robustness & Edge Features

* **PWA:** Service workers and offline-ready flows.
* **Resilience:** Local persistence, session recovery, and no-data-loss logic.
* **Real-time UX:** Silent reconnection and state synchronization.
* **Mobile:** Memory-safe image processing and low-friction mobile flows.

---





### GitHub Velocity
<p align="left">
  <img src="https://img.shields.io/badge/2025_Contributions-3%2C318-33B2EA?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Activity-Very High-7C3AED?style=for-the-badge" />
</p>

> **Continuous Iteration** | High-velocity building across private production environments and AI-integrated systems.

---





# Featured Projects

<table border="0">
  <tr>
    <td width="33%" valign="top">
      <h3>Resultats.stepupfactory.fr</h3>
      <p><b>Transformation Studio and Gallery</b></p>
      <p><i>Visual proof engine for fitness results.</i></p>
      <ul>
        <li>Before/After editor</li>
        <li>Lead generation funnel</li>
        <li>Mobile image pipeline</li>
      </ul>
      <a href="https://resultats.stepupfactory.fr">Visit Project</a>
    </td>
    <td width="33%" valign="top">
      <h3>Bilan.stepupfactory.fr</h3>
      <p><b>Booking System</b></p>
      <p><i>Live booking fully personalisable by the coach.</i></p>
      <ul>
        <li>Ultra efficient automated funnel</li>
        <li>n8n orchestration</li>
        <li>Custom slug system</li>
      </ul>
      <a href="https://bilan.stepupfactory.fr">Visit Project</a>
    </td>
<td width="33%" valign="top">
  <h3>D’Artgil Café</h3>
  <p><b>Voice Assistant</b></p>
  <p><i>Real-time voice AI for local business.</i></p>
  <ul>
    <li>Bidirectional streaming</li>
    <li>Gemini Live API</li>
    <li>Instant FAQ & Booking</li>
  </ul>
  <a href="https://wa.me/33783005392?text=Hey%20Anton!%20I%20just%20saw%20D'Artgil%20Café%20on%20your%20GitHub.%20I'd%20love%20to%20get%20access%20to%20the%20demo%20and%20chat%20about%20it!">Request demo access</a>
</td>
  </tr>
  <tr>
    <td width="33%" valign="top">
      <h3>Sudoku Multiplayer</h3>
      <p><b>Real-time Game</b></p>
      <p><i>Collaborative experience with sync recovery.</i></p>
      <ul>
        <li>Unique Cooperative & Versus modes</li>
        <li>Actually enjoyable design</li>
        <li>Live and State persistence</li>
      </ul>
      <a href="https://sudoku-together-36386059600.us-west1.run.app">Play Now</a>
    </td>
    <td width="33%" valign="top">
      <h3>QSE Brunel</h3>
      <p><b>Industrial Training</b></p>
      <p><i>Immersive platform used as a teaching tool for professionals and students.</i></p>
      <ul>
        <li>Deeply personalized scenario generation</li>
        <li>Investigation engine</li>
        <li>Performance analytics & feedback</li>
      </ul>
      <a href="https://qse.antton-brunel.com">Visit Project</a>
    </td>
    <td width="33%" valign="middle" align="center">
  <p><b>Next Project?</b></p>
  <p>Could be yours.</p>
  <a href="https://wa.me/33783005392?text=Hi%20Anton!%20I'm%20reaching%20out%20from%20your%20GitHub.%20I%20have%20a%20project%20idea%20and%20I'd%20love%20to%20discuss%20how%20we%20could%20build%20it%20together.">Get in touch</a>
  <br>
  <small><i>I would love to hear about your vision.</i></small>
</td>
  </tr>
</table>
<p align="center">
  <a href="https://portfolio.antton-brunel.com">
    <img src="https://img.shields.io/badge/Portfolio-Explore%20Work-33B2EA?style=for-the-badge&logo=react&logoColor=white"/>
  </a>
  
  <a href="https://projects.antton-brunel.com">
    <img src="https://img.shields.io/badge/All%20Projects-Live%20Demos-7C3AED?style=for-the-badge&logo=vercel&logoColor=white"/>
  </a>
</p>

---





# Capabilities

### Product

• Idea to product architecture

• Conversion funnels

• UX design

• Business logic

### Engineering Orchestration

• AI-generated code into maintainable modules

• Automation workflows (n8n)

• Infrastructure deployment

• Data pipelines

### AI Integration

• Prompt engineering and system constraints

• Conversational systems (text + voice)

• Guardrails and safe UX

---





# Philosophy

**Speed > perfection :** Build fast

Ship real things

Learn from usage

---





# Connect

<p>
  <a href="https://github.com/antonbrunel">
    <img src="https://img.shields.io/badge/GitHub-antonbrunel-black?style=for-the-badge&logo=github"/>
  </a>
  <a href="https://wa.me/33783005392?text=Hi%20Anton!%20I'm%20coming%20from%20your%20GitHub%20profile.%20I'd%20love%20to%20discuss%20a%20project%20with%20you.">
    <img src="https://img.shields.io/badge/WhatsApp-Contact%20Me-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/>
  </a>
</p>

---

If you have a project involving AI in mind, feel free to reach out or follow the repository.

And before leaving, enjoy a bit more lettuce 🥬🥬🥬
