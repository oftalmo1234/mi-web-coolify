# Mi Web en Coolify

Página web estática desplegada automáticamente con [Coolify](https://coolify.io) desde GitHub.

## Descripción

Sitio web sencillo que muestra cómo funciona el despliegue continuo usando Coolify conectado a un repositorio de GitHub.

## Archivos

- `index.html` — estructura de la página
- `style.css` — estilos y diseño visual

## Despliegue

El proyecto se despliega automáticamente en Coolify cada vez que se hace un `push` a la rama `main`.

### Requisitos
- Cuenta en [Coolify](https://coolify.io)
- Repositorio en GitHub
- Webhook configurado entre GitHub y Coolify

### Pasos para configurar
1. Crear una aplicación de tipo **Static Site** en Coolify
2. Conectar el repositorio de GitHub
3. Añadir el webhook de Coolify en GitHub → Settings → Webhooks
4. Hacer `push` a `main` para desplegar

## Tecnologías

- HTML5
- CSS3
