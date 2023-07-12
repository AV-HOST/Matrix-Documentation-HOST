---
title: "Räume teilen"
date: 2020-07-02T21:23:14+02:00
chapter: true
draft: false
weight: 40
---
# Räume teilen und publik machen

Jeder Raum hat eine Adresse, die man in den Raumeinstellungen unter dem Reiter Erweitert finden kann, bspw.

!DnaqBrQVlLOGfWxyjF:matrix.hochschule-stralsund.de

Da diese kryptische Adresse aber von Menschen nicht leicht gelesen werden kann, können Raumadressen vergeben werden, die von Menschen gelesen werden können. Dies ist nur in Räumen nötig, die man an anderen Stellen publik machen möchte.

Entweder durch global veröffentlichte Adressen (auffindbar von Benutzenden in anderen Servern - sinnvoll bei Themen, die über die Hochschule Stralsund hinausgehen) oder durch eine lokale Adresse, die nur innerhalb des Matrix-Homeservers an der Hochschule Stralsund gilt.

{{% notice note %}}    
Um eine globale Adresse zu veröffentlichen, muss diese zu aller erst als lokale Adresse erstellt worden sein. **Das heißt in beiden Fällen ist es notwendig eine lokale Adresse zu erstellen.**
{{% /notice %}}  

Um eine lokale Adresse zu vergeben, wechseln Sie in die Raumeinstellungen > Reiter **Allgemein** > Bereich **Lokale Addressen**. Hier können Sie eine neue Raumadresse erstellen (vor der Erstellung wird geprüft, ob der Name bereits vergeben ist):

![Raumeinstellungen mit dem mehr anzeigen ausgewählt](/doc/images/01_Sharing_de.png)

Sie können einem Raum mehrere lokale Adressen geben und diese auch wieder entfernen:

![Raumeinstellungen mit dem lokale Adressen ausgewählt](/doc/images/02_Sharing_de.png)

Wenn Sie lokale Adressen erstellt haben, können sie eine öffentlich Adressen hinterlegen. Wechseln Sie dazu in den Bereich **Öffentliche Adresse** und wählen entweder eine der lokalen Adressen (Primären Adresse im Drop-Down-Menü) als öffentliche Adresse aus oder fügen Sie eine neue hinzu. Sollte die Raumadresse im Raum-Verzeichnis des Matrix-Homeservers der Hochschule Stralsund veröffentlicht werden sollen, kann dies durch den folgend gezeigten Schalter erfolgen:

![Raumeinstellungen mit dem öffentliche Raumadresse ausgewählt](/doc/images/03_Sharing_de.png)

Die Raumadresse hat dann folgende Struktur

#Raumadressname:matrix.hochschule-stralsund.de

Wenn innerhalb von Matrix auf einen anderen Raum verlinkt werden soll, kann dies einfach durch (beginnendes) Eintippen in das Nachrichtenfeld von

```
#Raumadressname:matrix.hochschule-stralsund.de
```

geschehen. Ist man selber Mitglied in dem Raum, so erscheinen automatisch Vorschläge. Dies ist dann ein spezieller Hyperlink innerhalb von Matrix, der auch direkt im Client der empfangenden Person (mit einem Mausklick) genutzt werden kann.

Erhält man solche Adressen auf anderem Wege (z.B. via E-Mail) hilft es, diese in einen persönlichen Notizraum (selbst angelegter Raum ohne weitere Personen) zu senden. Anschließend kann man dann bequem auf diesen sich ergebenden Raumlink klicken.

Das Teilen-Symbol oben rechts in jedem Raum, bietet einen matrix.to-Link an, sowie einen QR-Code und verschiedene soziale Netzwerke. Der matrix.to- Link führt auf eine Seite, auf der ausgewählt werden kann, wie der Link geöffnet werden soll. So kann z.B. der installierte Client Element Desktop verwendet werden, oder ausgewählt werden, über welchen Heimserver der Raum betreten werden soll. 

![Teilensymbol in der Chatansicht des Raums makiert](/doc/images/04_Sharing-Button_de.png)

Ein standardisiert vergebener Einladungslink zum Raum kann dann so aussehen:

```
https://matrix.to/#/#Raumadresse:matrix.hochschule-stralsund.de
```

Weiterhin könnte man aus der vergebenen Raumadresse eine Internetadresse (URL) nach folgender Struktur konstruieren:

```
https://matrix.hochschule-stralsund.de/#/room/#Raumadressname:matrix.hochschule-stralsund.de
```

Diese könnte, ähnlich des matrix.to-Links, auch leicht in der Öffentlichkeit bzw. an die Zielgruppe verteilt werden (**öffnet sich allerdings nur in Element Web**, nicht in einem ggf. installiertem Element Desktop). Universeller (insb. für die große Gruppe an Personen mit Element Desktop) und inzwischen empfehlenswerter ist daher der zuvor beschriebene Weg mit dem matrix.to-Link.





