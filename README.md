# Marley Coffee · Prototipo web (versión final)

Maqueta interactiva con cuatro partes, todas dentro del mismo sitio:

1. **Sitio Marley Partners**: portada, soluciones (Café al paso, Bar, Oficina, Pods) y sus páginas de detalle.
2. **Portal Partners B2B**: botón «Portal Partners B2B» del menú, acceso empresarial, «Ingresar como Operador Demo», dashboard con consulta de stock, pedidos habituales y pedido de emergencia.
3. **Centro de Ayuda Marley** (menú «Preguntas Frecuentes»): buscador, categorías, preguntas destacadas, asistente de demostración y datos estructurados SEO/AEO.
4. **Academia Marley** (menú «Academia Marley»): biblioteca de cápsulas de limpieza por segmento, filtros, buscador y reproductor de video simulado.

Todo es una demostración: los datos son simulados, no hay conexión con sistemas reales y los contenidos marcados «Pendiente de validación» deben confirmarse con Marley.

## Requisitos
- Node.js 18 o superior (en CodeSandbox ya viene incluido).

## Cómo ejecutarlo
1. Abre una terminal en la carpeta del proyecto (donde está `package.json`).
2. Instala las dependencias: `npm install`
3. Inicia la aplicación: `npm run dev`
4. Abre en el navegador la dirección que aparece (normalmente http://localhost:5173).

Otros comandos: `npm run build` (genera la versión final en `dist/`) y `npm run preview` (la sirve).

## En CodeSandbox
Entra a codesandbox.io → Create → Import → Upload (o arrastra el ZIP). CodeSandbox instala todo y lanza `npm run dev` automáticamente.

## Estructura
- `index.html`: página base.
- `src/main.js`: toda la lógica y las vistas (sitio, portal B2B, centro de ayuda, academia).
- `src/styles.css`: estilos de Marley (colores, tipografías, componentes).
- `public/favicon.svg`: icono.
- `vite.config.js` y `package.json`: configuración (el servidor acepta el host de CodeSandbox).

Las tipografías (Barlow, Barlow Condensed y Caveat) se instalan como paquetes locales (@fontsource), no dependen de internet. El prototipo no usa fotografías: las imágenes son degradados y dibujos vectoriales incluidos en el código.
