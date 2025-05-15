Sistema de Gestión Empresarial Multidepartamental
Dashboard Preview

![index](https://github.com/user-attachments/assets/59921e40-d518-41d6-ac8f-252b0f320b5c)

![contact](https://github.com/user-attachments/assets/71e45879-b399-4135-9ca1-28a054087465)

![login](https://github.com/user-attachments/assets/7209d978-10c7-4aa1-a190-1017fc6bcac3)


Sistema integral para gestión de departamentos empresariales desarrollado con Go (Gin), Bootstrap 5, y JavaScript, que incluye módulos independientes para:

🏢 Departamentos y Funcionalidades Clave
🌐 Página Informativa Base
Landing page corporativa con acceso a los sistemas departamentales

Autenticación centralizada con redirección según rol

🔧 Departamento de Servicio
Carrusel interactivo de servicios (JavaScript)

Acceso restringido (rol "servicio")

Detalles completos de cada servicio

Sistema de tickets integrado

💻 Departamento de Tecnología
go
// Ejemplo de estructura para equipos tecnológicos
type Equipo struct {
    ID          int
    Nombre      string
    Estado      string // "Activo"|"Inactivo"
    UltimaConex time.Time
    UsuarioAsignado string
}
Monitor en tiempo real con indicadores LED (verde/rojo)

Inventario de equipos tecnológicos

Integración con sistema de RRHH para monitoreo de presencia
![usertecnologia](https://github.com/user-attachments/assets/37ff90bf-e22f-401f-af04-97211ef0c80e)

![usertecnologia2](https://github.com/user-attachments/assets/7c530c7e-4a8b-4b35-8660-8f483d6d03af)


👥 Recursos Humanos
Registro completo de empleados

Control de asistencia con notificaciones visuales (LED)

Dashboard analítico de personal activo/inactivo

Generación de reportes mensuales
![resursoshumanos](https://github.com/user-attachments/assets/ebcd0f96-7bca-451f-85f4-59a4443d81be)

![recursohumaomonitoreousuarios](https://github.com/user-attachments/assets/142b762d-71b4-4db3-a954-fa40090eb591)
![ersonasconectadas](https://github.com/user-attachments/assets/e21be9dc-3ab6-47ec-aaed-c3ba3e663a72)


💰 Administración
Gestión de bienes y activos

Sistema de nómina automatizado

Cálculo de presupuestos para equipos

Generación de reportes PDF (ej: balances, proyecciones)
![admimisteaciin1](https://github.com/user-attachments/assets/4bb158ac-b245-4d5b-9487-f9d919957558)

![administraciin2](https://github.com/user-attachments/assets/183ee3b9-a27e-4a46-91dd-573838aa3787)
![adminsteaciin3](https://github.com/user-attachments/assets/a2a39adc-bfb1-4624-9fe1-d4fe6e60bb14)
![administraciin4](https://github.com/user-attachments/assets/4d7e75bc-89a1-483f-9506-24f62ac971b2)

🚀 modulo de servicios 
![servicios1](https://github.com/user-attachments/assets/3d686df9-efb7-49a2-9d45-7d82853f17e2)
![service2](https://github.com/user-attachments/assets/070031f5-7bc5-41a7-ab65-fd470d6c7e68)


🛠️ Stack Tecnológico
Capa	Tecnologías
Backend	Go (Golang), Gin Framework, PostgreSQL
Frontend	Bootstrap 5, JavaScript (ES6+), Chart.js, HTML5/CSS3
Autenticación	JWT, Middlewares de autorización por rol
Reportes	PDFKit (generación de PDFs), Excel export
Real-Time	WebSockets (para monitoreo de conexión)
🚀 Cómo Ejecutar el Proyecto
Requisitos:

bash
Go >= 1.20
PostgreSQL >= 13
Node.js (para assets frontend)
Configuración:

bash
git clone https://github.com/tuempresa/sistema-gestion-empresarial.git
cd sistema-gestion-empresarial
cp .env.example .env
# Configurar variables en .env
Iniciar:

bash
# Backend
go mod tidy
go run main.go

# Frontend (otra terminal)
cd frontend && npm install
npm run dev

📌 Características Destacadas
Sistema Multi-Rol: Autenticación JWT con middlewares por departamento

Monitor en Tiem Real: WebSockets para estados de conexión

Responsive: Compatible con móviles y tablets

Seguro: Validación de datos en backend y frontend

db PostgreSQL
![dbdeparralekto](https://github.com/user-attachments/assets/5c165183-2004-41da-8125-0226b8e1294f)

code

![Screenshot_1](https://github.com/user-attachments/assets/67ab8d43-4c28-47f5-bdf2-896745ef1097)



