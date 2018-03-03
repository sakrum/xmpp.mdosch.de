---
title: "Serverliste"
date: 2018-03-02T18:36:00+01:00
weight: 1
---


Diese Liste umfasst einige Server, die meiner Meinung nach alle wichtigen XMPP-Funktionen unterstützen.
Es gibt natürlich noch deutlich mehr Server, eine (unvollständige) Liste gibt es bei [jabber.at][10],
und es steht natürlich jedem frei einen anderen Server, statt einem aus dieser Empfehlungsliste zu nutzen.
Serverbetreiber, die meinen ihr Server sollte in dieser Liste stehen bitte ich mir [eine Nachricht][20]
zu schicken, sofern die [Voraussetzungen][30] erfüllt sind.
 
## Erklärung

Die **Max. Dateigröße** gibt an wie groß Dateien zum Versenden über XMPP maximal sein dürfen. Da meistens
Bilder verschickt werden dürfte diese Größe bei allen hier gelisteten Servern groß genug gewählt sein.

Unter **Speicherdauer** wird angegeben nach welcher Zeitspanne die Dateien vom Server gelöscht werden.
D.h. wenn euer Kontakt die Datei nicht innerhalb dieses Zeitraums heruntergeladen hat, müsst ihr sie
erneut senden. Die kürzeste Speicherdauer der Server in der Liste beträgt 14 Tage, da vermutlich kaum
jemand seinen Messenger für länger als zwei Wochen nicht nutzt sollte dies auch ausreichend sein.

Unterstützt ein Server **Web-Registrierung** kommt ihr direkt zum Fomular indem ihr auf das
:heavy_check_mark:-Symbol klickt.

## Liste

Servername | Max. Dateigröße | Speicherdauer | InBand-Registrierung | Web-Registrierung | Kontakt
------------ | :-------------: | :------------: | :------------: | :------------: | :------------:
[5222.de](https://5222.de/) | 50 MB | 30 Tage | ? | [:heavy_check_mark:](https://www.jabber.de/anmeldung/) | [:mailbox:](https://www.jabber.de/support/)
[conversations.im](https://account.conversations.im/) | 50 MB | 1 Jahr | :heavy_check_mark: | :x: | [:mailbox:](https://account.conversations.im/contact/)
[dismail.de](https://dismail.de/) | 25 MB | 31 Tage | ? | [:heavy_check_mark:](https://dismail.de/register.html) | [:mailbox:](https://dismail.de/contact.html)
[draugr.de](https://www.draugr.de/) | ? | ? | ? | [:heavy_check_mark:](https://account.draugr.de/) | [:mailbox:](https://www.draugr.de/kontakt/)
[jabber.hot-chilli.net](https://jabber.hot-chilli.net/) [^1] | 10 MB | 31 Tage | ? | [:heavy_check_mark:](https://jabber.hot-chilli.net/forms/create/) | [:mailbox:](https://jabber.hot-chilli.net/de/)
[jabjab.de](https://jabjab.de/) | 50 MB | 30 Tage | ? | [:heavy_check_mark:](https://jabjab.de/registrieren.php) | [:mailbox:](https://jabjab.de/kontakt.php)
[kode.im](https://kode.im/) | ? | ? | :heavy_check_mark: | [:heavy_check_mark:](https://im.koderoot.net/register-on-kode.im) | [:mailbox:](https://kode.im/)
[magicbroccoli.de](https://magicbroccoli.de/xmpp/) | 25 MB | 31 Tage | ? | [:heavy_check_mark:](https://magicbroccoli.de/register/) | [:mailbox:](https://magicbroccoli.de/contact/)
[pimux.de](https://www.pimux.de/) | 10 MB | 30 Tage | ? | [:heavy_check_mark:](https://www.pimux.de/page/registrierung) | [:mailbox:](https://www.pimux.de/page/kontakt)
[riotcat.org](https://riotcat.org/) | 10 MB | 14 Tage | :heavy_check_mark: | :x: | [:mailbox:](https://riotcat.org/#contact)
[simplewire.de](https://simplewire.de/) | 15 MB | 14 Tage | :heavy_check_mark: | [:heavy_check_mark:](https://simplewire.de/register.html) | [:mailbox:](https://simplewire.de/impressum.html)
[trashserver.net](https://trashserver.net/) | 50 MB | 14 Tage | ? | [:heavy_check_mark:](https://trashserver.net/registrieren/) | [:mailbox:](https://trashserver.net/kontakt/)
[wiuwiu.de](https://wiuwiu.de/) | 10 MB | 30 Tage | ? | [:heavy_check_mark:](https://wiuwiu.de/#register) | [:mailbox:](https://wiuwiu.de/Imprint/)

## Voraussetzungen

Um in dieser Liste aufgenommen werden sollte euer Server eine Datenschutzerklärung bereitstellen, idealerweise
in Deutschland gehosted sein und alle wichtigen XEPs unterstützen.
Für eine reibungslose Benutzung für jedermann sehe ich folgende XEPs als wichtig an:

* XEP-0163: Personal Eventing Protocol
* XEP-0045: Multi-User Chat
* XEP-0191: Blocking Command
* XEP-0198: Stream Management
* XEP-0280: Message Carbons
* XEP-0352: Client State Indication
* XEP-0065: SOCKS5 Bytestreams (Proxy)
* XEP-0313: Message Archive Management
* XEP-0363: HTTP: File Upload
* XEP-0357: Push Notifications
* XEP-0368: SRV records for XMPP over TLS

[^1]: Bei **jabber.hot-chilli.net** kann man auch folgende Servernamen nutzen: **jabber.hot-chilli.eu**, **hot-chilli.net**, **hot-chilli.eu**, **im.hot-chilli.net**, **im.hot-chilli.eu**, **jabb3r.de**, **jabb3r.org**, **jabber-hosting.de** und **xmpp-hosting.de**.

[10]:https://list.jabber.at/
[20]:https://xmpp.mdosch.de/invite/#martin@mdosch.de
[30]:/serverwahl/serverliste#voraussetzungen
