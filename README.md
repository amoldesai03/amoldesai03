# Amol Desai

**Android & Kotlin Multiplatform Engineer — AI-augmented development**

Nashik, India · 15+ apps shipped to the Play Store · [LinkedIn](https://www.linkedin.com/in/amol-desai-ba6818196/)

I build production mobile apps with 5+ years of experience, currently focused on **Kotlin Multiplatform** — shipping one codebase to Android, iOS, and Desktop with Compose Multiplatform — and on using **GenAI tooling as a force multiplier** in how I design, build, and test software.

Most of my work lives in private, commercial repositories; the sections below reflect what I work with in production.

## Kotlin Multiplatform

Production-grade KMP architecture, not proof-of-concept work:

- **Compose Multiplatform** UI across Android / iOS / Desktop, with adaptive layouts (compact / medium / expanded form factors; one ViewModel driving multiple screen variants)
- **Multi-module clean architecture**: `core / feature / app` layering, Gradle convention plugins (`build-logic`), and build-time module dependency rules that fail the build on architecture violations
- **Type-safe navigation** behind a library-agnostic `Navigator` abstraction — `@Serializable` routes, centralized deep-link routing with auth guards, designed so a Navigation 2 to Navigation 3 migration touches exactly one adapter file
- **Networking**: Ktor, gRPC over HTTP/2 with Wire-generated protobufs, custom interceptors (auth, token refresh)
- **Persistence**: SQLDelight, multiplatform-settings (FlowSettings), DataStore patterns
- **Dependency injection**: Koin 4 (module-per-feature); Hilt/Dagger on Android-native projects
- **State management**: MVVM with `StateFlow` and sealed view states, one-shot UI event channels
- **Testing & CI**: kotlin.test, Turbine, fakes over mocks, tests shipping in the same change as features; GitHub Actions across desktop, Android, and iOS targets

## GenAI

<!-- EDIT: trim or extend to match exactly what you've done -->

- **Agentic and AI-assisted development**: spec-driven workflows with agentic coding tools (Claude Code) — exploration-first phased plans, verification gates, one-commit-per-phase execution on real codebases
- **LLM API integration**: chat and completion APIs, streaming responses, structured (JSON) outputs, tool/function calling from Kotlin clients
- **Prompt and spec engineering**: system-prompt design, decomposing large refactors into machine-executable specifications

## Toolbox

Kotlin · Compose Multiplatform · Jetpack Compose · Ktor · gRPC / Wire · SQLDelight · Koin · Hilt · Coroutines & Flow · Room · Retrofit · GitHub Actions · Claude Code · Flutter

## Selected work

- [**WeatherApp**](https://github.com/amoldesai03/WeatherApp) — Kotlin Multiplatform app consuming the Open-Meteo API; shared networking and UI across platforms

## Highlights

- Cut app startup time by 30% in high-traffic applications
- Reduced app size by 50% through R8, resource, and dependency optimization
- Migrated legacy codebases (Fragments/XML) to Compose and clean architecture
- Delivered across fintech, banking, education, social, chat, and security domains

---

Open to interesting KMP and AI-in-mobile problems — reach out on [LinkedIn](https://www.linkedin.com/in/amoldesai03).
