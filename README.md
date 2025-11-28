# odoo_dev_dam – Gestión de Gimnasio con Odoo

Este proyecto corresponde al desarrollo de un sistema de gestión para un **gimnasio**, utilizando Odoo como base.  
El objetivo es centralizar la administración de clases, eventos, monitores, usuarios y reservas, y publicar esta información en el sitio web del gimnasio.


---

## 🏋️‍♂️ Funcionalidad del proyecto

El sistema permite:

### 📅 Gestión de clases y eventos
- Creación de clases como **Yoga**, **CrossFit**, **Spinning**, etc.
- Gestión de eventos especiales del gimnasio.
- Configuración de horarios, duración y monitores asignados.
- Estado de eventos (Nuevo, Anunciado, Reservado, Finalizado).

### 🌐 Publicación en la web
- Inserción de bloques dinámicos de eventos en el sitio web.
- Selección del evento desde el **Website Builder**.
- Visualización pública de:
  - Imagen del evento
  - Fecha y hora
  - Localización
  - Botón de registro
- Página de detalle del evento totalmente integrada con Odoo.

### 🧑‍🤝‍🧑 Gestión de asistentes
- Control de registros a clases o eventos.
- Opcional: venta de entradas, inscripción online.

## 🛒 Venta de productos:
- Tienda de productos
- Reserva de pistas

---

## 🧩 Módulos utilizados

- `event` – Gestión de eventos
- `website` – Constructor de páginas web
- `website_event` – Publicación de eventos en la web
- `calendar` – Horarios

