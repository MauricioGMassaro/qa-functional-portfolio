# Plan de Pruebas

## 1. Introducción

El presente documento describe la estrategia de pruebas funcionales para la plataforma PHPTravels, orientada a la gestión de reservas y servicios turísticos.

El objetivo principal es validar el correcto funcionamiento de los módulos críticos del sistema y asegurar la estabilidad de los procesos principales relacionados con reservas y navegación del usuario.

---

## 2. Objetivo de las pruebas

El objetivo de las pruebas es validar el correcto funcionamiento de los módulos principales de la plataforma PHPTravels, asegurando que los usuarios puedan realizar búsquedas, consultas y reservas de servicios turísticos de manera satisfactoria.

Las pruebas se enfocarán en los procesos críticos del negocio, incluyendo autenticación, búsqueda de hoteles, vuelos, coches, tours, paquetes y consultas de visa.

Durante la ejecución inicial del Smoke Testing se identificó una incidencia relacionada con el proceso de registro de usuarios, específicamente en el envío del correo de validación.

Debido a esta limitación, parte de las pruebas funcionales serán ejecutadas utilizando la modalidad de reserva como invitado (Guest Checkout), con el objetivo de continuar la validación de los flujos principales del sistema.

---

## 3. Alcance

### 3.1 Funcionalidades incluidas

- Registro de usuarios
- Inicio de sesión
- Recuperación de contraseña
- Búsqueda de hoteles
- Búsqueda de vuelos
- Búsqueda de coches
- Búsqueda de tours
- Búsqueda de paquetes
- Consulta de visa
- Reservas como invitado
- Navegación general
- Validaciones de formularios

### 3.2 Funcionalidades limitadas

Durante la ejecución del Smoke Testing se detectó una incidencia en el proceso de registro y activación de usuarios relacionada con el envío del código/correo de validación.

Debido a esta limitación no fue posible completar la validación funcional de los módulos de Registro e Inicio de Sesión mediante cuentas nuevas.

Las pruebas continuarán utilizando la modalidad de reserva como invitado para garantizar la cobertura de los flujos principales del negocio.

---

## 4. Ambiente de pruebas

### Ambiente

| Elemento | Valor |
|-----------|---------|
| Aplicación | PHPTravels |
| Tipo | Web |
| Navegador principal | Google Chrome |
| Sistema Operativo | Windows 10 |
| Conectividad | Internet |

---

## 5. Tipos de pruebas

### Functional Testing

Validación de las funcionalidades principales del sistema.

### Smoke Testing

Verificación inicial de estabilidad de los módulos principales.

### End-to-End Testing

Validación completa de los flujos críticos de negocio.

### Regression Testing

Revalidación de funcionalidades previamente verificadas.

### UI Validation

Validación visual y de comportamiento de la interfaz de usuario.

---

## 6. Riesgos identificados

### Riesgos funcionales

- El sistema no envía correos de validación durante el registro.
- Posibles fallos en procesos dependientes de autenticación.
- Validaciones incorrectas de formularios.
- Errores en filtros de búsqueda.
- Inconsistencias en disponibilidad de servicios.

### Riesgos de negocio

- Imposibilidad de activar nuevas cuentas.
- Abandono del proceso de registro por parte del usuario.
- Impacto en la experiencia de onboarding.
- Dependencia de servicios externos para validación de cuentas mediante correo electrónico.

---

## 7. Criterios de entrada y salida

### Criterios de entrada

- Plataforma PHPTravels accesible desde navegador web.
- Disponibilidad de conexión a Internet.
- Datos de prueba definidos para la ejecución.
- Módulos principales accesibles para navegación.
- Ejecución previa de Smoke Testing.

### Criterios de salida

- Escenarios críticos ejecutados.
- Casos de prueba documentados.
- Defectos identificados y registrados.
- Evidencias almacenadas en el repositorio.
- Resultados de ejecución consolidados.

---

## 8. Herramientas utilizadas

| Herramienta | Propósito |
|-------------|------------|
| GitHub | Gestión del portafolio y versionado |
| Google Sheets / Excel | Documentación de escenarios y casos de prueba |
| Google Chrome | Ejecución de pruebas |
| Chrome DevTools | Inspección y análisis |
| Lightshot | Captura de evidencias |
| Jira | Gestión de defectos |

