# Stiller und Partner Mediengruppe GmbH/Holding
In diesem Repository findet ihr die gesamte Dokumentation des ERP systems der Stiller und Partner Mediengruppe GmbH. 

> zum Unternehmen: [Hier Klicken](https://sebastianstiller.at/unternehmen)

## Rechtliche Informationen
### Herausgeber/Urheber
> &emsp; **Name:** Sebastian Stiller 
### Kontakt: ### 
> &emsp; **Telefon**: +43 660 2084555 \
> &emsp; **E-Mail**: [Kontakt](mailto:kontakt@sebastianstiller.at) \



## Durchführen von commit

```bash
git add -A
git commit -m "your commit message"
git push
```
### Hinweis zu commits
Um die Struckurierung der Commits so einfach wie möglich zu gestalten werden Collaborators gebeten bei ihren Messages folgendes Schema beizubehalten 

> Update **{Datum}_{Sequenznummer (ab dem zweiten Commit)}**: **{significant change description}**

Somit sollte eine Valide Commit Message beispielhaft wie folgt aussehen

```Bash
git commit -m "16.03.2026_{2->n}: expanding README.md (Adding Commit Message Example)
```

### Hinweis zur Preview
Wenn sie Visual Studio Code als Editor verwenden müssen sie bitte folgende Dinge beachten. 

1. **Notwendige Erweiterungen**

| Erweiterung      | Beschreibung      |
| -------------    | ------------- |
|AsciiDoc          | Grundlegende Erweiterung für AsciiDoc IntelliSense |
| PlantUML         | Erweiterung zur korrekten Darstellung von PlantUML Diagrammen | 

2. **Notwendige Einstellungen**

Damit VS-Code das Alles auch richtig darstellt müssen noch eine Einstellung vorgenommen werden.

In den VS-Code Einstellungen (Zahnradsymol links unten) suchen sie nach 
```
AsciiDoc: Enable_Kroki
```
Und aktivieren sie diesen Punkt.

