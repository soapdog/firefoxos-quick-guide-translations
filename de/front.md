{frontmatter}

## Danksagungen 

An meine Ehefrau Lili, die beste Frau der Welt!

An Mozilla, dafür, dass sie immer an uns glaubten, dass sie das Web offen und frei halten und dafür, dass sie immer den Benutzer an erste Stelle setzen!

An die brasilianische Mozilla-Community dafür, dass sie mich so klasse aufnahmen und einfach nur beeindruckend sind!

An meinen GSoC-Mentor Marcos Caceres, dem Mozilla WebAPI-Team, den Mozilla Tech-Evangelisten und dem Dev Engagement-Teams dafür, dass sie mehr als nur beeindruckend sind!

An Google für den Google Summer of Code 2013 (GSoC)! Dieses Programm ist einfach nur wundervoll.

## Dieses Buch befindet sich im fortwährendem Beta-Status

Mein Plan ist es, dieses Buch oft zu aktualisieren und seine Inhalte zu erweitern, sowie neue Probleme von den Lesern aufgeworfen werden. Da einige APIs immer noch für Firefox OS implementiert werden, willst du sicher gehen, auch eine aktuelle Version dieses Buches zu lesen.

## Über mich

In diesem Buch wirst du viele Abschnitte finden, in denen ich meine eigene Meinung ausdrücke und Entscheidungen treffe, die so vielleicht nicht von anderen Programmierern getroffen werden würde - insbesondere, wenn es hilft, eine Idee einfacher zu erklären. Ich werde immer versuchen, es klar zu machen und meine Gründe zu erläutern, wenn ich meine eigene Meinung kund tue. Wie dem auch sei, falls es einen Fehler bei dem gibt, was ich sage, werde ich den Text überarbeiten und das Buch aktualisieren. Lies im Abschnitt Feedback & Pull Requests für weitere Informationen.

## Wie dieses Buch entstand

Ursprünglich hatte ich dieses Buch in meiner freien Zeit geschrieben - aber dank der guten Hilfe von meinem Google Summer of Code (GSoC) Mentor, Marcos Caceres, wurde dieses Buch Teil meines GSoC-Projekts - welches darauf abzielte, eine nützliche Entwickler-Quelle für Firefox OS zu erstellen. Von daher, riesigen Dank an Google, dass sie diese Arbeit finanziert haben und an das Web API-Team von Mozilla dafür, dass sie mich sie den Sommer über besuchen ließen.

## Auf dem aktuellsten Stand bleiben

Dieses Buch wird **kostenlos** über [Leanpub](http://leanpub.com) vertrieben.

Du kannst dich mit deiner E-Mail-Adresse dort registrieren, um automatische Aktualisierungen nach dem Herunterladen dieses Buches von der [Leanpub Buchseite](http://leanpub.com/quickguidefirefoxosdevelopment) zu erhalten. Der Plan ist dabei, dieses Buch mehrere Male im Monat zu aktualisieren. Falls du das Buch von einem Freund oder aus einer anderen Quelle erhalten haben solltest, überlege dir, ob du nicht zu obiger Seite gehen möchtest, um es herunterzuladen und dich dabei zu registrieren. Auf diese Weise kannst du sicher stellen, über Aktualisierungen benachrichtigt zu werden.

## Spenden

Ein Buch zu schreiben verlangt eine Menge Arbeit und ich würde gerne mehr Zeit in diese Art von Aktivitäten stecken, wenn der Google Summer of Code 2013 vorbei ist. Jene, die meinen, dass dieses Buch nützlich (oder cool) ist, möchten vielleicht den Preis-Regler auf der Leanpub Download-Seite höher schrauben und mir eine kleine Entschädigung in beliebiger Höhe zukommen lassen. All jene, die lieber über PayPal spenden möchten, können mich über *agarzia@mac.com* erreichen.

Unabhängig von den Spenden solltest du deine E-Mail-Adresse auf der Download-Seite angeben, um über Aktualisierungen benachrichtigt zu werden, wenn das Buch erneuert wird!

## Wie man den Autor erreichen kann

Um Kommentare und Feedback einzusenden, schreibe mir eine E-Mail an [fxosquickguide@andregarzia.com](mailto:fxosquickguide@andregarzia.com). Meine Website ist [http://andregarzia.com](http://andregarzia.com). Mein Twitter-Account ist [@soapdog](http://twitter.com/soapdog).

Wenn du die Inhalte dieses Buches verbessern möchtest, lies bitte den Abschnitt Feedback & Pull Requests.

## Cover Illustration

Die Cover-Seite wurde von Raphael Eckhardt erstellt, ein Designer und Illustrator aus Brasilien. Du kannst seine Arbeit unter [http://raphaeleckhardt.com/](http://raphaeleckhardt.com/) einsehen. Dort kannst du auch mit ihm Kontakt aufnehmen (er ist Freischaffender).

## Wer sollte dieses Buch lesen

Dieses Buch ist für Leser mit mittleren Kenntnissen in HTML, CSS und JavaScript geschrieben, die mobile Anwendungen für Firefox OS schreiben wollen. HTML, CSS und JavaScript zu lehren, übersteigt den Rahmen dieses Buches. Ich werde dir aber Verweise auf gute Referenz-Bücher geben.

## Best Practices vs. Anfänger-Freundlichkeit

Erfahrene Entwickler werden bemerken, dass ich manchmal nicht alle Good Practices im Beispiel-Quellcode folgen werde. Auch wenn ich Anti-Patterns zu vermeiden versuche, bemühe ich mich, sich sofort aufrufende Funktionen und andere vergleichbare Praktiken auf ein Minimum zu reduzieren. Der Hauptgrund dafür liegt darin, dass dies ein Einführungsbuch ist. Bewährte Programmierer werden merken, wann und wie Dinge umgeändert werden müssen, während Anfänger-Programmierer immer noch in der Lage sind, zu verstehen, was vor sich geht. Sämtlicher Code hier funktioniert und sowie ich das Buch aktualisier, gehe ich noch einmal durch den Code und verwende mehr und mehr Best Practices in Abhängigkeit vom Feedback der Leser.

Wenn du noch tiefer in die Welt von hochqualitativem JavaScript-Programmieren eintauchen willst, gibt es hier einige gute Bücher:

* [JavaScript: The Good Parts](http://shop.oreilly.com/product/9780596517748.do): DAS Buch zu JavaScript.
* [JavaScript Patterns](http://shop.oreilly.com/product/9780596806767.do): Entwurfsmuster und Best Practices.
* [JavaScript Enlightenment](http://shop.oreilly.com/product/0636920027713.do): Fortgeschrittene JavaScript-Techniken.
* [Maintainable JavaScript](http://shop.oreilly.com/product/0636920027713.do): Code schreiben, der leicht zu warten und zu verwenden ist.

## Feedback & Pull Requests

Dies ist ein Freies und Offenes Buch und ich freue mich über jedes Feedback, dass Menschen mir geben können. Sämtlicher Inhalt dieses Buches befindet sich im [GitHub Repository](https://github.com/soapdog/firefoxos-quick-guide) und wurde mit Markdown geschrieben (plus einige Erweiterungen von Leanpub). Um mir Feedback, Bugfixes und Verbesserungen zukommen zu lassen, schicke einfach ein Pull Request. Danke schon einmal im Voraus für alle Beiträge.

Das Git Repository für dieses Buch befindet sich auf [https://github.com/soapdog/firefoxos-quick-guide](https://github.com/soapdog/firefoxos-quick-guide).

## Übersetzungen

Dieses Buch wurde ursprünglich auf Portugiesisch geschrieben und dann von mir in's Englische übersetzt. Beide Versionen sind frei erhältlich im Netz:

* [Portugiesische Version](http://leanpub.com/guiarapidofirefoxos): Guia Rapido para Desenvolvimendo para Firefox OS.
* [Englische Version](http://leanpub.com/quickguidefirefoxosdevelopment): Quick Guide for Firefox OS App Development.

Ich begrüße jede Hilfe, dieses Buch in weiteren Sprachen zu übersetzen (und mein gebrochenes Englisch zu überarbeiten).

## Versionsverlauf

### Version 0.2

Dieses Buch wurde von Marcos Caceres aus dem WebAPI-Team von Mozilla überarbeitet. Der Inhalt von jedem Kapitel wurde auf technische Korrektheit überprüft und viele grammatikalische Fehler und Rechtschreibfehler wurden dabei entfernt.

### Version 0.1

Dies ist die erste Version dieses Buches. Ich bin immer noch dabei, es an einen Lektor zu senden, denn es wurde noch nicht auf Rechtschreibfehler, grammatikalische Fehler usw. geprüft. Englisch ist nicht meine Muttersprache, also korrigier mich bitte, wenn ich irgendwo einen Fehler gemacht habe. Was du hier liest, begann am 20. August 2013 als eine Schnellanleitung auf der [BrazilJS Conference](http://braziljs.com.br/), die am 22. und 23. stattfand. Von daher liest du eher einen schnellen Entwurf von zwei Tagen.

Ich benutze das [Leanpub](http://leanpub.com) System, um das Buch zu schreiben. Dieses erlaubt mir, schnell voranzukommen und das Projekt zu verwalten. Diese Version ist also eine quasi-wörtliche Übersetzung des portugiesischen Originals.

{mainmatter}
