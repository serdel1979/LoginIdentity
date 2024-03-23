# Implementación de Login con ASP.NET Identity

Este repositorio es un ejemplo de la implementación de un sistema de login para una aplicación web API utilizando ASP.NET Identity.

## Descripción

ASP.NET Identity es un marco de trabajo flexible y potente para la administración de autenticación y autorización en aplicaciones web. En este repositorio, se proporciona un ejemplo básico de cómo configurar y utilizar ASP.NET Identity para gestionar la autenticación de usuarios en una aplicación web API desarrollada en .NET.

## Pasos para Clonar y Ejecutar el Proyecto

Sigue estos pasos para clonar y ejecutar el proyecto en tu entorno local:

1. **Clonar el repositorio:**

    ```bash
    git clone https://github.com/serdel1979/LoginIdentity.git
    ```

2. **Abrir el Proyecto:**

    Navega hasta el directorio clonado:

    ```bash
    cd LoginIdentity
    ```

3. **Compilar el Proyecto:**

    Utiliza el comando `dotnet build` para compilar el proyecto:

    ```bash
    dotnet build
    ```

4. **Configurar la Base de Datos:**

    Antes de ejecutar la aplicación, asegúrate de que la cadena de conexión a la base de datos sea válida en el archivo `appsettings.json`. Puedes utilizar una base de datos local o remota según tus necesidades.

5. **Aplicar Migraciones:**

    Utiliza el comando `dotnet ef database update` para aplicar las migraciones a tu base de datos:

    ```bash
    dotnet ef database update
    ```

6. **Ejecutar la Aplicación:**

    Una vez configurada la base de datos, puedes ejecutar la aplicación utilizando el comando `dotnet run`:

    ```bash
    dotnet run
    ```

7. **Probar la Aplicación:**

    Una vez que la aplicación esté en funcionamiento, puedes probarla accediendo a través de un cliente HTTP como Postman o utilizando herramientas de prueba de API.

## Contribución

Si deseas contribuir a este proyecto, ¡siéntete libre de hacer un fork y enviar tus propias contribuciones a través de pull requests!
