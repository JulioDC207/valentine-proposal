# 💝 Propuesta de San Valentín

Una página web interactiva y romántica para hacer tu propuesta de San Valentín de una manera divertida.

## 🎯 Características

- Diseño romántico y moderno con gradientes animados
- **Imágenes de Bubu y Dudu** que cambian automáticamente cada 3 segundos
- Corazones flotantes en el fondo
- **Botones separados horizontalmente** para mejor experiencia
- Botón "Sí" estático y fácil de presionar
- Botón "No" que se mueve cuando intentas hacer hover (¡imposible de hacer clic!)
- Mensaje de celebración con confetti cuando aceptan
- Responsive para móviles y tablets

## 🚀 Despliegue en Render

### Opción 1: Despliegue desde GitHub

1. **Sube el código a GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Valentine's proposal page"
   git branch -M main
   git remote add origin https://github.com/TU-USUARIO/TU-REPOSITORIO.git
   git push -u origin main
   ```

2. **Despliega en Render:**
   - Ve a [Render.com](https://render.com) y crea una cuenta
   - Click en "New +" → "Static Site"
   - Conecta tu repositorio de GitHub
   - Configura:
     - **Name:** valentine-proposal (o el nombre que prefieras)
     - **Branch:** main
     - **Build Command:** (dejar vacío)
     - **Publish Directory:** . (punto)
   - Click en "Create Static Site"

### Opción 2: Despliegue directo (sin GitHub)

1. Ve a [Render.com](https://render.com)
2. Click en "New +" → "Static Site"
3. Selecciona "Deploy from Git"
4. Sigue las instrucciones de arriba

## 📁 Estructura del Proyecto

```
.
├── index.html          # Página principal
├── README.md          # Este archivo
└── render.yaml        # Configuración de Render
```

## 🎨 Personalización

Puedes personalizar fácilmente:
- Los colores en los gradientes CSS
- El texto de la pregunta
- El mensaje final
- Los emojis utilizados
- **Las imágenes de Bubu y Dudu**: Edita el array `bubuDuduImages` en el JavaScript para agregar o cambiar imágenes
- El tiempo de cambio de imágenes (actualmente 3 segundos)

## 🌐 Demo Local

Para ver la página localmente, simplemente abre `index.html` en tu navegador.

## 💻 Tecnologías

- HTML5
- CSS3 (Animaciones y Gradientes)
- JavaScript Vanilla
- Google Fonts (Pacifico & Quicksand)

## 📝 Licencia

Este proyecto es de uso libre. ¡Úsalo para tu propuesta especial! 💖

---
