**Table of Content**
- [Plan](#week-1)
- [Voortgang](#week-2)
- [Voortgang part II](#week-3)
- [Afronding](#week-4)

---

# Week 4
## Eind resultaat
## Punten
### Soepel
### Stroef
### Trots
## Inzichten
Wat heb ik geleerd
## Meer
Waar wil ik meer mee gaan doen? Zijn er CSS vaardigheden waar ik sterk(er) in wil worden?


# Week 3
## Progressie in week 3
### Wat ging soepel
### Wat ging tegenstrijdig
### Inzichten CSS-POWER
### Wijzigingen planning
### Nieuwe uitdagingen

# Week 2
## Progressie in week 2
### Wat ging soepel
### Wat ging Stroef
### Inzichten CSS-POWER
### Wijzigingen planning
### Nieuwe uitdagingen

# Week 1
### Welke opdracht
Menu-kaart visualiseren met animaties in een strak ontwerp.
### Welke opties qua uitwerking

#### Contexten
Voor de context wil ik het volgende uitoefenen op het menukaart.
- print-stylesheet  
  - Zodat de gebruiker een statische variant heeft om deze uit te printen.
- prefers-color-scheme  
  - Zodat de menu samenwerkt met de de preferenties van de website.  
  Ook ervoor te zorgen dat dit nog zichtbaar is op high-contrast-mode.

 #### Restricties
Qua restricties wil ik het volgende uitoefenen
- Twee kleuren
  - Met twee kleuren wil ik de website visualiseren. Deze twee kleuren worden naast zwart en wit gebruikt om de visualisatie te versterken.  
  _Zwart en wit zijn officieel geen kleuren maar [tinten](https://www.adobe.com/creativecloud/design/discover/is-black-a-color.html#:~:text=Black%20is%20the%20absence%20of,on%20the%20visible%20light%20spectrum.&text=But%20in%20a%20technical%20sense,colors%2C%20they're%20shades.)_.  - Responsive zonder media queries  
  - Het responsive maken van het menu zonder ```@media only screen and (min-width: 600px)```
    Hiervoor zullen CSS technieken zoals ```grid``` en ```flex``` gebruikt worden.
### CSS technieken
### Grootste uitdagingen
### Schetsen || Breakdown-schets


---
<details>
  <summary>Original Repo Content</summary>
  # CSS to the Rescue @cmda-minor-web 2020 - 2021

Wij vinden het web fascinerend. De laatste jaren is CSS een volwassen en zeer krachtige taal geworden (niet langer een bottleneck - integendeel). Veel van de (nieuwe) **CSS-lekkernijen** worden echter nog niet ten volle benut. Sommige delen van de spec worden onterecht (nog) niet bemind, andere delen zijn zo groot en complex dat we mogelijkheden nog niet hebben doorgrond. Aan jou de  mooie opdracht om de onontgonnen delen van de CSS-wereld in kaart te brengen.

**In dit vierweekse vak ga je experimenteren met (voor jou) nieuwe CSS technieken - om daarna/mee een innovatieve, experimentele én aangename ervaring te creëren - met vanilla CSS en HTML dus (frameworks, preprocessors, libraries en JS zijn niet toegestaan).**

Nb. Het experiment wordt gewaardeerd - zelfs/zeker als het niet (helemaal) lukt. Voel je vrij om verder te gaan dan de CSS-technieken die je al beheerst.

## Dingen om vooraf te doen
- 🔱 **Fork** deze repository
- ✅ [**Enroll** je voor de minor via de courselector](https://icthva.sharepoint.com/sites/courseselector#/CourseSelector/web-design-and-development/2020-2021) (dan kun je je werk straks ook op [DLO](https://dlo.mijnhva.nl/d2l/home/275640) opleveren)
- 🎥 **Camera's aan** tijdens lessen en co (zorg dat je webcam werkt)
- 📒 **Bekijk** het programma en de kennismakingsoefening alvast even

## Opdrachten
Het vak bestaat uit:
- [Een kennismakingsoefening](https://cmda-minor-web.github.io/css-to-the-rescue-2021/oefening.html)
- [De eindopdracht](https://cmda-minor-web.github.io/css-to-the-rescue-2021/index.html)

De [beoordelingscriteria voor de eindopdracht](https://cmda-minor-web.github.io/css-to-the-rescue-2021/beoordelingsformulier.html) op een rijte.

## Programma
Het vak beslaat 4 weken. Bekijk de presentatie met alle details [soon]. 

In Teams vind je de [Excel met de indeling en planning](https://teams.microsoft.com/l/file/6E37FED4-91C7-4293-A7C4-C0309D24634D?tenantId=0907bb1e-21fc-476f-8843-02d09ceb59a7&fileType=xlsx&objectUrl=https%3A%2F%2Ficthva.sharepoint.com%2Fsites%2FFDMCI_EDU__CMD20_21_Minor_Web_5i7j73jt%2FShared%20Documents%2F03%20-%20CSS%20to%20the%20Rescue%2FCSS%20to%20the%20rescue%20-%20Indeling%20%26%20Planning.xlsx&baseUrl=https%3A%2F%2Ficthva.sharepoint.com%2Fsites%2FFDMCI_EDU__CMD20_21_Minor_Web_5i7j73jt&serviceName=teams&threadId=19:84bbb4a3b90d40a6b434649359689744@thread.tacv2&groupId=5d001f9a-0a4b-4768-92b1-0f1768328ba3). 
Daar schrijf je je ook in voor themasessies en het eindgesprek.

Colleges, lessen en gesprekken vinden plaats [in Teams](https://teams.microsoft.com/l/channel/19%3a84bbb4a3b90d40a6b434649359689744%40thread.tacv2/03%2520-%2520CSS%2520to%2520the%2520Rescue?groupId=5d001f9a-0a4b-4768-92b1-0f1768328ba3&tenantId=0907bb1e-21fc-476f-8843-02d09ceb59a7).

## Docenten
- Vasilis van Gemert
- Thijs Spijker
- Sanne 't Hooft
- Leonie Smits

## Learning goals
- _You understand the broader scope of CSS: You can show that CSS can be used for more than just styling web pages._
- ~~_You understand the progressive enhancement parts of CSS: You can show that you can use the cascade, inheritance and specificity in your project_~~
- _You understand the interactive parts of CSS: Is the UX fully enhanced within in given CSS scope?_
- _You have been experimenting: Have the learning goals been stretched?_

[](https://docs.google.com/spreadsheets/d/1Xv48MSiACNmnM6nXpGGUb8mJDC459uSaxJszO_zLEp8/edit?usp=sharing)

## De Selector First CSS & No JS aanpak
Het **eerste uitgangspunt** is dat je *geen* ID's en classes gebruikt. Niet omdat ze niet nuttig zijn, maar om te oefenen met de [vele CSS selectoren](https://css-tricks.com/almanac/) die je tot je beschikking hebt. ID's mag je alleen gebruiken om de :target selector te triggeren. En als het echt echt echt niet anders kan, heb je permissie om een paar classes toe te voegen.

Een **tweede uitgangspunt** is dat je *geen* JS gebruikt (i.i.g. zo min mogelijk - het vak heet niet voor niets CSS to the Rescue). Wat met CSS en/of HTML kan mag je *niet* met JS realiseren en het is *niet* toegestaan om CSS properties met JS aan te passen. We vinden het daarentegen wel interessant dat je verkent waar JS en CSS elkaar raken/versterken, bijv. het [uitlezen en aanpassen van CSS custom properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties), of bijv. de [animationstart](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/animationstart_event), [animationcancel](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/animationcancel_event), [animationiteration](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/animationiteration_event) en [animationend](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/animationend_event) events gebruiken.

</details>
