# Portfolio Edwin Torres

Portafolio personal de Edwin Torres, desarrollador de software. Un sitio moderno y responsivo construido con Astro y Tailwind CSS.

## 🌟 Características

- **Diseño Moderno**: Interfaz limpia y profesional
- **Dark Mode**: Soporte para tema oscuro/claro
- **Responsive**: Optimizado para todos los dispositivos
- **Rápido**: Construido con Astro para máximo rendimiento
- **SEO Friendly**: Generación automática de robots.txt
- **Accesible**: Siguiendo mejores prácticas de accesibilidad

## 📋 Secciones

- **Hero**: Introducción principal
- **Experiencia**: Historial laboral
- **Proyectos**: Portfolio de proyectos realizados
- **Sobre mí**: Información personal y habilidades

## 🛠️ Tecnologías

- [Astro](https://astro.build/) - Framework moderno
- [Tailwind CSS](https://tailwindcss.com/) - Utilidades CSS
- [TypeScript](https://www.typescriptlang.org/) - Type safety
- [Astro Robots TXT](https://github.com/alextim/astro-robots-txt) - SEO

## 📦 Instalación

```bash
# Clonar el repositorio
git clone https://github.com/EdTowers1/potfolio-edtorres.git
cd potfolio-edtorres

# Instalar dependencias (con pnpm recomendado)
pnpm install

# O con npm
npm install

# O con yarn
yarn install
```

## 🚀 Desarrollo

Para iniciar el servidor de desarrollo:

```bash
# Con pnpm
pnpm dev

# O con npm
npm run dev
```

El sitio estará disponible en `http://localhost:3000`

## 🔨 Build

Para crear una versión optimizada para producción:

```bash
# Con pnpm
pnpm build

# O con npm
npm run build
```

Los archivos compilados estarán en la carpeta `dist/`

## 👁️ Preview

Para previsualizarar la versión de producción localmente:

```bash
pnpm preview
```

## 📁 Estructura del Proyecto

```
src/
├── components/          # Componentes reutilizables
│   ├── AboutMe.astro   # Sección sobre mí
│   ├── Badge.astro     # Componente de badge
│   ├── Card.astro      # Componente de tarjeta
│   ├── Experience.astro # Sección de experiencia
│   ├── ExperienceItem.astro
│   ├── Footer.astro    # Pie de página
│   ├── Header.astro    # Encabezado
│   ├── Hero.astro      # Sección hero
│   ├── Projects.astro  # Sección de proyectos
│   ├── SectionContainer.astro # Contenedor de secciones
│   ├── ThemeToggle.astro # Toggle tema claro/oscuro
│   └── icons/          # Componentes de iconos SVG
├── layouts/            # Layouts base
├── pages/              # Rutas/páginas del sitio
│   ├── index.astro     # Página principal
│   └── components.astro # Página de componentes
└── env.d.ts           # Tipos TypeScript

public/               # Archivos estáticos
tailwind.config.mjs   # Configuración de Tailwind
astro.config.mjs      # Configuración de Astro
tsconfig.json         # Configuración de TypeScript
```

## 🔗 Enlaces

- [Sitio en vivo](https://porfolio.dev/)
- [Perfil de GitHub](https://github.com/EdTowers1)

## 📝 Licencia

Este proyecto está bajo la licencia MIT. Ver el archivo `LICENSE.md` para más detalles.

## 🤝 Contribución

Las contribuciones son bienvenidas. Para cambios significativos, abre un issue primero para discutir los cambios propuestos.

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request
