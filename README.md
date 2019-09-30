# Fortgeschrittene Programmierung (I & II) Winter 19/20


Willkommen zum Kurs. Es wird großartig!

-------------------

## Onboarding


Bitte lesen Sie sich bereits **im Vorfeld** das [hier](slides/intro-orga.html){:target="_blank"} durch damit Sie eine Idee davon bekommen was auf Sie zukommt.  

Bitte bereiten Sie sich unbedingt auf den ersten Präsenztermin vor, indem Sie **vor** 17.10.2019, 14:00h:

- einen Github Account anlegen
- Ihre Github Info [hier](https://forms.gle/yDZEg239hjeyEdzt7){:target="_blank"} eintragen -- sonst kommen Sie nicht an die Übungsaufgaben.
- Ihren privaten Rechner fit machen: [Genaue Instruktionen](ex/setup-ex.html){:target="_blank"} dafür, und, falls er tragbar ist, diesen dann am besten auch mit vollgeladenem Akku immer mitbringen.

**Vorkenntnisse:**

[Hier](slides/intro-basics.html){:target="_blank"} steht ein sehr kurzer Überblick zu dem was Sie allermindestens schon gut beherrschen sollten damit Sie geschmeidig in diesen Kurs zu starten können. 

**Bemerkung zu den HTML-Slides:**

- Navigation mit den Pfeil-Tasten
- (Mindestens) in Chrome sollten sie sich auch mittels "Print" als PDF abspeichern lassen (am besten in  Querformat, obvs.), für einfachen Offline-Gebrauch. 

-------------------

##  Woche 1 (11.- 18.10.)

Diese Woche viel zum Lesen / Ansehen, relativ wenig zum selber coden...

**Lesen/Anschauen:**

- Styleguide: [slides](slides/codingstyle-styleguide.html){:target="_blank"}  
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/4NK0pHp_aMw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

- Programmentwurf: [slides](slides/codingstyle-topdown.html){:target="_blank"}  
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/6hqgC5mGZVs" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

- Defensive Programming:  
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/videoseries?list=PLMyWaJl2LoXwTRBPnemw_BU-iUgU1j-Cw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    - Intro [slides](slides/codingstyle-defensive.html){:target="_blank"}
    - `{checkmate}` [slides](slides/codingstyle-defensive-checkmate.html){:target="_blank"}
    - Exception Handling [slides](slides/codingstyle-defensive-exceptions.html){:target="_blank"}
    - `{testthat}` [slides](slides/codingstyle-defensive-testthat.html){:target="_blank"}
- Code Smells:  
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/videoseries?list=PLMyWaJl2LoXypsXYQGK9Mn5OrF2MgiSOA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    - Intro [slides](slides/codingstyle-smells.html){:target="_blank"}
    - Conditional Complexity [slides](slides/codingstyle-smells-conditionalcomplexity.html){:target="_blank"}

Vorbereitend für die Präsenzzeit am 24.10. bitte unbedingt Section 2 aus diesem Paper lesen:  
Angiulli, 2019: *CFOF: A Concentration Free Measure for Anomaly Detection* [[pdf]](https://arxiv.org/pdf/1901.04992v1.pdf){:target="_blank"}  
Diesen Algorithmus werden wir gemeinsam im Top-Down-Stil implementieren.

**Machen:**

- Defense: [1](ex/defensive-lag-ex.html){:target="_blank"}, [2](ex/defensive-count-ex.html){:target="_blank"}, [3](ex/defensive-colmeans-ex.html){:target="_blank"}
- Smells: [1](ex/conditional-complex-swipe-ex.html){:target="_blank"}, 
[2](ex/refactor-dry-ex.html){:target="_blank"}, [3](ex/styleguide-sanierung-ex.html){:target="_blank"}


S.a. Assignment-Repos.
  
-------------------

##  Woche 2 (19.10. - 25.10.)

Am 24.10. werden wir zusammen einen Entwurf für eine Implementation des
von Angiulli für die Entdeckung von Ausreißern vorgeschlagenen [CFOF-Scores](https://arxiv.org/pdf/1901.04992v1.pdf){:target="_blank"} entwickeln. Bitte lesen Sie vorbereitend dafür (mindestens) Section 2 aus dem oben verlinkten Paper.  
Eine einfachere Fingerübung ist die Promillerechner-Aufgabe, die Sie unbedingt versuchen sollten selbst zu lösen.

**Lesen/Anschauen:**

Programmentwurf [slides](slides/codingstyle-topdown.html){:target="_blank"}  
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/6hqgC5mGZVs" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

**Machen:**

- CFOF (Demo & gemeinsame Gruppenarbeit am 24.10.)
- [Promillerechner](ex/topdown-promille-ex.html){:target="_blank"}

S.a. Assignment-Repos.

-------------------

##  Woche 3 (26.10. - 1.11.)

Präsenzzeit am 1.11. entfällt wegen Feiertag.  
Diese Woche entsprechend wieder etwas mehr zum Lesen / Ansehen und eher kürzere Übungen.  

**Lesen/Anschauen:**

- Funktionen
  - Intro [slides](slides/functions-intro.html){:target="_blank"}, [video]()
  - Struktur [slides](slides/functions-structure.html){:target="_blank"}, [video]()
  - Aufrufe [slides](slides/functions-functioncalls.html){:target="_blank"}, [video]()
  - Spezielle Funktionstypen [slides](slides/functions-specialfunctions.html){:target="_blank"}, [video]()
- Environments & Scoping
  - Intro [slides](slides/environments-intro.html){:target="_blank"}, [video]()
  - Funktionsaufrufe [slides](slides/environments-functions-calls.html){:target="_blank"}, [video]()
  - Scoping [slides](slides/environments-scoping.html){:target="_blank"}, [video](), [Lektüre](ex/env-scoping-reading-ex.html){:target="_blank"}
  
**Machen:**

- [Funktionen](ex/functions-ex.html){:target="_blank"}
- [Environments](ex/env-ex.html){:target="_blank"}

S.a. Assignment-Repos.

-------------------

##  Woche 4 (2.11. - 8.11.)

**Lesen/Anschauen:**

- Debugging
  - Intro [slides](slides/debugging-intro.html){:target="_blank"}, [video]()
  - Workflow [slides](slides/debugging-process.html){:target="_blank"}, [video]()
  - Tools [slides](slides/debugging-tools.html){:target="_blank"}, [video](), [Lektüre](ex/debug-reading-ex.html)
  - Häufige Quellen von Bugs [slides](slides/debugging-frequentmistakes.html){:target="_blank"}, [video]()
   
- Performance 
  - Profiling [slides](slides/performance-profiling.html){:target="_blank"}, [video]()
  - Effizientes Programmieren [slides](slides/performance-programming.html){:target="_blank"}, [video]()
  - Parallelisierung [slides](slides/performance-parallel.html){:target="_blank"}, [video](), [Lektüre](ex/parallel-reading-ex.html){:target="_blank"}
  
**Machen:**

- Debugging: [1](ex/debug-matcharg-ex.html){:target="_blank"}, [2](ex/debug-rainbowbug-ex.html){:target="_blank"}, [3](ex/debug-rainbowbug-ex.html){:target="_blank"}.  
Beachten Sie auch die Hinweise und Hilfsmittel [hier](ex/debug-reading-ex.html){:target="_blank"}.
- [Performance](ex/prof-simprofile-ex.html){:target="_blank"}


S.a. Assignment-Repos.

-------------------

## Woche 5/6 (9.11. - 22.11.)

Übung, Vertiefung, Nachbereitung/Peer Reviews - kein neuer Stoff.

**Machen:**

- Stability Selection: [1](ex/stabsel-reading-ex.html){:target="_blank"}, [2](ex/stabsel-ex.html){:target="_blank"}
- [RANSAC](ex/topdown-parallel-ransac-ex.html){:target="_blank"}

S.a. Assignment-Repos

-------------------

## Woche 7/8 (23.11. - 6.12.)

Übung, Vertiefung, Nachbereitung/Peer Reviews - kein neuer Stoff.

**Machen:**

- [Half-Space Mass](ex/topdown-halfspacemass-ex.html){:target="_blank"}

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

- [Half-Space Mass](ex/topdown-halfspacemass-ex.html){:target="_blank"}

S.a. Assignment-Repos.

-->