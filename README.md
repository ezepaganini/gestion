# Mapa de proveedores

Un pizarrón para explorar y juntar ideas mientras buscás fabricantes y proveedores. Pensado para unas semanas de búsqueda, entre dos personas.

- Pegá el link de un proveedor arriba y Enter: aparece una tarjeta con la imagen de su página.
- Arrastrá tarjetas, notas y temas. Arrastrá el fondo para moverte y usá la rueda del mouse para acercar o alejar.
- **Unir** conecta dos elementos con una línea (si ya estaban unidos, los separa).
- Cada tarjeta tiene estado (tocá la etiqueta), estrellas, nombre y notas. Los descartados se ven apagados y se pueden ocultar.
- Notas de colores y "Mensaje a proveedor" con botón para copiar.

## Publicarlo
Subí `index.html` a un repo y activá **Settings, Pages, Deploy from a branch, main / root**.

## Compartido para cualquiera que tenga el link
Se guarda en una base gratuita de Firebase, así que todos ven y editan el mismo mapa y los cambios aparecen solos en unos segundos.
1. Entrá a https://console.firebase.google.com y creá un proyecto (sin Analytics).
2. Build, Realtime Database, Create Database, **modo de prueba**.
3. En **Rules** pegá `{"rules":{".read":true,".write":true}}` y tocá Publish (así no vence a los 30 días).
4. Copiá la URL de la pestaña Data (termina en `firebaseio.com` o `firebasedatabase.app`).
5. Pegala en `index.html`, en `const DB_URL='';`, y subí el cambio. Desde ahí funciona en cualquier dispositivo sin configurar nada.

Cualquiera que tenga el link puede editar o borrar. **Descargar copia** guarda un archivo de respaldo.
