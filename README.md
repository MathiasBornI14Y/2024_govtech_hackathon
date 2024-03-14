# GovTech-Hackathon 2024: iSurvey

Baue eine Brücke zwischen der I14Y-Interoperabilitätsplattform und dem Online-Befragungstool Limesurvey.

## Limesurvey

Lokale Installation mit Docker

```

docker pull crramirez/limesurvey:latest
docker run -d --name limesurvey -p 80:80 crramirez/limesurvey:latest

``` 

Die Installation läuft anschliessend unter ```http://localhost```. Dort kann die Plattform konfiguriert werden. (Das Passwort für die Datenbank ist leerzulassen. Weitere Infos zur Konfiguration sind in der [Beschreibung des Docker-Images](https://hub.docker.com/r/crramirez/limesurvey/) zu finden.

