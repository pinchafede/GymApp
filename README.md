# Fede · Rutina & Fútbol 💪⚽

App personal de seguimiento de gym y fútbol. PWA instalable en celular.

---

## Cómo subir a GitHub Pages (paso a paso)

### 1. Crear cuenta en GitHub
- Entrá a **github.com**
- Hacé clic en **Sign up**
- Elegí un username (ej: `fedediaz`), tu email y una contraseña
- Verificá el email

---

### 2. Crear un repositorio nuevo
- Una vez dentro, hacé clic en el botón verde **New** (arriba a la izquierda)
- **Repository name:** `rutina-fede` (o el nombre que quieras)
- Dejalo en **Public** (necesario para GitHub Pages gratis)
- ✅ Marcá **Add a README file**
- Hacé clic en **Create repository**

---

### 3. Subir los archivos
Dentro del repositorio recién creado:
- Hacé clic en **Add file** → **Upload files**
- Arrastrá o seleccioná estos 5 archivos:
  - `index.html`
  - `manifest.json`
  - `sw.js`
  - `icon-192.png`
  - `icon-512.png`
- Abajo donde dice **Commit changes** escribí algo como `primera versión`
- Hacé clic en **Commit changes**

---

### 4. Activar GitHub Pages
- Hacé clic en **Settings** (en el menú del repositorio, arriba)
- En el menú de la izquierda, hacé clic en **Pages**
- En **Source**, seleccioná **Deploy from a branch**
- En **Branch**, seleccioná **main** y la carpeta **/ (root)**
- Hacé clic en **Save**
- Esperá 1-2 minutos

---

### 5. Tu URL
GitHub Pages te va a dar una URL así:
```
https://TUUSUARIO.github.io/rutina-fede/
```
Reemplazá `TUUSUARIO` con tu nombre de usuario de GitHub.

Podés verla en **Settings → Pages** una vez que esté lista.

---

## Instalar en el celular

### Android (Chrome) — recomendado
1. Abrí Chrome en el celular
2. Entrá a tu URL de GitHub Pages
3. Chrome te va a mostrar un banner **"Agregar a pantalla de inicio"** — tocalo
4. Si no aparece el banner: tocá los tres puntitos (⋮) → **Agregar a pantalla de inicio**
5. Confirmás y listo — aparece el ícono en tu home screen

### iPhone (Safari)
1. Abrí Safari (tiene que ser Safari, no Chrome)
2. Entrá a tu URL de GitHub Pages
3. Tocá el botón de compartir (el cuadrado con la flecha ↑)
4. Scrolleá y tocá **"Agregar a pantalla de inicio"**
5. Confirmás el nombre y tocás **Agregar**

---

## Actualizar la app

Cuando quieras actualizar (si cambiás algo):
1. Entrá al repositorio en GitHub
2. Hacé clic en el archivo que querés reemplazar (ej: `index.html`)
3. Hacé clic en el ícono del lápiz ✏️ o en **...** → **Upload new version** si estás reemplazando un archivo
4. En la misma pantalla de upload: borrá el viejo y subí el nuevo
5. Commit y listo — en unos minutos la app se actualiza

> **Nota:** Si tenés la app instalada en el celular, puede tardar unos minutos en actualizarse automáticamente por el service worker. Si querés forzar la actualización, cerrá y volvé a abrir la app.

---

## Archivos incluidos

| Archivo | Qué hace |
|---|---|
| `index.html` | La app completa |
| `manifest.json` | Configuración de la PWA (nombre, colores, íconos) |
| `sw.js` | Service worker — permite usar la app sin internet |
| `icon-192.png` | Ícono para Android y pantalla de inicio |
| `icon-512.png` | Ícono de alta resolución |
