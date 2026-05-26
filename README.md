<div align="center">

<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- HERO IMAGE — sube tu infografía "dev card" como assets/hero.png -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<img src="assets/hero.png" alt="Dajarony — No construyo apps. Construyo una forma controlada de construir apps." width="100%" />

<br/>

<!-- Animación tipo terminal -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3200&pause=700&color=2563EB&center=true&vCenter=true&width=720&lines=Arquitecto+de+sistemas+gobernados;Creador+del+protocolo+SCP;IA+controlada%2C+no+IA+improvisada;Cada+contrato+declara+la+verdad" alt="Animated headline" />

<br/><br/>

<!-- Pilares de la marca -->
<table>
<tr>
<td align="center">🛡️<br/><b>Tipado fuerte</b></td>
<td align="center">📐<br/><b>Declarativo</b></td>
<td align="center">📋<br/><b>Predecible</b></td>
<td align="center">🔒<br/><b>Confiable</b></td>
<td align="center">🧠<br/><b>Auditable</b></td>
</tr>
</table>

<br/>

### ✨ *"No construyo apps. Construyo una forma controlada de construir apps."*

</div>

---

## 🌐 El ecosistema Dajarony

Una sola filosofía aplicada a seis productos: **gobernanza + contratos formales + modularidad + IA controlada**.

<table>
<tr>
<th align="left">Proyecto</th>
<th align="left">Qué hace</th>
<th align="left">Stack</th>
<th align="center">Estado</th>
</tr>

<tr>
<td><b>🛡️ Auralis</b><br/><sub>Governance layer</sub></td>
<td>Plan · Contract · Approve · Execute · Audit. La capa de gobernanza que falta a los AI agents.</td>
<td>Python · FastAPI · SQLite</td>
<td align="center">🟢 activo</td>
</tr>

<tr>
<td><b>🤖 Trinidad</b><br/><sub>Multi-agent engine</sub></td>
<td>Generator · Critic · Evaluator · Coordinator. Consenso configurable (STRICT/WEIGHTED/MAJORITY/ADAPTIVE).</td>
<td>Python · React · Docker</td>
<td align="center">🟢 activo</td>
</tr>

<tr>
<td><b>💹 Dajarony Trading AI</b><br/><sub>Ejecución financiera</sub></td>
<td>Trading multi-instrumento. OANDA real. Multi-LLM (Claude · DeepSeek · Qwen · OpenAI). Risk-first.</td>
<td>Python · FastAPI · OANDA</td>
<td align="center">🟢 activo</td>
</tr>

<tr>
<td><b>🎨 Dajarony Núcleo Flutter</b><br/><sub>UI framework</sub></td>
<td>Framework Flutter modular con SCP, errores tipados (Result/DajaronyError), lifecycle de módulos y trazabilidad.</td>
<td>Flutter · Dart</td>
<td align="center">🔵 maduración</td>
</tr>

<tr>
<td><b>🌊 Piscinas API</b><br/><sub>Cliente vertical IoT</sub></td>
<td>SaaS para gestión y monitorización de piscinas. Diagnóstico IA, control de bombas, simulación.</td>
<td>FastAPI · Firebase · Docker</td>
<td align="center">🟣 vertical</td>
</tr>

<tr>
<td><b>🔐 VPN Backend Auralis</b><br/><sub>Cliente vertical infra</sub></td>
<td>VPN empresarial con WireGuard, Firebase Auth, herramientas de seguridad IA. Security audit completo.</td>
<td>Python · WireGuard · Firebase</td>
<td align="center">🟣 vertical</td>
</tr>

</table>

> 🟢 activo y abierto · 🔵 en maduración · 🟣 producto vertical de cliente

---

## 📐 SCP — Screen Contract Protocol

<div align="center">

<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- Sube la infografía SCP como assets/scp.png                       -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<img src="assets/scp.png" alt="SCP — Screen Contract Protocol: Pantalla → Estados → Acciones → Validaciones → Result" width="100%" />

### *"Cada pantalla declara su verdad."*

</div>

El **Screen Contract Protocol** es mi aportación al diseño de UI. Cada pantalla declara formalmente qué módulos pide, qué estados acepta, qué acciones permite, qué validaciones impone y qué errores puede devolver.

```
1. Pantalla       →  qué muestra
2. Estados        →  qué puede cambiar
3. Acciones       →  qué puede ejecutar
4. Validaciones   →  qué reglas exige
5. Result<T, E>   →  qué devuelve
```

<div align="center">

> **El código obedece al contrato. No improvisa.**

</div>

---

## 🧱 Dajarony Núcleo Flutter

<div align="center">

<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- Sube la infografía del núcleo Flutter como assets/core.png       -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<img src="assets/core.png" alt="Dajarony Núcleo Flutter — Framework modular con contratos explícitos" width="80%" />

</div>

Framework Flutter modular con **errores tipados end-to-end**, lifecycle de módulos con `DependencyResolver` topológico, DI propio sin librerías externas, EventBus, AuditTrail y HealthMonitor con timeout por módulo.

**Lo que lo hace único:**

- 🎯 **`Result<T, DajaronyError>`** impuesto por contrato — sin excepciones huérfanas.
- 🧩 **`DajaronyModule`** con lifecycle explícito: `discovered → validated → initializing → active → error/inactive`.
- 📜 **SCP en código** — cada pantalla con su contrato formal P1…PN.
- 🤖 **Diseñado para agentes IA** — `AGENTS.md` + Playbook + STATUS.md permiten a Claude, Codex y GPT continuar el trabajo sin improvisar.
- 🩺 **HealthMonitor** con backpressure — un módulo colgado no tumba la app.

---

## 🎯 Capas del ecosistema

```
┌────────────────────────────────────────────────────────────┐
│  CAPA INTELIGENCIA                                          │
│  🛡️ Auralis   →  Governance, contratos, approvals          │
│  🤖 Trinidad  →  Multi-agent engine, consenso              │
├────────────────────────────────────────────────────────────┤
│  CAPA VERTICAL                                              │
│  💹 Trading AI  →  Ejecución financiera con risk control    │
│  🌊 Piscinas    →  IoT/SaaS modular                         │
│  🔐 VPN         →  Infra empresarial con WireGuard          │
├────────────────────────────────────────────────────────────┤
│  CAPA CLIENTE                                               │
│  🎨 Dajarony Flutter  →  UI con SCP, errores tipados        │
└────────────────────────────────────────────────────────────┘
```

Cada capa puede usarse independiente. Las capas se conectan por contratos, nunca por acoplamiento.

---

## 💡 Filosofía de código

<table>
<tr>
<td width="50%" valign="top">

### 🎯 Errores tipados
`Result<T, E>` en lugar de excepciones huérfanas. Cada error sabe **qué pasó, dónde, cuándo, y por qué**. Trazabilidad con `TraceId` end-to-end.

</td>
<td width="50%" valign="top">

### 📋 Contratos explícitos
Si una pantalla, módulo o agente puede hacer X, **el contrato lo declara**. Si no, no puede. Sin magia. Sin sorpresas.

</td>
</tr>
<tr>
<td valign="top">

### 🧩 Modularidad real
Cada módulo con su lifecycle, sus dependencias y su salud. **Topological sort** para arrancar en orden. Health monitor con timeout.

</td>
<td valign="top">

### ⏳ Hecho para durar
Código que en 5 años sigue legible. Sin dependencias mágicas. Sin *"esto funciona, no lo toques"*. **Mantenible por humanos y por agentes IA.**

</td>
</tr>
</table>

---

## 🤖 Diseñado para agentes IA

Todos mis proyectos llevan un `AGENTS.md` con reglas obligatorias para que **Claude, Codex y GPT puedan mantenerlos sin improvisar**.

```
AGENTS.md     →  reglas globales, qué hacer y qué NO hacer
STATUS.md     →  bitácora de fases, qué hizo cada agente
Playbook      →  metodología completa de construcción
```

**Resultado real:** durante el desarrollo de Dajarony Núcleo Flutter, **Codex avanzó 5 fases consecutivas sin intervención humana** entre ellas — leyendo solo el `AGENTS.md`.

---

## 🛠️ Stack

<div align="center">

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=for-the-badge&logo=wireguard&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)

</div>

---

## 📊 GitHub stats

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=dajarony&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=dajarony&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)

![Streak](https://streak-stats.demolab.com?user=dajarony&theme=tokyonight&hide_border=true)

![Trophies](https://github-profile-trophy.vercel.app/?username=dajarony&theme=tokyonight&no-frame=true&row=1&column=7&margin-w=10)

</div>

---

## 🧭 Métricas de calidad que persigo

```yaml
calidad:
  - flutter analyze:    No issues found
  - pytest:             All tests passed
  - flake8 / black:     clean
  - bandit + safety:    no vulnerabilities

disciplina:
  - max_file_lines:     300
  - tipo_errores:       Result<T, E>
  - colores_hardcoded:  0
  - try_catch_huerfano: 0
  - contratos_scp:      obligatorios

arquitectura:
  - modular_por_feature:   sí
  - barriles_por_carpeta:  sí
  - DI_centralizado:       sí
  - lifecycle_explícito:   sí
```

---

<div align="center">

### 🌌 *"Código que dura. Diseño que escala."*

<br/>

**SCP** · **Screen Contract Protocol** · Una forma controlada de construir apps

<br/>

![Visitors](https://visitor-badge.laobi.icu/badge?page_id=dajarony.dajarony&left_color=2563EB&right_color=16A34A&left_text=visitantes)

<br/>

*"Cada error tipado cuenta una historia.*  
*Cada módulo tiene un propósito.*  
*Cada contrato declara la verdad.*  
*Código legible hoy, mantenible mañana."*

</div>
