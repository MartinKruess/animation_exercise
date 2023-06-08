# Kleine Übungen zum Thema Animation

<video src="preview/Animationen_sind_toll!.mp4" controls title="Title"></video>

## Aufgaben

Beim nachbauen der Seite sollst du animationen nur mit **transition** anwenden.
Achte darauf semantische Tags zu verwenden (main, section, article) sofern möglich.
Gebe jeder Section eine Höhe von 90vh
Das Ziel dieser ÜPbung ist es dir parktische Anwendungsbeispiele für Animationen zu zeigen.

## Hilfestellung

- jede Animation verwendet ausschließlich transition (property und duration)
- der main container wird zentriert und die sections haben eine Höhe von 90vh
- die inneren Container haben eine feste Höhe von 14rem
- die divs haben eine Breite und Höhe von 10rem


Tip: Die Strecke, die rollende Gegenstände bei einer Umdrehung schaffen ist der Umfang ;)
Dadurch entsteht ein realistischer Effekt (rollt nicht auf der Stelle)

## Toggle Switch

Einen Toggle-Switch zu erstellen besteht aus 4 Schritten.

Schritt 1:
Wir brauchen einen Container, hierfür eignet sich ein Label, da nur dieses eine checkbox ansprechen kann.

Schritt 2:
Wir benötigen einen checkbox, die wir mit display: none unsichtbar machen.

Schritt 3:
Wir benötigen Content, den wir komplett fertig stylen!
Der content conatiner MUSS auf der selben Ebene sein, wie die checkbox!

Schritt 4:
Wir sagen was gescheheben soll, wenn checkbox = checked
Beliebt sind änderungen der display Eigenschaften oder der width/height

```
  <label>
    <input type="checkbox" id="name">
    <p>Anklickbares Element/Überschrift/Icon/:befor/:after</p>
    <ul>
      <li>Content...</li>
    </ul>
  </label>
```

## Schwierigkeitsgrad

- section 1: Roll-Animation - sehr leicht
- section 2: Dekoration - leicht
- section 3: toggle-switch - etwas schwerer

es gibt einen solution branch auf dem ihr nachschauen könnt, falls ihr absolut nicht weiter kommt. Sonst einfach anschreiben und fragen ;)