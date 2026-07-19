# Proyecto 68kg ðŸ’ª

App web personal para bajar de **73,8 kg a 68 kg** antes del **13 de septiembre** con calistenia militar (4 dÃ­as/semana) y dÃ©ficit calÃ³rico. Sin gimnasio, sin apps de pago.

Todo cabe en un Ãºnico `index.html`: sin build, sin dependencias, sin backend. Los datos (ejercicios marcados, semana/dÃ­a activos y registros de peso) se guardan en el `localStorage` del navegador, asÃ­ que persisten en tu mÃ³vil entre sesiones.

## QuÃ© incluye

- **ðŸ‹ï¸ Entreno**: 8 semanas con la progresiÃ³n aplicada (mÃ¡s reps/series, variantes difÃ­ciles, circuitos y semana de descarga). Eliges **semana** y luego **dÃ­a** (Empuje, TirÃ³n, Pierna, Full body). Cada ejercicio con su ilustraciÃ³n y casilla para marcar. Barra de progreso por dÃ­a.
- **ðŸ½ï¸ Dieta**: menÃº por **semana y dÃ­a** que rota entre 4 plantillas para no repetir, con las calorÃ­as bajando de forma escalonada (~1.950 â†’ ~1.820) y la proteÃ­na subiendo. Sin coliflor ni brÃ³coli.
- **ðŸ“‰ Peso**: grÃ¡fico que dibuja tu curva real sobre la lÃ­nea objetivo, con estadÃ­sticas de kg perdidos/restantes y registro semanal editable.

## CÃ³mo usarlo

Abre `index.html` en cualquier navegador. No necesita servidor.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo (por ejemplo `proyecto-68kg`) y sube `index.html` y este `README.md`.
2. En el repo: **Settings â†’ Pages**.
3. En *Source* elige la rama `main` y la carpeta `/root`. Guarda.
4. En un minuto tendrÃ¡s la app publicada en `https://TU-USUARIO.github.io/proyecto-68kg/`.

## Notas tÃ©cnicas

- HTML + CSS + JS puro, en un solo archivo.
- TipografÃ­as vÃ­a Google Fonts (Bricolage Grotesque + Inter).
- Las ilustraciones de los ejercicios se cargan por URL. Si quieres que el repo sea 100% autÃ³nomo, descarga las imÃ¡genes a una carpeta `img/` y cambia los `src` de cada ejercicio en el bloque `days` del script.

---

Constancia > perfecciÃ³n. El entreno esculpe, el dÃ©ficit adelgaza.
