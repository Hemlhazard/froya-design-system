# FRØYA — Corporate Design System v1.0

> **Status:** Erster umsetzbarer Entwurf, noch keine freigegebene Reinzeichnung oder markenrechtliche Prüfung. Wortmarke und Icons wurden als eigenständige Vektoren auf Basis der visuellen Richtung konstruiert; sie sind keine pixelgenauen Tracings der KI-Moodboards.

## 1. Unternehmen & Positionierung

**Markenschreibweise:** FRØYA im Logo; Frøya als Name; Froya in laufenden Texten, wenn das Sonderzeichen nicht erwünscht ist.  
**Zielgruppe:** Inhabergeführte KMU mit ca. 20–100 Mitarbeitenden, unterdigitalisierte Nischenbranchen; Start Sanitätshäuser, später weitere Branchen.  
**Leistung:** Zuerst zuhören und Zeitfresser verstehen, dann maßgeschneiderte Lösungen entwickeln, einführen und dauerhaft betreiben.  
**Markencharakter:** der Kollege — zuhörend, handfest, warm, verlässlich, unprätentiös, kompetent. Keine Berater- oder Tech-Show.  
**Markenclaim:** **Zuhören. Verstehen. Machen.**  
**Nutzenbotschaft:** Mehr Zeit für das, was zählt.  
**Branchenzeile:** Frøya für Sanitätshäuser: mehr Zeit für die Versorgung.

## 2. Designprinzip

Nordisch zurückhaltende Gestaltung trifft auf einen entschlossenen Lingon-Akzent. Kein Neon, keine Verläufe. Das diagonale Ø ist das zentrale Zeichen: Es symbolisiert **gestrichen / erledigt / abgenommen**. Die Marke wirkt freundlich, menschlich und direkt; nicht luxuriös-distanziert, nicht verspielt.

## 3. Farben (verbindliche Tokens)

| Token | HEX | Zweck |
|---|---|---|
| `--froya-lingon` | `#E71D51` | Markenzeichen, Links, Akzente, CTA |
| `--froya-obsidian` | `#0F0F0F` | Fließtext, Wortmarke, dunkle Flächen |
| `--froya-linen` | `#F7F4ED` | Haupt-Hintergrund, ruhige Flächen |
| `--froya-mist` | `#D9A3B3` | sekundäre Flächen, dekorative Details |
| `--froya-white` | `#FFFFFF` | Negativlogo, Karten |

**Kontrast:** Lingon nicht als kleine Schrift auf Linen/Weiß verwenden, wenn WCAG-AA-Kontrast nicht erreicht wird. Für kleine CTA-Texte weiße Schrift auf Lingon separat testen oder dunklen Text nutzen. Auf Obsidian kann Lingon als prägnanter Akzent stehen.

## 4. Schriften

- **Headlines:** Fraunces (Google Fonts, OFL), bevorzugt Gewicht 500–600, für große emotionale Aussagen; Schriftart vor Verwendung laden.
- **UI / Body / Navigation / Logo-Claim:** Inter (Google Fonts, OFL), 400/500/600.
- **Logo:** maßgezeichnete Vektor-Wortmarke, **nicht** als editierbarer Fonttext nachsetzen.
- Fließtext 16–18 px, Zeilenhöhe 1.55–1.65; Headlines 36–64 px, Zeilenhöhe 1.05–1.15; Labels 11–13 px mit dezenter Laufweite.
- Nicht alles in Versalien; nur Wortmarke, Eyebrows und kleine Kategorien.

## 5. Logo-Regeln

- Standard: Obsidian-Wortmarke mit Lingon-Ø-Strich auf Linen oder Weiß.
- Dunkel: weiße Wortmarke mit Lingon-Strich.
- Einfarbig: komplett Schwarz oder Weiß, wenn Drucktechnik dies verlangt.
- Schutzraum mindestens die Höhe des Ø-Kreises rundherum / 2; keine Bilder oder Texte im Schutzraum.
- Kein Schatten, keine Kontur, keine Verläufe, keine Rotation.
- Mindestbreite Wortmarke digital ca. 160 px; darunter lieber Signet.
- Die Signet-Quadratvarianten eignen sich für Avatar und App-Icon. Transparente Signets für Druck und Favicons.
- Der Claim wird separat gesetzt; nicht in das Logo einbrennen, wenn die Breite klein wird.

## 6. Icon-System

Fünf individuell gezeichnete Icons: `zuhoren_verstehen`, `aufgaben_identifizieren`, `losung_entwickeln`, `einfuhren_begleiten`, `dauerhaft_entlasten`. Schwarze, leicht gerundete Linien, ein Lingon-Strich oder eine Lingon-Bewegung. Alle in 256 × 256 viewBox; SVG als Master. PNG nur für Tools ohne SVG-Unterstützung. Nicht mit beliebigen Lucide-Icons mischen, ohne Strichstärke und Rundungen anzupassen.

## 7. Fotografie & Illustration

- Echte Menschen in echten Betrieben, Handgriffe, Arbeitssituationen, ruhige natürliche Beleuchtung.
- Authentische Details aus Sanitätshaus, Büro, Werkstatt; keine gestellten Handshakes.
- Nordische Landschaft nur sparsam als Stimmungsbild, nicht als Hauptbeweis der Dienstleistung.
- Topografische Linien: sparsame Hintergrundstruktur, eine markante Lingon-Linie.
- MacBook-Sticker: **physikalisch glaubwürdig**: kleine matte Vinylfläche, Perspektive passend zum Deckel, Licht und Materialkörnung realistisch; nicht frei schwebend, nicht über das Apple-Logo gelegt.

## 8. Tonalität & Beispiele

- Duzen, kurze Sätze, verständliche Sprache, kein Buzzword-Sprech.
- Erst über Alltag und Zeitverlust reden, dann über Technologie.
- Headline: **Mehr Zeit für das, was zählt.**
- Einleitung: **Wir hören zu, finden die Zeitfresser und kümmern uns um Lösungen, die im Alltag wirklich helfen. Von der Einführung bis zum laufenden Betrieb.**
- CTA: **Lass uns sprechen** / **Zeitfresser finden**.
- Branchenmodul: **Frøya für Sanitätshäuser — mehr Zeit für die Versorgung.**

## 9. Layout & Komponenten

- Editoriales Raster, viel Weißraum, ruhige asymmetrische Layouts.
- Basisabstände 4/8/12/16/24/32/48/64 px; Kartenradius 8–12 px; Buttons 8–10 px.
- Hintergründe Linen/White, dunkle Bildüberlagerungen nur bei lesbarem Kontrast.
- CTA Lingon sparsam; keine permanenten Pinkflächen überall.
- Vier Schritte: Zuhören → Lösung entwickeln → Umsetzen → Betreiben. Fünf Icons sind ein eigenständiges Kommunikationssystem und müssen nicht 1:1 den vier Prozessschritten entsprechen.
- Responsive, zugänglich, mobil zuerst; Animationen dezent und mit `prefers-reduced-motion`.

## 10. Sub-Brands

- Masterbrand immer FRØYA; branchenspezifische Produkte mit Textzusatz, nicht mit neuem Logo.
- Beispiel: **Frøya für Sanitätshäuser**. Keine Branchen-Symbole im Masterlogo.
- Wiederverwendung von Lingon, Signet, Typografie und Raster.

## 11. Übergabe an Claude Design — Arbeitsauftrag

Erstelle aus diesem Design System eine responsive, wartbare, barrierearme Website für Frøya. Nutze die gelieferten SVG-Assets unverändert als Logo- und Icon-Master, die PNGs nur als Fallback. Verwende die Farb-Tokens und Fraunces/Inter. Erstelle Hero, Vorgehensweise, Branchen-Einstieg Sanitätshäuser, Nutzen, Über-uns (drei Gründer), Kontakt-CTA und Footer. Deutsche Du-Tonalität. Keine erfundenen Kundenreferenzen oder quantifizierten Ergebnisse. Kein generischer KI-Look. Erzeuge zuerst Design-Tokens und Komponenten, dann Seitenlayouts. Liefere Desktop- und Mobile-Ansichten und prüfe Kontrast und Lesbarkeit.

## 12. Asset-Inventar

- `logos/svg/` + `logos/png/`: Wortmarke primär, negativ, einfarbig, mit Claim, mit Deskriptor
- `signets/svg/` + `signets/png/`: Signet transparent, negativ, monochrom, zwei App-Varianten
- `icons/svg/` + `icons/png/`: fünf eigenständige Prozess-/Leistungsicons
- `patterns/svg/`: topografische Linien
- `brand/favicon.ico`: Favicon-Größen
- `brand/tokens.css`: CSS-Variablen
- `preview/`: visuelles Moodboard als Referenz, **nicht** als Asset-Master

**Wichtig:** Die SVGs sind die technisch editierbaren Erstentwürfe; vor finalem Druck, Markenanmeldung oder größerem Rollout sollten Wortmarkenproportionen, Icon-Konsistenz und Kontrast in einer gestalterischen Reinzeichnung geprüft werden. Der Moodboard-Entwurf ist eine Stilreferenz, kein exakt exportierbares Vektor-Original.
