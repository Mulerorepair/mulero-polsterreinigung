# Mulero Polsterreinigung Onepager

Statische Onepager-Webseite für die mobile **Polster-, Sofa- und Matratzenreinigung** in Sprockhövel & Wuppertal.

## Lokal öffnen

Die Seite benötigt kein Backend und keine Datenbank.

1. Öffne `index.html` direkt im Browser.
2. Prüfe die Seiten `impressum.html` und `datenschutz.html`.

## Kontakt- und Profil-Links

- WhatsApp: `https://wa.me/4915730198873` (mit vorbefülltem Anfragetext)
- Kleinanzeigen-Anzeige: `https://www.kleinanzeigen.de/s-anzeige/polsterreinigung-sofa-matratze-teppich-sprockhoevel-wuppertal/3452141105-239-1556`

## Preise (Stand Juli 2026, aus Marktrecherche)

| Leistung | Preis |
| --- | --- |
| Sofa 2-Sitzer | 79 € |
| Sofa 3-Sitzer | 95 € |
| Ecksofa klein | 139 € |
| Ecksofa groß / Wohnlandschaft | 169 € |
| Sessel (solo / als Zusatz) | 59 € / 39 € |
| 4 Esszimmerstühle | ab 49 € |
| Matratze 90×200 | 69 € |
| Matratze 140–180×200 | ab 89 € |
| Teppich flach (nur Zusatz) | ab 8 €/m², mind. 29 € |

Mindestauftragswert: 79 €.

## Deployment auf Vercel (wie Mulero Repair)

1. Neues GitHub-Repository erstellen und Dateien hochladen bzw. pushen.
2. Projekt bei Vercel importieren, Framework `Other` / statisches Projekt.
3. Kein Build Command nötig, Output Directory leer lassen.
4. Nach dem Deployment:
   - Domain in Google Search Console anmelden und den Verification-Meta-Tag in `index.html` eintragen.
   - Vercel Web Analytics im Vercel-Dashboard aktivieren (Script ist bereits eingebunden).

## Nach dem Livegang (SEO-Checkliste)

- [ ] Google Search Console: Property anlegen, Verification-Tag eintragen, Sitemap/Indexierung anstoßen.
- [ ] Google Unternehmensprofil (Google Business Profile) anlegen — wichtigster Hebel für lokale Suchen wie „Polsterreinigung Sprockhövel“.
- [ ] Website-Link in die Kleinanzeigen-Anzeige aufnehmen.
- [ ] Echte Vorher-/Nachher-Fotos der ersten Aufträge ergänzen (mit Einwilligung der Kunden) — stärkstes Vertrauenssignal.
- [ ] Erste Google-Bewertungen zufriedener Kunden sammeln.

## Dateien

- `index.html` – SEO-Onepager mit LocalBusiness-, Service- und FAQ-Strukturdaten
- `styles.css` – responsives Styling (helles, sauberes Design)
- `impressum.html` – Impressum
- `datenschutz.html` – Datenschutzerklärung
- `assets/` – Platz für Bilder (z. B. Vorher-/Nachher-Fotos)
