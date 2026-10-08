# Explorer App

Aplicación web para explorar países, buscar por nombre, filtrar por región y consultar el detalle de cada país.

## Stack

- TypeScript
- Vite
- Tailwind CSS v4
- Datos de países locales en `public/countries.json`, con consulta opcional a REST Countries para el detalle

## Requisitos

- Node.js compatible con Vite 8
- pnpm

## Ejecución

```sh
pnpm install
pnpm run dev
```

Para verificar la compilación de producción y previsualizarla localmente:

```sh
pnpm run build
pnpm run preview
```

## Captura

![Explorer App en escritorio](Responsively-Screenshots/MacBook%20Pro-1788661057880.jpeg)

## Verificación local

- `pnpm run build`: correcto (`tsc` y `vite build`).
- Revisión en navegador local: búsqueda, filtro por región, navegación al detalle de Canadá y anuncio del estado sin resultados comprobados.
- Resultado de revisión: las funciones comprobadas siguen operativas; el estado sin resultados se anuncia con `aria-live="polite"`.

## Publicación y Pull Request

- Repositorio: [Dise-o-web-](https://github.com/josehrdez127-hue/Dise-o-web-).
- Pull Request: [Abrir el formulario para la rama de mejora](https://github.com/josehrdez127-hue/Dise-o-web-/pull/new/feat/announce-empty-search-results); pendiente de crear.
- Producción: pendiente de conectar el repositorio a Vercel y publicar el proyecto.

La protección de `main`, la revisión del PR, la preview y la URL de producción siguen pendientes. GitHub solicita iniciar sesión para completar el PR y Vercel devuelve `403` al iniciar la importación.