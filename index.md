---
layout: default
---


# Bewegende beelden coderen

Betreed de wereld van creatieve code en verleg de grenzen van je verbeelding met Hydra, een live codeer omgeving gemaakt om creatief te zijn met bewegende beelden. Maak je eigen visuele werken door je webcam, kleuren, vormen en nog veel meer samen te mixen tot een kunstwerk met eindeloze mogelijkheden.

Je hebt helemaal geen codeer ervaring nodig om ermee te beginnen. Beelden coderen met Hydra is toegankelijk voor iedereen en helemaal gratis te gebruiken rechtstreeks in je browser.

### De Basis

- Ga naar [hydra.ojack.xyz](http://hydra.ojack.xyz) in je internet browser
- Druk op de prullenbak rechtsboven om met een lege pagina te beginnen
- Je code begint altijd met een bron (zie voorbeelden verderop)
- Daarna kan je de bron vervormen met transformaties, deze beginnen altijd met een punt
- Transformaties en bronnen kunnen totaal verschillende resultaten geven afhankelijk van welke cijfers je gebruikt voor de waarden tussen de haakjes
- Onderaan je code moet je altijd een einde toevoegen *.out()*
- Om je code te activeren druk je op *ctrl+shift+enter*
- Aarzel niet om te experimenteren!

```jsx
osc(10,0.1,0.5)
.color(1,0.895,0.55)
.out()
```

Probeer het voorbeeld uit en wijzig de nummers om te kijken wat er gebeurd. Vergeet niet de code te activeren met *ctrl+shift+enter* 

Vervolgens kun je kijken wat er gebeurd als je andere transformaties toevoegt of de bron veranderd.

### Error

Wat te controleren als je code niet werkt

- Heb je typfouten gemaakt?
- Begint je code met een bron?
- lege regels? zorg dat de code aansluit
- Beginnen al je transformaties een punt?
- Heb je .out() op het einde hebt staan?
- Als het beeld is vastgelopen nadat je de code hebt geactiveerd; kopieer jouw code door alles te selecteren, *ctrl-C*, en ververs dan de browser. Klik op de prullenbak om  alles te verwijderen, plak je eigen code door *ctrl-V*  


### Bronnen

Hieronder staan een paar bronnen en transformaties om je op weg te helpen. De volledige lijst is in het engels te vinden op [hydra.ojack.xyz/functions/](https://hydra.ojack.xyz/functions/)


`osc()`
`gradient()`
`voronoi()`
`noise()`
`shape()`
`solid()`

### Transformaties

`rotate()`
`pixelate()`
`kaleid()`
`scroll()`
`scale()`