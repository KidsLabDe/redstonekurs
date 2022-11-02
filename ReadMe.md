



# Verzeichnisstruktur



# Aufbau Markdown Dateien

## YAML Front Matter

Am Anfang der Datei mit --- enigeschossen:

```toml
title: Scratch
weight: -100
type: docs
Draft: false
icon: "fas fa-cat" # fontawesome icon : https://fontawesome.com/icons
description: "Erfinde & Programmiere Dein eigenes Spiel - mit der Katze Scratch."
# type dont remove or customize
type : "docs"
```

| Feld        | Beschreibung                         |
| ----------- | ------------------------------------ |
| title       | Titel - Wird im Menü angezeigt       |
| weight      | Sortierung Menü, -100 ganz oben      |
| draft       | Anzeige im Web?                      |
| type=docs   | Anzeige auf der Handbuch-Startseite  |
| description | Beschreibung auf Handbuch-Startseite |
| icon        | Icon, FontAwesome (standard)         |

## Inhalt

Jedes Kapitel ein Verzeichnis, Dateiname: `index.md`

### Markdown

Ganz normales Markdown.

### Bilder

In der gleichen Ordner wie das jeweilige Kapitel.

Namen: CamelCase - **ohne Lehrzeichen und ohne Umlaute.**

### Besondere Codes

#### Hinweis Boxes

Notice $typ $title

```xml
{{< notice note title>}}

***\*Hier kannst Du MD Verwenden...\****

This is a simple note.

{{< /notice >}}
```



Mögliche Typen:

- `note` - blau - Hinweis, Hintergrund...
- `task` - gelb - Aufgabe für den Leser
- `success` - grün
- `error` - rot - Fehler oder wichtiger Hinweis
- `mentor` - Purpur, interne Infos für Mentoren. 

#### Youtube

`{{< youtube C0DPdy98e4c >}}`