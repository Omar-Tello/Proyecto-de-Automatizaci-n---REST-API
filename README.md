# Proyecto de Automatización - REST API

Este proyecto implementa la automatización de pruebas para una API REST. Las pruebas se realizan utilizando el framework **Serenity** junto con **IntelliJ IDEA** como entorno de desarrollo.


## Métodos Implementados

- **DELETE /airlines/{id}**: Elimina una aerolínea existente a partir de su ID.
- **GET /airlines**: Obtiene la lista de todas las aerolíneas disponibles.
- **POST /airlines**: Crea una nueva aerolínea con los datos proporcionados.
- **PUT /airlines/{id}**: Actualiza la información de una aerolínea existente.

## Tecnologías Utilizadas

- **Java**: El lenguaje principal para la automatización de pruebas.
- **Serenity**: Framework para la automatización de pruebas que facilita la creación de informes detallados y el manejo de escenarios de prueba.
- **IntelliJ IDEA**: Entorno de desarrollo integrado (IDE) utilizado para escribir y ejecutar las pruebas.
  
-**https://www.instantwebtools.net/fake-api/fake-rest-api/**

## Descripción del Proyecto

Este repositorio contiene los scripts necesarios para automatizar las pruebas de los métodos de una API REST que simula la gestión de aerolíneas. A través de estas pruebas, se verifica la correcta implementación de los endpoints para crear, obtener, actualizar y eliminar aerolíneas.

### ¿Cómo Ejecutar las Pruebas?

1. **Clonar el Repositorio:**
   - Clona este repositorio en tu máquina local:
    

2. **Configuración del Proyecto:**
   - Abre el proyecto en **IntelliJ IDEA**.
   - Asegúrate de tener las dependencias de Serenity configurada en tu proyecto. Puedes agregar las dependencias necesarias en el archivo `pom.xml` si usas Maven.

3. **Ejecutar las Pruebas:**
   - Ejecuta las pruebas directamente desde IntelliJ IDEA.
   - Alternativamente, puedes ejecutar las pruebas utilizando Maven con el siguiente comando:
     ```bash
     mvn clean verify
     ```

4. **Ver Resultados:**
   - Serenity generará un informe detallado de los resultados de las pruebas, el cual estará disponible en la carpeta `target/serenity`.



