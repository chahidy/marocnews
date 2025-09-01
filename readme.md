# 🌍 Marokko News – Deutschsprachige Nachrichtenplattform

![Marokko News Banner](https://images.unsplash.com/photo-1593642632823-8f785ba67e45?fit=crop&w=1200&q=80)

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](https://github.com/deinusername/marokko-news/actions)
[![Coverage](https://img.shields.io/badge/coverage-90%25-green)]()
[![License](https://img.shields.io/badge/license-MIT-blue)]()
[![Live Demo](https://img.shields.io/badge/demo-vercel-blueviolet)](https://marokko-news.vercel.app)

---

## 🌟 Projektidee

**Marokko News** bringt die aktuellsten Meldungen aus Marokko **auf Deutsch**, kompakt und verständlich.  
Wir verwandeln Fakten aus französischen und arabischen Quellen in **rechtssichere, redaktionell geprüfte Artikel**.

> „Die News, die du brauchst – ohne Sprachbarrieren.“

---

## 🚀 Features

| Feature | Status | Beschreibung |
|---------|--------|-------------|
| RSS-Ingest | ✅ | Automatisches Abrufen der wichtigsten marokkanischen Quellen |
| Rohübersetzung | ⚙️ | DeepL / Google Translate als Ausgangspunkt |
| Redaktioneller Workflow | ⚙️ | Draft → Review → Published |
| Admin-Dashboard | ⚙️ | WYSIWYG Editor, Rollen & Kanban |
| SEO Optimierung | ✅ | Meta, OG, JSON-LD, Sitemap |
| Responsive Design | ✅ | Mobile & Desktop, Dark Mode |
| RSS Feed für Leser | ⚙️ | Export der deutschsprachigen Artikel |

---

## 🛠️ Tech Stack

- **Frontend & Backend:** Next.js (App-Router, TypeScript)  
- **Datenbank:** PostgreSQL + Prisma  
- **Übersetzung:** DeepL API  
- **Hosting:** Vercel (Serverless + ISR)  
- **Editor:** TipTap / Lexical  
- **Monitoring & Analytics:** Sentry + Plausible  

---

## 🎯 Roadmap (MVP)

```
Phase 1: Setup & Architektur         ✅
Phase 2: Admin UI & Artikelmanagement ⬜
Phase 3: Automatisierung & Übersetzung ⬜
Phase 4: Frontend & SEO               ⬜
Phase 5: CI/CD & Hosting              ⬜
Phase 6: Go-Live MVP                  ⬜
```

**Detailierte Roadmap:** [Notion-Template](./Notion_Template)

---

## ⚡ Installation / Setup

```bash
git clone https://github.com/deinusername/marokko-news.git
cd marokko-news
npm install
```

Umgebungsvariablen konfigurieren:

```env
DATABASE_URL=postgresql://...
DEEPL_API_KEY=...
NEXTAUTH_SECRET=...
```

Datenbank migrieren & Next.js starten:

```bash
npx prisma migrate dev --name init
npm run dev
```

Admin-Panel erreichbar unter `/admin`  

---

## 🤝 Mitmachen

Wir suchen **Redakteure, Entwickler & Designer**:

- Artikel umschreiben & Review durchführen  
- Neue Features & Frontend-Verbesserungen  
- SEO, Social Media & Community Management  

💌 Kontakt: kontakt@marokkonews.de  
GitHub Issues für Bugs & Feature Requests

---

## ⚖️ Rechtliches

- Artikel **werden neu formuliert**, keine direkten Übersetzungen  
- **Quellenangabe bei jeder Meldung**  
- Bilder: nur eigene oder lizenzfreie Bilder  
- Takedown-Anfragen → `/contact`  

---

## 🔮 Zukunftspläne

- Mehrsprachigkeit (Englisch, Französisch)  
- Newsletter & Premium-Content  
- API für Partner / Drittplattformen  
- Automatisiertes Social Media Sharing  

---

![Marokko News GIF](https://media.giphy.com/media/xT0GqeSlGSRQut4f0w/giphy.gif)

