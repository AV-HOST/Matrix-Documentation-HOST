---
title: "Räume erstellen"
date: 2020-07-02T21:23:14+02:00
chapter: true
draft: false
weight: 10
---
## Räume erstellen und Verantwortung übernehmen

Neue Räume werden über das + in der linken Leiste in der Kategorie **Räume** erstellt.

![Makierung des Raumhinzufügenbuttons](/doc/images/01_Rooms_de.png)
Anschließend können Sie einen neuen Raum erstellen. Auch kann optional ein Thema (das später öfter angepasst werden kann) vergeben werden. Optional kann der Raum auch öffentlich zugänglich gemacht werden (dies ist nicht die Standardeinstellung). Mit einem zusätzlichen Klick auf „Weitere Einstellungen anzeigen“ kann anschließend noch verhindert werden, dass Matrix-Nutzende von außerhalb des Hochschule Stralsund Homeservers den Raum betreten können. Standard ist inzwischen, dass alle neuen Räume (genau wie alle neuen 1:1-Gespräche) eine [Ende-zu-Ende-Verschlüsselung]({{< relref "encryption" >}}) eingerichtet haben. Sollte man dies nicht wünschen (bspw. weil in sehr großen Räumen die Verifikation der Teilnehmenden sehr unpraktisch wird) kann hier vor der Raum-Erstellung der Schieberegler benutzt werden um die Ende-zu-Ende-Verschlüsselung nicht zu aktivieren.

![Eingabemenü für den Raumnamen](/doc/images/02_Rooms_de.png)

Wenn Sie den Raum erstellt haben, erhält er eine beliebige bunte Icon-Farbe. Durch Klick auf das **i** (Raum-Info) oben rechts und anschließend das Zahnrad „Raumeinstellungen“ gelangt man zu genau jenen Raum-Einstellungen:

![Makierung des Raumenstellungsbuttons für den neu erstellten Raum](/doc/images/03_Rooms_de.png)

Hier kann im Reiter **Allgemein** ein raumspezifisches Bild/Icon hochgeladen werden. Eine wichtige Eigenschaft ist die Vergabe einer lokalen Raumadresse. Diese kann von Menschen leichter gelesen werden als die parallel auch immer vorhandene kryptische Raumadresse (die man unter dem Reiter Erweitert einsehen kann). Die vergebene lokale Raumadresse kann dann leicht in der Öffentlichkeit bzw. an die Zielgruppe verteilt werden und hat folgende Struktur:

#Raumadressname:matrix.hochschule-stralsund.de

Eine weitere wichtige Einstellmöglichkeit ist hier, ob der Raum im Raum-Verzeichnis der Hochschule Stralsund auftauchen soll. Auch die URL-Vorschau für den Raum zu aktivieren kann hier eingestellt werden.

![Raumeinstellungen](/doc/images/04_Rooms_de.png)

Im Reiter **Sicherheit** sind für Raumadministrator:innen wichtige Entscheidungen zu treffen: Soll der Raum verschlüsselt werden? Wer darf Zugang erhalten? Und wer darf den bisherigen Chatverlauf lesen?

**Zur Erklärung der Raumzugangsoptionen:**

1. „Nur Personen, die eingeladen wurden“: Das sind geschlossene Räume. Zugang zur Zeit nur durch explizite Einladung durch Moderator:innen oder Administrator:innen
2. „Alle, denen der Raum-Link bekannt ist (ausgenommen Gäste)“: Das ist ein öffentlicher Raum, aber lesen kann man nur, wenn man ihn betritt (und damit ersichtlich wird für alle Raummitglieder). Hier kann man genau nachvollziehen, wer wann im Raum ist und ggf. mit Kicken und Verbannen handeln, wenn Personen dabei sind, die hier nicht hingehören sollten...
3. „Alle, denen der Raum-Link bekannt ist (auch Gäste)“: Das ist ein öffentlicher Raum und lesen können ihn alle. Weltweit. Und Raummitglieder werden nie erfahren, wer es wann gelesen hat. Dies ist also so wie eine Internetseite, auf der alle mitschreiben können. Zu dieser Einstellung oft passend wäre auch die später zu tätigende Option, dass „Jeder“ den Chatverlauf lesen darf.

Ein "Anklopfen" an geschlossene Räume ist bisher nicht möglich. Der nahestehendste Workaround ist, an die raumadministrierende Person eine Direkte Nachricht zu senden, die einen dann einlädt.

{{% notice note %}}
Die Ende-zu-Ende-Verschlüsselung größerer oder öffentlicher Räume ist kritisch hinsichtlich der schwierigen Verifikation für viele Personen. Siehe [Ende-zu-Ende-Verschlüsselung nutzen]({{< relref "encryption" >}}).
{{% /notice %}}
{{% notice warning %}}
Als Raumadministrierende Person haben Sie die **Verantwortung** für die im Raum geteilten Inhalte (bspw. Falschnachrichten, Hetze etc.). Binden Sie weitere Personen in diese Verantwortung ein, in dem Sie in der rechten Leiste (nach Klick auf das Personensymbol) über das Drop-Down-Menü „Berechtigungslevel“ Rollen vergeben, bspw. zu Administrator:innen oder Moderator:innen.
{{% /notice %}}

Rollen und Berechtigungen können über Alle Einstellungen > Rollen und Berechtigungen gesteuert werden. Hier können Sie nach Personen suchen und ihnen ein Rolle zuweisen. Zudem können Sie verschiedene Rollen selbst erstellen und ihre Berechtigungen anpassen:

![Einstellungen für Rollen und Berechtigungen](/doc/images/06_Users-Permissions-1_de.png)

Über die Admin-Werkzeuge können Sie auch auf etwaiges Fehlverhalten reagieren (Stummschalten, Kicken, Verbannen, Nachrichten löschen, etc.).


