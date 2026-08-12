# Hi, I'm Rami!

## About Me
* **Computer Science** student at The Hebrew University of Jerusalem
* Minor in **Game Design & Development** at Bezalel Academy | Specializing in **Unity** + **C#**
* I build **gameplay and engine systems** — object pooling, event buses, state machines, steering behaviours
* Currently building **Zinnia**, my final game project for the Bezalel minor
* I develop with **AI tooling daily** (Claude Code, MCP) and I'm interested in how far agentic workflows can push game development

## Skills & Tech Stack
* **Languages**: C#, Python, C, C++, Java
* **Game Engines**: Unity (6 / URP), Godot
* **Tools**: Git, Unity, Rider / Visual Studio, Claude Code, MCP
* **Concepts**: Data Structures & Algorithms, OOP, Design Patterns, Procedural Generation, Steering Behaviours, Computer Vision

## Featured Projects

### Zinnia — 3D Swarm Game *(in progress)*
My capstone project for the Bezalel Game Design & Development minor, built with a team.
> **Core mechanics**: a controllable 3D swarm — flocking agents that follow, scatter, and react as one living mass.
> **Architecture**: every steering rule (separation, alignment, cohesion, leader-follow, wander, obstacle-avoidance) is a hot-swappable `ScriptableObject` (Strategy + Composition), so an entire swarm "personality" is composed by dragging assets into a list — no code changes.
> **Performance**: uniform spatial-hash grid for near-O(n) neighbour queries with zero per-frame allocations, scaling from ~100 to 1,000+ agents.
> **Role**: Gameplay & systems programmer — designed and implemented the boid architecture end-to-end using Claude Code.

### One Button Boss *(solo)*
A single-button boss battle built for the Advanced Unity course — a study in clean gameplay architecture.
> **Core mechanics**: a multi-phase boss that escalates through designer-configured health thresholds, each phase running its own attack patterns.
> **Engineering**: generic type-constrained object pooling (`BTNMonoPool<T>` + `IPoolable`), a custom event bus for decoupled systems, coroutine-driven attack patterns behind an abstract Strategy base, and interface-based contracts (`IHealthProvider`, `IProjectile`).
> **Role**: Solo — design, architecture, and implementation.

### Zeninja
A high-octane 2D action-arcade game developed in one week for the Brackeys Game Jam 2025.2.
> **Core mechanics**: slingshot-style charge-and-release movement utilizing screen borders as bouncy walls to slice through incoming enemy waves.
> **Role**: Gameplay Programmer and **top contributor (60 commits)** — architected the enemy system with the Strategy pattern: swappable movement (`IMovementBehavior` — straight-line & sine) and targeting (`ITargetProvider`) behaviours, an interface-based health/damage system, a data-driven multi-spawn-point spawner with escalating difficulty, and an event-driven combo-scoring system.
> [▶️ Play on Itch.io](https://omerelhadad.itch.io/zeninja)

### The Little Helper
A 2D top-down roguelike where you play as a tiny fox gathering recipe ingredients in a hazardous environment.
> **Core mechanics**: procedurally generated house layouts, progression-based upgrade systems, and room-specific enemy variants.
> **Role**: Gameplay Programmer — designed and implemented the procedural map generation algorithm and dynamic item placement systems.
> [▶️ Play on Itch.io](https://danaeck.itch.io/the-little-helper)

### ElseWhere
A narrative-driven 2D puzzle platformer exploring a child's imagination as he overcomes real-world obstacles.
> **Core mechanics**: dual-world puzzle navigation where actions in one dimension alter the environment of the other in real time, featuring seamless world transitions.
> **Role**: Gameplay Programmer — refined 2D physics and character movement, developed real-time cutscene sequencing, and implemented dynamic animation states.
> [▶️ Play on Itch.io](https://danaeck.itch.io/elsewhere)

### Mega Man (1987) — Recreation
My final project for Introduction to Unity, the first course of the Bezalel minor.
> A faithful recreation of the classic NES-era Mega Man: run-and-gun platforming, shooting mechanics, enemy patterns, and level hazards.
> **Role**: Solo — full implementation.

> 🎮 My complete playable portfolio lives on **[itch.io](https://flubbedtulip.itch.io/)**.
> Some projects are coursework hosted in private university organizations — code samples available on request.

## 📫 Let's Connect!
* [Itch.io](https://flubbedtulip.itch.io/)
* [LinkedIn](https://www.linkedin.com/in/rami-hubeishi-2b731a390/)

---
### 📊 GitHub Stats
[![Rami's GitHub Stats](https://github-readme-stats.vercel.app/api?username=FlubbedTulip&show_icons=true&count_private=true&hide_title=true&theme=dark)](https://github.com/FlubbedTulip)
