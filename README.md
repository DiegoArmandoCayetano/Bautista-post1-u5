
# 📚 Biblioteca API

API REST desarrollada con Spring Boot para la gestión de libros en una biblioteca.

## 🚀 Tecnologías utilizadas

- Java 17+
- Spring Boot
- Spring Data JPA
- Base de datos H2 (en memoria)
- Maven


## ⚙️ Ejecución del proyecto

1. Clonar el repositorio:
```bash
git clone https://github.com/DiegoArmandoCayetano/Bautista-post1-u5.git
Entrar al proyecto:
cd biblioteca-api
Ejecutar la aplicación:
mvn spring-boot:run
Acceder a:
API: http://localhost:8080
H2 Console: http://localhost:8080/h2-console
🔑 Configuración H2
JDBC URL: jdbc:h2:mem:biblioteca_db
User: sa
Password: (vacío)
📌 Endpoints disponibles
➤ Crear libro

POST /api/libros

➤ Listar libros

GET /api/libros

➤ Buscar libros

GET /api/libros/buscar?q=texto

➤ Eliminar libro

DELETE /api/libros/{id}

🧪 Pruebas realizadas
✅ Creación de libro (POST)
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/f2906d29-3735-453f-9689-73f7f8ea6822" />

✅ Visualización en base de datos (H2)
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/b72a302b-30b5-4e60-8b0b-f8d4f5af8daf" />

✅ Consulta de libros (GET)
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/aa9ba344-d0f6-4055-bbda-6e2161ff62e4" />

✅ Creación de otro libro
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/5c76c659-cdbc-4ad5-a86b-f1b8a5e3a27b" />

✅ Verificación en base de datos
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/1f26d113-1bed-4eaa-b2ce-a4f645e491bd" />

✅ Eliminación de libros (DELETE)
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/373dfd44-2be7-499a-b0ff-c733c2179dbc" />

🎯 Funcionalidades
Crear libros
Listar libros
Buscar por título
Eliminar libros
Persistencia en base de datos en memoria
👨‍💻 Autor

Proyecto desarrollado por Diego Armando Cayetano.
