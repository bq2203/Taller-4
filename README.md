Readme · MDCopa Élite FC – Taller 4: Ecosistema Web Bootstrap

Proyecto multipágina desarrollado con Bootstrap 5 para el Taller Final del curso HTML + Bootstrap + Git del SENA.

Tema

Torneo de Fútbol – Copa Élite FC 2025

Tecnologías usadas


Bootstrap 5.3.3 (vía CDN)
Bootstrap Icons 1.11.3
HTML5 semántico
Sin CSS personalizado


Estructura del proyecto

taller4/
├── index.html              # Landing Page pública
├── README.md
└── app/
    ├── login.html          # Inicio de sesión
    ├── registro.html       # Registro de participante
    ├── recuperar.html      # Recuperación de contraseña
    ├── admin.html          # Dashboard Administrativo
    └── cliente.html        # Dashboard de Jugador/Cliente

Páginas desarrolladas

Parte A – Landing Page (index.html)


Navbar fija con colapso hamburguesa
Carrusel con 3 slides, texto superpuesto y botones primarios
Sección de estadísticas
6 tarjetas de información con Bootstrap Cards
Sección de categorías del torneo
Cronograma
Footer en 4 columnas


Parte B – Módulo de Autenticación


login.html: Etiquetas flotantes, checkbox Recordarme, botón w-100
registro.html: Cuadrícula row col-md-6 con múltiples campos agrupados
recuperar.html: Validación visual estática con is-invalid e is-valid


Parte C – Dashboards


admin.html: Sidebar + tarjetas de métricas + tabla table-striped table-hover con badges de estado + Modal de edición
cliente.html: Panel de perfil con rounded-circle + pestañas nav-tabs (Activas / Historial) + alerta alert-warning alert-dismissible
