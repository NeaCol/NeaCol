<div align="center">

# NeaCol

**Cybersecurity & AppSec • Native Android Engineering (Kotlin / Compose) • High-Concurrency Distributed Systems • Full-Stack Web**

[![GitHub Followers](https://img.shields.io/github/followers/NeaCol?label=Follow&style=flat-square)](https://github.com/NeaCol)
[![Android Development](https://img.shields.io/badge/Mobile-Android%20%7C%20Kotlin-3DDC84?style=flat-square&logo=android&logoColor=white)](https://developer.android.com)
[![Jetpack Compose](https://img.shields.io/badge/UI-Jetpack%20Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)](https://developer.android.com/jetpack/compose)
[![Kali Linux](https://img.shields.io/badge/OS-Kali%20Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)](https://www.kali.org/)
[![Security Focus](https://img.shields.io/badge/Focus-AppSec%20%7C%20NetSec-critical?style=flat-square&logo=securityscorecard&logoColor=white)](https://github.com/NeaCol)
[![Modrinth](https://img.shields.io/badge/Modrinth-NeaCommand-00AF5C?style=flat-square&logo=modrinth&logoColor=white)](https://modrinth.com/plugin/neacommand)
[![Email](https://img.shields.io/badge/Contact-milansanchz%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:milansanchz@gmail.com)

</div>

---

### Tech Stack & Security Tooling

<p align="center">
  <img src="https://skillicons.dev/icons?i=kotlin,androidstudio,java,kali,linux,bash,python,ts,js,react,astro,nodejs,fastapi,postgres,mysql,docker,git&perline=9" alt="Tech Stack" />
</p>

- **Mobile & Native Android Ecosystem:** Kotlin, Android SDK (API 26–35), Jetpack Compose, Material Design 3, Coroutines, Flow, Android Studio, Gradle (Kotlin DSL / KTS), Room DB, Retrofit, Ktor Client, Hilt, Koin, WorkManager.
- **Mobile AppSec & Reverse Engineering:** R8 / ProGuard bytecode obfuscation, Android KeyStore hardware cryptography, Biometric authentication, Root/Jailbreak detection, Certificate Pinning, APK static & dynamic analysis (JADX, APKTool, Frida).
- **Cybersecurity & Network Security:** Kali Linux, Wireshark, Packet Dissection (L2–L7), Vulnerability Assessment, Network Forensics, Defensive Penetration Testing, AppSec Auditing, Stateless JWT Security.
- **Core Languages:** Kotlin, Java (21 LTS / 17), Python (3.10+), TypeScript, JavaScript, SQL, Bash.
- **Server Systems & High Concurrency:** PaperMC, Folia, Purpur, Asynchronous Non-blocking Concurrency, HikariCP Connection Pooling, ProtocolLib, Adventure MiniMessage.
- **Web & Cloud Services:** React, Astro, Node.js, FastAPI, PostgreSQL, Supabase, Docker, RESTful Microservices.

---

### 📱 Android Engineering & Mobile Architecture

Modern, reactive Android app engineering built with Google's Clean Architecture & Modern Android Development (MAD) principles:

- **Declarative UI System:** 100% declarative interfaces built with **Jetpack Compose** and **Material Design 3**, utilizing dynamic theming, custom UI components, smooth physics animations, and strict state hoisting.
- **Clean Architecture & MVI/MVVM:** Robust decoupling across `Presentation`, `Domain`, and `Data` layers with unidirectional data flow (UDF) and Single Source of Truth (SSOT).
- **Reactive Asynchronous Pipelines:** Kotlin **Coroutines** combined with **StateFlow** and **SharedFlow** for seamless, non-blocking asynchronous event dispatching and UI-state binding.
- **Offline-First Persistence & Caching:** Local caching with **Room ORM** and SQLite, reactive preferences with **Jetpack DataStore**, and resilient networking via **Ktor Client** or **Retrofit** with exponential backoff retry interceptors.
- **Dependency Injection & Modularization:** Scalable dependency inversion via **Hilt (Dagger)** or **Koin** supporting multi-module Gradle project architectures (`:feature`, `:core:database`, `:core:network`).
- **Background Orchestration:** Battery-efficient background sync, periodic jobs, and deferrable tasks using **WorkManager** and Foreground Services.
- **Mobile AppSec Hardening:** Secure cryptographic key management via hardware-backed **Android KeyStore**, tamper detection, SSL/TLS Certificate Pinning via OkHttp network security configs, and proactive vulnerability scanning using Kali Linux and bytecode decompilers.

---

### 🛡️ Security & Engineering Philosophy

- **Zero-Trust Input Sanitization:** Protection against format string injections, command injection, and parameter tampering at every client, mobile, and server boundary.
- **Asynchronous Architecture:** Non-blocking thread design, persistent connection pooling, and resilient rate-limiting engines designed for high-concurrency production workloads.
- **Mobile Integrity & Anti-Reverse:** Defensive bytecode shrinking, obfuscation strategies with ProGuard/R8, and cryptographic signing verification to maintain application authenticity.
- **Continuous Defensive Auditing:** Continuous auditing of network traffic, REST endpoints, and protocol packets using Kali Linux toolsets, Wireshark, and automated test suites.

---

### Featured Projects

<table>
  <tr>
    <td width="50%">
      <h3><a href="https://github.com/NeaCol/netscope">NetScope</a></h3>
      <p>Network diagnostic tool and topology visualizer. Packet dissection (L2–L7), RFC-compliant DNS benchmarking, latency/jitter analysis, and local web dashboard.</p>
      <p>
        <img src="https://img.shields.io/badge/Python-3.10%2B-blue?style=flat-square" />
        <img src="https://img.shields.io/badge/Kali%20Linux-Verified-557C94?style=flat-square&logo=kalilinux&logoColor=white" />
        <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" />
      </p>
    </td>
    <td width="50%">
      <h3><a href="https://github.com/NeaCol/NeaCommand">NeaCommand</a></h3>
      <p>Security whitelist and tab-completion filtering engine for Paper & Folia networks. LuckPerms group inheritance, strict namespace quarantine, and audit logging.</p>
      <p>
        <img src="https://img.shields.io/badge/Java-21-orange?style=flat-square" />
        <img src="https://img.shields.io/badge/Paper%20%2F%20Folia-1.20%2B-1e87f0?style=flat-square" />
        <img src="https://img.shields.io/badge/Modrinth-Available-00AF5C?style=flat-square" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3><a href="https://github.com/NeaCol/NeaBans">NeaBans</a></h3>
      <p>Enterprise punishment suite with proxy synchronization (Velocity/Bungee), embedded REST API, JWT stateless auth, and HikariCP connection pooling.</p>
      <p>
        <img src="https://img.shields.io/badge/Java-21-orange?style=flat-square" />
        <img src="https://img.shields.io/badge/AppSec-JWT%20Secured-005571?style=flat-square" />
        <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" />
      </p>
    </td>
    <td width="50%">
      <h3><a href="https://github.com/NeaCol/NeaWelcomer">NeaWelcomer</a></h3>
      <p>High-performance player connection engine for Paper 1.21.1. Anti-injection TagResolver sanitization, async I/O player tracking, and Adventure MiniMessage.</p>
      <p>
        <img src="https://img.shields.io/badge/Java-21-orange?style=flat-square" />
        <img src="https://img.shields.io/badge/Adventure-MiniMessage-brightgreen?style=flat-square" />
        <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3><a href="https://github.com/NeaCol/NeaBows">NeaBows</a></h3>
      <p>Elemental projectile framework and custom weaponry system. 8 elemental disciplines, 3-tiered mechanics, PDC binary metadata serialization, and ray-tracing particles.</p>
      <p>
        <img src="https://img.shields.io/badge/Java-21-orange?style=flat-square" />
        <img src="https://img.shields.io/badge/Bukkit-PDC-red?style=flat-square" />
        <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" />
      </p>
    </td>
    <td width="50%">
      <h3><a href="https://github.com/NeaCol/NeaFutbol">NeaFutbol</a></h3>
      <p>Minigame physics engine for Paper 1.21. Custom ball vectors, entity collision detection, team spawns, and real-time holographic scoreboards.</p>
      <p>
        <img src="https://img.shields.io/badge/Java-17%2F21-orange?style=flat-square" />
        <img src="https://img.shields.io/badge/Minecraft-1.21-1e87f0?style=flat-square" />
        <img src="https://img.shields.io/badge/License-MIT-yellow?style=flat-square" />
      </p>
    </td>
  </tr>
</table>

---

### Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=NeaCol&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=NeaCol&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=NeaCol&theme=tokyonight&hide_border=true" alt="Streak Stats" />
</div>
