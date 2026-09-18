# Plan de Pruebas

Esta carpeta contiene el Plan de Pruebas elaborado para la validación funcional de la plataforma PHPTravels.

El documento establece la estrategia, el alcance y los criterios utilizados para planificar y ejecutar las pruebas sobre los principales flujos funcionales de la aplicación.

## Documento

### Test_Plan_PHPTravels.md

Documento principal que define el enfoque de pruebas utilizado para el proyecto.

El Plan de Pruebas incluye:

- Introducción y contexto del proyecto.
- Objetivos de las pruebas.
- Alcance funcional.
- Funcionalidades incluidas y limitadas.
- Ambiente de pruebas.
- Tipos de pruebas a ejecutar.
- Riesgos identificados.
- Criterios de entrada y salida.
- Herramientas utilizadas.

## Alcance de las pruebas

El plan contempla la validación de los principales procesos de PHPTravels, incluyendo:

- Registro de usuarios.
- Inicio de sesión.
- Recuperación de contraseña.
- Búsqueda de hoteles.
- Búsqueda de vuelos.
- Búsqueda de coches.
- Búsqueda de paquetes.
- Reservas como invitado.
- Navegación general.

Durante la ejecución inicial del Smoke Testing se identificó una incidencia relacionada con el proceso de registro y activación de usuarios, específicamente con el envío del correo de validación.

Esta condición fue considerada dentro de la planificación y se estableció el uso de Guest Checkout para continuar con la validación de los principales flujos de negocio.

## Estrategia de pruebas

El proyecto contempla diferentes niveles y tipos de validación:

- **Pruebas funcionales:** validación del comportamiento esperado de las funcionalidades.
- **Smoke Testing:** verificación inicial de estabilidad de los módulos principales.
- **Pruebas End-to-End:** validación de los flujos críticos de negocio.
- **Pruebas de regresión:** revalidación de funcionalidades previamente verificadas.
- **Validación de UI:** comprobación visual y funcional de la interfaz.

## Criterios de ejecución

La ejecución de las pruebas se realizará considerando los criterios de entrada y salida definidos en el Plan de Pruebas.

Los resultados obtenidos, las evidencias y los defectos identificados durante la ejecución se documentan en las carpetas correspondientes del portafolio.

## Herramientas

Las principales herramientas utilizadas durante el proyecto incluyen:

- **GitHub:** gestión y versionado del portafolio.
- **Excel / Google Sheets:** documentación de escenarios, casos de prueba y seguimiento.
- **Google Chrome:** ejecución de las pruebas.
- **Lightshot:** captura de evidencias.
- **Jira:** gestión y seguimiento de defectos.

## Trazabilidad

El Plan de Pruebas constituye el punto de partida del proceso de testing y se relaciona con el resto de la documentación del proyecto:

**Plan de Pruebas → Escenarios → Casos de Prueba → Ejecución → Evidencias → Informes de Errores**
