# Stoodio Agents

Specialized AI agent teams for building products. Each team is structured like a professional agency with a lead orchestrator and domain specialists.

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

### Usage

Call the QA team for a project, and the lead will deploy the right specialists:

- **Web app**: qa-lead deploys qa-web, qa-accessibility, qa-automation
- **iOS app**: qa-lead deploys qa-ios, qa-accessibility, qa-performance
- **Payment integration**: qa-lead deploys qa-payments, qa-security, qa-api
- **Streaming app**: qa-lead deploys qa-media, qa-performance, qa-ios/qa-android

### Agent Details

| Agent | Focus | Key Expertise |
|-------|-------|---------------|
| qa-lead | Orchestration | Project assessment, team deployment |
| qa-web | Web platforms | React Testing Library, Playwright, visual regression |
| qa-ios | Apple mobile | XCUITest, ViewInspector, Universal Links |
| qa-tvos | Apple TV | Focus Engine, XCUIRemote, Top Shelf |
| qa-watchos | Apple Watch | Complications, WatchKit, health permissions |
| qa-android | Android | Espresso, Compose testing, deep links |
| qa-flutter | Cross-platform | Widget tests, golden testing, platform channels |
| qa-api | API testing | REST, GraphQL, gRPC, Pact contracts |
| qa-backend | Backend systems | Message queues, event-driven, databases |
| qa-security | Security | OWASP, injection, authentication |
| qa-performance | Performance | Load testing, chaos engineering, metrics |
| qa-accessibility | Accessibility | WCAG, screen readers, keyboard |
| qa-exploratory | Manual testing | Session-based, heuristics, bug hunting |
| qa-automation | Test automation | Framework design, CI/CD, stability |
| qa-payments | Payments | Stripe, Square, PCI, subscriptions |
| qa-media | Streaming | HLS, DRM, adaptive bitrate, live |
| qa-i18n | Internationalization | L10n, RTL, Unicode, formatting |

## License

MIT
