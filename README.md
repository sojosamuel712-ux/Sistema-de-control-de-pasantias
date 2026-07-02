# 📊 Sistema de Control de Pasantías (Caso de Estudio)

**Nota sobre el repositorio:** Este proyecto es una recreación funcional y visual (Caso de Estudio) orientada al diseño de interfaz (UI/UX) y la arquitectura de software del sistema original implementado en entorno empresarial.

Solución web integral diseñada para automatizar, organizar y supervisar el registro de asistencias y actividades diarias realizadas por los pasantes dentro de una organización. El sistema transforma un flujo de trabajo tradicionalmente manual y propenso a errores en un proceso digital rápido, limpio y centralizado.

🚀 Arquitectura y Flujo del Sistema

 1. Control de Acceso y Seguridad (Autenticación)
El sistema maneja un flujo de seguridad donde los datos de los pasantes son precargados en la base de datos relacional por la administración. 
Al ingresar por primera vez, el usuario valida su identidad y registra manualmente su contraseña personal para activar su cuenta de forma segura.

<img width="1366" height="768" alt="registro de usuario" src="https://github.com/user-attachments/assets/74f8eca1-6c87-4b99-be3d-cdac03d3c5ef" />


<img width="1366" height="768" alt="inicio de sesion" src="https://github.com/user-attachments/assets/8f1b22e4-b7c5-49ac-bc23-1d612c8d477a" />

2. Panel Principal Dinámico (Dashboard del Pasante)
Una vez autenticado, el pasante es recibido en un Home personalizado.
Inyección Automática de Datos: La barra superior muestra dinámicamente el nombre del usuario activo.
Control de Tiempo: Incorpora un módulo de reloj en tiempo real que marca la fecha y la hora exacta del sistema para garantizar la precisión en los registros.

<img width="1366" height="768" alt="panel del pasante" src="https://github.com/user-attachments/assets/55428e3f-ad1e-4cb4-9916-49b966f33f82" />


3. Módulo "Hoja de Trabajo" (Registro y Visualización)
Este núcleo operativo está dividido estratégicamente en dos subapartados para optimizar la experiencia de usuario:

Registro de Actividades: El pasante selecciona la actividad asignada por su supervisor. Para estandarizar los procesos, estas actividades se cargan dinámicamente desde una tabla relacional en la base de datos, permitiendo reutilizar criterios por grupos de pasantes. El sistema precarga de forma automatizada los campos de usuario y fecha actual, evitando la duplicidad o alteración de datos.

Visualización y Exportación Dinámica: La información guardada se estructura en una hoja de pasantías adaptativa. El sistema permite filtrar los registros (semanales o mensuales) según los requerimientos del ente educativo correspondiente y exportar los datos directamente a formatos **Excel o PDF**.

<img width="1366" height="768" alt="apartado de hoja_ usuario" src="https://github.com/user-attachments/assets/153fbd87-47e3-4440-b0d2-0f16430da76d" />

<img width="1366" height="768" alt="apartado de hoja_ usuario_ visualización" src="https://github.com/user-attachments/assets/d0e5b593-2156-4f00-95f5-d853555d6f28" />

4. Panel de Administración y Auditoría (Rol Supervisor)
El sistema cuenta con un módulo exclusivo para el personal administrativo y tutores empresariales encargado del monitoreo diario.

A través del apartado **Pasantes**, el supervisor accede a un panel donde se listan los nombres, apellidos y credenciales del personal en entrenamiento.

Incluye herramientas de consulta rápida para previsualizar los registros de actividades y asistencias de cualquier pasante con un solo clic, facilitando el seguimiento del rendimiento real.

<img width="1366" height="768" alt="panel de administrador" src="https://github.com/user-attachments/assets/4c2a79ae-b0b6-44d2-8e6f-335a8a17d6ea" />

<img width="1366" height="768" alt="apartado de administración _ pasantes" src="https://github.com/user-attachments/assets/979a8673-9a99-4f94-9bfc-3af38109f890" />
