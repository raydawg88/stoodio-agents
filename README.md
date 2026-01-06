# Stoodio Agents

Specialized AI agent teams for building products. Each team is structured like a professional agency with a lead orchestrator and domain specialists.

---

## Teams

| Team | Lead | Specialists | Focus |
|------|------|-------------|-------|
| **QA Team** | qa-lead | 17 agents | Testing, quality assurance |
| **UX Team** | ux-lead | 48 agents | Design, research, user experience |
| **Dev Team** | dev-lead | 42 agents | Architecture, implementation, deployment |

---

## QA Team

17 specialized QA agents organized as a professional testing agency.

### Structure

```
qa-lead (orchestrator)
├── Platform Specialists
│   ├── qa-web       (React, Vue, Angular, PWA, cross-browser)
│   ├── qa-ios       (XCUITest, SwiftUI, Universal Links)
│   ├── qa-tvos      (Focus Engine, Siri Remote, 10-foot UI)
│   ├── qa-watchos   (Complications, WatchKit, HealthKit)
│   ├── qa-android   (Espresso, Compose, App Links)
│   └── qa-flutter   (Widget tests, golden testing)
│
├── Infrastructure Specialists
│   ├── qa-api       (REST, GraphQL, gRPC, contract testing)
│   └── qa-backend   (Kafka, RabbitMQ, databases, caching)
│
├── Quality Dimension Specialists
│   ├── qa-security      (OWASP Top 10, auth, injection)
│   ├── qa-performance   (k6, chaos engineering, Core Web Vitals)
│   └── qa-accessibility (WCAG, screen readers, keyboard nav)
│
├── Methodology Specialists
│   ├── qa-exploratory   (Session-based testing, heuristics)
│   └── qa-automation    (Framework design, CI/CD, POM)
│
└── Domain Specialists
    ├── qa-payments   (Stripe, Square, PCI compliance)
    ├── qa-media      (HLS, DASH, DRM, adaptive bitrate)
    └── qa-i18n       (Localization, RTL, Unicode)
```

---

## UX Team

48 legendary designers and researchers working as a world-class design agency.

### Structure

```
ux-lead (orchestrator)
├── Research Specialists (15)
│   ├── don-norman       (Human-centered design, affordances)
│   ├── jakob-nielsen    (Usability heuristics, evaluation)
│   ├── erika-hall       (Efficient research, right questions)
│   ├── jared-spool      (Strategic research, org alignment)
│   ├── indi-young       (Mental models, deep understanding)
│   ├── steve-portigal   (User interviews, story extraction)
│   ├── steve-krug       (Usability testing, simplification)
│   ├── alan-cooper      (Personas, goal-directed design)
│   ├── kim-goodwin      (Scenarios, requirements)
│   ├── whitney-quesenbery (Storytelling, accessibility)
│   ├── leah-buley       (Lean methods, constraints)
│   ├── jan-chipchase    (Field research, global contexts)
│   ├── cyd-harrell      (Civic design, public sector)
│   ├── susan-weinschenk (Behavioral science)
│   └── gregg-bernstein  (Research operations)
│
├── Product & Industrial Designers (10)
│   ├── dieter-rams      (Less but better, functionalism)
│   ├── james-dyson      (Engineering, relentless iteration)
│   ├── charles-ray-eames (Constraint-driven, joy)
│   ├── jony-ive         (Obsessive refinement, Apple)
│   ├── naoto-fukasawa   (Intuitive, invisible design)
│   ├── philippe-starck  (Democratic, playful)
│   ├── marc-newson      (Organic futurism)
│   ├── karim-rashid     (Sensual minimalism)
│   ├── patricia-urquiola (Texture, craft)
│   └── yves-behar       (Purpose, sustainability)
│
├── Brand & Graphic Designers (11)
│   ├── paul-rand        (Timeless logos, visual wit)
│   ├── paula-scher      (Large-scale typography)
│   ├── saul-bass        (Symbolic power, motion)
│   ├── aaron-draplin    (Bold simplicity, Americana)
│   ├── massimo-vignelli (Systematic grids)
│   ├── stefan-sagmeister (Provocative, emotional)
│   ├── milton-glaser    (Conceptual, iconic)
│   ├── jessica-walsh    (Bold color, emotion)
│   ├── michael-bierut   (Strategic identity)
│   ├── herb-lubalin     (Typography as art)
│   └── neville-brody    (Rule-breaking, punk)
│
├── Digital & UI Designers (10)
│   ├── dann-petty       (Bold digital, landing pages)
│   ├── marc-hemeon      (Product strategy at scale)
│   ├── tobias-van-schneider (Premium, immersive)
│   ├── rauno-freiberg   (Motion, performance)
│   ├── pablo-stanley    (Illustration systems)
│   ├── julie-zhuo       (Product at scale)
│   ├── brian-lovin      (Systems thinking)
│   ├── claudio-guglieri (Enterprise with soul)
│   ├── mike-creative-mints (Visual craft)
│   └── david-kelley     (Design thinking)
│
└── Leadership (2)
    └── tina-roth-eisenberg (Joy-driven, community)
```

### Process

1. **Research** - Understand users and problems
2. **Design Philosophy** - Establish principles
3. **Visual Language** - Define the aesthetic
4. **UI Design** - Create the interface
5. **Synthesis** - Compile UX Plan for Dev Team

---

## Dev Team

42 legendary developers who built the languages, frameworks, and infrastructure we use every day.

### Structure

```
dev-lead (orchestrator)
├── Language Creators (11)
│   ├── linus-torvalds   (Linux, Git)
│   ├── dennis-ritchie   (C, Unix)
│   ├── ken-thompson     (Unix, B, Go, UTF-8)
│   ├── bjarne-stroustrup (C++)
│   ├── rob-pike         (Go, Plan 9, UTF-8)
│   ├── anders-hejlsberg (TypeScript, C#, Delphi)
│   ├── chris-lattner    (Swift, LLVM, Clang, Mojo)
│   ├── guido-van-rossum (Python)
│   ├── yukihiro-matsumoto (Ruby)
│   ├── brendan-eich     (JavaScript)
│   └── graydon-hoare    (Rust)
│
├── Framework Creators (9)
│   ├── dhh              (Ruby on Rails)
│   ├── jordan-walke     (React)
│   ├── evan-you         (Vue.js, Vite)
│   ├── rich-harris      (Svelte)
│   ├── guillermo-rauch  (Next.js, Socket.io, Vercel)
│   ├── ryan-dahl        (Node.js, Deno)
│   ├── tj-holowaychuk   (Express, Koa, Mocha)
│   ├── taylor-otwell    (Laravel)
│   └── matt-mullenweg   (WordPress)
│
├── Architecture & Patterns (5)
│   ├── martin-kleppmann (DDIA, distributed systems)
│   ├── martin-fowler    (Refactoring, PEAA)
│   ├── robert-martin    (SOLID, Clean Code)
│   ├── kent-beck        (XP, TDD, JUnit)
│   └── sandi-metz       (POODR)
│
├── React Core (2)
│   ├── dan-abramov      (Redux)
│   └── sebastian-markbage (Hooks, Concurrent Mode)
│
├── Cloud & Infrastructure (3)
│   ├── werner-vogels    (AWS Architecture)
│   ├── urs-holzle       (Google Cloud)
│   └── kelsey-hightower (Kubernetes)
│
├── AI/ML Platforms (6)
│   ├── jeff-dean        (MapReduce, TensorFlow, Transformers)
│   ├── demis-hassabis   (AlphaGo, AlphaFold, Gemini)
│   ├── ilya-sutskever   (AlexNet, GPT)
│   ├── andrej-karpathy  (Tesla Autopilot)
│   ├── chris-olah       (Mechanistic Interpretability)
│   └── dario-amodei     (Constitutional AI, Claude)
│
├── Game & Graphics (2)
│   ├── john-carmack     (id Tech, Doom, Quake)
│   └── tim-sweeney      (Unreal Engine)
│
├── Animation (2)
│   ├── matt-perry       (Framer Motion)
│   └── jack-doyle       (GSAP)
│
└── Performance (2)
    ├── addy-osmani      (DevTools, Lighthouse)
    └── jesse-james-garrett (Ajax, UX architecture)
```

### Process

1. **Architecture** - Design the system
2. **Coding Principles** - Establish standards
3. **Implementation** - Build production code
4. **Review** - Quality gate
5. **Synthesis** - Deliverable ready

---

## Usage

Call a team lead for any project, and they deploy the right specialists:

### Examples

**"Deploy QA team for this iOS payment app"**
→ qa-lead deploys: qa-ios, qa-payments, qa-security, qa-accessibility

**"Deploy UX team for brand identity"**
→ ux-lead deploys: paul-rand, massimo-vignelli, paula-scher, michael-bierut

**"Deploy dev team for React + Node API"**
→ dev-lead deploys: jordan-walke, dan-abramov, ryan-dahl, tj-holowaychuk, martin-kleppmann

---

## Team Workflow

For full product builds, teams work sequentially:

```
UX Team → Dev Team → QA Team
   │          │          │
   │          │          └── Test everything
   │          └── Build to UX spec
   └── Research, design, create UX Plan
```

---

## License

MIT
