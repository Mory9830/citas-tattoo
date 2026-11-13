# Plan de ejecución

| ID | Tarea | Descripción | Resultado esperado |
|---|---|---|---|
| T01 | Crear el repositorio y el tablero en GitHub | Crear el repositorio citas-tattoo con README.md y docs/, y un tablero de GitHub Projects con una issue por tarea. | Repositorio con README y docs/, y tablero con todas las tareas. |
| T02 | Preparar el entorno y Supabase | Instalar VS Code, Live Server y ESLint, y crear el proyecto de desarrollo en Supabase con las claves en .env. | Proyecto que arranca en local y conectado a Supabase. |
| T03 | Cerrar requisitos con el estudio | Confirmar con Tuétano las duraciones de los servicios, horarios, señal y cancelación. | docs/requisitos-cerrados.md con los valores acordados. |
| T04 | Diseñar el modelo de datos y las reglas | Definir tablas, relaciones, la restricción anti-solapamiento y las políticas de permisos por rol. | Diagrama entidad-relación y documento de reglas en docs/. |
| T05 | Wireframes y prototipo en Figma | Dibujar y enlazar las pantallas de los tres roles, con colores y tipografías. | Prototipo navegable con enlace público. |
| T06 | Estructurar el frontend | Crear los módulos JS, el CSS responsive base y la navegación con datos simulados. | Navegación entre pantallas con datos de prueba. |
| T07 | Crear tablas, autenticación y roles | Migración SQL con las tablas y configuración de Supabase Auth con tres roles. | Registro e inicio de sesión funcionando con los tres roles. |
| T08 | Implementar anti-solapamiento y reglas en SQL | Restricción de exclusión de citas, cancelación con 72 horas y validación de horario. | Una cita cruzada o fuera de plazo se rechaza. |
| T09 | Implementar las políticas de permisos (RLS) | Activar RLS en todas las tablas y escribir las políticas por rol. | Cada rol solo accede a sus datos. |
| T10 | Crear la función de huecos libres | Función SQL que calcula los huecos según horario, ausencias, citas y duración. | Devuelve los huecos esperados en 5 casos de prueba. |
| T11 | Pantallas de acceso | Registro, inicio de sesión y control de sesión. | Un usuario se registra, entra y sale. |
| T12 | Reserva y citas del cliente | Consulta de huecos, formulario de reserva y listado con modificar y cancelar. | El cliente reserva, modifica y cancela una cita. |
| T13 | Agenda del tatuador | Vista de su agenda con confirmar, reprogramar, rechazar y completar. | El tatuador gestiona solo sus citas. |
| T14 | Panel de administración | Gestión de tatuadores, servicios, horarios, cierres y de todas las citas, con la señal. | El administrador gestiona recursos y citas. |
| T15 | Validaciones e integración | Validar formularios, mostrar errores claros y revisar los tres recorridos completos. | Los tres recorridos funcionan y los errores salen en español. |
| T16 | Pruebas | Un caso por requisito, permisos por rol, solapamiento y concurrencia, y responsive y accesibilidad. | docs/pruebas.md con resultados y Lighthouse de 90 o más. |
| T17 | Corregir errores y desplegar | Resolver los bugs y publicar en Netlify y en Supabase de producción con HTTPS y subdominio. | Aplicación accesible por HTTPS. |
| T18 | Documentación final | README completo, manual breve para el estudio y memoria. | README, manual y memoria terminados. |
| T19 | Vídeo y entrega final | Grabar el vídeo, probar el enlace en incógnito y entregar en Aules. | Entrega con repositorio y vídeo. |
