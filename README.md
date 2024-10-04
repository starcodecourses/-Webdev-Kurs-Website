# Webdev-Kurs-Website
Dieses Repository enthält die Inhalte der Webdev-Kurs-Website, auf der Lehrmaterialien für den Webdev Kurs bereitgestellt wird.

Dieses Repository enthält die Website mit dem Kursmaterial. Die Website wurde mit [Docusaurus 2](https://docusaurus.io/) erstellt. Die Website wird auf GitHub Pages gehostet und ist [hier](https://jantiegges.github.io/WebDev-Course/) erreichbar.


## Nutzung

### Installation
```
$ yarn
```

### Lokale Entwicklung
```
$ yarn start
```

Dieser Befehl startet einen lokalen Entwicklungsserver und öffnet ein Browserfenster. Die meisten Änderungen werden live angezeigt, ohne dass der Server neu gestartet werden muss.

### Build
```
$ yarn build
```

Dieser Befehl generiert statische Inhalte im Verzeichnis `build` und kann mit jedem Hosting-Service für statische Inhalte bereitgestellt werden.

### Deployment
Mit SSH:

```
$ USE_SSH=true yarn deploy
```

Ohne SSH:
```
$ GIT_USER=<Dein GitHub-Benutzername> yarn deploy
```

Wenn du GitHub Pages zum Hosting verwendest, ist dieser Befehl eine bequeme Möglichkeit, die Website zu erstellen und in den `gh-pages`-Branch zu pushen.

