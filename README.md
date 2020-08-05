# 1. FCK Triathlon Team Homepage

## Seiteninhalt verändern

### Voraussetzungen

* Github account und Mitglied in der GH-Gruppe fck-triathlon-team (Falco fragen)
 
* Eine Git versionsverwaltungssoftware, zum Beispiel die von Github: `http://desktop.github.com`

* Die Software `Jekyll` (www.jekyllrb.com) installieren

### Den Seitenquelltext runterladen

* Per git den quelltext von der Adresse: `https://github.com/FCK-Triathlon-Team/fck-triathlon-team.github.io.git` herunterladen.

### Die Seite bearbeiten

**** Die Software Jekyll baut aus den eizelnen Seiten und den Stilvorlagen die fertigen Webseiten. Sie kann zum entwickeln
  lokal als Server gestartet werden und man kann mit einem Browser dann seine Änderungen anschauen.

* Der Server erkennt automatisch wenn eine Seite verändert wurde und aktualisiert die Seiten dann. Wenn man die Seite dann
  im Browser neu lädt, erhält man die aktualisierte Version.

* In der Powershell in das Basisverzeichnis der Seite wechseln und `jekyll serve` ausführen. Im Browser dann die
  Adresse `http://localhost:4000` eingeben und die Seite sollte angezeigt werden.

### Die Änderungen hochladen

* Per Git werden die Änderungen dann lokal eingetragen/commit (am besten mit einem aussagekräftigen Kommentar) und dann 
  auch auf den Github Server hochgeladen (push). Einige Sekunden nach dem Hochladen geht die Seite dann automatisch live.
