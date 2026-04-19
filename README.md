# Sistema de Gestión de Turnos Médicos 🏥

Este proyecto consiste en el diseño y desarrollo de una base de datos relacional para administrar la operativa diaria de un hospital o clínica, centrada en la gestión de pacientes, médicos y la asignación de turnos.

## 🚀 Objetivo
El sistema busca organizar la información de manera eficiente, garantizando la integridad de los datos mediante el uso de claves foráneas y restricciones, facilitando la consulta de disponibilidad horaria y el historial de pacientes.

## 🛠️ Tecnologías utilizadas
* **Lenguaje:** SQL (MySQL)
* **Modelado:** Entidad-Relación (E-R)

## 📊 Estructura de la Base de Datos
El modelo cuenta con las siguientes entidades principales:
- **Pacientes:** Registro de datos personales y contacto.
- **Médicos:** Información profesional vinculada a su especialidad.
- **Especialidades:** Clasificación de las áreas médicas disponibles.
- **Turnos:** Gestión de citas vinculando pacientes con médicos en fechas y horarios específicos.

## 📂 Contenido del Repositorio
- `schema.sql`: Script con la creación de todas las tablas y relaciones.
- `data_seeds.sql`: (Próximamente) Datos de prueba para testear el sistema.
- `queries.sql`: (Próximamente) Consultas útiles como reportes de turnos por día o médico.

## ⚙️ Cómo utilizarlo
1. Clona este repositorio.
2. Importa el archivo `schema.sql` en tu gestor de base de datos (MySQL Workbench, phpMyAdmin, etc.).
3. ¡Listo para realizar consultas!
