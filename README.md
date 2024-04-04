# web-gallery

Dieses Projekt, bestehend aus Gitlab Pages, dient als Galerie für den Verein AmperPerchten e.V.

## Bedienung

- unter / wird ein Ordner angelegt mit der jeweiligen Saison angelegt
    - Im Ordner wird eine Datei mit dem Namen aufführung-datum.md angelegt
    - darin wird der Inhalt laut dem Kapitel <Syntax> angelegt
- unter /img/ wird ein Ordner angelegt mit der gleichen Saison
- unter /img/jahr/ wird ein Ordner pro Aufführung angelegt
    - Der Ordnername besteht aus Datum und Ort im Format Tag_Monat_Jahr-Ort
- unter /img/jahr/aufführung/ werden die jeweiligen Bilder abgelegt
    - Die Bilder werden mit dem Namen aufführung-nummer.jpg (vorlaufende Nummer -1, -2, -3, etc.) abgelegt.

## Syntax

Der Inhalt der Datei /jahr/aufführung-datum.md wird nach folgendem Schema aufgebaut:
</br>
<code>layout: photo_set</br>
title: %Datum% %Ort%</br>
description: "Fotos vom %Datum% in %Ort%."</br>
</br>
photos:</br>
    set: %jahr%/%datum%-%ort%/%ort%</br>
    size: %Anzahl der Bilder im Ordner%</br>
</code>

## Aufbau index.md

Die Index wird folgendermaßen aufgebaut
</br>
<code>'# Auftritte 2023/2024</br>
[![Galerie](./assets/img/folder48.png 25.11.2023 - Kaltenberg)] (./docs/2023/kaltenberg-25_11_23.html)</br>
25.11.2023 - Kaltenberg
</code>

## Autor
Projekt ist entstanden durch Gitlab Pages (Jekyll) und der Galerie-Methode von [michaelx](https://github.com/michaelx/jekyll-photos)
</br></br>
Die Bilder sind entstanden durch Annett Rost und Robert Hoiss diese sind Mitglieder des AmperPerchten e.V.
</br></br>
AmperPerchten e.v.</br>
Webseite: [AmperPerchten e.V.](https://www.amperperchten.de)
</br></br>
Seite wird durch Feicht entwickelt.</br>
Feicht</br>
Webseite: [Fullme.sh](https://fullme.sh)</br>
Gitlab: [Feicht](https://github.com/Feicht)