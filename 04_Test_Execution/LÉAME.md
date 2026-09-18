# Ejecución de Casos de Prueba

Esta carpeta contiene la documentación y las evidencias generadas durante la ejecución de los casos de prueba definidos en el proyecto.

Las evidencias permiten demostrar la ejecución de las pruebas y documentar los resultados obtenidos durante el proceso de validación funcional.

## Organización

La carpeta se encuentra organizada según el estado de ejecución de los casos:

### Exitosos

Contiene las evidencias de los casos de prueba que fueron ejecutados correctamente y cuyo resultado obtenido coincide con el resultado esperado.

### Fallidos_Bloqueados

Contiene las evidencias de los casos que:

- **Fallidos:** presentaron una desviación entre el resultado esperado y el resultado obtenido.
- **Bloqueados:** no pudieron completarse debido a una dependencia, restricción o condición que impidió continuar con la ejecución.

En ambos casos se documentan las condiciones observadas y las evidencias correspondientes.

### En_Curso

Contiene los casos de prueba cuya ejecución se encuentra en proceso o que permanecen pendientes de una validación, información o condición necesaria para completar la prueba.

Una vez finalizada la ejecución, el caso será trasladado a la carpeta correspondiente según su resultado.

## Evidencias

Las evidencias pueden incluir capturas de pantalla, documentos y demás información necesaria para respaldar el resultado de cada caso de prueba.

Cada evidencia se encuentra asociada al identificador del caso de prueba correspondiente.

## Criterios de clasificación

La clasificación de los casos se realiza de acuerdo con el resultado de la ejecución:

| Estado | Descripción |
|---|---|

| **Exitoso** | El resultado obtenido coincide con el resultado esperado. |
| **Fallido** | Se identifica una desviación respecto del resultado esperado. |
| **Bloqueado** | La ejecución no puede completarse debido a una condición que impide continuar. |
| **En curso** | La ejecución aún no ha finalizado o se encuentra pendiente de una validación. |
