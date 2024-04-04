# web-gallery

Dieses Projekt, bestehend aus Gitlab Pages, dient als Galerie für den Verein AmperPerchten e.V.

## Bedienung

- unter /docs/ wird ein Ordner angelegt mit der jeweiligen Saison angelegt
    - Im Ordner wird eine Datei mit dem Namen aufführung-datum.md angelegt
    - darin wird der Inhalt laut dem Kapitel <Syntax> angelegt
- unter /docs/img/ wird ein Ordner angelegt mit der gleichen Saison
- unter /docs/img/jahr/ wird ein Ordner pro Ausführung angelegt
    - Der Ordnername besteht aus Datum und Ort im Format Tag_Monat_Jahr-Ort
- unter /docs/img/jahr/auffürhung/ werden die jeweiligen Bilder abgelegt
    - Die Bilder werden mit dem Namen aufführung-nummer.jpg (vorlaufende Nummer -1, -2, -3, etc.) abgelegt.

## Syntax

Der Inhalt der Datei /docs/jahr/aufführung-datum.md wird nach folgendem Schema aufgebaut:
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
[![Galerie](./docs/assets/img/folder48.png 25.11.2023 - Kaltenberg)] (./docs/2023/kaltenberg-25_11_23.html)</br>
25.11.2023 - Kaltenberg
</code>

## Autor
Projekt ist entstanden durch Gitlab Pages (Jekyll) und der Galerie-Methode von michaelx (https://github.com/michaelx/jekyll-photos)
</br></br>
Die Bilder sind entstanden durch Anett Rost und Robert Hoiss diese sind Mitglieder des AmperPerchten e.V.
</br></br>
AmperPerchten e.v.</br>
Webseite: https://www.amperperchten.de
</br></br>
Seite wird durch Feicht entwickelt.</br>
Feicht</br>
Webseite: "{{ site.github.owner_url }}" </br>
Gitlab: https://github.com/Feicht