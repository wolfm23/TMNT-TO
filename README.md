# TMNT-TO
želvy ninja tower defense

## Setup
1. V Supabase vytvoř tabulku pomocí `supabase.sql` (SQL Editor).
2. Zkopíruj `.env.example` do `.env` a doplň klíče.
3. Nainstaluj závislosti a spusť server:

```
npm install
npm start
```

Otevři `http://localhost:3000`.

## Hra
- Startuješ se 4 želvami, další spojence kupuješ za meta-měnu.
- Každá vteřina života jednotky dává 1 coin na upgrade.
- Boss na konci levelu musí padnout, jinak level prohraješ.
