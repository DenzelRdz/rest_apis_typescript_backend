# REST API Node + TypeScript Server

Este proyecto es un servidor REST API construido con **Express.js**, **TypeScript** y **Sequelize** para manejar operaciones CRUD y conexión con base de datos PostgreSQL. Incluye documentación Swagger y pruebas automatizadas con Jest.

## 🚀 Características

- Desarrollado con **Express** y **TypeScript**
- Integración con **Sequelize** y **PostgreSQL**
- Validación con **express-validator**
- Documentación con **Swagger**
- Testing con **Jest** y **Supertest**
- Middleware de logging con **Morgan**
- Variables de entorno con **dotenv**
- Estructura modular y escalable

## 📦 Instalación

1. Clona el repositorio:

```bash
git clone https://github.com/tu_usuario/rest_api_node_ts_server.git
cd rest_api_node_ts_server
```

2. Instala las dependencias:

```bash
npm install
```

3. Configura tus variables de entorno en el archivo `.env`.

## 🛠️ Scripts disponibles

- `npm run dev`: Inicia el servidor en modo desarrollo con nodemon
- `npm run build`: Compila el proyecto a JavaScript
- `npm test`: Ejecuta los tests con Jest
- `npm run test:coverage`: Ejecuta los tests y genera el reporte de cobertura

## 📂 Estructura del Proyecto

```
src/
├── config/           # Configuración de base de datos y Swagger
├── data/             # Scripts de datos o reseteo
├── handlers/         # Controladores de rutas
├── middleware/       # Middlewares personalizados
├── models/           # Modelos Sequelize
├── __tests__/        # Pruebas unitarias
├── index.ts          # Punto de entrada
├── router.ts         # Definición de rutas
├── server.ts         # Configuración y levantamiento del servidor
```

## 📄 Documentación Swagger

Accede a la documentación Swagger en:  
```
http://localhost:3000/api-docs
```

## ✅ Pruebas

El proyecto utiliza Jest y Supertest para realizar pruebas automatizadas.  
Se genera un reporte de cobertura en `coverage/lcov-report/index.html`.

## 👨‍💻 Autor

**Denzel Rodriguez**  
Licencia: ISC
