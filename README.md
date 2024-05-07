# Security-Toolkit
The Security Toolkit of BaySec.
Botiguard Security-Toolkit v1

Botiguard ist ein umfangreiches, hauseigenes Security Werkzeug der BaySec. Es ist das führende Werkzeug für uns, welches wir auch produktiv bei Kunden nutzen. Für bestimmte Einrichtungen wollen wir dies kostenlos anbieten, um die Cybersicherheit in Deutschland und Bayern zu verbessern. Sie können dies neben Ihren bereits eingesetzten Werkzeugen verwenden oder wenn Sie noch keines haben, sogar vollständig darauf setzen.

**Was ist Botiguard Security-Toolkit?**
Botiguard Security-Toolkit ist eine KI-gestützte Cybersicherheitslösung. Botiguard prüft die Sicherheit eines Auftritts (z.B. einer Stadt) und erstellt voll-automatisch umfangreiche Berichte (im Format PPT, PDF und XLS). Der Kunde erhält ein ganzes Paket an Berichten samt einem Video, in dem unser Bot die Sicherheitslücken erklärt. Das Produkt wurde technisch zur nutzbaren Reife gebracht und fand bereits mehrfach Anwendung.

Der Bot erstellt nun die Berichte. Highlight ist das automatisch generierte Video, in dem der Bot in Wort und Schrift die Sicherheitslücken erklärt (z.B. in Englisch und Deutsch). Die Erstellung des KI-Videos ist experimentell.

**Das bekommen Sie**
* Management Summary als PPT oder PDF (2 Seiten)
* Cybersicherheits-Bericht als PPT oder PDF (je nach Größe 22 Seiten oder mehr)
* Maßnahmen-Katalog als XLS mit detallierten kurzfristigen und langfristigen Maßnahmen (Screenshot folgt)
* Infrastruktur-Übersicht als XLS
* Ergebnisse der Infrastruktur Scans als XLS (z.B. Port Scans, Verschlüsselung, etc.).
* Protokoll des e-Mail Spoofing als XLS
* Ergebnisse der Darknet-Analyse als XLS

**Beispiele**

Abbildungen: Der Bot erstellt automatisch eine Management-Summary über den öffentlichen Sicherheitszustand Ihrer Kommune
![Abbildung: Berichtscover](https://bay-sec.de/github/Botiguard_Bericht2.png)
![Abbildungen: Der Bot erstellt automatisch eine Management-Summary über den öffentlichen Sicherheitszustand Ihrer Kommune](https://bay-sec.de/github/Botiguard_Management_Summary1.png)

Abbildung: Die einzelnen Bereiche aus der Management-Summary werden in der Präsentation nochmal mit einem Tachometer bewertet: grün, hellgrün, gelb oder rot (kritische Lücken gefunden).
![Abbildung: Die einzelnen Bereiche aus der Management-Summary werden in der Präsentation nochmal mit einem Tachometer bewertet: grün, hellgrün, gelb oder rot (kritische Lücken gefunden).
](https://bay-sec.de/github/Botiguard_Beispiel_Verschluesslung.png)

Abbildung: Excel-Datei über die Infrastruktur eines Auftritts. Auch diese EXCEL-Datei erstellt der Bot automatisch. In diesem Fall war alles grau, und es gab keine Treffer (positiv).
Auf die Abbildung weiterer Dateien wird verzichtet. 
![Abbildung: Excel-Datei über die Infrastruktur eines Auftritts. Auch diese EXCEL-Datei erstellt der Bot automatisch. In diesem Fall war alles grau, und es gab keine Treffer (positiv).
Auf die Abbildung weiterer Dateien wird verzichtet.](https://bay-sec.de/github/Botiguard_Port_SCan.png)

Abbildung: In einem Video (experimentell freigegeben) erklärt der Bot die identifizierten Sicherheitslücken und umschreibt diese nochmal verständlich. Der Kunde ist also nicht nur auf Dokumente angewiesen, sondern erhält eine audio-visuelle Präsentation. Entweder in Englisch, Deutsch bereits möglich, sowie weitere Sprachen vorbereitet.
In diesem Video dauert die gesamte Präsentation 18 Minuten. Gerne stellen wir Ihnen einen Beispielbericht zusammen und geben Ihnen einen Link. Echte Namen der Kunden wurden verwischt. 

![Abbildung: In einem Video erklärt der Bot die identifizierten Sicherheitslücken und umschreibt diese nochmal verständlich. Der Kunde ist also nicht nur auf Dokumente angewiesen, sondern erhält eine audio-visuelle Präsentation. Entweder in Englisch, Deutsch bereits möglich, sowie weitere Sprachen vorbereitet.
In diesem Video dauert die gesamte Präsentation 18 Minuten. Gerne stellen wir Ihnen einen Beispielbericht zusammen und geben Ihnen einen Link. Echte Namen der Kunden wurden verwischt.](https://bay-sec.de/github/Botiguard_Video2.png)

**Hinweis:**
Das Produkt Botiguard Security-Toolkit kann auch produktiv verwendet werden.
Allerdings ist diese Doku neu und befindet sich im Aufbau. Daher kann die Installation und Handhabung noch als anstrengend empfunden sein.
Für eine bessere Erfahrung nutzen Sie am besten die vorgefertigte virtuelle Maschine von uns. Wir werden die Doku stetig verbessern.
Aktuell ist das Botiguard Security-Toolkit gedacht für erfahrene, technsiche Experten, etwa Administratoren, Entwickler und IT-Security Experten.

**Kostenlose, Trusted Source (TSv1) Lizenz:**
Für staatliche, oder gemeinnützigen Einrichtungen (z.B. Behörden, Gemeinde, Landratsämter, staatliche Universitäten, Schulen) bieten wir eine kostenlose Lizenz an. Ausgeschlossen sind privatwirtschaftliche Einrichtungen, auch in Teilen, z.B. private Universitäten und natürlich gewinnorientierte Unternehmen. Diese können eine Dienstleistung bei uns einkaufen. Es ist nicht erlaubt die Absicht der nicht-kommerziellen Nutzung indirekt zu Umgehen, z.B. die durch die angeschlossene Stiftung eines Unternehmens. Lesen Sie die License.md Datei in diesem Repo.

**Was wird geprüft?**
Alles, was von außerhalb erreichbar ist, wird geprüft, z.B:
Suche von durchgesickerten Daten (z.B. Passwörter, eMails, Telefonnummern etc.) im Darknet
Automatischer e-Mail Phishing Test
Sicherheitsanalyse der Webseite(n)
Sicherheitsanalyse der Internet-Domain (DNS)
Sicherheitsanalyse des eMail Systems des Auftritts (z.B. Ihrer Gemeinde)
Automatisierte Port-Scans, und detaillierte Überprüfung von FTP, SSH, Samba und VNC Ports u.w.
Detaillierte Überprüfung der Kryptografie Einstellungen
Überprüfung auf sensible Daten im Internet-Auftritt (z.B. Administrations-Bereiche, Content-Management Systeme).
Erkennung der öffentlichen Infrastruktur und Sub-Infrastrukturen...
.. und mehr

**Technische Voraussetzungen:**
* Für die Darknet-Analyse, brauchen Sie einen Zugang für Dehashed.com, oder einer anderen kompatiblen Dankbank. Dehashed.com verlangt zwei Pläne: Einmal für den generellen Zugriff. Hier können Sie zwischen mehreren Varianten wählen (Ein paar Tage, Monate oder ein ganzes Jahr). Der API-Zugang kostet nochmal Extra. Danach erhalten Sie einen API Key. Den API Key können Sie in Botiguard konfigurieren.
* Sie brauchen einen "freien" SMTP Server für die Spoofing Tests, die Zugangsdaten können Sie dann konfigurieren.
* Sie müssen Python und die notwendigen Abhängigkeiten installieren.

**Vorgefertigte Maschinen:**
Einfacher ist es mit unserer vorgefertigten Maschine zu starten.

**Zugriff bekommen:**
Schreiben Sie uns eine eMail an botiguard@bay-sec.de. Wir verifizieren ob Sie eine staatliche Einrichtung sind und geben Ihnen anschließend Zugriff auf unser Git Repository. Sie können dann den Quellcode einsehen und herunterladen. Gerne können Sie dann auch eine der vorgefertigten VirtualBox Maschinen herunterladen, um sofort starten zu können. Dies ist auch unsere Empfehlung. Eine selbstständige Installation ist sehr aufwändig und die Doku für eine selbstständige Installation noch nicht fertig. Sie werden gerade in der Anfangszeit Probleme erfahren.

Wieso kein "echtes" Open Source? Trusted Source ist doch "Closed Source"!
Das stimmt, wenn man es genau nimmt, ist unsere Lösung keine echtes Open Source. Wir wollen nicht, dass unsere Lösung, vollständig Open Source ist aus mehreren Gründen:
Erstens, könnte unsere Lösung als Cyberwaffe missbraucht werden. Damit erlangen die Hacker einen Vorteil und nutzen sicher dies als Angriffswerkzeug. Wir öffnen den Source Code daher nur gegenüber vertrauenswürdigen Stellen.
Zweitens, wollen wir kontrollieren, wer im Code selbst beitragen darf. Wenn vertrauenswürdige Stellen Beiträge zum Code machen, reduziert dies das Risiko von Supply Chain Angriffen.
Drittens, wir brauchen auch eine Grundlage, um Geschäft zu machen und um, dieses Produkt nachhaltig finanzieren zu können.

Werden Daten an BaySec übertragen oder gibt es Hintertüren?
Nein, es werden keine Daten an uns übermittelt.

**Nachteile:**
wenn Sie die kostenfreie Software selbst nutzen, können Sie unsere vorgefertigte Maschine verwenden oder müssen gegebenenfalls Ihre eigene Umgebung aufbauen. Das schafft ggf. Aufwand bei Ihnen. Wenn Sie den Source Code selbst nutzen, bieten wir soweit gesetzlich zulässig keine Gewährleistung, Sachmängelhaftung oder Garantien an, dass sich die Software für Ihre angedachten oder für bestimmte Zwecke nutzen lässt oder fehlerfrei funktioniert. Das Angebot ist freibleibend und es gilt die zum Zeitpunkt der Ausgabe mitgeltende Lizenz.

Wenn Sie entsprechende Risiken umgehen möchten, beauftragen Sie uns die Tests für Sie durchzuführen. Die Verantwortung übernehmen wir dann, z.B. für Updates, Betriebskosten.

**Grundeinrichtung:**
1) Fragen Sie einen Zugriff an unter botiguard@bay-sec.de. Wir prüfen Ihre Anfrage und geben Ihnen Zugriff auf unser Github Projekt.
Bitte nennen Sie uns die E-Mail-Adressen bzw. Github Usernamen die wir freigeben wollen.
Wenn Sie weitere Lieferungen darüber hinaus benötigen, kann dies kostenpflichtig sein (z.B. als ZIP als Download).

2) Laden Sie sich anschließend die vorgefertigte virtuelle Maschine herunter (empfohlen) oder bauen Sie sich selbst eine Umgebung auf.

3) Nehmen Sie eine Grundkonfiguration vor:
In "configs/spoofing_smtp_configuration.json" können Sie den eMail Server angeben, welcher das Spoofing verwenden soll.
Ändern Sie den API Key "dehashed_apikey" in Datei "bin/1_scanner_darknet_leaks.py"
Wenn Sie Ihre Berichte am Ende Ihre Nextcloud hochladen wollen, müssen Sie noch die Konfiguration dafür anpassen. Gehen Sie unter "5_uploader.py" und ändern:
nc = nextcloud_client.Client('https://url-to-your-nextcloud.com')
nc.login('nextcloud_username', 'nextcloud_password')

**Erste Schritte:**
1) Als nächstes können Sie das Testobjekt konfigurieren. Kopieren Sie die orderfiles/template_order.json zu z.B. order_stadt-freilassing.de.json
Der Domainname ist dabei Teil des Dateinamens.
Öffnen Sie die Datei und füllen alle Felder aus.

2) Führen Sie Ihren Scan durch:
Für einen vollständigen Scan, inklusive Darknet-Prüfung und eMail Sicherheit, tippen Sie ein:
```
./bin/controlscript.sh stadt-freilassing.de
```

Wenn Sie jedoch keinen Mail-Server haben führen Sie das wie folgt aus:
```
./bin/controlscript.sh stadt-freilassing.de
```

Wenn Sie kein Dehashed Konto haben, führen Sie das wie folgt aus:
```
./bin/controlscript.sh stadt-freilassing.de noleakcheck
```

Wenn Sie keinen Upload Server haben, können Sie den Upload am Ende weglassen. Ihre Daten bleiben dann lokal:
```
./bin/controlscript.sh stadt-freilassing.de noupload
```

Ein Bericht kann zwischen 10 Minuten oder mehrere Stunden dauern, je nach Größe!
Ihre Berichte sollten nun unter /results zur Verfügung stehen.
Viel Spass und viel Erfolg.

