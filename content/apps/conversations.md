---
title: "Conversations"
date: 2017-11-04T17:30:32+01:00
draft: false
weight: 1
---

**ToDo:**

* OMEMO?
* Auf mehrere Seiten aufsplitten?
* Adressbuchzugriff?
* Hinweis auf Einladungsseite

Hier wird die Installation, Einrichtung und Benutzung der Android-App
**Conversations** beschrieben.

## Installation

### Play-Store

Conversations bezieht man am einfachsten aus dem **[Google Play Store][10]** 
für 2,39€. Dieser Preis ist gemessen an der Qualität der App sehr niedrig
und ich empfehle jedem ihn auszugeben. Es ist deutlich weniger als ein
Bier in der Kneipe. Wer gerne Sprachnachrichten versenden möchte installiert
auch gleich das [Voice Recorder Plugin][20] und wer seinen aktuellen 
Standort als Sofortnachricht verschicken möchte das [Share Location Plugin][30].

Wenn ihr keine Möglichkeit habt im Play-Store zu bezahlen könnt ihr 
Conversations aus dem **F-Droid** Store beziehen.  
Wer Conversations im Play Store gekauft hat kann die Anleitung zu F-Droid
[überspringen][40].

### F-Droid

Conversations gibt es kostenlos im F-Droid Store. Diesen könnt ihr [hier][50]
herunterladen. Zum Installieren von F-Droid muss man in Android zulassen,
dass Apps aus fremden Quellen installiert werden können.
Dies könnt ihr unter **Einstellungen → Sicherheit → Unbekannte Herkunft**
einstellen.

{{% notice warning %}}
Es ist eine Sicherheitsfunktion von
Android die Installation aus unbekannter Herkunft standardmäßig zu
deaktivieren. Neuere Android-Versionen bieten die Möglichkeit an, die
Installation nur einmalig zu erlauben. Wenn eure Android-Version das
anbietet, solltet ihr diese Funktion nutzen. Ihr müsst dann zur Installation
von F-Droid, zur Installation von Conversations und bei jedem Update von
Conversations einmalig die Installation aus unbekannten Quellen erlauben.
Das ist lästig, aber sicherer als es generell zu erlauben.{{% /notice %}}

![Installation gesperrt](/images/conversations/installation_gesperrt.png?height=400px)
![Apps unbekannter Herkunft erlauben](/images/conversations/unbekannte_herkunft.png?height=400px)

Nach der Installation von F-Droid kann man nun Conversations über F-Droid
installieren. Nachdem man die F-Droid App geöffnet hat drückt man auf das
Lupensymbol und tippt "Conversations" ein. Im folgenden Screenshot sieht 
man Conversations als zweiten Treffer der Suche.

![F-Droid Suche](/images/conversations/fdroid_suche.jpg?height=400px)

Wer auch Sprachnachrichten versenden möchte installiert auch das **Voice
Recorder Plugin** das man im vorigen Bild als letzten Treffer sehen kann.

### Einrichtung

Wer sich bereits einen Account auf einem Server angelegt hat kann mit
[Vorhandenen Account nutzen][60] fortfahren. Wer die InBand-Registrierung
nutzen möchte hat die Wahl zwischen einer [Registrierung bei conversations.im][70]
(die Nutzung dieses Servers kostet nach einem kostenlosen halben Jahr 8€ /
Jahr) oder einem Server aus [dieser Liste][80]. Wer sich für letzters
entscheided springt weiter zur [Anleitung für andere Server][90].

#### InBand-Registrierung

##### Conversations.im

Um einen Account bei conversations.im anzulegen wählt man im Startbildschirm
**Konto erstellen**.

![Conversations Startbildschirm](/images/conversations/conversations_start.png?height=400px)

Als nächstes wählt man den gewünschten Benutzernamen aus.

![Converations.im Benutzername](/images/conversations/conversations_im_nutzername.png?height=400px)

Nun muss man ein Passwort wählen, ein Captcha lösen und schon ist die Registrierung abgeschlossen.

![Conversations.im Passwort setzen](/images/conversations/passwort_setzen.png?height=400px)
![Conversations.im Captcha löesen](/images/conversations/captcha.png?height=400px)

Abschließend kann man, wenn man möchte, ein Avatar (Benutzerbild) setzen oder 
diesen Schritt überspringen.

![Conversations Avatar wählen](/images/conversations/avatar.png?height=400px)

Jetzt geht es weiter mit ein paar [Hinweisen zur Benutzung][100].

##### Andere Server

Um einen Account bei einem Server anzulegen wählt man im Startbildschirm
**Nutze eigenen Provider**.

![Conversations Startbildschirm](/images/conversations/conversations_start.png?height=400px)

Im nächstem Bildschirm gibt man den gewünschten Namen ein und vergibt
ein Passwort. Dann setzt man den Haken bei **Neues Konto auf dem 
Server erstellen** und trägt das Passwort ein zweites Mal zur
Bestätigung ein.

![Conversations Registrierung bei anderem Server](/images/conversations/account_erstellen.jpg?height=400px)

Abschließend kann man, wenn man möchte, ein Avatar (Benutzerbild) setzen oder
diesen Schritt überspringen.

![Conversations Avatar wählen](/images/conversations/avatar3.jpg?height=400px)

Jetzt geht es weiter mit ein paar [Hinweisen zur Benutzung][100].

#### Vorhandenen Account nutzen

Um einen vorhandenen Account in Conversations zu nutzen wählt man im 
Startbildschirm **Nutze eigenen Provider**.

![Conversations Startbildschirm](/images/conversations/conversations_start.png?height=400px)

Im folgenden Bildschirm gibt man den Benutzernamen und das Passwort
des vorhandenen Accounts ein.

![Conversations mit vorhandenem Account](/images/conversations/vorhandener_provider.jpg?height=400px)

Abschließend kann man, wenn man möchte, ein Avatar (Benutzerbild) setzen oder
diesen Schritt überspringen.

![Conversations Avatar wählen](/images/conversations/avatar2.jpg?height=400px)

### Benutzung

#### Batterieoptimierung deaktivieren

Wenn Conversations fragt ob man die **Batterieoptimierung deaktivieren** möchte,
sollte man dies erlauben. Androids Batterieoptimierung könnte sonst im Hintergrund
Conversations beenden und man erhält keine Benachrichtung über neue Nachrichten
mehr bis man die App wieder öffnet. Der Akkuverbrauch von Conversations ist so
gering, dass man das ohne Bedenken erlauben kann.

![Conversations Hinweis Batterieoptimierung](/images/conversations/batterie_hinweis.jpg?height=200px)

Nach einem Klick auf **Weiter** im Hinweis-PopUp bestätigt man mit Klick auf
**Ja** die Deaktivierung.

![Conversations Batterieoptimierung deaktivieren](/images/conversations/batterieoptimierung.jpg?height=200px)

#### Kontakte hinzufügen

Nach der Anmeldung präsentiert sich Conversations mit einem recht
leeren Fenster. Um einen Kontakt hinzuzufügen klickt man auf das Symbol
mit dem **+**.

![Conversations nach der Anmeldung](/images/conversations/nach_der_anmeldung.png?height=400px)

Nun gibt man im Feld **Jabber-ID** die **JID** des Kontakts ein.

![Conversations Kontakt erstellen](/images/conversations/kontakt_erstellen.png?height=400px)

Der Kontakt erscheint darauf in der Kontaktliste und man kann mit dem
Kontakt chatten nachdem man auf den Namen klickt.

![Conversations Kontaktliste](/images/conversations/kontaktliste.png?height=400px)

#### Eine Kontaktanfrage beantworten

Wird man selbst von jemand anderem zu dessen Kontaktliste hinzugefügt, 
den man selbst noch nicht als Kontakt gespeichert hat kann man diese
Person als Kontakt speichern indem man auf **Auch hinzufügen** klickt.

![Conversations Kontaktanfrage erhalten](/images/conversations/kontaktanfrage.jpg?height=400px)

Im folgenden Fenster setzt man beide Häkchen, damit man gegenseitig
sehen kann ob der Kontakt gerade online ist.

![Conversations Online-Status](/images/conversations/online_status.jpg?height=400px)

#### Einen Gruppenchat betreten


[10]:https://play.google.com/store/apps/details?id=eu.siacs.conversations
[20]:https://play.google.com/store/apps/details?id=eu.siacs.conversations.voicerecorder
[30]:https://play.google.com/store/apps/details?id=eu.siacs.conversations.sharelocation
[40]:/apps/conversations/#einrichtung
[50]:https://f-droid.org/
[60]:/apps/conversations/#vorhandenen-account-nutzen
[70]:/apps/conversations/#conversations-im
[80]:https://datenschutzhelden.org/2017/07/12/daten-sparsame-xmpp-server/
[90]:/apps/conversations/#andere-server
[100]:/apps/conversations/#benutzung
