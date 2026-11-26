# Subir TraceNo'j a GitHub

## El repo

- **Nombre:** `trace-noj` (sin apóstrofo: GitHub no acepta `'` en nombres de repo)
- **Visibilidad:** Público (GitHub Pages gratis exige repo público)
- **Dirección final:** https://kuckling.github.io/trace-noj/

## Archivos del paquete

- `index.html` — la app completa (un solo archivo, sin dependencias)
- `README.md` — descripción del proyecto
- `LICENSE` — CC BY-NC-SA 4.0
- `tracenoj-icono.png` — icono del pez kay
- `tracenoj-presentacion-v5.png` — imagen de presentación (pez arriba y nombre abajo, con tiburones y glifos de fondo, sin lema)
- Este archivo (`LEEME_SUBIR_A_GITHUB.md`) — solo es la guía, no hace falta subirlo

## Pasos

1. En GitHub, **New repository**.
2. **Repository name:** `trace-noj`. **Public**. No marques ninguna casilla de README, `.gitignore` ni licencia (ya vienen en el paquete). **Create repository**.
3. En el repo vacío, **uploading an existing file** (o "Add file" → "Upload files"). Arrastra los archivos del paquete (menos este LEEME) y **Commit changes**.
4. **Settings** → **Pages** → **Build and deployment** → **Source:** Deploy from a branch → **Branch:** `main`, carpeta `/ (root)` → **Save**.
5. Espera 1 o 2 minutos y abre https://kuckling.github.io/trace-noj/

## Después de publicar

- **Descripción sugerida del repo:** "TraceNo'j — La traza, explicada. Intérprete de trazas SIP y Q.931 en español claro, con diagrama de flujo, laboratorio guiado y diagnóstico del posible origen de la falla."
- **Topics sugeridos:** `sip`, `voip`, `q931`, `freeswitch`, `troubleshooting`, `telecom`, `guatemala`
- **Verificación:** abre la página, en el Intérprete carga el Caso 1 del laboratorio y confirma que explica la llamada. Prueba también pegar una traza con prefijos de log.

## Notas

- Todo el código es de Marlon Estuardo Alvarado Kuckling. Las trazas del laboratorio son ficticias.
- No subas trazas reales con números de clientes al repo ni a ningún lado: la app trabaja 100% en el navegador y nunca envía nada a un servidor.
