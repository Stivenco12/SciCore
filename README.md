# Prueba de Astro 🚀

Proyecto de práctica construido con [Astro](https://astro.build), basado en la plantilla oficial *Basics*. Sirve como punto de partida para explorar la estructura y el flujo de trabajo de Astro.

## 📦 Tecnologías

- [Astro](https://astro.build) — Framework web para sitios rápidos y orientados a contenido.
- TypeScript (configuración incluida vía `tsconfig.json`).

## 🗂️ Estructura del proyecto

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── assets/
│   │   └── astro.svg
│   ├── components/
│   │   └── Welcome.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

- `src/pages/` — Cada archivo `.astro` se convierte automáticamente en una ruta del sitio.
- `src/components/` — Componentes reutilizables de Astro.
- `src/layouts/` — Plantillas de diseño compartidas entre páginas.
- `public/` — Archivos estáticos que se sirven tal cual (imágenes, favicon, etc.).

Más información en la [guía de estructura de proyectos de Astro](https://docs.astro.build/en/basics/project-structure/).

## 🧞 Comandos disponibles

Todos los comandos se ejecutan desde la raíz del proyecto en una terminal:

| Comando                   | Acción                                                       |
| :------------------------ | :------------------------------------------------------------ |
| `npm install`              | Instala las dependencias                                     |
| `npm run dev`               | Inicia el servidor de desarrollo en `localhost:4321`         |
| `npm run build`             | Genera el sitio de producción en `./dist/`                   |
| `npm run preview`           | Previsualiza el build localmente antes de desplegar           |
| `npm run astro ...`         | Ejecuta comandos CLI de Astro, como `astro add` o `astro check` |
| `npm run astro -- --help`   | Muestra la ayuda del CLI de Astro                             |

## 🚀 Cómo empezar

1. Clona el repositorio:
   ```bash
   git clone https://github.com/Stivenco12/Prueba_de_Astro.git
   cd Prueba_de_Astro
   ```
2. Instala las dependencias:
   ```bash
   npm install
   ```
3. Levanta el servidor de desarrollo:
   ```bash
   npm run dev
   ```
4. Abre [http://localhost:4321](http://localhost:4321) en tu navegador.

## 👀 Recursos adicionales

- [Documentación oficial de Astro](https://docs.astro.build)
- [Discord de Astro](https://astro.build/chat)

## 📄 Licencia

Este proyecto no especifica una licencia. Puedes añadir una según lo necesites (por ejemplo, MIT).
