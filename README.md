# RAKON VERCEL BRIDGE v1.0

Capa estética ligera sobre los demos de Google Apps Script.
Vercel sirve URLs limpias tipo `rakontech.vercel.app/food` y envuelve
cada demo en un iframe a pantalla completa.

## Rutas
- `/` → Hub principal
- `/food` → Heladería
- `/services` → Barbería
- `/retail` → Boutique
- `/ops` → Taller
- `/vet` → Veterinaria
- `/wash` → Lavadero

## Despliegue en Vercel

1. Sube esta carpeta como repo en GitHub.
2. Entra a vercel.com → Add New → Project → importa el repo.
3. Framework Preset: **Other**. Build command: vacío. Output dir: vacío.
4. Deploy. Al terminar, tu Hub vive en `https://<nombre>.vercel.app`.
5. Project Settings → Domains → cambia nombre a `rakontech` si quieres URL `rakontech.vercel.app`.

## Mantenimiento

Si cambias la URL de la Web App de GAS:
- Abre cada `*.html` (food, services, retail, ops, vet, wash).
- Busca y reemplaza la URL de script.google.com vieja por la nueva.
- Commit y push — Vercel redeploya solo.

**RAKON Technology** · 2026
