# VibeCode Solutions

Solo-Werkstatt für KI-gestützte Software-Entwicklung. Eigene Multi-Agent-Architektur, eigene Memory-Disziplin, Vibecoding mit Quality-Engineering. Sitz Bad Harzburg, gegründet 02/2026.

## Was wir aktuell bauen

- **Friday** — Personal AI Orchestrator. Zentrale Konsole, die mehrere parallel laufende Claude-Instanzen (CLI, IDE) steuert. Mailbox-Infrastruktur, Hook-System, Routing. Frühe Phase, im Bau. _Repo privat._
- **NEXUS** — Personal-Todo-OS mit Voice-First-BrainDump, KI-gestützter Sortierung und Cross-Device-Sync (Rust-Core, Tauri-Desktop, Kotlin/Compose-Android). Produktiv lauffähig, mehrere Releases live. _Code bei mir, Nutzung frei._
- **Tracelab** — Plattformübergreifender KI-Debug-Workflow. Sammelt Logs, Crashes und Test-Outputs aus Android/Linux/Windows in eine zentrale SQLite-DB auf NTFS-shared Storage. Claude Code greift via MCP-Server zu — dieselbe Test-Historie, egal aus welchem OS gebootet. _Repo public._
- **XBrain** — KI-Agenten-Memory-System. Multi-Agent-Skill-Crew mit Memory-Hierarchie (Persona → Short-Term → Long-Term → Wissen-Lazy-Load), Pflicht-Outro-Disziplin, Findings-Gate. Echte Rollenarchitektur, kein RAG-Wrapper. _Vault-natives Methodik-Showcase, kein Public-Repo._

## Werkzeugkasten

Rust · Kotlin/Compose · Go · Tauri 2 (Rust + WebView) · Markdown-Vault + Claude-Code-Skills. Sprachen sind austauschbar — die Methodik bleibt: Architektur planen, Findings-Gate vor Merge, Memory-Disziplin pro Agent.

## Skill-Showcase — Sprint-Burst Q1 2026 (abgeschlossen)

Sechs kleine Android- und Tauri-Apps in einem Sprint-Burst gebaut. Repos bleiben öffentlich erreichbar als Übungsstrecken-Beleg, werden aber nicht weiter gepflegt.

- [Pulse-Guard](https://github.com/VibeCodeSolutions/Pulse-Guard) — Lokale Blutdruck-Tracking-App, offline (Kotlin · Compose · Room)
- [Pomodoro-Timer](https://github.com/VibeCodeSolutions/Pomodoro-Timer) — 3-Phasen-Pomodoro-Widget (Tauri v2 · Vanilla JS)
- [colorlens](https://github.com/VibeCodeSolutions/colorlens) — Farb-Picker via CameraX (Kotlin · Compose)
- [netpulse](https://github.com/VibeCodeSolutions/netpulse) — TCP-Ping, Port-Scan, DNS, WiFi-Monitoring (Kotlin · Compose · Vico Charts)
- [sensordash](https://github.com/VibeCodeSolutions/sensordash) — 5-Sensor-Live-Dashboard mit Aufzeichnungs-Service (Kotlin · Compose · Vico Charts)
- [mobile-mouse](https://github.com/VibeCodeSolutions/mobile-mouse) — Wayland-WLAN-Maus per PWA (Python · FastAPI · WebSocket · evdev/uinput)

## Wer hier liest

Auftragsentwicklung ist, woran wir arbeiten. Eigene Werkstücke entstehen parallel aus eigenem Bedarf — manche werden öffentlich, manche bleiben proprietär. Die Repos hier sind das, was sichtbar sein darf.

---

# VibeCode Solutions

Solo workshop for AI-assisted software development. Custom multi-agent architecture, custom memory discipline, vibecoding with quality engineering. Based in Bad Harzburg, founded 02/2026.

## What we're currently building

- **Friday** — Personal AI Orchestrator. A central console that drives multiple parallel Claude instances (CLI, IDE). Mailbox infrastructure, hook system, routing. Early phase, in build. _Repo private._
- **NEXUS** — Personal-Todo-OS with voice-first brain-dump, AI-assisted sorting, and cross-device sync (Rust core, Tauri desktop, Kotlin/Compose Android). Production-running, several releases out. _Code stays with me, free to use._
- **Tracelab** — Cross-platform AI debugging workflow. Aggregates logs, crashes, and test outputs from Android, Linux, and Windows into a single SQLite database on NTFS-shared storage. Claude Code connects via MCP server — same test history, no matter which OS you booted into. _Repo public._
- **XBrain** — AI agent memory system. Multi-agent skill crew with a memory hierarchy (Persona → Short-Term → Long-Term → Knowledge lazy-load), mandatory outro discipline, findings gate. A real role architecture, not a RAG wrapper. _Vault-native methodology showcase, no public repo._

## Toolbox

Rust · Kotlin/Compose · Go · Tauri 2 (Rust + WebView) · Markdown vault + Claude Code skills. Languages are interchangeable — the methodology stays: plan the architecture, findings gate before merge, memory discipline per agent.

## Skill Showcase — Q1 2026 sprint burst (completed)

Six small Android and Tauri apps built in one sprint burst. Repos stay publicly reachable as practice-run evidence; they aren't maintained further.

- [Pulse-Guard](https://github.com/VibeCodeSolutions/Pulse-Guard) — Local offline blood-pressure tracker (Kotlin · Compose · Room)
- [Pomodoro-Timer](https://github.com/VibeCodeSolutions/Pomodoro-Timer) — 3-phase pomodoro widget (Tauri v2 · Vanilla JS)
- [colorlens](https://github.com/VibeCodeSolutions/colorlens) — Color picker via CameraX (Kotlin · Compose)
- [netpulse](https://github.com/VibeCodeSolutions/netpulse) — TCP ping, port scan, DNS, Wi-Fi monitoring (Kotlin · Compose · Vico Charts)
- [sensordash](https://github.com/VibeCodeSolutions/sensordash) — 5-sensor live dashboard with recording service (Kotlin · Compose · Vico Charts)
- [mobile-mouse](https://github.com/VibeCodeSolutions/mobile-mouse) — Wayland Wi-Fi mouse via PWA (Python · FastAPI · WebSocket · evdev/uinput)

## Who's reading this

Client work is what we do. The repos here are workshop output that grew from our own needs — some go public, some stay proprietary. What you see here is what we let you see.
