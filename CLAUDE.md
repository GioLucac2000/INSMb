# CLAUDE.md — INSMb studie-repository

Dit is geen softwareproject. Het is een **studie-repository** voor het vak
Internationaal Strategisch Management (INSMb, Hogeschool Tio).

## Standaardgedrag

- Antwoord in het **Nederlands**. Engelse vaktermen mogen, mits uitgelegd.
- **Max 3 zinnen per alinea**, bullets waar mogelijk, kernbegrippen **vet**.
- Geen jargon zonder uitleg. Analogieën boven abstracte definities.
- Eindig met **één concrete volgende stap**, nooit met een lijst opties.

## Bij studievragen

Gebruik de agent `insmb-tutor` (`.claude/agents/insmb-tutor.md`) voor uitleg,
overhoren, flashcards en case-analyses. Die bevat het volledige lesprotocol.

## Bestandsconventies

- Theorie: `01-theorie/frameworks/<model>.md`, altijd dit stramien:
  `Wat is het` → `Analogie` → `De onderdelen` → `Voorbeeld` → `Checkvragen` → `Valkuilen`.
- Flashcards: `04-toets/flashcards.md`, formaat `- **V:** ... / **A:** ...`.
- Oefenvragen: `04-toets/oefenvragen.md`, antwoorden onderaan in een aparte sectie.
- Cases en colleges: kopieer het bijbehorende `TEMPLATE-*.md`, hernoem, vul in.

## Niet doen

- Geen bestaande aantekeningen herschrijven of "opschonen" zonder te vragen.
- Geen samenvattingen van 3 pagina's — dat werkt averechts bij dyslexie.
- Geen antwoord meteen weggeven bij een overhoring; eerst een hint.

## De praktijkopdracht

De hoofdmoot van dit vak is de praktijkopdracht: een strategisch adviesrapport over één
internationaal bedrijf, plus pitch deck en een individueel competentie-interview van 25 minuten.

- Gebruik daarvoor de agent `insmb-opdracht` (`.claude/agents/insmb-opdracht.md`).
- Lees altijd eerst `00-opdracht/README.md`, `00-opdracht/deliverables-per-week.md` en
  `00-opdracht/bedrijfsdossier.md`.
- **Nooit cijfers verzinnen.** Elk getal krijgt een bron of het label `[AANNAME]` met onderbouwing
  en gevoeligheid. Onbekend en niet op te zoeken → `>> NAVRAAG:` erbij en doorgaan.
- Elk onderdeel eindigt met een **verdedigingsblok** voor het interview.
