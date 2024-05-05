---
layout: plain
sitemap: true
permalink: /archiv/
---

# Archiv

## Quick Start
### Archiv clonen / herunterladen

Das Archiv kann entweder per GIT[^1] geclont oder als ZIP heruntergeladen werden.

GIT: Clonen mit HTTPS `git clone https://github.com/theghostdivision/erbschuld.git` wahlweise SSH<br/>
ZIP: [Archiv.zip](https://archiv.erbschuld.info/main.zip)

### Lokale Ausführung
1. Repository herunterladen [Archiv.zip](https://archiv.erbschuld.info/main.zip) und unzippen -  alternativ mit GIT clonen.
2. Im terminal `cd` in das root Verzeichnis (in dem sich `_config.yml` befindet).
3. `bundle install`[^2] ausführen.
4. `bundle exec jekyll serve` ausführen
5. Im Browser zu <http://localhost:4000> navigieren

## Nächste Schritte
* Dateien öffnen und die Kommentare lesen, falls es Fragen zu den Einstellungen geben sollte

[^1]: [GIT](https://git-scm.com/)
[^2]: Benötigt Bundler und Ruby. Bundler und benötigte Gems mit `gem install bundler` installieren.<br/>Falls erforderlich Ruby (3.1 empfohlen)mit Devkit installieren.<br/>Windows: [Rubyinstaller](https://rubyinstaller.org/downloads/), auf Linux (rbenv / RVM) bzw. macOS (RVM) sollte Ruby  vorhanden sein.