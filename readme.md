# Umfrage Server/Client
## Server
### Vorbereitungen
Zunächst müssen die notwendigen Komponenten installiert werden.
```
cd Server
npm install
```
### Starten des Servers
Nach der Installation der Pakete kann der Server gestertet werden.
```
npm start
```
Der Server läuft standradmäßig auf Port 3000, über http://localhost:3000 kann abgefragt werden ob der Server ordnungsgemäß läuft.
## Client
Auch hier müssen zunächst die notwendigen Module geladen werden.
```
cd Client
npm install
```
Der Client ist eine Angualr CLI Anwendung und kann wie folgt gestartet werden.
```
ng serve
```
Anschließend kann der Client aufgerufen werden via http://localhost:4200