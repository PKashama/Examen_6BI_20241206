# Examen_6BI_20241206

Deze repository bevat drie verschillende Python-scripts die elk een specifieke taak uitvoeren: een GUI-applicatie, een back-upscript en een script voor het automatisch aanmaken van mappen en submappen.

---

## 1. Python GUI Applicatie

Een applicatie gemaakt om op een efficiënte en digitale manier ontbrekende gegevens van studenten te registreren.

### Functionaliteiten:
- Gebruikers voeren hun **voornaam**, **achternaam**, en **studentennummer** in.
- Gebruikers selecteren hun **geslacht** en **klas** uit de gegeven opties.
- Aleen de klassen **5BI**, **6BI**, **5BI**, **6WEWE**, **6ECW**, zijn beschikbaar.
- Foutmeldingen worden weergegeven als verplichte velden leeg blijven.
- Alle ingevoerde gegevens worden opgeslagen in een document binnen een aangewezen map.

---

## 2. Python Script Automatisatie – Backup

Een script dat mappen en bestanden automatisch back-upt naar een backup map.

### Functionaliteiten:
- Gebruikers selecteren de map die zij willen back-uppen.
- De back-upmap wordt opgeslagen in de **C:**-schijf onder een standaard map (`C:/Backup`).
- Het script beheert versies door altijd de nieuwste back-up te bewaren en de oudste te vervangen.

### Belangrijk:
- Bij duplicaten wordt de oude back-up overschreven zonder waarschuwing.

---

## 3. Python Script Automatisatie – Aanmaak Folders en Subfolders

Een script dat automatisch een hoofdfolder en een reeks submappen aanmaakt. Het script genereert ook een logbestand om de uitgevoerde acties bij te houden.

### Functionaliteiten:
- Maakt een **hoofdfolder** en bijbehorende **subfolders** in de opgegeven structuur.
- Genereert een **logbestand** waarin wordt vastgelegd:
  - Welke mappen zijn aangemaakt.
  - De datum en tijd van uitvoering.
  - Eventuele fouten of uitzonderingen tijdens het proces.

### Voordelen:
- Bespaart tijd bij het handmatig aanmaken van complexe mapstructuren.
- Helpt bij het overzichtelijk beheren van bestanden en mappen.

---

## Installatie en Gebruik

1. Zorg ervoor dat Python 3 correct is geïnstalleerd op je systeem.
2. Clone of download deze repository.
3. Installeer eventuele benodigde pakketten zoals `tkinter` en `shutil`.
4. Voer de gewenste script uit:
   - **GUI-applicatie:** `python gui_app.py`
   - **Backup-script:** `python backup_script.py`
   - **Folder-creatie-script:** `python create_folders.py`

---

## Auteur

Dit project is gemaakt als onderdeel van het **Examen Informatica 20241206** door **Plamedie K**.
