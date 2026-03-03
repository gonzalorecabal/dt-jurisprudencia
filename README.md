# dt-jurisprudencia

Repositorio de jurisprudencia administrativa de la Dirección del Trabajo (DT) en formato JSON.

## Estructura
- `data/<año>/dictamenes.json` (y en el futuro: `ordinarios.json`, `circulares.json`, `ordenes.json`)
- `indexes/etiquetas.json`
- `schema/dt_documento.schema.json`

## Publicar como API estática (GitHub Pages)
1. En GitHub: **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` y carpeta `/ (root)`
4. Guarda y usa la URL `https://<usuario>.github.io/<repo>/`

Ejemplo:
- `https://<usuario>.github.io/dt-jurisprudencia/data/2016/dictamenes.json`
