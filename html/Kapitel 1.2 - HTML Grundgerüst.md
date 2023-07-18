# Kapitel 1.2 HTML Grundgerüst
Das HTML Grundgerüst ist das Grundgerüst jeder Webseite. Dieses Grundgerüst ist eine Pflicht jeder .html Datei.
```html
<!DOCTYPE html>
<html lang="de-DE">
  <head>

  </head>
  <body>

  </body>
</html>
```
Das ```<!DOCTYPE html>``` Element, ist für den Browser die Information, dass Folgendes nun HTML Code darstellt. 
Im ```<html>``` Element wird nun der ganze HTML Code geschrieben. Dieser besteht aus einem ```<head>``` und einem ```<body>```. 
## Kapitel 1.2.1 - Der Head
Der ```<head>``` ist für die Metadaten der Internetseite verantwortlich. Hier werden alle, nicht sichtbaren, Elemente gespeichert. Beispielsweise wird hier der Titel, der Zeichensatz und der Autor gespeichert.
## Kapitel 1.2.2 - Der Body
Der ```<body>``` ist für alle sichtbaren Elemente gedacht. Hier werden Überschriften, Absätze, Links, Bilder, ... eingefügt. 
## Kapitel 1.2.3 - Beispiel für eine Seite mit dem HTML Grundgerüst
```html
<!DOCTYPE html>
<html lang="de-DE">
  <head>
    <meta charset="UTF-8">
    <title>Meine erste Webseite</title>
    <meta name="description" content="Dies ist meine erste Internetseite">
    <meta name="keywords" content="Internetseite, lernen, html">
    <meta name="author" content="Mein Name">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  </head>
  <body>
    <h1>Das bin ich</h1>
    <p>
      Hallo ich bin {name} und lerne gerade das Schreiben von HTML-Code.
    </p>
    <p>
      Meine Stärken sind:
      <ul>
        <li>Stärke 1</li>
        <li>Stärke 2</li>
        <li>Stärke 3</li>
      </ul>
      Meine Top-3 Programmiersprachen sind:
      <ol>
        <li>Typescript</li>
        <li>Javascript</li>
        <li>C#</li>
      </ol>
    </p>
  </body>
</html>
```
Die Webseite dieses Codes, sieht dann folgendermaßen aus:
![Erste Website](./assets/img/erste_website.png)

[Zurück](./Kapitel%201.1%20-%20HTML%20Elemente.md)
[Home](../README.md)
[Weiter](./Kapitel%201.3%20-%20HTML%20Aufgabe.md)