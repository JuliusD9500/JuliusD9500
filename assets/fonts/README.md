# Google Sans Flex

Lokale variable Schriftdatei im Format WOFF2 aus Google Fonts (Version 4.005).
Lateinischer Basiszeichensatz einschließlich deutscher Umlaute und ß.

Alle sechs Individualisierungen / Achsen sind enthalten:

| Achse | Tag    | Bereich    | CSS                                   |
|-------|--------|------------|---------------------------------------|
| Weight         | `wght` | 1–1000     | `font-weight`                         |
| Width          | `wdth` | 25–151     | `font-stretch`                        |
| Optical size   | `opsz` | 6–144      | `font-optical-sizing: auto`           |
| Slant          | `slnt` | −10–0      | `font-style: oblique 0deg … 10deg`    |
| Grade          | `GRAD` | 0–100      | `font-variation-settings: "GRAD" n`   |
| Roundness      | `ROND` | 0–100      | `font-variation-settings: "ROND" n`   |

## Verwendung in den SVGs

GitHub bindet SVGs in der README als `<img>` ein. In diesem Modus laden Browser
keine externen Dateien, also auch keine Schrift per `url(assets/fonts/…)`.
Deshalb ist diese Datei unverändert als Base64 direkt in jede
`assets/*-hu-*.svg` eingebettet (Header, Projekte, Werdegang).
Die Link-Buttons `assets/link-*.svg` enthalten ihre Beschriftung als Pfad
und kommen deshalb ohne eingebettete Schrift aus.

Projekt: https://github.com/googlefonts/googlesans-flex

Lizenz: SIL Open Font License 1.1. Siehe [OFL.txt](OFL.txt).

Lizenzquelle: https://github.com/google/fonts/blob/main/ofl/googlesansflex/OFL.txt

„Google Sans Flex“ ist eine Marke der Google LLC. Die Verwendung impliziert keine Verbindung zu Google.
