# macOS-Configuration

## Systemeinstellungen

### Allgemein

- Erscheinungsbild: Dunkel
- Seitenleistensymbole: Mittel
- Standard Webbrowser: (later)
- Handoff: off

### Schreibtisch und Bildschirmschoner

- Upload background image and set as background
- Configure Wirbel

### Dock

- Effekt: Linear
- Tabs bevorzugen: Manuell
- Doppelklick: Zoomen
- Fenster hinter Programmsysmbolen ablegen: ein
- Öffnen von Programmen animieren: aus
- Dock automatisch ein- und ausblenden: ein
- Zuletzt verwendet: aus

### Spotlight

Suchergebnisse: alles aus bis auf

- Programme
- Rechner
- Systemeinstellunge 

### Monitore

Mehr Fläche (für 13" Laptop)

### Energie sparen

Batterie: Monitor ausschalten nach: 15 min
Netzteil: Monitor ausschalten nach: 1 Std

### Tastatur

Tastatur: 

- Tastenwiederholung Schnell - 1
- Ansprechverzögerung: kurz
- Standard-Funktionstasten: ein

Sondertasten:

- Feststelltaste: ESC

Kurzbefehle -> App-Tastaturkurzbefehhle

- + Mail.app Senden Cmd-Return

### Trackpad

Zeigen und klicken: 

- Zeigerbewegung: Schnell - 3

### Benutzer und Gruppen

Bild: ändern

Anmeldeobjekte: FIXME (später)

### Bedienungshilfen

Anzeige:

- Bewegung reduzieren: ein
- Kontrast erhöhen: ein
- Kontraste: Normal + 1

## root Password


## brew

Install brew:

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

Commandline tools:

```
brew install htop vim midnight-commander ncdu python wget cask
```

Applications

```
brew cask install alt-tab gimp hammerspoon keka macvim mpv iina skype google-chrome vlc dropbox firefox bbedit grandperspective skype-for-business rocket-typist bettertouchtool bartender google-chat itsycal google-drive-file-stream karabiner-elements
```

## Default Applications

### Finder

- Enable path and status bar

### Terminal

### Mail

- Configure accounts
- Install keyboard plugin
- Rules
- Gspamblock


## Chrome Web Apps

- Feedbin
- Google Calendar

## Config files

## Installed Applications

### Karabiner Elements

### Patch Google Chat CSS

## Install Microsoft Office

FIXME

## App Store

- [Copyclip](https://apps.apple.com/de/app/copyclip-clipboard-history/id595191960?mt=12)
- [Meeter](https://apps.apple.com/de/app/meeter-f%C3%BCr-zoom-teams-co/id1510445899)
- [Tasktab](https://apps.apple.com/de/app/tasktab-simple-to-do-list/id1395414535?mt=12)
- [Slack](https://apps.apple.com/de/app/slack/id803453959?mt=12)
- [Battery stats for Airpod](https://apps.apple.com/de/app/battery-stats-for-airpods/id1405763798?mt=12)
- [Simplemind Lite](https://apps.apple.com/de/app/simplemind-lite-mind-mapping/id439654198?mt=12)
- [Geogebra](https://apps.apple.com/de/app/geogebra-graphing-calculator/id1294018688?mt=12)
- [Automute](https://apps.apple.com/de/app/automute-preventing-awkward-situations/id1118136179?mt=12)
- [Byword](https://apps.apple.com/de/app/byword/id420212497?mt=12)
- [Keynote](https://apps.apple.com/de/app/keynote/id409183694?mt=12)
- [Pages](https://apps.apple.com/de/app/pages/id409201541?mt=12)
- [Numbers](https://apps.apple.com/de/app/numbers/id409203825?mt=12)
- [Whatsapp Desktop](https://apps.apple.com/de/app/whatsapp-desktop/id1147396723)
- [Moom](https://apps.apple.com/de/app/moom/id419330170?mt=12)
- [Clean](https://apps.apple.com/de/app/clean/id418412301?mt=12)
- [ICMPUtil](https://apps.apple.com/de/app/icmputil/id866965011?mt=12)
- [1Password](https://apps.apple.com/de/app/1password/id443987910?mt=12)
- [XCode](https://apps.apple.com/de/app/xcode/id497799835?mt=12)
- [The Unarchiver](https://apps.apple.com/de/app/the-unarchiver/id425424353?mt=12)

## Dock and Menu bar

- Configure Dock
- Dock spacers: `defaults write com.apple.dock persistent-apps -array-add '{"tile-type"="small-spacer-tile";}' && killall Dock`
- Configure Menu Bar

