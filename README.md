# 🌐 Proyecto Vite con BOOTSTRAP 5.3.3

Este proyecto es una plantilla básica que integra Vite con BootStrap version 5.3.3 con algo de responsive.

## 🛠️ Tecnologías Utilizadas
- Vite: Herramienta de compilación rápida para proyectos web modernos.
- BootStrap 5.3.3: Framework de CSS utilitario para diseñar interfaces de usuario eficientes.

**Requisitos:📑**
Asegúrate de tener instalados los siguientes componentes:

- Node.js (versión 12 o superior)
- npm (gestor de paquetes de Node.js)

## ⚙️ Instalación

Para poner en marcha este proyecto en tu máquina local, sigue estos pasos:

1. Clona el repositorio

2. Instalar dependencias
```bash
npm install
```
3. Inicializar la configuracion de BootStrap
```bash
npm i bootstrap@5.3.3
```
Este comando genera los archivos tailwind.config.js y postcss.config.js en la raíz del proyecto.
4. Configurar los archivos de BootStrap🧮 
```bash
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```
5. Ejecutar el servidor de desarrollo
```bash
npm run dev
```

📄 Licencia

Este proyecto está bajo la licencia MIT.

🎨 Capturas de Pantalla
Aquí tienes una vista previa de cómo luce el proyecto:

![Pantalla Principal](https://github.com/AlbertoContento/Proyecto-BootStrap/blob/main/Bootstrap/media/Captura%20de%20pantalla.png)
