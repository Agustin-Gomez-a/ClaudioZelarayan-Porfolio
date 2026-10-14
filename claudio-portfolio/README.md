# Claudio Zelarayan — Portfolio

Portfolio editorial de una página, construido con Astro y Tailwind CSS 4. El sitio parte de la información pública, los enlaces y las piezas visuales del portfolio actual de Claudio.

## Empezar

Requiere Node.js 22.12 o superior.

```sh
npm install
npm run dev
```

Para generar y previsualizar la versión estática:

```sh
npm run build
npm run preview
```

## Personalizar

- Editá textos, proyectos y enlaces en `src/pages/index.astro`.
- Reemplazá las imágenes de `src/assets/work/` conservando o actualizando sus importaciones.
- Ajustá colores, tipografía y movimiento en `src/styles/global.css`.
- El formulario prepara un correo dirigido a Claudio; no requiere servidor ni servicio externo.

## Despliegue

El proyecto genera un sitio estático compatible con Cloudflare Pages. Usá `npm run build` como comando de construcción y `dist` como directorio de salida.

Las imágenes incluidas se obtuvieron del portfolio público facilitado como referencia: <https://portfolio-claudio.pages.dev/>.
