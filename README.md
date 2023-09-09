# APV - Aplicación de Pacientes de Veterinaria

Este backend está desarrollado utilizando Node.js y Express.js y proporciona la funcionalidad necesaria para gestionar pacientes y veterinarios en una aplicación de veterinaria.

## Instalación

1. Clona este repositorio en tu máquina local:
    
    ```bash
    git clone https://github.com/marvin211/APV_BackEnd.git
    ```

2. Navega al directorio del proyecto:

    ```bash
    cd APV_BackEnd
    ```

3. Para instalar las dependencias del proyecto, ejecuta el siguiente comando:

    ```bash
    npm install
    ```

## Configuración

El proyecto utiliza variables de entorno para la configuración. Debes crear un archivo .env en la raíz del proyecto y configurar las siguientes variables:
    
    ```bash
    MONGO_URI= # URI (Uniform Resource Identifier) de conexión a la base de datos MongoDB
    EMAIL_USER= # Dirección de correo electrónico desde la que se enviarán los correos
    EMAIL_PASS= # Contraseña de la dirección de correo electrónico
    EMAIL_HOST= # Servidor de correo electrónico
    EMAIL_PORT= # Puerto del servidor de correo electrónico
    FRONTEND_URL= # URL del frontend
    JWT_SECRET= # Clave secreta para la generación de tokens JWT
    PORT= # Puerto en el que se ejecutará el servidor
    ```

## Ejecución

Para ejecutar el proyecto, ejecuta el siguiente comando:

```bash
npm start
```

## Desarrollo

Para ejecutar el proyecto en modo desarrollo, ejecuta el siguiente comando:

```bash
npm run dev
```
