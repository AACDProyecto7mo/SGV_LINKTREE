# SGV · Sistema de Gestión de Vacunas

Hub del proyecto **SGV** (Sistema de Gestión de Vacunas) para el vacunatorio del CAPS San José Obrero de Hurlingham, Buenos Aires.
Trabajo integrador del **Equipo N.° 01** de 7.° Informática — Instituto Leonardo Murialdo, ciclo lectivo 2026.

---

## 🌐 Sitio en vivo

Una vez publicado en GitHub Pages, el hub queda en:

**`https://<usuario>.github.io/sgv/`**

Reemplazá `<usuario>` por el nombre de tu cuenta o de la organización de GitHub donde subas el repo.

---

## 📂 Estructura del repositorio

```
sgv/
├── index.html          # Hub del proyecto (linktree)
├── docs/
│   └── index.html      # Documentación técnica del proyecto
├── manual/
│   └── index.html      # Manual de usuario (placeholder)
├── faq/
│   └── index.html      # Preguntas frecuentes (placeholder)
├── landing/
│   └── index.html      # Landing page pública (placeholder)
└── README.md
```

Cada carpeta con un `index.html` queda accesible por URL limpia:
- `.../sgv/` → hub
- `.../sgv/docs/` → documentación
- `.../sgv/manual/` → manual
- `.../sgv/faq/` → FAQ
- `.../sgv/landing/` → landing

---

## 🚀 Cómo publicar (paso a paso)

### 1. Crear el repositorio en GitHub

1. Ir a **https://github.com/new**
2. Nombre del repo: `sgv`
3. Visibilidad: **Public**
4. **No** marcar "Add a README" (ya viene uno)
5. Crear el repo.

### 2. Subir estos archivos

Desde la carpeta descomprimida:

```bash
git init
git add .
git commit -m "Publicación inicial del hub SGV"
git branch -M main
git remote add origin https://github.com/<usuario>/sgv.git
git push -u origin main
```

O más simple: arrastrar todos los archivos al botón "uploading an existing file" desde la web de GitHub.

### 3. Activar GitHub Pages

1. En el repo, ir a **Settings → Pages**
2. En *Source*, elegir **Deploy from a branch**
3. Branch: **main**, carpeta: **/ (root)**
4. Guardar.

En 1–2 minutos, la URL queda live en:
**`https://<usuario>.github.io/sgv/`**

### 4. Actualizar el link del repo en el hub

Editar `index.html` y reemplazar `<usuario>` por el usuario/organización real en:

```html
<a class="card teal is-live" href="https://github.com/<usuario>/sgv" ...>
```

---

## 🎨 Design system

- **Paleta**: teal `#0FA99E` (marca), lima `#A6CE39` (acento), sobre superficie `#FBFBFB`
- **Tipografía**: [Inter](https://fonts.google.com/specimen/Inter) (400–800), monoespaciada JetBrains Mono
- **Radios**: 8 / 12 / 18 / 24 px
- **Sombras**: multicapa con tinte teal (`rgba(7,104,98, .05–.22)`)
- **Auras**: radial-gradients teal + lima sobre onda SVG en el fondo

Todos los archivos son autocontenidos (CSS inline, logo en base64) — no dependen de recursos externos salvo Google Fonts.

---

## 📄 Contenido actual

| Página | Estado | Fuente |
|---|---|---|
| Hub (`/`) | ✅ Publicado | Este ZIP |
| Documentación (`/docs/`) | ✅ v1.1 (Primera y Segunda Sección completas) | Este ZIP |
| Host online del sistema | ✅ [Railway](https://sgv.up.railway.app/) | En vivo |
| Diagrama Gantt | ✅ [Google Sheets](https://docs.google.com/spreadsheets/d/1Ay-myLDqhTbIhL5ofrn1_Eldh-zxotrcFzRWhfUxkPs/) | En vivo |
| Manual de usuario (`/manual/`) | ⏳ Placeholder | Por completar |
| Preguntas frecuentes (`/faq/`) | ⏳ Placeholder | Por completar |
| Landing page (`/landing/`) | ⏳ Placeholder | Por completar |
| Repositorio GitHub | ⏳ Por definir usuario | — |

---

## 👥 Equipo N.° 01

- **Aloia Touzon, Morella** — Project Manager · UX/UI Designer
- **Aloia Mircovich, Agustín** — Desarrollador Front End / Back End
- **Cosimi, Tomás** — Desarrollador Back End
- **Dellepiane, Felipe** — Desarrollador Front End · Administrador de Base de Datos

7.° Informática · Instituto Leonardo Murialdo · Ciclo lectivo 2026
