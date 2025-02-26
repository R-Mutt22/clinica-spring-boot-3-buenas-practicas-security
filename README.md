# clinica-spring-boot-3-buenas-practicas-security

Java  
-buenas practicas en diseño de API  
++fundamentos basicos de autenticación y autorización  
*retornar codigos de error HTTP  
**fundamentos de Spring Security

# Clínica - Spring Boot 3 con Buenas Prácticas y Seguridad

![Clinica](https://via.placeholder.com/800x200.png?text=Clinica+API) <!-- Puedes reemplazar esta URL con una imagen relevante -->

## Descripción

El proyecto **Clínica** es una API REST desarrollada con **Spring Boot 3** que implementa buenas prácticas de desarrollo y seguridad. Este sistema permite gestionar la información de pacientes, médicos y citas en una clínica, asegurando la protección de datos sensibles y la integridad de las operaciones.

## Características

- **Gestión de Pacientes:** Agregar, actualizar, eliminar y consultar información de pacientes.
- **Gestión de Médicos:** Agregar, actualizar, eliminar y consultar información de médicos.
- **Gestión de Citas:** Programar, cancelar y consultar citas médicas.
- **Seguridad:** Implementación de autenticación y autorización utilizando Spring Security.
- **Buenas Prácticas:** Estructura de código organizada, uso de patrones de diseño y documentación clara.

## Tecnologías Utilizadas

- **Java 17**
- **Spring Boot 3**
- **Spring Security**
- **Spring Data JPA**
- **Hibernate**
- **MySQL**
- **Maven**
- **Postman** (para pruebas de API)

## Instalación

Sigue estos pasos para configurar y ejecutar la API en tu entorno local:

1. **Clona el repositorio:**

   ```bash
   git clone https://github.com/R-Mutt22/clinica-spring-boot-3-buenas-practicas-security.git

2. **Navega al directorio del proyecto:**

      ```bash
   cd clinica-spring-boot-3-buenas-practicas-security

3. **Configura la base de datos:**
-Crea una base de datos en MySQL llamada clinica.
-Actualiza el archivo application.properties con tus credenciales de MySQL.

   ```bash
   spring.datasource.url=jdbc:mysql://localhost:3306/clinica
   spring.datasource.username=tu_usuario
   spring.datasource.password=tu_contraseña
   ```

4. **Ejecuta el proyecto:**

   ```bash
   mvn spring-boot:run

## Uso

Una vez que la API esté en funcionamiento, puedes utilizar herramientas como **Postman** para interactuar con los siguientes endpoints:

### Pacientes:
- `GET /api/pacientes` - Obtener todos los pacientes.
- `POST /api/pacientes` - Agregar un nuevo paciente.
- `PUT /api/pacientes/{id}` - Actualizar un paciente existente.
- `DELETE /api/pacientes/{id}` - Eliminar un paciente.

### Médicos:
- `GET /api/medicos` - Obtener todos los médicos.
- `POST /api/medicos` - Agregar un nuevo médico.
- `PUT /api/medicos/{id}` - Actualizar un médico existente.
- `DELETE /api/medicos/{id}` - Eliminar un médico.

### Citas:
- `GET /api/citas` - Obtener todas las citas.
- `POST /api/citas` - Programar una nueva cita.
- `DELETE /api/citas/{id}` - Cancelar una cita.

## Seguridad

Este proyecto implementa **Spring Security** para proteger los endpoints. Asegúrate de autenticarte antes de realizar operaciones que modifiquen datos. Puedes utilizar un **token JWT** para la autenticación.

## Contribuciones

Si deseas contribuir a este proyecto, siéntete libre de abrir un **issue** o enviar un **pull request**. Todas las contribuciones son bienvenidas.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

## Contacto

Para más información, puedes contactarme a través de:

- **LinkedIn:** [Tu perfil de LinkedIn](https://www.linkedin.com/in/matiaszelarayan22/)
- **GitHub:** [R-Mutt22](https://github.com/R-Mutt22)

¡Gracias por tu interés en la API Clínica! Espero que este proyecto sea útil y que puedas contribuir a su mejora.
