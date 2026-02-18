# PERN Stack Task Manager

Aplicación Full Stack para la gestión de tareas (CRUD) desarrollada con arquitectura desacoplada. El proyecto integra un frontend interactivo en React y un backend en Node.js con persistencia de datos en PostgreSQL.

## STACK TECNOLÓGICO

### Frontend
- React.js: Biblioteca principal para la interfaz de usuario.
- Material UI (MUI): Framework de componentes para diseño responsivo.
- React Router Dom: Gestión de navegación y rutas SPA.

### Backend
- Node.js & Express: Entorno de ejecución y framework para la API REST.
- PostgreSQL: Sistema de gestión de base de datos relacional.
- Morgan & CORS: Middlewares para logging y manejo de políticas de acceso.

## ESTRUCTURA DEL PROYECTO

pern-stack/
├── client/          # Aplicación Frontend (React)
├── src/             # Lógica del Servidor (Node.js/Express)
├── database/        # Scripts SQL y configuración de DB
├── .gitignore       # Configuración unificada de exclusiones
└── package.json     # Dependencias y scripts del backend

## INSTALACIÓN Y EJECUCIÓN

1. Clonar repositorio:
   git clone https://github.com/Gabriel15278/Test_Fullstack_PERN.git

2. Configurar Backend:
   cd pern-stack
   npm install
   # Configurar variables de entorno (.env) con credenciales de PostgreSQL
   npm run dev

3. Configurar Frontend:
   cd client
   npm install
   npm start

## FUNCIONALIDADES CLAVE
- CRUD Completo: Creación, lectura, actualización y eliminación de tareas.
- Consumo de API: Comunicación asíncrona mediante fetch y manejo de JSON.
- Persistencia: Almacenamiento real en base de datos SQL.
