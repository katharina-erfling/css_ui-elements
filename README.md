# 🧩 CSS UI Elements
Eine wachsende Sammlung von wiederverwendbaren UI-Komponenten – entstanden beim Lernen und Ausprobieren moderner CSS-Features.
 
🚧 Work in Progress  
Dieses Repo wächst mit – neue Komponenten kommen regelmäßig dazu.
 
---
 
## 📁 Projektstruktur
```
/
├── index.html                  ← Übersichtsseite
├── new-positions/              ← Anchor Positioning Menü
│   ├── index.html
│   └── css/
│       └── style.css
└── nav-uebung/                 ← Navigation (Work in Progress)
    ├── index.html
    └── css/
        └── style.css
```
 
---
 
## 🧩 Komponenten
 
### 📍 Anchor Positioning Menü
 
> 🧪 **Experimentelles CSS** – die CSS Anchor Positioning API ist so neu, dass sie aktuell nur in modernen Chromium-Browsern läuft
 
> 💡 **Kein JavaScript** – Menü-Toggle und Positionierung funktionieren vollständig per nativer Browser-API
 
- Dropdown-Menü per nativer **Popover API** – kein JavaScript für den Toggle nötig
- Positionierung per **CSS Anchor Positioning** – `anchor-name`, `position-anchor` und `anchor()`
- Intelligenter Fallback per `position-try-fallbacks` – das Menü springt automatisch in vier Richtungen wenn kein Platz ist (`--below-right`, `--below-left`, `--up-left`, `--up-right`)
- `width: max-content` – Menübreite richtet sich automatisch am längsten Item aus
 
---
 
## 🛠️ Technologien
- **HTML5** – natives `popover` Attribut, `popovertarget`
- **CSS3** – `anchor-name`, `position-anchor`, `anchor()`, `position-try-fallbacks`, `@position-try`, `max-content`, `display: grid`
 
---
