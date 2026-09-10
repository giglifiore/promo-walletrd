# PromoWallet

MVP visual preparado para GitHub + Vercel.

## Stack
HTML + CSS + JavaScript. No requiere build.

## Deploy
1. Crea un repositorio GitHub y sube todo el contenido.
2. En Vercel: Add New -> Project -> Import Git Repository.
3. Framework Preset: Other.
4. Build Command: vacío.
5. Output Directory: vacío.
6. Deploy.

Vercel puede servir sitios estáticos directamente, y al conectar GitHub cada push puede generar un nuevo deployment.

## Demo
Flujo negocio: index -> login -> dashboard -> crear promoción.
Flujo cliente: index -> reclamar -> cupón -> canjear.
Código: PW-DEMO-2026.

## Siguiente fase
Firebase Auth + Firestore, QR reales, API de Vercel y Google/Apple Wallet.
