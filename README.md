dschungelbuch-siegen
====================

Das Dschungelbuch von Klaus Reifenrath in TeX

Uschi und Estban Shure machten mich auf Klaus Reifenraths ["Dschungelbuch Siegen" (Stand Dez.2014) ](http://krsiegen.de/wp/?page_id=466) aufmerksam, eine Sammlung von Informationen, Möglichkeiten, Organistationen, Adressen, Öffnungszeiten um in Siegen und Umgebung zurecht zu kommen.

"Dschungelbuch Siegen" von Klaus Reifenrath
--------------------

Informationen für Menschen in und um Siegen mit wenig oder keinem Einkommen.
* Die Idee zum „Dschungelbuch Siegen“ ist mit Freunden und Betroffenen entstanden.
* Wir haben diese Informationen zusammengestellt und sie unter dem Namen “Dschungelbuch Siegen“ im Internet veröffentlicht.
* Zu finden über Google „Dschungelbuch Siegen“
* oder unter www.krwe.de
* Dort können Sie das „Dschungelbuch Siegen“ kostenlos herunterladen, lesen oder ausdrucken und gerne an Menschen, die es interessiert, weitergeben.
* Es besteht KEIN Copyright und kein kommerzielles Interesse! Bitte weiterreichen.
* Es soll einfach nur eine Hilfe im Dschungel der Stadt darstellen.
* Wir suchen nach weiteren sozialen Einrichtungen in Siegen und Umgebung, damit wir das „Dschungelbuch Siegen“ erweitern können.
* Senden Sie uns bitte per Mail eine Nachricht, wenn Sie im „Dschungelbuch Siegen“ etwas lesen, das sich geändert hat.

"dschungelbuch-siegen"
--------------------

Diese Repository dient dem TeX-en von Klaus "Dschungelbuch Siegen". Alle Anmerkungen, Erweiterungen und Fehler bitte als Issue aufgeben oder für einen pull request selber korrigieren. 

### "Where to start"

Hier ein paar Erklärungen, wie du mitmachen kannst:

### Design

Im Ordner "./Pictures/" kann man folgendes ablegen: 

* Bilder für das Buch
* Bilder von Orten, die im Buch erwähnt werden

Um am Buchlayout zu entwicklen, empfehle ich die Seiten
* ./dschungelbuch.tex
* ./structure.tex
* ./kapitel/einleitung.tex

### Inhalt

Die bisherigen Kategorien erkennt man an den Ordnern in "./kapitel/":
 * alter
 * anzeigenmarkt 
 * begegnung
 * beratung
 * fortbewegung 	
 * garten 	
 * hausstand 	
 * jugend 	
 * kleidung 	
 * kultur 	
 * nahrung 	
 * reparaturen 	
 * tiere

In diesen Kategorien sind jeweils Artikel eingebunden, die relevante Informationen enthalten. Um eine eigene Überschrift zu bekommen, sollten sie folgendes enthalten: 

    \section{Gewünschte Überschrift}\index{Indextext}

Der Indextext lässt diesen Artikel im Index auftauchen (kommt noch). 

### Issues

In den Issues dieses Repositories findest du bestimmt eine Liste von Dingen, die getan werden müssen. Dringend, so meine ich, ist ein Layout für Adressen und Öffungszeiten.


Happy Hacking!
.nanooq

