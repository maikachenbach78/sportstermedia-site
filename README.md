# Sportstermedia – Website

Statische One-Page-Website (HTML/CSS, keine Abhängigkeiten), aufgebaut nach dem Muster großer Holding-/Beratungsseiten: Hero → Kennzahlen → Mission → Leistungen → Ablauf → Erfahrung → Gratis-Ressourcen → Über uns → FAQ → CTA.

## Deployment über GitHub Pages
1. Repo auf GitHub anlegen und pushen (Branch `main`).
2. Settings → Pages → Source: **GitHub Actions**.
3. Der Workflow `.github/workflows/pages.yml` veröffentlicht automatisch.

## Offene To-dos vor Go-live
- [ ] Kontakt-Link / Calendly in `#bewerben` (aktuell `kontakt@…`)
- [ ] Foto in der „Über uns“-Sektion
- [ ] Impressum: Anschrift, HRB, USt-ID, Kontakt ergänzen (UG & GF sind eingetragen); Datenschutz erstellen (Hosting: GitHub Pages; Schriften sind lokal eingebunden, keine Google-Fonts-Verbindung)
