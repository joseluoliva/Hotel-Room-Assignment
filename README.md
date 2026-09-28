# Hotel Room Assignment

<p align="center"><b>A TesselAI project</b><br>
<a href="https://github.com/joseluoliva">@joseluoliva</a> · <a href="https://github.com/migsaebae1">@migsaebae1</a></p>

---

**A decision-support tool for hotel front desk teams.** Reception imports the day's
arrivals and the system proposes how to distribute them across rooms — explaining every
choice and leaving the final decision to the receptionist.

> **This repository is documentation only.** The source code, the data and the operational
> detail are private. What follows is a high-level description of the problem and the
> approach.

---

## The problem

Assigning rooms looks trivial until you watch it being done. Every morning someone has to
place the day's arrivals across a finite set of rooms while juggling constraints that pull
in different directions:

- guests who asked for something specific when they booked;
- groups who want to be near each other;
- returning guests who liked a particular room;
- long stays, which are better off in the larger rooms;
- rooms out of service;
- and the hard one: **never two bookings in the same room on the same night.**

It is done by hand, it takes time, and the knowledge lives in the head of whoever is on
shift that day.

## What the tool does

1. **Imports** the day's arrivals from the property management system's own export.
2. **Proposes** a distribution with no clashes.
3. **Explains** why each guest ended up where they did.
4. **Lets reception change anything**, showing the consequences of a change before it is
   applied.

The receptionist always decides. The tool suggests — it does not act on its own.

## Status

In active development under **TesselAI**, being prepared for a pilot in a real hotel.

## What is *not* in this repository

No source code · no guest data · no configuration · no implementation detail.

Everything here is a description of the product. The working system lives in a private
repository.

---

## Credits

Built under **TesselAI**, the name [@joseluoliva](https://github.com/joseluoliva) and
[@migsaebae1](https://github.com/migsaebae1) work under.

---

<details>
<summary><b>🇪🇸 Versión en español</b></summary>

<br>

**Una herramienta de apoyo a la decisión para recepción de hotel.** Recepción importa las
llegadas del día y el sistema propone cómo repartirlas entre las habitaciones, explicando
cada decisión y dejando la última palabra al recepcionista.

Un proyecto de **TesselAI**.

> **Este repositorio es solo documentación.** El código, los datos y el detalle operativo
> son privados. Lo que sigue es una descripción general del problema y del enfoque.

### El problema

Asignar habitaciones parece trivial hasta que lo ves hacer. Cada mañana alguien tiene que
repartir las llegadas del día entre un número limitado de habitaciones, con criterios que
tiran en direcciones distintas:

- huéspedes que pidieron algo concreto al reservar;
- grupos que quieren estar cerca;
- repetidores a los que les gustó una habitación;
- estancias largas, que encajan mejor en las habitaciones grandes;
- habitaciones fuera de servicio;
- y el criterio que no admite excepciones: **nunca dos reservas en la misma habitación la
  misma noche.**

Se hace a mano, lleva tiempo, y el conocimiento vive en la cabeza de quien esté de turno.

### Qué hace la herramienta

1. **Importa** las llegadas del día desde el export del propio PMS.
2. **Propone** un reparto sin choques.
3. **Explica** por qué cada huésped está donde está.
4. **Deja cambiar cualquier cosa**, enseñando las consecuencias antes de aplicar el cambio.

El recepcionista siempre decide. La herramienta sugiere, no actúa por su cuenta.

### Estado

En desarrollo bajo **TesselAI**, preparándose para un piloto en un hotel real.

### Qué *no* hay en este repositorio

Nada de código · nada de datos de huéspedes · nada de configuración · nada de detalle de
implementación.

Todo lo que hay aquí es una descripción del producto. El sistema vive en un repositorio
privado.

### Créditos

Desarrollado bajo **TesselAI**, el nombre con el que trabajamos
[@joseluoliva](https://github.com/joseluoliva) y
[@migsaebae1](https://github.com/migsaebae1).

</details>
