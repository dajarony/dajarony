<div align="center">

<!-- Header animado tipo terminal -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=3500&pause=600&color=2563EB&center=true&vCenter=true&width=600&lines=Hola%2C+soy+dajarony+%F0%9F%91%8B;Arquitecto+de+software;Creador+del+protocolo+SCP;Construyo+frameworks+con+disciplina" alt="Typing animation" />

###  *"No construyo apps. Construyo una forma controlada de construir apps."*

</div>

---

##  Sobre mí

```yaml
nombre:      dajarony
rol:         Arquitecto de software / Framework builder
stack:       Flutter · Dart · Python · TypeScript · C++
filosofia:   "El código tiene que envejecer bien"
obsesion:    Errores tipados · contratos formales · modularidad
metodologia: CMCF · Protocolo Dajarony · SCP
```

---

##  Lo que estoy construyendo

###  **Dajarony Núcleo Flutter**  
Un framework Flutter modular con errores tipados (`Result<T, DajaronyError>`), lifecycle de módulos con `DependencyResolver` topológico, DI propio sin librerías externas, y trazabilidad end-to-end (`TraceId`).

**Lo que lo hace único:**
- **SCP — Screen Contract Protocol**: cada pantalla declara su contrato (módulos, estados, acciones, validaciones). El código obedece al contrato, no improvisa.
- **AGENTS.md + Playbook** para que agentes IA (Claude, Codex, GPT) puedan mantenerlo sin improvisar.
- **Lifecycle explícito**: `discovered → validated → initializing → active → error/inactive`.

> Estado: v0.1.0 validado con una app real (Memory Cards). 50/50 tests verdes.  
> Próximo paso: una segunda app encima para validar el protocolo.

---

##  Tecnologías

<div align="center">

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</div>

---

##  Filosofía de código

<table>
<tr>
<td width="50%">

###  Errores tipados
`Result<T, E>` en lugar de excepciones huérfanas. Cada error sabe qué pasó, dónde, cuándo y por qué.

</td>
<td width="50%">

###  Contratos explícitos
Si una pantalla puede hacer X, el contrato lo declara. Si no, no puede. **No hay magia.**

</td>
</tr>
<tr>
<td>

###  Modularidad de verdad
Cada módulo con su lifecycle, sus dependencias y su salud. Topological sort para que arranquen en orden.

</td>
<td>

###  Hecho para durar
Código que en 5 años sigue legible. Sin dependencias mágicas. Sin "esto funciona, no lo toques".

</td>
</tr>
</table>

---

##  Estadísticas

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=dajarony&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=dajarony&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)

![Streak](https://streak-stats.demolab.com?user=dajarony&theme=tokyonight&hide_border=true)

</div>

---

##  Proyectos destacados

| Proyecto | Tipo | Stack |
|---|---|---|
| **Dajarony Núcleo Flutter** | Framework modular | Flutter · Dart |
| **NeuroRecall Mini** | App de validación del framework | Flutter · Dart |
| **flutter_pelis** | App de películas | Flutter · Dart |
| **qscannv** | Escáner QR nativo | C++ |
| **apppbuses** | API de buses | TypeScript |

---

##  Métricas de calidad que persigo

```
✓ flutter analyze → No issues found
✓ flutter test    → All tests passed
✓ Ningún archivo > 300 líneas
✓ Cero try/catch huérfanos
✓ Cero colores hardcodeados en pantallas
✓ Cada pantalla con SCP declarado
```

---

<div align="center">

###  *"El código que merece la pena escribir es el que merece la pena volver a leer."*

![Visitors](https://visitor-badge.laobi.icu/badge?page_id=dajarony.dajarony&left_color=2563EB&right_color=16A34A)

</div>
