# Kapitel 2.1 CSS Einbinden
Um CSS einzubinden, gibt es 3 Methoden.
- Die Inlinemethode:
  ```html
  <p style=""></p>
  ```
  Hiermit lässt sich zwischen den beiden Anführungsstrichen die CSS Eigenschaften dieses Elementes einbinden. Diese Methode wird sehr selten und meistens für kleine Änderungen genutzt.

- Über das Style Element
  ```html
  <style>

  </style>
  ```
  Hiermit lässt sich der CSS Code zwischen den beiden Tags einbinden. Dies wird im ```<head>``` definiert. Diese Methode wird meistens bei kleineren Projekten genutzt.

- Über eine externe .css Datei
  ```html
  <link rel="stylesheet" href="./style.css">
  ```
  Hiermit lässt sich der CSS Code in eine externe Datei schreiben und mit HTML einbinden. Dies wird im ```<head>``` definiert. Diese Methode wird meistens bei größeren Projekten genutzt.

[Zurück](./Kapitel%202%20-%20CSS.md)
[Home](../README.md)
[Weiter](./Kapitel%202.2%20-%20CSS%20Syntax.md)