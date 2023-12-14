# <img alt="Aseprite German Translation Preview" src="https://github.com/inxomnyaa/Aseprite-German-Translation/blob/main/image/de.png" height="100px" width="auto"> Aseprite German Translation [![Translation Status](https://hosted.weblate.org/widget/aseprite/aseprite/de/svg-badge.svg?native=1)](https://hosted.weblate.org/engage/aseprite/-/de/)
![Aseprite German Translation Preview](https://github.com/inxomnyaa/Aseprite-German-Translation/blob/main/image/2023-12-13_234021.png)

# 🇩🇪 Deutsch
## Installieren
1. Laden Sie die `.zip`-Datei herunter (github > Code-Dropdown > ZIP herunterladen)
2. Gehen Sie zu `Edit` > `Preferences` > `Extensions` > `Add Extension` (`Bearbeiten` > `Voreinstellungen` > `Erweiterungen` > `Erweiterung hinzufügen`)
3. Wählen Sie die heruntergeladene `.zip`-Datei der Spracherweiterung
4. Gehen Sie dann zu `Edit` > `Preferences` > `General` > `Language` (`Bearbeiten` > `Voreinstellungen` > `Allgemein` > `Sprache`) und wählen Sie die neue Sprache in der Combobox
5. Drücken Sie auf die Schaltfläche OK.

## Konvertierungsskript für Weblate-Dateien (vor Aseprite v1.3.3)
Aseprite unterstützt die .ini-Dateien von Weblate in der Version v1.3.2 noch nicht.
Die Entwickler planen jedoch, diese Unterstützung in v1.3.3 hinzuzufügen, siehe [diesen Kommentar](https://github.com/aseprite/languages/issues/30#issuecomment-1854507501) für weitere Informationen.

Da der Hauptunterschied in den Übersetzungsdateien in der unterschiedlichen Darstellung von Zeilenumbrüchen (\n) zu liegen scheint, habe ich 2 Skripte zur Konvertierung der .ini von Weblate in eine kompatible Version beigefügt.
### Verwendung
#### Linux 🐧
- Machen Sie das Skript ausführbar, indem Sie `chmod +x convert.sh` ausführen.
- Führen Sie das Skript aus, indem Sie den folgenden Befehl ausführen: `. ./convert.sh < input.ini > output.ini`, wobei `input.ini` die von Weblate heruntergeladene Datei ist.
#### Windows 🪟
- Das Skript nimmt 2 optionale Parameter an:
- `InputFile`, Standard: `input.ini`
- `OutputFile`, Standard: `output.ini`
- Führen Sie das Skript durch einen Doppelklick auf `.\convert.ps1` aus. Dazu muss die Datei von Weblate `input.ini` genannt werden. Oder
- Führen Sie das Skript über PowerShell/Terminal wie folgt aus: `.\convert.ps1 -InputFile c:\path\to\input.ini -OutputFile c:\path\to\output.ini`

# 🇺🇸 🇬🇧 English
## Install
1. Download the `.zip` (github > Code dropdown > Download ZIP)
2. Go to `Edit` > `Preferences` > `Extensions` > `Add Extension`
3. Select the downloaded `.zip` of the language extension
4. Then go to `Edit` > `Preferences` > `General` > `Language` and select the new language in the combobox
5. Press the OK button.

## Conversion script for Weblate files (pre Aseprite v1.3.3)
Aseprite does not support the .ini files from Weblate as of v1.3.2
The developers are planning to add support for it in v1.3.3 though, see [this comment](https://github.com/aseprite/languages/issues/30#issuecomment-1854507501) for more information.

Since the main difference appears to be a different representation of translations with line breaks (\n), I have included 2 scripts for converting the .ini from Weblate into a compatible version.
### Usage
#### Linux 🐧
- Make the script executable by running `chmod +x convert.sh`
- Execute the script by running `. ./convert.sh < input.ini > output.ini`, where `input.ini` is the file downloaded from Weblate.
#### Windows 🪟
- The script takes in 2 optional parameters:
- - `-InputFile`, default: `input.ini`
- - `-OutputFile`, default: `output.ini`
- Run the script by double-clicking `.\convert.ps1`. This requires naming the file from Weblate `input.ini`. Or
- Run the script from PowerShell/terminal like `.\convert.ps1 -InputFile c:\path\to\input.ini -OutputFile c:\path\to\output.ini`
