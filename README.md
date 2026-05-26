<div align="center">

<!-- ════════════════════════════════════════════════════════════════ -->
<!--                        HERO CARD                                 -->
<!-- ════════════════════════════════════════════════════════════════ -->

# ⬢ **dajarony**

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=3200&pause=700&color=2563EB&center=true&vCenter=true&width=720&lines=Arquitecto+de+sistemas+gobernados;Creador+del+protocolo+SCP;IA+controlada%2C+no+IA+improvisada;C%C3%B3digo+que+dura.+Dise%C3%B1o+que+escala" alt="Animated headline" />

<br/>

### ❝ *No construyo apps. Construyo una forma controlada de construir apps.* ❞

<br/>

<table>
<tr>
<td align="center" width="20%">
<picture><source srcset="https://img.shields.io/badge/-Tipado_fuerte-1E40AF?style=for-the-badge" /></picture><br/>
🛡️
</td>
<td align="center" width="20%">
<picture><source srcset="https://img.shields.io/badge/-Declarativo-1E40AF?style=for-the-badge" /></picture><br/>
📐
</td>
<td align="center" width="20%">
<picture><source srcset="https://img.shields.io/badge/-Predecible-1E40AF?style=for-the-badge" /></picture><br/>
📋
</td>
<td align="center" width="20%">
<picture><source srcset="https://img.shields.io/badge/-Confiable-1E40AF?style=for-the-badge" /></picture><br/>
🔒
</td>
<td align="center" width="20%">
<picture><source srcset="https://img.shields.io/badge/-Auditable-1E40AF?style=for-the-badge" /></picture><br/>
🧠
</td>
</tr>
<tr>
<td align="center"><b>Tipado fuerte</b></td>
<td align="center"><b>Declarativo</b></td>
<td align="center"><b>Predecible</b></td>
<td align="center"><b>Confiable</b></td>
<td align="center"><b>Auditable</b></td>
</tr>
</table>

</div>

---

<div align="center">

##  El ecosistema Dajarony

*Una sola filosofía aplicada a seis productos:*  
**gobernanza + contratos formales + modularidad + IA controlada**

</div>

<table>
<tr>
<th align="left" width="22%">Proyecto</th>
<th align="left" width="48%">Qué hace</th>
<th align="left" width="20%">Stack</th>
<th align="center" width="10%">Estado</th>
</tr>

<tr>
<td>🛡️ <b>Auralis</b><br/><sub><i>Governance layer</i></sub></td>
<td>Plan · Contract · Approve · Execute · Audit. La capa de gobernanza que falta a los AI agents.</td>
<td><sub>Python · FastAPI · SQLite</sub></td>
<td align="center"><img src="https://img.shields.io/badge/-activo-16A34A?style=flat-square" /></td>
</tr>

<tr>
<td>🤖 <b>Trinidad</b><br/><sub><i>Multi-agent engine</i></sub></td>
<td>Generator · Critic · Evaluator · Coordinator. Consenso configurable (STRICT/WEIGHTED/MAJORITY/ADAPTIVE).</td>
<td><sub>Python · React · Docker</sub></td>
<td align="center"><img src="https://img.shields.io/badge/-activo-16A34A?style=flat-square" /></td>
</tr>

<tr>
<td>💹 <b>Dajarony Trading AI</b><br/><sub><i>Ejecución financiera</i></sub></td>
<td>Trading multi-instrumento. OANDA real. Multi-LLM (Claude · DeepSeek · Qwen · OpenAI). Risk-first.</td>
<td><sub>Python · FastAPI · OANDA</sub></td>
<td align="center"><img src="https://img.shields.io/badge/-activo-16A34A?style=flat-square" /></td>
</tr>

<tr>
<td>🎨 <b>Dajarony Núcleo Flutter</b><br/><sub><i>UI framework</i></sub></td>
<td>Framework Flutter modular con SCP, errores tipados (Result/DajaronyError), lifecycle de módulos y trazabilidad.</td>
<td><sub>Flutter · Dart</sub></td>
<td align="center"><img src="https://img.shields.io/badge/-maduraci%C3%B3n-2563EB?style=flat-square" /></td>
</tr>

<tr>
<td>🌊 <b>Piscinas API</b><br/><sub><i>Cliente vertical IoT</i></sub></td>
<td>SaaS para gestión y monitorización de piscinas. Diagnóstico IA, control de bombas, simulación.</td>
<td><sub>FastAPI · Firebase · Docker</sub></td>
<td align="center"><img src="https://img.shields.io/badge/-vertical-8B5CF6?style=flat-square" /></td>
</tr>

<tr>
<td>🔐 <b>VPN Backend</b><br/><sub><i>Cliente vertical infra</i></sub></td>
<td>VPN empresarial con WireGuard, Firebase Auth, herramientas de seguridad IA. Security audit completo.</td>
<td><sub>Python · WireGuard · Firebase</sub></td>
<td align="center"><img src="https://img.shields.io/badge/-vertical-8B5CF6?style=flat-square" /></td>
</tr>

</table>

---

<div align="center">

##  SCP — Screen Contract Protocol

### ❝ *Cada pantalla declara su verdad.* ❞

</div>

<table>
<tr>
<td align="center" width="20%" valign="top">

###  ❶
### **Pantalla**

<sub>**qué muestra**</sub>

Define la interfaz y los datos que presenta al usuario.

</td>
<td align="center" width="3%"><h2>→</h2></td>
<td align="center" width="20%" valign="top">

###  ❷
### **Estados**

<sub>**qué puede cambiar**</sub>

Modela la información de la pantalla y cómo evoluciona.

</td>
<td align="center" width="3%"><h2>→</h2></td>
<td align="center" width="20%" valign="top">

###  ❸
### **Acciones**

<sub>**qué puede ejecutar**</sub>

Define las intenciones del usuario que disparan cambios.

</td>
<td align="center" width="3%"><h2>→</h2></td>
<td align="center" width="11%" valign="top">

###  ❹
### **Reglas**

<sub>**qué exige**</sub>

Validaciones para que los datos sean válidos.

</td>
</tr>
</table>

<table>
<tr>
<td align="center" valign="top">

###  ❺  **`Result<T, DajaronyError>`** — qué devuelve

Devuelve un resultado tipado: **éxito con datos `T`** o **error controlado** con `TraceId`, severity, módulo de origen y contexto serializable.

</td>
</tr>
</table>

<div align="center">

<table>
<tr>
<td align="center" width="20%">
<sub>**`</>`**</sub><br/>
<b>Tipado total</b><br/>
<sub>Contratos explícitos<br/>sin ambigüedades</sub>
</td>
<td align="center" width="20%">
<sub>🧩</sub><br/>
<b>Reutilizable</b><br/>
<sub>Contratos que se<br/>componen y escalan</sub>
</td>
<td align="center" width="20%">
<sub>🛡️</sub><br/>
<b>Predecible</b><br/>
<sub>Menos sorpresas,<br/>más control</sub>
</td>
<td align="center" width="20%">
<sub>🔬</sub><br/>
<b>Testeable</b><br/>
<sub>Fácil de simular,<br/>fácil de verificar</sub>
</td>
<td align="center" width="20%">
<sub>🧠</sub><br/>
<b>IA integrada</b><br/>
<sub>Convive con IA sin<br/>perder determinismo</sub>
</td>
</tr>
</table>

<br/>

### ❝ *El código obedece al contrato. No improvisa.* ❞

</div>

---

<div align="center">

##  Dajarony Núcleo Flutter

*Framework modular con contratos explícitos*

</div>

<table>
<tr>
<td width="33%" valign="top">

###  Módulos

```
┌──────────────────┐
│  auth_core       │
│  Autenticación   │
├──────────────────┤
│  user_core       │
│  Usuarios        │
├──────────────────┤
│  shop_core       │
│  Catálogo        │
├──────────────────┤
│  analytics_core  │
│  Analítica       │
└──────────────────┘
```

</td>
<td width="33%" valign="top" align="center">

###  Núcleo

🛡️ **SCP**  
*Screen Contract Protocol*

⚠️ **Errores tipados**  
*`Result<T, DajaronyError>`*

🔄 **Lifecycle de módulos**  
*Estados explícitos*

🔗 **Trazabilidad end-to-end**  
*`TraceId` propagado*

</td>
<td width="33%" valign="top">

###  Contratos

```
┌──────────────────┐
│ Screen Contracts │
│ Interfaces       │
├──────────────────┤
│ Typed Errors     │
│ Errores tipados  │
├──────────────────┤
│ Data Contracts   │
│ Estructuras      │
├──────────────────┤
│ Event Contracts  │
│ Eventos          │
└──────────────────┘
```

</td>
</tr>
</table>

<div align="center">

###  Arquitectura modular

```
┌──────────┐    ┌──────┐    ┌───────────┐    ┌──────┐    ┌──────────┐
│ UI Layer │ →  │ Core │ →  │ Contracts │ →  │ Data │ →  │ Services │
└──────────┘    └──────┘    └───────────┘    └──────┘    └──────────┘
```

**Desacoplado · Tipado · Trazable · Escalable**

</div>

<br/>

```dart
// Ejemplo real del núcleo: ejecutar un contrato con error tipado
Result<T, E> execute<T, E>(Contract c) {
  try {
    return Ok(run(c));
  } on DomainError catch (e, st) {
    return Err(e).trace(TraceId.newId(), st);
  }
}
```

---

<div align="center">

##  Capas del ecosistema

</div>

```
┌─────────────────────────────────────────────────────────────────┐
│  CAPA INTELIGENCIA                                              │
│  🛡️  Auralis     →   Governance, contratos, approvals          │
│  🤖  Trinidad    →   Multi-agent engine, consenso              │
├─────────────────────────────────────────────────────────────────┤
│  CAPA VERTICAL                                                  │
│  💹  Trading AI  →   Ejecución financiera con risk control      │
│  🌊  Piscinas    →   IoT/SaaS modular                           │
│  🔐  VPN         →   Infra empresarial con WireGuard            │
├─────────────────────────────────────────────────────────────────┤
│  CAPA CLIENTE                                                   │
│  🎨  Dajarony Flutter  →  UI con SCP, errores tipados           │
└─────────────────────────────────────────────────────────────────┘
```

> Cada capa puede usarse independiente. Las capas se conectan por contratos, nunca por acoplamiento.

---

<div align="center">

##  Filosofía de código

</div>

<table>
<tr>
<td width="50%" valign="top">

###  Errores tipados
`Result<T, E>` en lugar de excepciones huérfanas. Cada error sabe **qué pasó, dónde, cuándo, y por qué**. Trazabilidad con `TraceId` end-to-end.

</td>
<td width="50%" valign="top">

###  Contratos explícitos
Si una pantalla, módulo o agente puede hacer X, **el contrato lo declara**. Si no, no puede. Sin magia. Sin sorpresas.

</td>
</tr>
<tr>
<td valign="top">

###  Modularidad real
Cada módulo con su lifecycle, sus dependencias y su salud. **Topological sort** para arrancar en orden. Health monitor con timeout.

</td>
<td valign="top">

###  Hecho para durar
Código que en 5 años sigue legible. Sin dependencias mágicas. Sin *"esto funciona, no lo toques"*. **Mantenible por humanos y por agentes IA.**

</td>
</tr>
</table>

---

<div align="center">

##  Diseñado para agentes IA

</div>

Todos mis proyectos llevan un `AGENTS.md` con reglas obligatorias para que **Claude, Codex y GPT puedan mantenerlos sin improvisar**.

```yaml
AGENTS.md:    reglas globales, qué hacer y qué NO hacer
STATUS.md:    bitácora de fases, qué hizo cada agente
Playbook:     metodología completa de construcción
```

> **Resultado real:** durante el desarrollo de Dajarony Núcleo Flutter, Codex avanzó **5 fases consecutivas** sin intervención humana entre ellas — leyendo solo el `AGENTS.md`.

---

<div align="center">

##  Stack

<br/>

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
![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)

</div>

---

<div align="center">

##  GitHub stats

<br/>

![Stats](https://github-readme-stats.vercel.app/api?username=dajarony&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=dajarony&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)

![Streak](https://streak-stats.demolab.com?user=dajarony&theme=tokyonight&hide_border=true)

![Trophies](https://github-profile-trophy.vercel.app/?username=dajarony&theme=tokyonight&no-frame=true&row=1&column=7&margin-w=10)

</div>

---

<div align="center">

##  Métricas de calidad que persigo

</div>

```yaml
calidad:
  flutter_analyze:    "No issues found"
  pytest:             "All tests passed"
  flake8_black:       clean
  bandit_safety:      "no vulnerabilities"

disciplina:
  max_file_lines:     300
  tipo_errores:       Result<T, E>
  colores_hardcoded:  0
  try_catch_huerfano: 0
  contratos_scp:      obligatorios

arquitectura:
  modular_por_feature:   yes
  barriles_por_carpeta:  yes
  DI_centralizado:       yes
  lifecycle_explicito:   yes
  trazabilidad:          end-to-end
```

---

<div align="center">

###  ❝ *Cada error tipado cuenta una historia.* ❞
###  ❝ *Cada módulo tiene un propósito.* ❞
###  ❝ *Cada contrato declara la verdad.* ❞
###  ❝ *Código legible hoy, mantenible mañana.* ❞

<br/>

**SCP** · **Screen Contract Protocol** · *Una forma controlada de construir apps*

<br/>

![Visitors](https://visitor-badge.laobi.icu/badge?page_id=dajarony.dajarony&left_color=2563EB&right_color=16A34A&left_text=visitantes)

<br/>

*Código que dura. Diseño que escala.*

</div>
