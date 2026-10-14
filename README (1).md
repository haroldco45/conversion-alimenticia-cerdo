# Conversión del Cerdo 🐖

**¿Cuánto alimento necesita un cerdo para ganar 1 kg?**

App (PWA) estilo Toyota para porcicultores: calcula la conversión alimenticia de un lote con los datos reales de la granja.

## Qué hace
- Fotos reales (Unsplash) y videos reales de granjas porcinas (Pexels), enlazados desde la red.
- Explica el concepto y la fórmula: **Conversión = consumo de alimento (kg MS) ÷ ganancia de peso (kg)**.
- Calculadora con peso inicial y final, bultos, kg por bulto, días y número de cerdos.
- Opción de % de materia seca (como se pesa, ~88% o ~90%).
- Resultados: conversión, ganancia por cerdo, consumo diario, ganancia diaria y semáforo (menos de 2,5 / 2,5–3,0 / 3,0–3,5 / más de 3,5).
- Costos opcionales: costo del alimento por kg ganado y margen sobre alimento por cerdo.
- Historial de lotes guardado en el celular (localStorage), con respaldo `.json` para descargar y cargar.
- Compartir el resultado por WhatsApp.
- Instalable y funciona sin internet (manifest + service worker).

Ejemplo cargado: cerdo de 14 a 100 kg con 6 bultos de 40 kg (240 kg) en 100 días → **2,79 kg por kg ganado**.

## Archivos
| Archivo | Para qué |
|---|---|
| `index.html` | La app completa |
| `manifest.json` | Instalación como app |
| `sw.js` | Funcionamiento sin internet |
| `icon-192.png`, `icon-512.png` | Íconos |
| `og-image.png` | Imagen al compartir el enlace (1200×630) |

Créditos de fotos y videos: aparecen al pie de la galería. Licencia Unsplash y Licencia Pexels (uso libre, incluso comercial).

## Publicación
Repositorio sugerido: `haroldco45/conversion-alimenticia-cerdo` → GitHub Pages (rama `main`, carpeta raíz).
URL: https://haroldco45.github.io/conversion-alimenticia-cerdo/

Si cambias el nombre del repo, actualiza las URLs de `og:url`, `og:image`, `twitter:image` y el enlace del mensaje de WhatsApp en `index.html`.

---
Desarrollada por **Vibras Positivas HM** — Derechos de Autor Reservados · Caucasia, Antioquia
