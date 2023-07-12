---
title: "Element Web (Browser)"
date: 2020-07-15T16:46:07+02:00
draft: false
chapter: true
weight: 5
---

# Element Web

Starten Sie auf {{% button href="https://matrix.hochschule-stralsund.de" icon="fas fa-globe" %}}matrix.hochschule-stralsund.de{{% /button %}}.

![Startseite von Element Webclient mit Anmeldebutton](/doc/images/01_Welcome_de.png)

Hierzu ist keine Registrierung nötig, der Dienst kann sofort durch Klick auf „Anmelden“ genutzt werden.

![Loginfenster mit Aufforderung HOST-Login und Passwort einzugeben](/doc/images/02_Login1_de.png)

Sie können die Anmeldemethode über das Dropdown-Menü „Anmelden mit:“ auswählen. Zur Verfügung stehen „Benutzername“, „E-Mail-Adresse“ oder „Telefon“. 

{{% notice warning %}}
Die Nutzung von Telefonnummern wird auf dem Matrix-Homeserver der Hochschule Stralsund nicht unterstützt.
{{% /notice %}}

Tragen Sie für die Anmeldung Ihre Anmeldedaten ein:

**Benutzername: HOST-Login** oder **E-Mail: HOST-E-Mail-Adresse**

**Passwort: Ihr Passwort**

Es folgt nach dem Erstlogin auch keine E-Mail / Bestätigungsmail.

Analog zu E-Mail-Adressen ergeben sich damit Matrix-Adressen folgender Struktur:

@HOST-Login:matrix.hochschule-stralsund.de

{{% notice warning %}}
Sollten Sie statt mit der oben genannten Website (Element Web-App an der Hochschule Stralsund installiert) sofort mit einem [Matrix Client]({{< relref "../clients" >}}) starten wollen, ist es wichtig den Heimserver vom zumeist standardmäßig eingestellten matrix.org auf `https://matrix.hochschule-stralsund.de` zu ändern (dargestellt in den folgenden Bildschirmfotos):
{{% /notice %}}

![Anmeldeseite mit Fokus auf dem Homeserver ändern Button](/doc/images/02_Login2_de.png)

Klicken Sie dazu auf **Bearbeiten** und fügen Sie danach die Adresse des Matrix-Homeservers der Hochschule Stralsund (`https://matrix.hochschule-stralsund.de`) hinzu.

![Eingabefeld zum Ändern des Homeserers mit der Eingabe matrix.hochschule-stralsund.de](/doc/images/02_Login3_de.png)

## Browsereinstellungen

### Browserwahl

Empfehlenswert sind die Browser [Firefox](https://www.mozilla.org/de/firefox/new/), [Chromium](https://www.chromium.org/getting-involved/download-chromium), neuere Versionen von MS Edge (basierend auf Chromium). Ältere oder ungeeignete Browser zeigen ggf. nur eine weiße Seite an.

### NoScript

Viele Menschen nutzen u.a. Skript-Blocker, um sich vor [Tracking](https://tu-dresden.de/tu-dresden/newsportal/news/datenschutz-beim-website-tracking) und Schadsoftware im Browser zu schützen, bspw. mit dem Addon [NoScript](https://addons.mozilla.org/de/firefox/addon/noscript/). Hier sind folgende Einstellungen durchzuführen (für den Integrationsmanager, z.B. Jitsi/Etherpad)

![Einstellungen des Browserplugins NoScript mit matrix.hochschule-stralsund.de und vector.im als vertrauenswürdige Skriptquellen ausgewählt](/doc/images/10_Sicherheit2_de.png)

### Cookies

Erlauben Sie auch Cookies von

- matrix.hochschule-stralsund.de
- vector.im (für den Integrationsmanager)
