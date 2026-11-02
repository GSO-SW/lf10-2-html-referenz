# 🔎 Nachschlagen: Wie mache ich …?

Das ist unser Cheat Sheet – nur anders: Statt einer Liste mit 120 Tags
findest du hier **Fragen**, die beim Programmieren wirklich auftauchen.
Jeder Link springt direkt zur passenden **Datei und Zeile** mit einem
kommentierten, funktionierenden Beispiel.

> **Tipp:** Öffne die Beispielseite zusätzlich im Browser (VS Code →
> Rechtsklick → *Open with Live Server*), dann siehst du Code und Ergebnis
> nebeneinander.

---

## 1 · Grundgerüst

| Wie …? | Beispiel |
|---|---|
| … sieht das Grundgerüst jeder Seite aus? | [01-grundgeruest.html](referenz/01-grundgeruest.html) |
| … sorge ich für Umlaute und Handy-Darstellung (`meta`)? | [charset und viewport](referenz/01-grundgeruest.html#L9-L17) |
| … wähle ich einen guten Seitentitel? | [`<title>`](referenz/01-grundgeruest.html#L21-L23) |
| … binde ich eine CSS-Datei ein? | [`<link rel="stylesheet">`](referenz/01-grundgeruest.html#L27-L28) |

## 2 · Texte

| Wie …? | Beispiel |
|---|---|
| … setze ich Überschriften richtig ein? | [h1–h6 als Gliederung](referenz/02-texte.html#L18-L33) |
| … schreibe ich Absätze und Zeilenumbrüche? | [`<p>` und `<br>`](referenz/02-texte.html#L37-L54) |
| … hebe ich etwas als wichtig hervor? | [`<strong>` vs. `<b>`](referenz/02-texte.html#L58-L67) |
| … schreibe ich Zitate, Abkürzungen, Tastenkürzel, `<` und `>`? | [blockquote, abbr, kbd, code](referenz/02-texte.html#L71-L82) |

## 3 · Listen

| Wie …? | Beispiel |
|---|---|
| … mache ich eine Aufzählung? | [`<ul>`](referenz/03-listen.html#L20-L27) |
| … mache ich eine nummerierte Schritt-Liste? | [`<ol>`](referenz/03-listen.html#L31-L39) |
| … verschachtele ich Listen? | [Unterliste im `<li>`](referenz/03-listen.html#L43-L54) |
| … mache ich ein Glossar (Begriff – Erklärung)? | [`<dl>`](referenz/03-listen.html#L58-L67) |

## 4 · Links und Bilder

| Wie …? | Beispiel |
|---|---|
| … verlinke ich eine andere Seite im Projekt? | [relativer Link](referenz/04-links-bilder.html#L21-L25) |
| … verlinke ich eine fremde Website? | [externer Link, neues Tab](referenz/04-links-bilder.html#L29-L40) |
| … springe ich zu einer Stelle auf derselben Seite? | [Anker `#id`](referenz/04-links-bilder.html#L44-L45) |
| … verlinke ich E-Mail-Adresse oder Telefonnummer? | [`mailto:` und `tel:`](referenz/04-links-bilder.html#L49-L52) |
| … schreibe ich einen guten Linktext? | [nicht „hier klicken“](referenz/04-links-bilder.html#L56-L61) |
| … binde ich ein Bild ein (und was gehört ins `alt`)? | [`<img alt>`](referenz/04-links-bilder.html#L66-L71) |
| … gehe ich mit reinen Deko-Bildern um? | [`alt=""`](referenz/04-links-bilder.html#L75-L78) |
| … gebe ich einem Bild eine Bildunterschrift? | [`<figure>`](referenz/04-links-bilder.html#L82-L87) |
| … mache ich ein Bild zum Link? | [Bild-Link](referenz/04-links-bilder.html#L91-L94) |
| … gestalte ich Links (Farbe, Unterstreichung)? | [CSS für Links](referenz/css/basis.css#L73-L81) |

## 5 · Seitenstruktur

| Wie …? | Beispiel |
|---|---|
| … gliedere ich eine Seite in Kopf, Navigation, Inhalt, Fuß? | [05-seitenstruktur.html](referenz/05-seitenstruktur.html) |
| … baue ich ein Menü? | [`<nav>` + Liste](referenz/05-seitenstruktur.html#L24-L33) |
| … gestalte ich das Menü waagerecht? | [CSS für die Navigation](referenz/css/basis.css#L57-L69) |
| … markiere ich die aktuelle Seite im Menü? | [`aria-current`](referenz/05-seitenstruktur.html#L24-L33) · [CSS](referenz/css/basis.css#L57-L69) |
| … baue ich den Hauptbereich? | [`<main>`](referenz/05-seitenstruktur.html#L39-L74) |
| … unterscheide ich `<section>` und `<article>`? | [section/article](referenz/05-seitenstruktur.html#L49-L64) |
| … baue ich einen Infokasten am Rand? | [`<aside>`](referenz/05-seitenstruktur.html#L68-L72) |
| … baue ich einen Footer mit Impressum? | [`<footer>`](referenz/05-seitenstruktur.html#L78-L87) |
| … baue ich einen „Zum Inhalt springen“-Link? | [HTML](referenz/05-seitenstruktur.html#L13-L15) · [CSS](referenz/css/basis.css#L235-L248) |
| … erkenne ich „div-Suppe“? | [schlecht](referenz/10-gut-vs-schlecht.html#L25-L45) · [gut](referenz/10-gut-vs-schlecht.html#L49-L67) |

## 6 · Tabellen

| Wie …? | Beispiel |
|---|---|
| … baue ich eine Datentabelle richtig auf? | [caption, thead, th scope](referenz/06-tabellen.html#L24-L66) |
| … verbinde ich Zellen? | [`colspan` / `rowspan`](referenz/06-tabellen.html#L70-L89) |
| … gestalte ich Tabellen (Linien, Kopfzeile, Handy)? | [CSS für Tabellen](referenz/css/basis.css#L206-L231) |

## 7 · Formulare

| Wie …? | Beispiel |
|---|---|
| … baue ich ein Formular? | [`<form action method>`](referenz/07-formulare.html#L21-L25) |
| … beschrifte ich ein Eingabefeld? | [`<label for>`](referenz/07-formulare.html#L29-L37) |
| … wähle ich den richtigen Feldtyp (E-Mail, Datum, Zahl)? | [`input type`](referenz/07-formulare.html#L41-L56) |
| … zeige ich einen Hinweis unter dem Feld an? | [`aria-describedby`](referenz/07-formulare.html#L60-L67) |
| … baue ich Radiobuttons (eine Auswahl)? | [fieldset, legend, radio](referenz/07-formulare.html#L71-L93) |
| … baue ich Checkboxen (mehrere Auswahlen)? | [checkbox](referenz/07-formulare.html#L97-L112) |
| … baue ich eine Auswahlliste (Dropdown)? | [`<select>`](referenz/07-formulare.html#L116-L129) |
| … baue ich ein großes Textfeld? | [`<textarea>`](referenz/07-formulare.html#L133-L137) |
| … lasse ich eine Datei hochladen? | [`type="file"`](referenz/07-formulare.html#L141-L144) |
| … mache ich ein Feld zur Pflicht oder prüfe das Format? | [`required`, `pattern`](referenz/07-formulare.html#L60-L67) |
| … zeige ich eine Fehlermeldung barrierefrei an? | [HTML](referenz/07-formulare.html#L159-L171) · [CSS](referenz/css/basis.css#L153-L202) |
| … gestalte ich Formularfelder? | [CSS für Formulare](referenz/css/basis.css#L153-L202) |

## 8 · Buttons

| Wie …? | Beispiel |
|---|---|
| … entscheide ich: Button oder Link? | [Button vs. Link](referenz/08-buttons.html#L20-L30) |
| … baue ich einen Button im HTML? | [`<button type>`](referenz/08-buttons.html#L34-L45) |
| … **formatiere ich einen Button?** | [Grundform (CSS)](referenz/css/basis.css#L95-L108) |
| … gestalte ich Hover, Fokus und „gesperrt“? | [Zustände (CSS)](referenz/css/basis.css#L112-L130) |
| … baue ich Varianten wie „Abbrechen“ oder „Löschen“? | [Varianten (CSS)](referenz/css/basis.css#L134-L149) · [HTML](referenz/08-buttons.html#L34-L45) |
| … baue ich einen Button nur mit Symbol? | [Icon-Button](referenz/08-buttons.html#L49-L67) |
| … sende ich ein Formular ab? | [submit / reset](referenz/07-formulare.html#L148-L154) |
| … und warum kein `<div onclick>`? | [Antipattern](referenz/08-buttons.html#L71-L75) |

## 9 · CSS-Grundlagen (nur das Nötigste)

| Wie …? | Beispiel |
|---|---|
| … lege ich Farben zentral fest? | [CSS-Variablen](referenz/css/basis.css#L11-L23) |
| … setze ich Schrift, Zeilenhöhe, Seitenbreite? | [Grundlayout](referenz/css/basis.css#L27-L53) |
| … mache ich den Tastatur-Fokus sichtbar? | [`:focus-visible`](referenz/css/basis.css#L85-L91) |
| … verstecke ich Text optisch, aber nicht für Screenreader? | [`.visually-hidden`](referenz/css/basis.css#L252-L264) |

## 10 · Barrierefreiheit und Qualität

| Wie …? | Beispiel |
|---|---|
| … was bedeuten die WCAG-Prinzipien? | [POUR](referenz/09-barrierefreiheit.html#L29-L39) |
| … prüfe ich meine Seite in 5 Minuten? | [10-Punkte-Schnellprüfung](referenz/09-barrierefreiheit.html#L43-L55) |
| … wann brauche ich ARIA – und wann nicht? | [Erste Regel von ARIA](referenz/09-barrierefreiheit.html#L59-L67) |
| … lasse ich eine Statusmeldung vorlesen? | [`role="status"`](referenz/09-barrierefreiheit.html#L71-L75) |
| … teste ich selbst (Validator, Tastatur, Screenreader)? | [Werkzeuge](referenz/09-barrierefreiheit.html#L79-L92) |
| … vermeide ich die häufigsten Fehler? | [Top-Fehler-Tabelle](referenz/10-gut-vs-schlecht.html#L72-L123) |

---

## Weiterlesen

- [MDN Web Docs (deutsch)](https://developer.mozilla.org/de/docs/Web/HTML) – die zuverlässigste Referenz
- [W3C-Validator](https://validator.w3.org/) – prüft, ob dein HTML gültig ist
- [WCAG-Überblick der W3C-WAI](https://www.w3.org/WAI/standards-guidelines/wcag/) – die Barrierefreiheits-Richtlinien

**Fehlt eine Frage?** Lege ein Issue an oder ergänze sie per Pull Request –
diese Seite wächst mit unserer Klasse.
