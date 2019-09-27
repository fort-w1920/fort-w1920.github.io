
Willkommen zum Kurs. 

-------------------

## Onboarding


Bitte lesen Sie sich **im Vorfeld** das [hier](slides/intro-orga.html){:target="_blank"} durch damit Sie eine Idee davon bekommen was auf Sie zukommt.  

Bitte bereiten Sie sich unbedingt auf den ersten Präsenztermin vor, indem Sie **vor** 17.10.2019, 14:00h:

- einen Github Account anlegen
- Ihre Github Info [hier](https://forms.gle/yDZEg239hjeyEdzt7) eintragen -- sonst kommen Sie nicht an die Übungsaufgaben.
- Ihren privaten Rechner fit machen: [Genaue Instruktionen](ex/setup-ex.html) dafür, und, falls er tragbar ist, diesen dann am besten auch mit vollgeladenem Akku immer mitbringen.

**Vorkenntnisse:**

[Hier](slides/intro-basics.html) steht ein sehr kurzer Überblick zu dem was Sie allermindestens schon gut beherrschen sollten damit Sie geschmeidig in diesen Kurs zu starten können. 

-------------------

##  Woche 1 (11.- 18.10.)

Diese Woche viel zum Lesen / Ansehen, eher wenig zum selbst coden...

**Lesen/Anschauen:**

- Styleguide: [slides](slides/codingstyle-styleguide.html), [video]()

- Defensive Programming:
    - Intro [slides](slides/codingstyle-defensive.html), [video]()
    - `{checkmate}` [slides](slides/codingstyle-defensive-checkmate.html), [video]()
    - Exception Handling [slides](slides/codingstyle-defensive-exceptions.html), [video]()
    - `{testthat}` [slides](slides/codingstyle-defensive-testthat.html), [video]()
- Code Smells: 
    - Intro [slides](slides/codingstyle-smells.html), [video]()
    - Teil 2: Conditional Complexity [slides](slides/codingstyle-smells-conditionalcomplexity.html), [video]()
- Programmentwurf [slides](slides/codingstyle-topdown.html), [video]()

Vorbereitend für die Präsenzzeit am 24.10. bitte unbedingt Section 2 aus diesem Paper lesen:  
Angiulli, 2019: *CFOF: A Concentration Free Measure for Anomaly Detection* [[pdf]](https://arxiv.org/pdf/1901.04992v1.pdf)  
Diesen Algorithmus werden wir gemeinsam im Top-Down-Stil implementieren.

**Machen:**

- Defense: [1](ex/defensive-lag-ex.html), [2](ex/defensive-count-ex.html), [3](ex/defensive-colmeans-ex.html)
- Smells: [1](ex/conditional-complex-swipe-ex.html), 
[2](ex/refactor-dry-ex.html), [3](ex/styleguide-sanierung-ex.html)


S.a. Assignment-Repos.
  
-------------------

##  Woche 2 (19.10. - 25.10.)

Am 24.10. werden wir zusammen einen Entwurf für eine Implementation des
von Angiulli für die Entdeckung von Ausreißern vorgeschlagenen [CFOF-Scores](https://arxiv.org/pdf/1901.04992v1.pdf) entwickeln. Bitte lesen Sie vorbereitend dafür (mindestens) Section 2 aus dem oben verlinkten Paper.

**Lesen/Anschauen:**

Programmentwurf [slides](slides/codingstyle-topdown.html), [video]()

**Machen:**

- CFOF (Demo & gemeinsame Gruppenarbeit am 24.10.)
- [Promillerechner](ex/topdown-promille-ex.html)

S.a. Assignment-Repos.

-------------------

##  Woche 3 (26.10. - 1.11.)

Präsenzzeit am 1.11. entfällt wegen Feiertag.  
Diese Woche entsprechend wieder etwas mehr zum Lesen / Ansehen und eher kürzere Übungen.  

**Lesen/Anschauen:**

- Funktionen
  - Intro [slides](slides/functions-intro.html), [video]()
  - Struktur [slides](slides/functions-structure.html), [video]()
  - Aufrufe [slides](slides/functions-functioncalls.html), [video]()
  - Spezielle Funktionstypen [slides](slides/functions-specialfunctions.html), [video]()
- Environments & Scoping
  - Intro [slides](slides/environments-intro.html), [video]()
  - Funktionsaufrufe [slides](slides/environments-functions-calls.html), [video]()
  - Scoping [slides](slides/environments-scoping.html), [video](), [Lektüre](ex/env-scoping-reading-ex.html)
  
**Machen:**

- [Funktionen](ex/functions-ex.html)
- [Environments](ex/functions-ex.html)

S.a. Assignment-Repos.

-------------------

##  Woche 4 (2.11. - 8.11.)

**Lesen/Anschauen:**

- Debugging
  - Intro [slides](slides/debugging-intro.html), [video]()
  - Workflow [slides](slides/debugging-process.html), [video]()
  - Tools [slides](slides/debugging-tools.html), [video]()
  - Häufige Quellen von Bugs [slides](slides/debugging-frequentmistakes.html), [video]()
- Performance 
  - Profiling [slides](slides/performance-profiling.html), [video]()
  - Effizientes Programmieren [slides](slides/performance-programming.html), [video]()
  - Parallelisierung [slides](slides/performance-parallel.html), [video](), [Lektüre](ex/parallel-reading-ex.html)
  
**Machen:**

- [`slow-sim`](ex/prof-simprofile-ex.html)

S.a. Assignment-Repo.

-------------------

## Woche 5/6 (9.11. - 22.11.)

Übung, Vertiefung, Nachbereitung/Peer Reviews - kein neuer Stoff.

**Machen:**

- Stability Selection: [1](ex/stabsel-reading-ex.html), [2](ex/stabsel-ex.html)
- [RANSAC](ex/topdown-parallel-ransac-ex.html)

S.a. Assignment-Repos

-------------------

## Woche 7/8 (23.11. - 6.12.)

Übung, Vertiefung, Nachbereitung/Peer Reviews - kein neuer Stoff.

**Machen:**

- [Half-Space Mass](ex/topdown-halfspacemass-ex.html)

S.a. Assignment-Repo.

--------------------

### Ende Teil I

<!--

--------------------

## Woche 9/10 (7.12. - 20.12.)

Präsenzzeit am 20.12. entfällt.

**Lesen/Anschauen:**

- `S3`
- `S4`

**Machen:**

- [Half-Space Mass](ex/topdown-halfspacemass-ex.html)

S.a. Assignment-Repos.

-->