# EETEPA Mission Control Classroom

Teacher command center for opening playful lessons, managing fictional teams, drawing missions, timing phases, scoring and exporting reports.

> Educational project inspired by EETEPA Vilhena Alves. It is not an official institutional system and does not use real student data.

## Overview

**Code:** L-01  
**Discipline focus:** Transversal Informatics, Networks, and Data Science  
**Format:** Teacher-led classroom web game  
**Suggested duration:** 25 to 35 minutes  
**Public demo:** https://albertomateus9.github.io/eetepa-mission-control-classroom/

This project turns a technical lesson into a guided mission. The teacher creates fictional teams, starts a timer, reveals mission phases, scores evidence and exports a classroom report.

## Classroom Flow

- **Open The Briefing:** Create a team name, choose a role, and explain the first decision in one sentence.
- **Dispatch The Mission:** Pick one mission card, identify the risk, and choose a safe action.
- **Debrief And Score:** Present what worked, what failed, and what should be improved.

## Competencies

- team collaboration
- technical communication
- problem solving
- formative assessment

## Run Locally

Open `index.html` directly or serve the folder:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Data Policy

- Uses synthetic missions and fictional teams only.
- Stores state only in browser `localStorage`.
- Has no login, backend, external API or real student record.

---

# EETEPA Mission Control Classroom

Teacher command center for opening playful lessons, managing fictional teams, drawing missions, timing phases, scoring and exporting reports.

> Projeto educacional inspirado na EETEPA Vilhena Alves. Nao e sistema oficial institucional e nao usa dados reais de estudantes.

## Visao Geral

**Codigo:** L-01  
**Foco disciplinar:** Transversal Informatica, Redes e Ciencia de Dados  
**Formato:** jogo web conduzido pelo professor  
**Tempo sugerido:** 25 a 35 minutos  
**Demo publica:** https://albertomateus9.github.io/eetepa-mission-control-classroom/

Este projeto transforma uma aula tecnica em uma missao guiada. O professor cria equipes ficticias, inicia cronometro, revela fases, pontua evidencias e exporta um relatorio da aula.

## Dinamica De Aula

- **Open The Briefing:** Create a team name, choose a role, and explain the first decision in one sentence.
- **Dispatch The Mission:** Pick one mission card, identify the risk, and choose a safe action.
- **Debrief And Score:** Present what worked, what failed, and what should be improved.

## Competencias

- team collaboration
- technical communication
- problem solving
- formative assessment

## Como Rodar

Abra `index.html` diretamente ou sirva a pasta:

```bash
python -m http.server 8000
```

Depois abra `http://localhost:8000`.

## Politica De Dados

- Usa apenas missoes sinteticas e equipes ficticias.
- Guarda estado apenas no `localStorage` do navegador.
- Nao possui login, backend, API externa ou registro real de estudante.

## License

MIT. See [LICENSE](LICENSE).
