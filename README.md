# 🌌 Glass Theme für Vencord

Ein durchsichtiges **Glassmorphism**-Theme für Discord (via [Vencord](https://vencord.dev/)) – mit Blur-Effekt, abgerundeten Ecken, dunklem Look und einem frischen grünen Akzentton. 💚

---

## ✨ Wie sieht es aus?

| Element | Style |
|---|---|
| 🖼️ Hintergrund | frei wählbares Bild (Standard: Anime-Wallpaper) |
| 🌫️ Blur | 4px Weichzeichner auf Sidebar & Fenster |
| 📐 Ecken | sanft abgerundet (10px) |
| 💬 Nachrichten | abgerundete Boxen mit dezentem Padding |
| 🎨 Akzentfarbe | Grün (Hue 160°) |
| 🔘 Buttons | pillenförmig, 20px Radius |

---

## ⚙️ Installation in Vencord

1. **Vencord installieren** (falls noch nicht geschehen) → offizielle Anleitung: https://vencord.dev/download/
2. Discord öffnen → **Einstellungen** (⚙️) → im linken Menü ganz unten **Vencord → Themes**
3. Auf **"Open Themes Folder"** klicken – es öffnet sich dein lokaler Theme-Ordner
4. Die `BUNDESTAG THEME.css`-Datei dieses Themes in den Ordner legen
5. Zurück in Discord: In der Themes-Liste den Haken bei der Datei setzen ✅
6. Discord ggf. neu laden (`Strg` + `R`), damit alles sauber greift

**Alternative:** Den kompletten CSS-Code direkt unter **Vencord → QuickCSS** einfügen – dann braucht es keine separate Datei.

---

## 🎨 Anpassbare Variablen

Das Theme arbeitet mit CSS-Variablen im `:root`-Block – die kannst du nach Belieben ändern:

| Variable | Bedeutung |
|---|---|
| `--app-bg` | Hintergrundbild der App |
| `--app-blur` | Stärke des Weichzeichners |
| `--app-radius` | Eckenradius der Fenster-Elemente |
| `--accent-hue/-saturation/-lightness` | Akzentfarbe (HSL) |
| `--sidebar-color` | Transparenz/Farbe der Sidebar |
| `--message-color` / `--message-radius` | Style der Chat-Bubbles |
| `--textarea-radius` | Rundung des Nachrichten-Eingabefelds |
| `--card-color` / `--card-color-hover` | Farbe von Karten (z. B. Einladungen, Embeds) |
| `--button-height` / `--button-radius` | Größe & Form der Buttons |

👉 Einfach die Hex-/HSL-Werte im `:root` austauschen und speichern – Vencord lädt CSS-Änderungen live nach.

---

## ⚠️ Hinweis

LASST DIE source.css in ruhe da die nur da ist um den source aufzugreifen.

---

## 📄 Lizenz

Nutzung auf eigene Verantwortung – für persönliche/Community-Zwecke gedacht.
