# Hörtexte für „Das Geheimnis des Super-Completo“

Die MP3-Dateien gehören in diesen Ordner (`audio/`). Das Spiel findet sie über den Dateinamen.
Solange eine Datei fehlt, liest die Computerstimme des Chromebooks den Text vor.
Ob die Dateien gefunden werden, zeigt die Lehrerseite: `super-completo.html#lehrer`.

| Niveau | Dateiname | Länge (ca.) | Sprechtempo |
|---|---|---|---|
| A2 | `completo-a2.mp3` | 60–75 s | langsam und deutlich |
| B1 | `completo-b1.mp3` | 80–100 s | normal |

## Einstellungen in ElevenLabs

- **Modell:** *Eleven Multilingual v2*. Damit klingen die spanischen Wörter (*¡Hola, chiquillos!*, *Tía*, *Vienesas*, *Paltas*) spanisch und der Rest deutsch.
- **Stimme:** warm, eher älter, weiblich. Tía Carmen ist eine herzliche Köchin aus Valparaíso. Ein leichter spanischer Akzent passt gut, die Stimme sollte aber gut verständlich bleiben.
- **Stability:** ca. 50 %. Bei A2 eher höher (60 %), damit die Stimme ruhig bleibt.
- **Speed:** A2 etwa 0,85–0,9 · B1 etwa 1,0.
- **Pausen:** Leerzeilen im Skript sind Absätze. Wenn die Stimme zu schnell weiterspricht, nach dem Absatz `<break time="1s" />` einfügen.
- **Export:** MP3, 44,1 kHz, 128 kbps reicht.

## Hochladen auf GitHub

1. Im Repo `deutsch-spiele` den Ordner **audio** öffnen.
2. **Add file → Upload files**, die MP3 hineinziehen.
3. Unten **Commit changes** klicken. Nach 1–2 Minuten ist die Datei online.

---

## Skript A2 · `completo-a2.mp3`

*Situation: Tía Carmen spricht in ihrer Fuente de Soda mit Sofía, Matías und Benja. Sie ist traurig, aber herzlich.*

> ¡Hola, chiquillos! Schön, dass ihr da seid. Ich bin Tía Carmen.
>
> Ich habe ein großes Problem. Am Samstag ist der Completo-Wettbewerb in Viña del Mar. Ich mache jedes Jahr mit. Mein Super-Completo ist sehr berühmt.
>
> Aber heute Morgen war mein Rezeptbuch weg! Jemand hat es gestohlen. Ohne Rezept kann ich nicht kochen. Ich habe nur noch das Brot. Das backe ich jeden Morgen selbst.
>
> Bitte helft mir! Ihr müsst die Zutaten finden. Fahrt zuerst nach Santiago, zum Mercado Central. Dort arbeitet mein Freund Don Pancho. Er verkauft die besten Vienesas in Chile.
>
> Dann fahrt ihr mit dem Bus nach Pucón. Dort wohnt meine Schwester Rosa. Sie hat Paltas in ihrem Garten.
>
> Und passt auf! Vielleicht ist der Dieb noch in Valparaíso. Viel Glück, chiquillos!

**Fragen im Spiel:** 1. Wann ist der Wettbewerb? (am Samstag) · 2. Was hat Tía Carmen noch? (das Brot) · 3. Wo wohnt ihre Schwester? (in Pucón)

---

## Skript B1 · `completo-b1.mp3`

*Situation: wie A2, aber Tía Carmen ist aufgeregter und erzählt ausführlicher.*

> ¡Hola, chiquillos! Gut, dass ihr endlich da seid. Setzt euch, ich muss euch etwas erzählen.
>
> Ihr wisst ja, dass am Samstag in Viña del Mar der große Completo-Wettbewerb stattfindet. Seit fünfzehn Jahren mache ich mit, und dreimal habe ich schon gewonnen.
>
> Aber heute Morgen, als ich die Fuente de Soda aufgemacht habe, war das Fenster offen – und mein Rezeptbuch war verschwunden! Das Buch hat meine Großmutter geschrieben. Es gibt keine Kopie.
>
> Brot habe ich zum Glück noch, das backe ich jeden Morgen selbst. Aber für den Rest brauche ich eure Hilfe. Mein alter Freund Don Pancho hat einen Stand im Mercado Central in Santiago. Er weiß genau, welche Vienesas ich immer nehme. Danach müsst ihr nach Pucón fahren, wo meine Schwester Rosa wohnt. Sie hat die besten Paltas im ganzen Süden.
>
> Ach ja, und noch etwas: Ich glaube, der Dieb hat einen Zettel verloren. Wenn ihr ihn findet, wisst ihr vielleicht, wer es war. Also los – wir haben nur bis Samstag Zeit!

**Fragen im Spiel:** 1. Was ist heute Morgen passiert? (Jemand hat das Rezeptbuch genommen.) · 2. Wer hat das Buch geschrieben? (ihre Großmutter) · 3. Warum zu Don Pancho? (Er weiß, welche Vienesas sie benutzt.) · 4. Wie oft hat sie gewonnen? (dreimal)

---

**Wichtig:** Wenn Sie den Text im Skript ändern, ändern Sie ihn bitte auch in `super-completo.html` (Feld `hoertext → skript`). Von dort wird nach dem Hören die Transkription angezeigt, und die Computerstimme liest diesen Text vor.
