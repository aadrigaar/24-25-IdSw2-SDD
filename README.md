# 🍽️ pyRestaurante - Grupo 7

<p align="center">
  <img src="/imagenRestaurante/restaurante.png" alt="Imagen Restaurante" width="300"/>
</p>

Sistema de gestión para un restaurante de alta cocina que administra reservas, mesas, pedidos y personal. 
Optimiza la asignación de mesas, gestiona tiempos de preparación y coordina la interacción entre cocina y sala.

## 📌 Características Principales

### 🏷️ Gestión de Mesas
- Registro de mesas con número, capacidad y ubicación.
- Control del estado de cada mesa: **libre, reservada, ocupada, en preparación**.
- Administración del tiempo promedio de ocupación según el tamaño de la mesa:
  - 🪑 **2 personas:** 60-90 min
  - 🪑 **4 personas:** 90-120 min
  - 🪑 **6+ personas:** 120-150 min

### 📆 Sistema de Reservas
- Registro de reservas con datos del cliente, fecha, hora, número de comensales y preferencias.
- Verificación automática de disponibilidad.
- Lista de espera para momentos de alta demanda.
- Envío de recordatorios automáticos **24 horas antes** de la reserva.

### 🍽️ Gestión de Pedidos
- Cada pedido está asociado a una mesa específica.
- Registro de platos solicitados por comensal.
- Control de tiempos: **pedido, preparación y servicio**.
- Cálculo del importe total y desglose por comensal si se solicita.

### 👨‍🍳 Gestión de Personal
- Administración de roles: **Camareros, Ayudantes, Sumiller, Chef, Ayudantes de cocina**.
- Asignación de responsabilidades por mesas o zonas.
- Registro de horarios de trabajo y descansos.
- Cálculo de carga de trabajo por empleado.

## 📊 Diagramas del Sistema

- 🔄 **Diagrama de Estados**: [Diagrama de Estados](/ModeloDeDominio/imagenes/DiagramaDeEstados.svg)
- 🖼️ **Diagrama de Clases**: [Diagrama de Clases](/ModeloDeDominio/imagenes/DiagramaDeClases.svg)
- 🖼️ **Diagrama de Clases V002**: [Diagrama de Clases V002](/ModeloDeDominio/imagenes/DiagramaDeClasesV002.svg)
- 🧩 **Diagrama de Objetos**: [Diagrama de Objetos](/ModeloDeDominio/imagenes/DiagramaDeObjetos.svg)

---

## 📄 Enlaces Relevantes

- **Código Fuente Versión 1 D**: [Ver código de la versión 1 D](/src-v001/src/)
- **Código Fuente Versión 2 DM**: [Ver código de la versión 2 DM](/src-v002/)
- **Código Fuente Versión 3 DOO**: [Ver código de la versión 3 DOO](/src-v003/)
- **README del Proyecto Diseño Modular (Versión 2)**: [Ver README de la versión 2 Diseño Modular](/src-v002/README.md) y [Ver diseño modular](/documentos/diseñoModular.md)
- **README del Proyecto Diseño Orientado a Objetos (Versión 3)**: [Ver README de la versión 3 Diseño Orientado a Objetos](/src-v003/readme.md)

---

## 👥 **Miembros del Proyecto**

- **Adrián García Arranz**
- **Sergio Moreno Vega**
- **Iker Celaya Buezo**
