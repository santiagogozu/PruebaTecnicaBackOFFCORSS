# Prueba Técnica OFFCORSS - Backend

Esta aplicación es el backend de la prueba técnica para OFFCORSS. Permite gestionar usuarios y operaciones relacionadas, conectándose a una base de datos MySQL.

## Funcionalidades principales

- Gestión de usuarios (crear, leer, actualizar, eliminar)
- Autenticación y autorización
- Conexión a base de datos MySQL

## Requisitos previos

- Node.js (v16 o superior recomendado)
- npm o yarn
- Acceso a una base de datos MySQL

## Instalación

1. Clona el repositorio:

   ```bash
   git clone https://github.com/santiagogozu/PruebaTecnicaBackOFFCORSS
   cd PruebaTecnicaBackOFFCORSS
   ```

2. Instala las dependencias:
   ```bash
   npm install
   # o
   yarn install
   ```

## Configuración

Crea un archivo `.env` en la raíz del proyecto con las siguientes variables de entorno para la conexión a la base de datos MySQL:

```
DB_HOST=
DB_PORT=
DB_USER=
DB_PASSWORD=
DB_NAME=
```

Asegúrate de completar estos valores según tu entorno de base de datos.

Actualmente, el archivo `.env` tiene la información de una base de datos desplegada. Si deseas conectar a otra base de datos, reemplaza este valor por la URL correspondiente.

## Ejecución

Para iniciar el servidor

```bash
npm run start
```

El servidor se ejecutará por defecto en el puerto 4000 (puedes cambiarlo en el archivo de configuración si es necesario).

## Notas adicionales

- Asegúrate de que el puerto configurado esté libre antes de iniciar la aplicación.
- Si necesitas cambiar la configuración de la base de datos, actualiza la variable en el archivo `.env`.
