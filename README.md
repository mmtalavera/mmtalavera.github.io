# mmtalavera.github.io

## Stack Tecnológico

Este sitio web está construido utilizando:

- **GitHub Pages**: Plataforma de hosting estático de GitHub que permite publicar sitios web directamente desde repositorios
- **Jekyll**: Generador de sitios estáticos que convierte archivos Markdown y otros formatos en sitios web completos

### Características

- Hosting gratuito en GitHub Pages
- Generación automática de sitios estáticos con Jekyll
- Soporte para Markdown, HTML, CSS y JavaScript
- Integración directa con el flujo de trabajo de Git

### Desarrollo Local

Para ejecutar el sitio localmente:

```bash
bundle install
bundle exec jekyll serve
```

El sitio estará disponible en `http://localhost:4000`

## Estructura del Proyecto

```
mmtalavera.github.io/
├── _config.yml              # Configuración principal de Jekyll
├── _data/                   # Archivos de datos (YAML)
│   └── services.yml        # Datos de servicios
├── _includes/              # Componentes reutilizables
├── _layouts/               # Plantillas de página
│   └── default.html       # Layout principal
├── _sass/                  # Archivos Sass/SCSS
│   ├── main.scss          # Estilos principales
│   └── custom.scss        # Estilos personalizados
├── assets/
│   ├── css/               # CSS compilado
│   └── images/            # Imágenes del sitio
│       └── services/      # Imágenes de servicios
├── index.html             # Página principal
├── Gemfile                # Dependencias Ruby
└── README.md              # Este archivo
```

## Archivos de Datos

### Servicios (`_data/services.yml`)

Contiene la información de los servicios ofrecidos. Estructura:

```yaml
- name: Nombre del Servicio
  description: Descripción del servicio
  image: assets/images/services/imagen.jpg
  benefits:
    - Beneficio 1
    - Beneficio 2
```

**Imágenes:** Las imágenes de servicios deben ubicarse en `assets/images/services/` utilizando rutas relativas para compatibilidad con GitHub Pages.

