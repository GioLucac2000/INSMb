# INSMb — Internationaal Strategisch Management

Studie-repository voor het vak **INSMb** (Hogeschool Tio, IBM jaar 2).
Alles op één plek: theorie, colleges, cases, oefenvragen en planning.

## Snel starten

| Ik wil...                        | Ga naar                              |
| -------------------------------- | ------------------------------------ |
| Een model snappen                | `01-theorie/frameworks/`             |
| Collegeaantekeningen maken       | `02-colleges/TEMPLATE-college.md`    |
| Een case uitwerken               | `03-cases/TEMPLATE-case.md`          |
| Mezelf overhoren                 | `04-toets/flashcards.md`             |
| Oefenen op tentamenniveau        | `04-toets/oefenvragen.md`            |
| Blackout in de toets             | `04-toets/blackout-noodplan.md`      |
| Weten wat ik vandaag moet doen   | `05-planning/studieplan.md`          |

## De Claude-agent

In `.claude/agents/insmb-tutor.md` staat een studiecoach-agent. Die is ingesteld op:

- **korte, gebulletpointe antwoorden** (geen muren tekst)
- **actieve recall** — hij overhoort je in plaats van uit te leggen en door te gaan
- **blackout-protocol** voor als je vastloopt in een toets
- **één concrete stap 1** in plaats van een eindeloos plan

Gebruik in Claude Code:

```
> gebruik de insmb-tutor agent: leg VRIO uit en overhoor me daarna
```

## Structuur

```
01-theorie/frameworks/   één bestand per model (PESTEL, Porter, VRIO, ...)
02-colleges/             aantekeningen per week
03-cases/                uitgewerkte casussen
04-toets/                flashcards, oefenvragen, noodplan
05-planning/             studieplan rond gym/werk/school
```

## Werkafspraken met mezelf

- **Na elk college**: binnen 24 uur 5 flashcards toevoegen. Meer niet.
- **Nooit herlezen** — altijd overhoren.
- **Klaar > perfect.** Een half ingevuld casebestand is beter dan een leeg.
