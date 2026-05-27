## Redactierapport — 2026-05-27-LMS-mockup-BK.html

**Datum redactie:** 2026-05-27

### Taalwijzigingen

| #  | Locatie       | Origineel                                                        | Gecorrigeerd                                                                | Reden |
|:---|:--------------|:-----------------------------------------------------------------|:----------------------------------------------------------------------------|:------|
| 1  | §1, regel 569 | `actuele AI-Wiki signalen`                                       | `actuele AI-Wiki-signalen`                                                  | Zinsstructuur — losse woorden gekoppeld tot één Nederlandse samenstelling |
| 2  | §1, regel 571 | `Allemaal voldoen aan dezelfde QbD-poort.`                       | `Ze voldoen allemaal aan dezelfde QbD-poort.`                               | Zinsstructuur — ontbrekend onderwerp; "Allemaal" alleen kan in publicatietekst niet als subject fungeren |
| 3  | §1, regel 570 | `LOOP dekt het ondergedekte 03 + 06`                             | `LOOP dekt de ondergedekte doelen 03 en 06`                                 | Zinsstructuur — "het ondergedekte" zonder kerwoord is grammaticaal mismatch; "+" is informeel teken |
| 4  | Module MECA, regel 644 | `Lectoraat Logistiek & Alliantiës`                      | `Lectoraat Logistiek & Allianties`                                          | Spelling — trema fout (geen klinkerbotsing op `-ies`); consistent met regel 1051 |
| 5  | Module LOOP, regel 887 | `10-jaars loopbaan­blauwdruk` (soft hyphen U+00AD)      | `10-jaars loopbaanblauwdruk`                                                | Speciaal teken — zachte koppelteken is onbedoeld in lopende tekst |
| 6  | §2, regel 1000 | `Elke module bovenstaand passeert`                              | `Elke bovenstaande module passeert`                                         | Zinsstructuur — bijvoeglijk naamwoord hoort vóór de kerm, niet erachter |
| 7  | §2, regel 1010 | `in het catalogus terecht komt`                                 | `in de catalogus terechtkomt`                                               | Lidwoord — "catalogus" is een de-woord; daarnaast: "terechtkomen" is één werkwoord |
| 8  | §2, regel 1011 | `Geen retro­spectie­f beoordelen` (twee soft hyphens)           | `Geen retrospectief beoordelen`                                             | Speciaal teken — onbedoelde zachte koppeltekens |
| 9  | §2, regel 1026 | `Ontwerp scoort ≥ 7.0 op alle vier motivatie-indicatoren`       | `Ontwerp scoort minimaal 7,0 op alle vier motivatie-indicatoren`           | Speciaal teken — `≥` niet op standaard QWERTY; bovendien decimaalpunt → decimaalkomma |
| 10 | §3, regel 1044 | `levert echte data naar lopende lectoraatsprojecten`            | `levert echte data aan lopende lectoraatsprojecten`                         | Zinsstructuur — "leveren" neemt voorzetsel "aan" voor de begunstigde, niet "naar" |
| 11 | §3, regel 1052 | `strategische renewal van MKB-ketens`                           | `strategische vernieuwing van MKB-ketens`                                   | Anglicisme — Nederlands equivalent "vernieuwing" is volledig gangbaar |
| 12 | §3, regel 1062 | `— bruikbaar bouwsteen voor HR-adviesrapporten`                 | `— bruikbare bouwsteen voor HR-adviesrapporten`                             | Spelling — `bouwsteen` is de-woord, attributief bijvoeglijk naamwoord krijgt -e |
| 13 | 32× in score-elementen | `<div class="score">X.Y</div>` (decimaalpunt)            | `<div class="score">X,Y</div>` (decimaalkomma)                              | Vertaalrest — Engels gebruikt decimaalpunt (8.5), Nederlands gebruikt decimaalkomma (8,5); op een 10-puntsschaal is dit conventie |

**Aantal wijzigingen:** 13 unieke tekstcorrecties + 32 systematische decimaalkomma's = 45 wijzigingen totaal.

**Oordeel:** Kleine tot middelgrote correcties — overwegend kleine puntcorrecties (lidwoord, verbuiging, samenstelling, soft hyphens) en één systematische vertaalrest (decimaalpunten). Geen ingrepen in de stem of inhoud van de tekst.

---

### Structuuranalyse (advies)

Bevindingen tegen het McKinsey Pyramid Principle. Geen wijzigingen aangebracht in de tekst — de auteur beslist of en hoe hij deze observaties verwerkt.

**SCQA-opening:** De hero opent answer-first met de governing thought ("Acht modules, één bedrijfskundig handelingskompas") en zet daarna meteen het ontwerpprincipe neer ("Elke module is ontworpen — niet achteraf gecontroleerd"). Dat is sterke SCQA-discipline: de Situation (modules worden vaak achteraf gecontroleerd) en Complication (audits zijn reactief) blijven impliciet, wat verdedigbaar is voor een UI-landingspagina waar de lezer al weet dat hij in een onderwijscontext zit. De Answer komt vroeg en helder; de Question ("hoe waarborg je kwaliteit zonder reactieve audits?") wordt door de lezer zelf geformuleerd. Geen aandachtspunten.

**Governing thought en supporting arguments:** De governing thought — kwaliteit zit ingebakken in het ontwerp, niet in audits achteraf — wordt herhaaldelijk consistent neergezet (hero, §2-intro, footer). De supporting arguments zijn de **vier QbD-poorten** (HAN-doelen, Leeruitkomsten, Motivatie, Onderzoek). Geen aandachtspunten op het niveau van governing thought zelf. Wél een **navigatie-asymmetrie**: de Anker-balk bovenaan toont slechts drie ankers (HAN-koers, Leeruitkomsten, Motivatie), terwijl §2 vier poorten introduceert. De vierde poort (Onderzoek) komt pas in §3 expliciet als onderzoeksstrip terug. Voor de lezer creëert dit een telmismatch: "drie ankers" boven, "vier poorten" in het midden.

**Horizontale en verticale logica:** De vier QbD-poorten in §2 zijn parallel geformuleerd ("POORT 01 · HAN", "POORT 02 · LEERUITKOMSTEN", etc.) — dat is sterke horizontale logica. De verticale logica klopt: governing thought roept de vraag op "waaraan herken je dat dit ontworpen is?", en de vier poorten beantwoorden precies die vraag.

Er staat één **inhoudelijke inconsistentie** die ik niet als taalkundige fout heb gecorrigeerd omdat de bedoeling onduidelijk is:

- Regel 496 (hero) en regel 507 (meta-chip) zeggen "**Acht** modules" / "8 modules". Regel 1044 (§3-intro) zegt nog steeds "**De zeven** modules sluiten aan op drie HAN-lectoraten". Waarschijnlijk een gemiste update na toevoeging van module LOOP. Als alle acht modules op de drie lectoraten aansluiten: maak er "De acht modules" van. Als één module bewust geëxcludeerd is (OEL4 noemt geen HAN-lectoraat in zijn bronlijn): formuleer als "Zeven van de acht modules sluiten aan op drie HAN-lectoraten; OEL4 verankert in extern onderzoek." 
- Daarnaast: §3 noemt bij "Lectoraat Human Capital Innovations" alleen SKILLSHIFT, terwijl module LOOP (regel 923) óók "Lectoraat Human Capital Innovations" als bronlijn heeft. Aanvulling waarschijnlijk per ongeluk overgeslagen.

**Concrete suggesties:**

- **Voeg een vierde Anker toe aan de bovenste balk** ("ANKER 04 · ONDERZOEK") om de 4 ankers symmetrisch te laten lopen met de 4 QbD-poorten in §2. Alternatief: hernoem §2 expliciet zodanig dat duidelijk wordt dat Onderzoek de "verborgen vierde" is — bijvoorbeeld door §2-intro te openen met "Drie ankers in beeld, plus één: Onderzoek."
- **Harmoniseer "zeven" / "acht" in §3** (regel 1044) met de rest van het document. Bij voorkeur: "De acht modules sluiten aan op drie HAN-lectoraten." 
- **Voeg LOOP toe** aan de Human Capital Innovations-paragraaf in §3 (regel 1062), zodat de mapping module ↔ lectoraat aan beide zijden consistent is.
- **Overweeg in de §1-intro een tweede zin** die de overgang van "vier poorten" naar "drie ankers boven" overbrugt, of update de Anker-balk zoals hierboven. Zonder die brug moet de lezer zelf de telmismatch uitleggen.

**Structureel oordeel:** Volgt het Pyramid Principle herkenbaar — answer-first opening, parallelle supporting arguments, evidence per module in de mod-kaarten. Kleine structurele aandachtspunten: telmismatch tussen drie ankers en vier QbD-poorten, en interne inconsistentie zeven/acht modules + LOOP-attributie.
