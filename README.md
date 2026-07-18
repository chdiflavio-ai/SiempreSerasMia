# Siempre Serás Mía — Leo Jimvaz

Landing del sencillo, con la misma estructura que el proyecto DETONARR.

## Qué incluye
- Fondo full-bleed con la portada que mandaste (humo azul/negro)
- Cuenta regresiva congelada en 00:00:00:00 (el sencillo ya salió)
- Reproductor del adelanto de 20s (audio embebido, no necesita archivos sueltos)
- Botones de streaming (Spotify / Apple Music) — los hrefs están en "#", reemplázalos en `src/App.jsx` → `STREAMING_LINKS`
- Sección de letra con placeholders (Verso 01 / Coro / Verso 02) — edítalos en `lyricsData`

## Correrlo en tu compu (opcional)
```
npm install
npm run dev
```

## Subir a GitHub (interfaz web)
1. Crea un repo nuevo en github.com (botón "New repository")
2. Click "uploading an existing file" y arrastra TODA esta carpeta (o cada archivo manteniendo la estructura de `src/`)
3. Commit directo a `main`

## Desplegar en Vercel
1. En vercel.com → "Add New" → "Project"
2. Importa el repo de GitHub que acabas de subir
3. Framework Preset: **Vite** (Vercel lo detecta solo)
4. Deploy — listo, te da la URL en ~1 min

## Para editar después
- Título / artista: arriba de `src/App.jsx`, constantes `ARTIST` y `SONG_TITLE`
- Letra real: `lyricsData`
- Links de streaming reales: `STREAMING_LINKS`
