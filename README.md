# LiterAlu
Este proyecto es una aplicación de gestión de literatura construida con Spring Boot. A continuación, se detalla la estructura del proyecto e instrucciones básicas para su configuración y puesta en marcha.

## Descripción de los Directorios y Archivos 

- **.idea**: Directorio de configuración para el IDE IntelliJ IDEA.
- **.mvn**: Directorio de configuración para Maven Wrapper.
- **src/main/java/com.alura.literatura**: Contiene el código fuente principal de la aplicación.
    - **config**: Almacena las configuraciones de la aplicación.
    - **dto**: Define los Objetos de Transferencia de Datos para el intercambio de información.
    - **model**: Define los modelos de datos que representan la estructura de la base de datos.
    - **principal**: Contiene la clase principal que inicia la aplicación Spring Boot.
    - **repository**: Define las interfaces de repositorio para el acceso a la base de datos.
    - **service**: Contiene la lógica de negocio de la aplicación.
    - **LiteraturaApplication.java**: La clase principal que arranca la aplicación Spring Boot.
- **src/main/resources**: Contiene los recursos de la aplicación.
    - **application.properties**: Archivo de configuración principal de la aplicación.
    - **logback-spring.xml**: Configuración para el registro de logs.
- **src/test**: Contiene las pruebas unitarias y de integración.
- **target**: Directorio donde se generan los archivos compilados por Maven.
    - **.gitattributes**: Configuración de atributos para Git.
    - **.gitignore**: Archivos y carpetas que Git ignora.
    - **HELP.md**: Documentación de ayuda.
    - **mvnw** y **mvnw.cmd**: Scripts de Maven Wrapper para ejecutar comandos de Maven sin necesidad de tener Maven instalado globalmente.
    - **pom.xml**: Archivo de configuración del proyecto Maven.
    - **README.md**: Este archivo, la documentación del proyecto.

## Configuración y Ejecución 

### Requisitos Previos ⚙️

- Java 11 o superior
- Maven

### Pasos para Ejecutar la Aplicación ▶️

1. Clona el repositorio:
   ```sh
https://github.com/jano-iestp/literalura
   ```

2. Compila y ejecuta la aplicación usando Maven:
   ```sh
   ./mvnw spring-boot:run
   ```

3. La aplicación estará disponible en `http://localhost:8080`.


