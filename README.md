# Préstamo Claro

Aplicación móvil para registrar préstamos personales entre dos personas de forma simple, transparente y sin ambigüedades.

---

## Descripción

Préstamo Claro es una aplicación móvil desarrollada con React Native que permite registrar préstamos de dinero entre personas, establecer fechas límite y mantener un estado claro del acuerdo.

El objetivo es eliminar discusiones, olvidos y confusiones cuando se presta dinero entre amigos, familiares o compañeros de trabajo.

La aplicación funciona bajo un modelo de confirmación bilateral: un préstamo solo es válido cuando ambas partes lo aceptan.

---

## Problema que resuelve

En contextos cotidianos es común que:

* No quede registro formal del monto prestado.
* Se olviden fechas acordadas.
* Se generen conflictos por falta de claridad.
* No exista seguimiento del estado del pago.

Préstamo Claro elimina la ambigüedad mediante registro digital compartido.

---

## Flujo principal

1. Usuario crea un préstamo:

   * Monto
   * Fecha límite
   * Nota opcional

2. La otra persona recibe notificación.

3. Puede aceptar o rechazar.

4. El préstamo queda con estado:

   * Pending
   * Paid
   * Overdue

5. Ambas partes pueden consultar historial.

---

## Características técnicas

* React Native (Mobile)
* Backend REST (Node/NestJS o Express)
* Base de datos relacional (PostgreSQL)
* Autenticación JWT
* Relaciones entre usuarios
* Manejo de estados de negocio
* Notificaciones push
* Persistencia
* Arquitectura limpia

---

## Objetivo del proyecto

Este proyecto fue desarrollado como demostración de capacidades Full Stack Mobile:

* Diseño de flujo completo end-to-end
* Modelado de dominio simple pero real
* Manejo de autenticación y autorización
* Gestión de estados de negocio
* UX enfocada en dispositivos de gama baja
* Arquitectura mantenible
