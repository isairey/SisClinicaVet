# 🐾 Sistema de Gestión Veterinaria

Aplicación desarrollada en **C# con .NET** para la administración de una clínica veterinaria. Permite gestionar mascotas, dueños, citas médicas y el historial clínico de manera eficiente.

---

## 🚀 Características

* 🐶 Gestión de mascotas (registro, edición y eliminación)
* 👤 Administración de dueños
* 📅 Control de citas veterinarias
* 🩺 Historial clínico de mascotas
* 💊 Registro de tratamientos y medicamentos
* 💰 Gestión de servicios y pagos
* 🔐 Sistema de autenticación de usuarios
* 📊 Panel de control con estadísticas

---

## 🛠️ Tecnologías Utilizadas

* 💻 C#
* ⚙️ .NET (ASP.NET Core / Windows Forms)
* 🗄️ SQL Server
* 🎨 HTML, CSS, JavaScript (si es web)
* 🧰 Visual Studio

---

## 📦 Instalación

### 1️⃣ Clonar el repositorio

```bash id="a1r9xf"
git clone https://github.com/isairey/SisClinicaVet.git
cd SisClinicaVet
```

---

### 2️⃣ Abrir el proyecto

* Abrir **Visual Studio**
* Seleccionar **Open Project/Solution**
* Cargar el archivo `.sln`

---

### 3️⃣ Configurar la base de datos

Editar el archivo `appsettings.json`:

```json id="ybqk7r"
"ConnectionStrings": {
  "DefaultConnection": "Server=localhost;Database=ClinicaVeterinaria;Trusted_Connection=True;"
}
```

---

### 4️⃣ Ejecutar migraciones (si aplica)

```bash id="e4q3j6"
dotnet ef database update
```

---

### 5️⃣ Ejecutar la aplicación

```bash id="9u2m7k"
dotnet run
```

👉 O presiona **F5** en Visual Studio

---

## 📁 Estructura del Proyecto

```id="2w6z0n"
📦 Proyecto
 ┣ 📂 Controllers
 ┣ 📂 Models
 ┣ 📂 Views
 ┣ 📂 Services
 ┣ 📂 Data
 ┗ 📄 Program.cs
```

---

## 🔌 Funcionalidades Principales

### 🐾 Mascotas

* Registro de mascotas
* Asociación con dueños
* Edición y eliminación

---

### 👤 Dueños

* Registro de clientes
* Gestión de información

---

### 📅 Citas

* Agendar consultas
* Control de fechas y horarios

---

### 🩺 Historial Clínico

* Diagnósticos
* Tratamientos
* Medicamentos

---

## 🔐 Seguridad

* Autenticación de usuarios
* Validación de datos
* Protección contra inyecciones SQL
* Control de acceso por roles

---

## 🧪 Pruebas

```bash id="b3zq1k"
dotnet test
```

---

## 🤝 Contribuciones

1. Fork del repositorio
2. Crear una rama (`git checkout -b feature/nueva-funcionalidad`)
3. Commit (`git commit -m 'Nueva funcionalidad'`)
4. Push (`git push origin feature/nueva-funcionalidad`)
5. Crear Pull Request

---

## 📜 Licencia

Este proyecto está bajo la licencia MIT.

---

## 👨‍💻 Autor

Desarrollado por **Isai Reyes**
