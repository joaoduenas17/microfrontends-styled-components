# Estilado aislado con Styled Components en Microfrontends

Este proyecto demuestra el uso de **Styled Components** para evitar colisiones de estilos
en una arquitectura de **microfrontends** desarrollados con React.

## 📦 Arquitectura

- **mf-productos** → Microfrontend de Productos
- **mf-usuarios** → Microfrontend de Usuarios
- **shell** → Aplicación contenedora que integra ambos microfrontends

Cada microfrontend:
- Usa React
- Usa Styled Components
- Mantiene estilos encapsulados y aislados

## 🚀 Tecnologías

- React
- Styled Components
- Node.js / npm

## ▶️ Ejecución del proyecto

### 1. Microfrontend Productos
```bash
cd mf-productos
npm install
PORT=3001 npm start


Microfrontend Usuarios
cd mf-usuarios
npm install
PORT=3002 npm start


Aplicación Contenedora (Shell)
cd shell
npm install
npm start


Abrir en el navegador:

Shell: http://localhost:3000

Productos: http://localhost:3001

Usuarios: http://localhost:3002
