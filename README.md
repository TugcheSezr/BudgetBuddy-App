<div align="center">

# 🌍✨ SDG Dashboard - Jouw Project ✨🌍

💸 *Data. Visuals. Impact.* 💸  
---

> Een interactieve webapplicatie voor het volgen en visualiseren van de Duurzame Ontwikkelingsdoelen (SDGs).  
> In dit project bouw je van de grond af een moderne web applicatie en leer je werken met professionele tools en technieken.

<div align="center">

![BudgetBuddy Dashboard](https://media.giphy.com/media/3o7TKtnuHOHHUjR38Y/giphy.gif)

</div>
---

![BudgetBuddy Demo](public/demo.gif)

---

![Next.js](https://img.shields.io/badge/Next.js-14-black?style=for-the-badge)
![React](https://img.shields.io/badge/React-UI-blue?style=for-the-badge)
![TypeScript](https://img.shields.io/badge/TypeScript-SafeCode-blue?style=for-the-badge)
![Tailwind](https://img.shields.io/badge/TailwindCSS-Styling-38B2AC?style=for-the-badge)
![Prisma](https://img.shields.io/badge/Prisma-ORM-2D3748?style=for-the-badge)
![MySQL](https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge)

</div>

---

## 🎯 Wat Ga Je Leren?

Dit project is ontworpen om je stap voor stap kennis te laten maken met moderne webdevelopment:

### 🖥️ Frontend Development
- Next.js 14: Een krachtig React framework voor moderne webapps  
- React: Component-based development, state management, hooks  
- TypeScript: Type-veilige code schrijven en beter bugs voorkomen  
- Tailwind CSS: Snel en efficient mooie interfaces bouwen  

### ⚙️ Backend & Database
- Prisma ORM: Type-safe database queries  
- MySQL: Relationele database voor data opslag  
- API Development: RESTful endpoints bouwen  
- Data Validatie: Zod voor input validatie  

### 📊 Data Visualisatie
- Chart.js: Interactieve grafieken en visualisaties  
- Data Processing: Trends berekenen, data filteren, aggregaties  

---

## 🚀 Project Opstarten

Volg deze stappen om het project voor het eerst te starten:

### 1. Installeer Dependencies
```bash
npm install
2. Maak Environment Bestand
cp .env.example .env

De standaard instellingen werken direct!

3. Initialiseer Database
npm run db:generate    # Genereer Prisma Client
npm run db:push        # Maak database tabellen
npm run db:seed        # Voeg voorbeeld data toe
4. Start Development Server
npm run dev

🌐 Open http://localhost:3000
 - je zou nu de applicatie moeten zien!

📁 Projectstructuur Begrijpen
template/
├── app/
│   ├── api/
│   ├── overview/
│   ├── sdg/[id]/
│   ├── layout.tsx
│   └── globals.css
│
├── components/
│   ├── ui/
│   └── charts/
│
├── lib/
│   ├── prisma.ts
│   ├── types.ts
│   └── data.ts
│
├── prisma/
│   ├── schema.prisma
│   └── seed.ts
│
└── data/
    └── sdg-info.json
🎓 Leertraject (6 Weken)
📌 Week 1: Basis Begrijpen

Doel: Project begrijpen en eerste component bouwen

Bekijk de hele codebase, open alle bestanden
Begrijp hoe Next.js routing werkt
Leer over React componenten door voorbeelden te bestuderen
Bouw je eerste eenvoudige component (Button)

📖 Start hier: components/ui/README.md

📌 Week 2: UI Componenten Bouwen

Doel: Herbruikbare interface componenten maken

Je gaat verschillende soorten componenten bouwen:

Formulier componenten: Voor gebruikers input
Display componenten: Voor informatie tonen
Interactieve componenten: Met state en events

Elke component moet:

TypeScript props interfaces hebben
Herbruikbaar zijn voor verschillende situaties
Responsive werken op alle schermen

📖 Details in: components/ui/README.md

📌 Week 3: Data Visualisatie

Doel: Grafieken bouwen met Chart.js

Begrijp hoe chart data gestructureerd wordt
Maak verschillende chart types (line, bar, pie)
Werk met kleuren en styling
Maak charts responsive

Je hebt al een werkend voorbeeld (BarChart.tsx) - gebruik dit als referentie!

📖 Voorbeelden in: components/charts/README.md

📌 Week 4: Pagina's Bouwen

Doel: SDG data tonen in een mooie interface

Overview Pagina:

Toon alle 17 SDGs in een grid
Gebruik je Card component
Maak het responsive
Voeg hover effects toe

Detail Pagina's:

Toon gedetailleerde info per SDG
Voeg KPI cards toe met statistieken
Begin met de layout en structuur

📖 Uitleg in: app/overview/README.md en app/sdg/[id]/README.md

📌 Week 5: Data & API's

Doel: Backend endpoints en data integratie

Database:

Voeg meer jaren toe aan de data
Voeg meer landen toe
Begrijp hoe Prisma queries werken

API Endpoints:

Bouw GET endpoints voor data ophalen
Voeg filters toe (land, jaar, SDG nummer)
Leer over request validatie met Zod

📖 API specs in: app/api/README.md

📌 Week 6: Visualisaties & Afronding

Doel: Charts toevoegen en alles afmaken

Integreer je charts in de detail pagina's
Voeg filters toe die de charts updaten
Bouw een data tabel met export functie
Fix bugs en verbeter styling
Test alles grondig

🗺️ Waar Begin Je?

🔍 Stap 1: Verken de Voorbeelden
Bekijk Card.tsx
Bekijk BarChart.tsx
Bekijk Header.tsx

📚 Stap 2: Lees de README's
components/ui/README.md
components/charts/README.md
app/overview/README.md
app/sdg/[id]/README.md
app/api/README.md

🧱 Stap 3: Begin Klein
Maak Button.tsx
Test het in een pagina
Pas styling aan met Tailwind CSS

🚀 Stap 4: Bouw Stap voor Stap
Simpele componenten → complexere
Gebruik ze in pagina’s
Voeg data integratie toe

💡 Belangrijke Concepten

⚡ Next.js App Router
Server Components: Default, draaien op de server
Client Components: gebruik 'use client'
Dynamic Routes: [id]

⚛️ React Hooks
useState
useMemo
useEffect

🧠 TypeScript
Interfaces voor props
Types voor data
Bugs voorkomen

🗄️ Prisma ORM
Schema
Queries
Migrations

🎨 Tailwind CSS
Utility-first
Responsive (md:, lg:)
Dark mode

🛠️ Nuttige Commando's

💻 Development
npm run dev
npm run build
npm run type-check
npm run lint

🗃️ Database
npm run db:studio
npm run db:seed
npm run db:generate

🐛 Problemen Oplossen
Prisma Errors
npm run db:generate
Project Opnieuw Beginnen
docker-compose down -v
docker-compose up -d
npm run db:push
npm run db:seed
📖 Externe Documentatie

Must-Read

Next.js Documentatie
React Documentatie
Tailwind CSS
TypeScript Handbook

Als Je Verder Wilt

Prisma Docs
Chart.js Docs
Zod Docs

SDG Data Bronnen

UN SDG Database
World Bank
Our World in Data

🎯 Tips voor Succes
Begin klein
Gebruik voorbeelden
Test vaak
Lees error messages
Google is je vriend
Gebruik TypeScript
Console.log is krachtig
Commit regelmatig

🎉 Klaar om te Beginnen?
Start het project
Open components/ui/README.md
Bouw je eerste component
Vraag om hulp als je vastloopt

🚀 Veel succes met je project!
