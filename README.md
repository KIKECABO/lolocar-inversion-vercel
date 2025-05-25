# Oportunidad de Inversión Lolocar

Este repositorio contiene una landing page interactiva para analizar la oportunidad de inversión en Lolocar.  
El sitio está diseñado para ser estático y desplegado fácilmente en [Vercel](https://vercel.com/).

## Despliegue en Vercel

1. Haz fork o clona este repositorio.
2. Sube los cambios a tu cuenta de GitHub.
3. Ingresa a [https://vercel.com/import](https://vercel.com/import) y conecta tu repositorio.
4. Vercel detectará automáticamente el archivo `index.html` y desplegará el sitio.

## Estructura

- `index.html`: Página principal, lista para producción.
- `vercel.json`: (Opcional) Asegura que la raíz del dominio cargue `index.html`.

## Notas de seguridad

Si usas APIs con clave (por ejemplo, Gemini), configura tus variables de entorno en Vercel y nunca expongas la clave directamente en el HTML. Usa funciones serverless si es necesario.