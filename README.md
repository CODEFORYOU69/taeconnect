# TaeConnect

**TaeConnect** est une plateforme de gestion de compétitions de Taekwondo conforme aux standards World Taekwondo.

## Stack

- Next.js, Tailwind CSS, shadcn/ui
- Prisma, tRPC, PostgreSQL
- Flutter (Mobile)
- ExcelJS, jsPDF
- Socket.IO, NextAuth.js

## Démarrage

```bash
pnpm install
pnpm dev
```

## Structure

- apps/web → Interface admin Next.js
- apps/mobile → Application mobile Flutter
- packages/api → Backend tRPC
- packages/ui → UI kit partagé
- packages/pdf → Exports PDF/Excel conformes WT
