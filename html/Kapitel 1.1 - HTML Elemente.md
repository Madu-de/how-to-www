# 1.1 - HTML-Elemente
HTML besteht aus verschiedenen vorgefertigten Elementen, die einen eindeutigen Namen tragen. Beispielsweise gibt es Elemente, mit denen man Überschriften, Absätze oder Bilder auf seiner Webseite hinzufügen kann.
## 1.1.1 Tags
HTML Elemente werden mit Tags (englisch ausgesprochen) abgebildet. Dabei hat fast jedes Element ein öffnendes und ein schließenden Tag.
Hierzu schauen wir uns nun dieses Beispiel an:
```html
<p>Das ist ein Absatz</p>
```
Das kleiner-als-Zeichen am Anfang öffnet ein Tag. Das größer-als-Zeichen schließt diesen wieder. Innerhalb dieser 2 "Klammern", wird der eindeutige Elementname hineingeschrieben (Hier beispielsweise p, welches für einen Absatz steht). Möchte man das Element schließen, nutzt man die gleiche Vorgangsweise, wobei vor dem Elementnamen ein **/** angehängt wird. Dies steht für ein schließendens Tag. Das schließende Tag ist jedoch nicht immer erforderlich. Es ist immer nur dann erforderlich, wenn das Element vorgeschriebenermaßen einen Inhalt besitzt. Beispielsweise Absätze, Überschriften und Links. 
```html
<h1>Beispiel für eine Überschrift</h1>
<p>Beispiel für einen Absatz</p>
<a href="https://www.github.com/madu-de">Beispiel für einen Link</a>
```
Beispiele für Elemente ohne Inhalt, sind Bilder oder Videos:
```html
<img src="https://avatars.githubusercontent.com/u/85842735">
<img src="./bilder/katzenbild.jpg">
<video src="https://onlinevideobeispiel.com/video.mp4">
<video src="./videos/katzenvideo.mp4">
```
## 1.1.2 Attribute
In den letzten zwei Beispielen sehen wir, dass im öffnenden Tag, einiger Elemente, Attribute vergeben worden sind. Diese sind bei einigen Elementen, wie bei Links, Bilder und Videos erforderlich, um Informationen über das Element anzugeben. Beispiesweise den Dateipfad des Bildes. 
Attribute werden immer mit dem Attributnamen, einem Gleicheitszeichen und den doppelten Anführungsstrichen dargestellt. Zwischen den doppelten Anführungszeichen wird der Wert des Attributs angegeben. <br>
Um das ganze noch ein wenig besser darzustellen, ist hier ein Beispiel mit Platzhaltern eines HTML-Elements:
```html
<tag-name attribut1="wert1" attribut2="wert2">Inhalt</tag-name>
```
## 1.1.3 Wichtige HTML-Elemente
| Tag-Name | Erforderliche Attribute | Beschreibung                                     | Schließendes Tag erforderlich |
|----------|-------------------------|--------------------------------------------------|-------------------------------|
| h1       | /                       | Dies steht für eine Überschrift erster Ordnung   | ✅                            |
| h2       | /                       | Dies steht für eine Überschrift zweiter Ordnung  | ✅                            |
| h3       | /                       | Dies steht für eine Überschrift dritter Ordnung  | ✅                            |
| h4       | /                       | Dies steht für eine Überschrift vierter Ordnung  | ✅                            |
| h5       | /                       | Dies steht für eine Überschrift fünfter Ordnung  | ✅                            |
| h6       | /                       | Dies steht für eine Überschrift sechster Ordnung | ✅                            |
| p        | /                       | Dies steht für einen Absatz                      | ✅                            |
| b        | /                       | Dies steht für einen dicken Text                 | ✅                            |
| i        | /                       | Dies steht für einen kursiven Text               | ✅                            |
| br       | /                       | Dies steht für einen Zeilenumbruch               | ❌                            |
| hr       | /                       | Dies steht für eine horizontale Linie            | ❌                            |
| ol       | /                       | Dies steht für eine geordnete Liste              | ✅                            |
| ul       | /                       | Dies steht für eine ungeordnete Liste            | ✅                            |
| li       | /                       | Dies steht für ein Listenelement                 | ✅                            |
| div      | /                       | Dies steht für einen leeren Container            | ✅                            |
| a        | href="link"             | Dies steht für einen Link                        | ✅                            |
| img      | src="link.png"          | Dies steht für ein Bild                          | ❌                            |
| video    | src="link.mp4"          | Dies steht für ein Video                         | ❌                            |

[Zurück](Kapitel%201%20-%20HTML.md)
[Home](../README.md)
[Weiter](./Kapitel%201.2%20-%20HTML%20Grundger%C3%BCst.md)