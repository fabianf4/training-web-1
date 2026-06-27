# Space Tourism Website

Frontend Mentor challenge implementado con **React 19**, **Vite 8**, **React Router v7** y **Styled Components**.

## Stack

- React 19 + React Router v7
- Vite 8 + @vitejs/plugin-react
- Styled Components v6
- gh-pages para deploy

## Development

```bash
pnpm dev      # servidor de desarrollo
pnpm build    # build producción
pnpm preview  # preview local del build
pnpm deploy   # deploy a GitHub Pages
```

## Estructura

```
src/
├── assets/data.js        # datos estáticos (destinos, crew, tecnología)
├── components/
│   ├── Nav.jsx           # navegación responsive
│   ├── NavElements.js    # styled components del nav
│   └── styled.js         # styled components compartidos
├── pages/
│   ├── index/            # home
│   ├── destination/      # selector de destinos
│   └── error/            # página de error
├── routes/index.jsx      # configuración de rutas (hash router)
├── App.jsx               # layout principal
├── main.jsx              # entry point
├── normalize.css         # reset CSS
└── vars.css              # variables CSS y fuentes
```
