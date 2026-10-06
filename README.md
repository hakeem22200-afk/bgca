# Balochistan Government Contractors Association (Reg.)

Official web portal for contractor (Takhedar) registration, admin approval, district-wise profiles, complaints, media uploads, reports, and rules.

## Features

- **Admin** — full permissions (approvals, uploads, complaints inbox, reports publish, rules edit)
- **Normal Takhedar** — limited access after admin approval
- Registration fields: **Name / CNIC / NTN / HEC / BRA / District**
- Pending → Admin Allow → Login unlocked
- Profiles tab (district-wise table)
- Complaint box (admin-only visibility)
- Media upload (photos, videos, PDF) — admin
- Reports download center
- Rules & Regulations section
- Construction video background
- Mobile + PC / laptop responsive

## Default Admin Login

- Username: `admin`
- Password: `Admin@123`

## Run locally

```bash
npm install
npm run dev
```

Open the local URL shown in the terminal (usually http://localhost:5173).

## Build for hosting

```bash
npm run build
```

Upload the `dist` folder to any static host:

- Netlify / Vercel / Cloudflare Pages / cPanel public_html
- Or any shared hosting that serves static HTML/CSS/JS

## Notes

- Data is stored in the browser (`localStorage`) for this version so it works instantly online without a paid database.
- For multi-device shared live data (same approvals for everyone), a backend/database can be added later (Firebase / Supabase / Node API).
