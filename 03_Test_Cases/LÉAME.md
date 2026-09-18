# Casos de Prueba

Esta carpeta contiene los casos de prueba definidos para la validación funcional de la plataforma PHPTravels.

Los casos de prueba representan la descomposición detallada de los escenarios definidos en la etapa de planificación y establecen las condiciones necesarias para verificar el comportamiento esperado de cada funcionalidad.

## Objetivo

Los casos de prueba permiten documentar de forma estructurada cómo se realizará la validación de cada funcionalidad, definiendo los datos, pasos de ejecución y resultados esperados.

Cada caso de prueba cuenta con un identificador único que permite mantener la trazabilidad durante todo el proceso de testing.

## Estructura de los casos

Los casos de prueba contemplan la información necesaria para realizar y documentar una ejecución reproducible, incluyendo:

- Identificador del caso de prueba.
- Escenario asociado.
- Título o descripción.
- Precondiciones.
- Datos de prueba.
- Pasos de ejecución.
- Resultado esperado.
- Resultado obtenido.
- Estado de ejecución.
- Evidencias.
- Observaciones, cuando corresponda.

## Relación con los escenarios

Los casos de prueba se encuentran relacionados con los escenarios definidos en la carpeta `02_Escenarios_de_prueba`.

Un escenario puede estar compuesto por uno o más casos de prueba, permitiendo cubrir diferentes condiciones y caminos de ejecución dentro de un mismo flujo funcional.

La trazabilidad se mantiene mediante la relación:

**Escenario → Caso de Prueba → Ejecución → Resultado → Evidencia**

## Cobertura funcional

Los casos de prueba permiten validar las funcionalidades contempladas en los escenarios definidos para PHPTravels, incluyendo:

- Authentication.
- Hotels.
- Vuelos.
- Coches.
- Paquetes de Viajes.
- ESIM.

La cobertura incluye pruebas funcionales, Smoke Testing y pruebas End-to-End, de acuerdo con lo establecido en el Plan de Pruebas.

## Gestión de resultados

Durante la ejecución, los casos de prueba pueden presentar diferentes resultados según el comportamiento observado:

- **Exitoso:** el resultado obtenido coincide con el resultado esperado.
- **Fallido:** se identifica una desviación respecto del resultado esperado.
- **Bloqueado:** la ejecución no puede completarse debido a una condición o dependencia que impide continuar.
- **En curso:** la ejecución aún no ha finalizado o permanece pendiente de una validación.

Los resultados y las evidencias correspondientes se encuentran documentados en la carpeta `04_Ejecución_de_Prueba`.

Cuando durante la ejecución se identifica una desviación que requiere seguimiento, esta puede ser registrada como defecto en Jira y documentada en la carpeta `05_Informes_de_errores`.

## Trazabilidad general

Los casos de prueba forman parte de un proceso de testing estructurado:

**Plan de Pruebas → Escenarios → Casos de Prueba → Ejecución → Evidencias → Informes de Errores**

Esta estructura permite mantener la trazabilidad entre la planificación, la definición de las pruebas, su ejecución y la gestión de los defectos identificados.
