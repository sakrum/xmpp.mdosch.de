---
title: "Serverwahl"
date: 2017-11-04T12:54:57+01:00
draft: false
weight: 2
alwaysopen: true
---

## Wer die Wahl hat...

...hat die Qual.

Es gibt sehr viele XMPP-Server und für einen Neuling ist es sicher schwer eine Wahl zu treffen. 
Nicht jeder Server unterstützt bereits alle gängigen Features und man möchte ja nicht bei einem Server landen
der dann Probleme macht. Glücklicherweise haben die *Datenschutzhelden* eine
[gute Liste mit empfehlenswerten Servern][10] erstellt. Wenn man einen dieser Server wählt macht man
schon mal nichts falsch. Die finale Auswahl kann man dann treffen indem man einfach den Server aus der
Liste wählt, dessen Name einem am besten zusagt. Schließlich wird dieser dann ein Teil eurer **JID**,
eurer XMPP-Adresse, sein.   
Fortgeschrittene oder Interessierte, die im Detail wissen wollen anhand welcher Kriterien diese Liste
erstellt wurde, können das bei [den Datenschutzhelden nachlesen][20].   

Ein sehr empfehlenswerter Server taucht in dieser Liste leider nicht auf: [conversations.im][25].
Wahrscheinlich weil dieser Server im Gegensatz zu den anderen nicht kostenlos ist, sondern ein halbes Jahr
kostenlos nutzbar ist und danach 8€ pro Jahr kostet. Wer es sich leisten kann sollte einen Account dort
in Erwägung ziehen. Für die Gebühr erhält man einen Server der vorbildlich gepflegt wird und alle neuen
Funktionen unterstützt. Conversations.im unterstützt nur [InBand-Registrierung][28].

## Registrierung

Einige Server bieten nur eine Registrierung über ein Webformular an, andere nur die sogenannte 
InBand-Registrierung und manche beides. Hier wird an einem Beispiel die Registrierung über ein
Webformular erklärt. Da die Art und Weise wie eine InBand-Registrierung durchgeführt wird stark
von der App bzw. vom Client abhängt, wird die InBand-Registrierung nicht hier, sondern in der Anleitung
zur jeweiligen App detailliert beschrieben.

### Webformular

Die Registrierung über ein Webformular läuft ab wie eine normale Registrierung bei einer Webseite oder 
einem Email-Anbieter.

Als Beispiel nehme ich den Server [dismail.de][30] aus der oben genannten Liste. Möchte man dort seinen
XMPP-Account anlegen ruft man die Seite auf und findet dort in der Navigationsleiste den Punkt 
**Register** über welchen man zum Registrierungsformular gelangt:

![Registrierung dismail.de](/images/serverwahl/dismail_register.png?height=200px)

In das Formular trägt man nun den gewünschten Benutzernamen und das Passwort ein, löst die Rechenaufgabe
und klickt auf den Button **Register**. Nun kann man sich mit diesen Benutzerdaten mit der [App der Wahl][50] einloggen.

### InBand-Registrierung

**InBand-Registrierung** heißt, dass die Registrierung nicht über ein Webformular vorgenommen werden
muss sondern direkt in der App bzw. im Client geschieht. Da die Vorgehensweise clientspezifisch ist
wird hier nicht darauf eingegangen sondern auf die Clients verwiesen, welche InBand-Registrierungen
beherrschen:

* Android: [Conversations][60]
* iOS: [ChatSecure][70]
* Linux: [Gajim][80]
* macOS: [Swift][90]
* Windows: [Gajim][80]

[10]:https://datenschutzhelden.org/serverliste/
[20]:https://datenschutzhelden.org/2017/07/12/daten-sparsame-xmpp-server/
[25]:https://account.conversations.im
[28]:/serverwahl/#inband-registrierung
[30]:https://dismail.de/
[50]:/apps/
[60]:/apps/conversations/
[70]:/apps/chatsecure/
[80]:/apps/gajim/
[90]:/apps/swift/
