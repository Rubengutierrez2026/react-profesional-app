# React Profesional App

Proyecto inicial de React con JavaScript y Vite.
La pantalla principal muestra el título "Base de App Inicializada".

## Requisitos

- Node.js 24 o una versión compatible con Vite.
- npm instalado.

## Instalación local

Descargá o cloná el repositorio y abrí una terminal dentro
de la carpeta `react-profesional-app`.

Instalá las dependencias:

```bash
npm install
```

## Ejecutar el proyecto

Iniciá el servidor de desarrollo:

```bash
npm run dev
```

Abrí en el navegador la dirección que indique la terminal,
habitualmente http://localhost:5173/.

Para detener el servidor, presioná Ctrl + C en la terminal.

## Verificación

- La página debe mostrar "Base de App Inicializada".
- La consola del navegador no debe mostrar errores ni archivos 404.
- Ejecutá `npm list react react-dom` para comprobar que ambos
  paquetes tienen la versión principal 19.

## Archivos excluidos del repositorio

El archivo `.gitignore` debe incluir `node_modules` y `dist`.
Las dependencias se recuperan ejecutando `npm install`.
