# Amol Desai

**Android & Kotlin Multiplatform Engineer — AI-augmented development**

Nashik, India · 15+ apps shipped to the Play Store · [LinkedIn](https://www.linkedin.com/in/amoldesai03/)

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

<p>
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white" alt="Kotlin"/>
  <img src="https://img.shields.io/badge/Compose%20Multiplatform-4285F4?style=flat&logo=jetpackcompose&logoColor=white" alt="Compose Multiplatform"/>
  <img src="https://img.shields.io/badge/Jetpack%20Compose-3DDC84?style=flat&logo=jetpackcompose&logoColor=white" alt="Jetpack Compose"/>
  <img src="https://img.shields.io/badge/Ktor-087CFA?style=flat&logo=ktor&logoColor=white" alt="Ktor"/>
  <img src="https://img.shields.io/badge/gRPC%20%2F%20Wire-244B5A?style=flat" alt="gRPC / Wire"/>
  <img src="https://img.shields.io/badge/SQLDelight-03589C?style=flat" alt="SQLDelight"/>
  <img src="https://img.shields.io/badge/Koin-F88909?style=flat" alt="Koin"/>
  <img src="https://img.shields.io/badge/Hilt%20%2F%20Dagger-2196F3?style=flat" alt="Hilt / Dagger"/>
  <img src="https://img.shields.io/badge/Coroutines%20%26%20Flow-7F52FF?style=flat&logo=kotlin&logoColor=white" alt="Coroutines and Flow"/>
  <img src="https://img.shields.io/badge/Room-4CAF50?style=flat" alt="Room"/>
  <img src="https://img.shields.io/badge/Retrofit-48B983?style=flat" alt="Retrofit"/>
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
  <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat&logo=claude&logoColor=white" alt="Claude Code"/>
  <img src="https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white" alt="Flutter"/>
</p>

## Selected work

- [**WeatherApp**](https://github.com/amoldesai03/WeatherApp) — Kotlin Multiplatform app consuming the Open-Meteo API; shared networking and UI across platforms

## Highlights

- Cut app startup time by 30% in high-traffic applications
- Reduced app size by 50% through R8, resource, and dependency optimization
- Migrated legacy codebases (Fragments/XML) to Compose and clean architecture
- Delivered across fintech, banking, education, social, chat, and security domains

---

Open to interesting KMP and AI-in-mobile problems — reach out on [LinkedIn](https://www.linkedin.com/in/amoldesai03/).
