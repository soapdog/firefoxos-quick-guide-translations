# Deine App verteilen {#distribution}

Jetzt wo unsere Anwendung fertig ist, müssen wir herausfinden, wie wir sie an den Mann bringen. Im [Einführungskapitel](#introduction) erwähnte ich, dass anders als bei Apple Mozilla dich nicht dazu zwingt, ihren Distributions-Kanal zu benutzen - wir sind frei unsere Werke so zu verteilen, wie wir möchten. In diesem Kapitel werden wir lernen, wie wir unsere App **außerhalb des [Firefox Marketplaces](http://marketplace.firefox.com)** verteilen.

Meiner bescheidenen Meinung nach ergibt das Verteilen deiner Anwendung außerhalb des Firefox Marketplaces in zwei Situationen Sinn.

 1. Du entwickelst eine Anwendung für den firmeninternen Gebrauch oder einem anderen eingeschränkten Nutzerkreis. Falls du sie im Marketplace einreichst, wird sie für jeden verfügbar sein und wenn du den Gebrauch der App auf eine Gruppe Personen einschränken willst, musst du irgendeine Form von Authentifizierungsschema mit einem Server-Backend oder Ähnliches einführen. Beispielsweise bittet die *Evernote*-Anwendung beim ersten Start den Benutzer, sich auf ihre Server einzuloggen.

 2. Du hast bereits eine riesige Nutzer-Basis, die du für die Verteilung deiner App heranziehen kannst. Ein Beispiel davon wäre ein Zeitungsverlag wie die *Financial Times*, die ihre App einfach auf der eigenen Seite anbieten kann und damit die meisten ihrer Nutzer erreicht. Behalte im Hinterkopf, dass du deine Anwendung aber auch gleichzeitig innerhalb wie außerhalb des Marketplaces anbieten kannst, so dass du bei bereits bestehenden Marketing-Kanälen diesen zum Durchbruch verhelfen und gleichzeitig den Marketplace zum Erreichen neuer Nutzer außerhalb deines eigenen Kanals nutzen kannst.

Der Verteilungsprozess für Hosted und Packaged Apps ist vergleichbar, aber benutzt unterschiedliche Funktionen. Daher betrachte ich sie getrennt. Unabhängig davon bleibt der Workflow gewöhnlich der selbe: Du stellst einen Knopf oder Link auf deiner Homepage bereit, der etwa sagt **Klicken zum Installieren der App** oder du benutzt eine spezielle URL, die die Installationsroutine anwirft. In beiden Fällen wird ein Dialog angezeigt, der den Benutzer um seine oder ihre Zustimmung zur Installation der fraglichen App bittet.

## Hosted Apps

<<[Code zur Installation einer Hosted App](code/distribution/hosted_apps_distribution.js)

Im obigen Beispiel beinhaltet die `manifestURL` die Adresse zur Manifest-Datei. Sobald dieser Code ausgeführt wird, fragt das System den Benutzer um Zustimmung zur Installation der gegebenen Anwendung und führt in Abhängigkeit der Wahl entweder den success- oder error-Callback aus.

Um mehr über diese API-Überprüfung zu lernen, lies dir [die MDN-Seite über die Installation von Anwendungen](https://developer.mozilla.org/docs/Apps/JavaScript_API) durch.

## Packaged Apps

Die Installation von Packaged Apps ist vergleichbar, aber anstelle des Aufrufs von `mozApps.install()` rufen wir `mozApps.installPackage()` auf wie im Code-Beispiel unten dargestellt.

<<[Code zur Installation einer Packaged App](code/distribution/packaged_apps_distribution.js)

W> Warnung: Ich habe den Eindruck, dass die Installation einer Packaged App außerhalb des Marketplace für Firefox OS in der Version 1.0.1 nicht möglich ist. Auch wenn die API dokumentiert ist, habe ich es nie versucht. Falls du es probieren solltest, gib mir Rückmeldung, so dass ich dieses Buch entsprechend aktualisieren kann.

## Zusammenfassung 

Dieses Kapitel besprach Möglichkeiten zur Verteilung von Anwendungen außerhalb des Firefox Marketplaces unter Verwendung der Installations- und Verwaltungs-APIs für *Offene Web-Anwendungen*. Es gibt daneben noch viele andere Routinen, die Dinge erledigen wie das Überprüfen auf bisherige Installation (so dass du den *Klicken zum Installieren der App*-Knopf verstecken kannst). Um mehr über diese APIs zu erfahren, lies die [MDN-Seite zur Installation von Anwendungen](https://developer.mozilla.org/docs/Apps/JavaScript_API) (ja, ich hab dir den Link schon vorher empfohlen - dieses Mal folge ihn! Es gibt dort wichtige Sachen).

Im nächsten Kapitel werden wir lernen, wie wir unsere App über den Firefox Marketplace verteilen.
