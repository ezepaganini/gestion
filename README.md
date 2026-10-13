# Tablero de proveedores

Página estática para juntar y evaluar fabricantes y proveedores de tu futura marca. Pegás un link, se trae la imagen y el título de la página, y le sumás tipo, productos, país, mínimo de compra, precio, puntaje, estado y notas.

## Publicarlo en GitHub Pages
1. Creá un repo y subí estos archivos (`index.html`, `README.md` y la carpeta `data/`).
2. En el repo: **Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)`**.
3. En un minuto queda en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Cómo se guardan los datos
- Todo lo que cargás queda en el **navegador** (localStorage) del dispositivo que usás.
- Para tener los datos en el repo (y verlos desde cualquier dispositivo): botón **Exportar**, reemplazá `data/proveedores.json` y hacé commit. Si un navegador no tiene datos propios, la página carga ese archivo.
- **Importar** acepta ese mismo archivo para restaurar o sumar proveedores.
- Exportá seguido: si borrás los datos del navegador, se pierde lo que no exportaste.

## Vista previa de las páginas
- Se pide a [Microlink](https://microlink.io) (gratis, con límite diario) la imagen y el título de la página.
- Si no hay imagen, se usa una captura de [thum.io](https://www.thum.io).
- Siempre podés pegar a mano la URL de una imagen.
