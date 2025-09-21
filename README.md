## WEB APPLICATION FOR HOLIDAY MANAGEMENT

Aplicación web desarrollada para gestionar solicitudes de vacaciones y ausencias de empleados dentro de una organización.
Su objetivo principal es automatizar y simplificar el proceso de gestión de permisos laborales, sustituyendo procesos manuales basados en hojas de cálculo o correos electrónicos por una plataforma centralizada, accesible y eficiente.

**Funcionalidades principales**
- Gestión de usuarios: Registro e inicio de sesión de empleados. Diferentes roles: empleado, responsable/manager y administrador.
- Gestión de vacaciones: Solicitud de días de vacaciones y permisos. Visualización del calendario personal y global de la empresa. Aprobación o rechazo de solicitudes por parte de los responsables.
- Panel administrativo: Resumen de todas las solicitudes pendientes y procesadas. Estadísticas de uso (días solicitados, aprobados, rechazados).
- Notificaciones: Confirmación automática al realizar solicitudes. Comunicación del estado de aprobación/rechazo.
- Control de acceso: Autenticación segura. Permisos según rol de usuario.

**Tecnologías utilizadas**

- Backend:Lenguaje: PHP (posiblemente con framework como Laravel o PHP puro, según el código detectado).Servidor: Apache. Base de datos: MySQL (gestión de usuarios y solicitudes).
- Frontend: HTML5, CSS3, JavaScript. Bootstrap para diseño responsivo y componentes de interfaz.
- Otros: Arquitectura cliente-servidor con sesiones. Scripts SQL para inicialización de la base de datos.

**Flujo de uso**
- Registro / Login → El empleado accede con sus credenciales.
- Solicitud de vacaciones → Indica las fechas deseadas y envía la petición.
- Revisión del manager → El responsable aprueba o rechaza la solicitud.
- Notificación → El empleado recibe el resultado.
- Registro → Todo queda almacenado en la base de datos para consulta y estadísticas.

(Para conocer mas acerca de este proyecto revisar la [memoria]([Web-application-for-holiday-management/CGIS (1).pdf])



