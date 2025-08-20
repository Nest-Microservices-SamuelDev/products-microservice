# Product Microservice 🚀

## Descripción

Este es un microservicio construido con **NestJS** y **Prisma** diseñado para la gestión de productos. Proporciona una API robusta y escalable para crear, leer, actualizar y eliminar información de productos. El microservicio utiliza Prisma como ORM para interactuar con la base de datos, lo que garantiza una gestión de datos eficiente y segura. NestJS, con su arquitectura modular y basada en TypeScript, facilita la creación de aplicaciones empresariales mantenibles y testables.

---

## 🛠️ Prerrequisitos

Asegúrate de tener instaladas las siguientes herramientas en tu sistema:

* **Node.js:** (Versión LTS recomendada)
* **npm** o **yarn**

---

## 🚀 Instalación y Configuración

Sigue estos pasos para configurar el entorno de desarrollo:

1.  **Clonar el Repositorio:**
    ```bash
    git clone [https://github.com/Nest-Microservices-SamuelDev/products-microservice.git](https://github.com/Nest-Microservices-SamuelDev/products-microservice.git)
    cd product-microservice
    ```

2.  **Instalar las Dependencias:**
    ```bash
    npm install
    ```
    O si prefieres `yarn`:
    ```bash
    yarn install
    ```

3.  **Configuración del Entorno:**
    Crea un archivo `.env` en la raíz del proyecto basado en el archivo `env.template`.
    ```bash
    cp env.template .env
    ```
    Luego, ajusta las variables de entorno.

4.  **Configuración de la Base de Datos:**
    Ejecuta las migraciones de Prisma para crear el esquema en tu base de datos:
    ```bash
    npx prisma migrate dev
    ```

---

## ▶️ Ejecución de la Aplicación

### Modo Desarrollo
Para iniciar el servidor en modo de desarrollo con recarga automática:
```bash
npm run start:dev