# n8n en Render

Este proyecto levanta una instancia de `n8n` usando Docker en Render.com

## 🔧 Variables de entorno necesarias

Asegúrate de definir estas variables en Render:

- `N8N_BASIC_AUTH_ACTIVE=true`
- `N8N_BASIC_AUTH_USER=admin`
- `N8N_BASIC_AUTH_PASSWORD=yourPassword`
- `N8N_HOST=n8n.onrender.com`
- `WEBHOOK_URL=https://n8n.onrender.com/`

## 🚀 Despliegue

1. Subir el proyecto a GitHub.
2. Crear un nuevo servicio en Render (tipo `Web Service`) desde Docker.
3. Definir las variables de entorno en el dashboard.
4. Render construirá y desplegará automáticamente.
