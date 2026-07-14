# Estudio Antropométrico · Vercel V5.21

Esta carpeta está lista para publicarse como sitio estático en Vercel.

## Archivos

- index.html: aplicación principal
- manifest.json: configuración PWA
- sw.js: funcionamiento sin conexión
- icon.svg: icono de la aplicación
- vercel.json: configuración de Vercel

## Publicación mediante Vercel CLI

1. Instalar Node.js.
2. Abrir PowerShell o Terminal dentro de esta carpeta.
3. Ejecutar:

   npm install -g vercel
   vercel login
   vercel

4. Para publicar en producción:

   vercel --prod

No necesita ejecutar npm install dentro de esta carpeta ni realizar una compilación.
