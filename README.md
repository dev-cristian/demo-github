# Proyecto Node.js con Express y TypeScript

Este es un proyecto base de Node.js configurado con Express y TypeScript.

## 🚀 Características

- **Node.js** - Entorno de ejecución de JavaScript
- **Express** - Framework web minimalista y flexible
- **TypeScript** - Superset de JavaScript con tipado estático
- **Nodemon** - Recarga automática durante el desarrollo
- **ts-node** - Ejecución directa de TypeScript

## 📦 Instalación

```bash
npm install
```

## 🛠️ Uso

### Modo Desarrollo

Inicia el servidor con recarga automática:

```bash
npm run dev
```

### Construcción

Compila TypeScript a JavaScript:

```bash
npm run build
```

### Modo Producción

Ejecuta la versión compilada:

```bash
npm start
```

## 📡 Endpoints

- `GET /` - Mensaje de bienvenida
- `GET /api/health` - Verificación del estado del servidor

## 🏗️ Estructura del Proyecto

```
demo-gitHub/
├── src/
│   └── index.ts        # Archivo principal del servidor
├── dist/               # Código compilado (generado)
├── node_modules/       # Dependencias (generado)
├── package.json        # Configuración del proyecto
├── tsconfig.json       # Configuración de TypeScript
└── README.md          # Este archivo
```

## 🔧 Tecnologías

- Node.js
- Express 4.x
- TypeScript 5.x
