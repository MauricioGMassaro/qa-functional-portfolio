# Escenarios de Prueba

Esta carpeta contiene los escenarios de prueba definidos para la validación funcional de la plataforma PHPTravels.

Los escenarios fueron elaborados a partir del alcance establecido en el Plan de Pruebas y representan los principales flujos funcionales que serán posteriormente desglosados en casos de prueba.

## Objetivo

Los escenarios permiten organizar la cobertura funcional del sistema, identificando los procesos principales a validar y estableciendo su prioridad, módulo, tipo de prueba y estado.

Cada escenario representa un flujo funcional que puede ser validado mediante uno o más casos de prueba.

## Cobertura

La matriz contempla un total de **13 escenarios de prueba**, identificados desde **ESC-001 hasta ESC-013**.

Los escenarios abarcan los siguientes módulos:

- **Authentication:** registro, inicio de sesión y recuperación de contraseña.
- **Hotels:** búsqueda y reserva de hoteles como invitado.
- **Vuelos:** búsqueda y reserva de vuelos como invitado.
- **Coches:** búsqueda y alquiler de coches.
- **Paquetes de Viajes:** búsqueda y reserva de paquetes de viajes religiosos (Umra).
- **ESIM:** búsqueda y reserva de servicios ESIM.

## Tipos de prueba

Los escenarios contemplan diferentes tipos de pruebas según el objetivo de cada flujo:

- **Smoke:** validación inicial de funcionalidades críticas.
- **Funcional:** verificación del comportamiento esperado de una funcionalidad.
- **E2E:** validación completa de un flujo de negocio de extremo a extremo.

## Priorización

Cada escenario cuenta con un nivel de prioridad que permite organizar la ejecución de acuerdo con su importancia funcional:

- **Crítica**
- **Alta**
- **Media**

La prioridad se encuentra definida en la matriz de escenarios y permite establecer el orden de atención de los diferentes flujos.

## Estado de los escenarios

Los escenarios se encuentran clasificados según su situación al momento de la ejecución.

### Bloqueado

Corresponde a escenarios cuya ejecución no puede realizarse debido a una condición o dependencia que impide continuar con la validación.

Actualmente, los escenarios **ESC-001, ESC-002 y ESC-003** se encuentran bloqueados debido a las limitaciones identificadas en el proceso de registro y activación de usuarios.

### Finalizado

Corresponde a escenarios cuya validación ya fue realizada o cuyo proceso de ejecución se encuentra concluido.

Un escenario finalizado puede haber obtenido un resultado exitoso o haber presentado una desviación que fue documentada y gestionada mediante el correspondiente reporte de bug.

Los escenarios **ESC-004 a ESC-013** se encuentran actualmente en estado finalizado.

## Consideraciones

Durante la ejecución inicial del Smoke Testing se identificó una incidencia relacionada con el proceso de registro de usuarios, específicamente con la recepción del código o correo de validación.

Esta condición afecta directamente a los escenarios relacionados con autenticación y genera dependencias para las funcionalidades que requieren una cuenta activa.

Los escenarios no afectados por esta dependencia pueden continuar siendo validados mediante los flujos disponibles, incluyendo las reservas como invitado cuando corresponda.

## Trazabilidad

La identificación única de cada escenario permite mantener la trazabilidad a lo largo del proceso de testing:

**Plan de Pruebas → Escenario → Caso de Prueba → Ejecución → Resultado → Evidencia → Bug**

Esta estructura permite relacionar los objetivos definidos durante la planificación con las pruebas ejecutadas y los resultados obtenidos.
