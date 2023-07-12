---
title: "Nachrichten"
date: 2020-07-15T18:10:07+02:00
draft: false
chapter: true
weight: 30
---

## Personen finden und Direktnachrichten versenden

Um einzelne Personen anzuschreiben und somit einen 1:1 Chat zu erzeugen ist als Erstes auf das + (Unterhaltung beginnen) in der Kategorie „Personen“ zu klicken:

![Klick au den Chat starten Button](/doc/images/01_Start-Chat_de.png)

Im Suchfeld können Sie den Namen oder das HOST-Login (falls bekannt) der gesuchten Person eintragen:

![Ein Suchergebnis auf eingegebenen Suchanfrage](/doc/images/04_Search.png)

Personen, die schon einen Account in Matrix haben sind durch ihren Anzeigenamen (meist „Vorname Nachname“) auffindbar. Bitte nach jedem letzten eingegebenen Zeichen 5 Sekunden warten, bis die Suchergebnisse angezeigt werden. Personen, die noch nicht eingeloggt waren, sind ausschließlich über ihre E-Mail-Adresse oder ihren HOST-Login auffindbar. Der Link-Button „Mehr zeigen“ lässt weitere Sucherergebnisse erscheinen. Beachten Sie auch, auf welchem Server Ihre gesuchte Person angezeigt wird.

{{% notice note %}}
Ein Einfügen von z. B. Namen (bspw. via Strg+V) reicht nicht aus, um Personen zu finden! Bitte geben Sie den Namen, das HOST-Login oder die E-Mail-Adresse Zeichen für Zeichen per Hand ein und warten abschließend 5 Sekunden bis zur Sichtung der Treffer.
{{% /notice %}}

Für das massenhafte Einladen von Personen (bis zu 100 auf einmal, dann wiederholbar) sind die Matrix-Namen notwendig, die in der Form @HOST-Login:matrix.hochschule-stralsund.de vorliegen sollten. Diese bspw. in einem Texteditor Zeile für Zeile sammeln und dann mittels Zwischenablage (Kopieren & Einfügen) in das Suchfeld in Matrix/Element einfügen.

Wenn Sie niemanden finden können, fragen Sie nach deren HOST-Logins oder teilen Sie Ihr HOST-Login (@HOST-Login:matrix.hochschule-stralsund.de oder https://matrix.to/#/@HOST-Login:matrix.hochschule-stralsund.de), damit die angesprochene Person Sie innerhalb von Matrix kontaktieren kann.

Wenn Sie die gesuchte Person im Suchergebnis gefunden haben, klicken Sie auf „Los“:

![Einen Kontakt anschreiben](/doc/images/04_Found-and-Go_de.png)

Es öffnet sich das Gespräch, welches nach Annahme der Einladung durch die verbundene Person [Ende-zu-Ende-verschlüsselt]({{< relref "encryption" >}}) (inzwischen Standard) beginnen kann. Die Verbindung zum Server an der Hochschule Stralsund ist natürlich auch transport-verschlüsselt.

![Das Chat-Fenster](/doc/images/04_Chat.png)

Nach dem Absenden der ersten Nachricht, werden auch Metadaten im Chat angezeigt:

![Die erste Nachricht mit Metadaten](/doc/images/04_First_Message.png)

Sollten Sie aus einem speziellen Grund explizit keine Ende-zu-Ende-Verschlüsselung wünschen, wäre ein unverschlüsselter [Raum zu erzeugen]({{< relref "rooms/create.md" >}}) und Ihre Kontakte in diesen einzuladen.

Weiteres: [Nachrichten formatieren]({{< relref "formatting.md" >}})

Ein Raum mit sich selbst ist auch möglich und kann als Zwischenablage / Notizbuch und für Tests benutzt werden, bspw. ob Formatierungen und Hyperlinks korrekt aussehen.

