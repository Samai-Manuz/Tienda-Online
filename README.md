# 🛒 Tienda Online - Sistema de Gestión de Inventario y Ventas (Python - POO)

¡Bienvenido al repositorio de **Tienda Online**! Este proyecto contiene la implementación de un **Sistema de Gestión de Inventario y Ventas para E-commerce**, desarrollado en Python usando **Programación Orientada a Objetos (POO)**.

---

## 📂 Contenido del repositorio
- `Tienda Online.ipynb`: Notebook principal con la implementación básica del sistema.
- `Tienda Online (Bonus).ipynb`: Extensión del sistema con funcionalidades avanzadas para gestión de clientes y compras.
- `Feedback`: Evaluación, comentarios y sugerencias sobre el ejercicio.
- `README.md`: Este archivo descriptivo del proyecto.

---

## 🧩 Descripción del ejercicio principal

El objetivo es crear una clase `TiendaOnline` que gestione el inventario y las ventas, con los siguientes aspectos clave:

### 📦 Inventario
- Representado como una **lista de diccionarios** con productos.
- Cada producto tiene:
  - `nombre` (string)
  - `precio` (float)
  - `cantidad` (int)
- Permite:
  - **Agregar productos** o actualizar cantidades si ya existen.
  - **Ver el inventario** completo mostrando nombre, precio y cantidad.
  - **Buscar productos** por nombre.
  - **Actualizar stock** sumando o restando unidades.
  - **Eliminar productos** por nombre.
  - **Calcular el valor total** del inventario (precio × cantidad).

### 💰 Ventas
- Lleva un registro de las **ventas totales** acumuladas.

### 📊 Métodos clave
- `agregar_producto()`
- `ver_inventario()`
- `buscar_producto()`
- `actualizar_stock()`
- `eliminar_producto()`
- `calcular_valor_inventario()`

Además, el sistema se prueba mediante instancias y llamadas a estos métodos para verificar su correcto funcionamiento.

---

## 🎁 Bonus: Gestión avanzada de clientes y compras

Como extensión del sistema, se añade la gestión de clientes y su historial de compras:

### 👥 Clientes
- Representados en un **diccionario** donde cada clave es el nombre del cliente y su valor es otro diccionario con:
  - `email` (string)
  - `compras` (lista de compras realizadas)

### 🛍 Funcionalidades añadidas
- **Agregar clientes** con nombre y correo electrónico.
- **Ver la lista de clientes** registrados.
- **Realizar compras** permitiendo seleccionar productos del inventario y actualizar cantidades.
- **Procesar pagos** con manejo de excepciones y cálculo de cambio.
- **Registrar compras** en el historial del cliente y actualizar las ventas totales.
- **Ver historial de compras** por cliente.
- **Calcular y mostrar ventas totales** de la tienda.

---

## 🚀 Tecnologías y conceptos usados

- **Python 3**
- **Programación Orientada a Objetos (POO)**
- Manejo de listas y diccionarios
- Uso de bucles y condicionales
- Gestión básica de errores con `try...except`
- Interacción mediante inputs (en el bonus)

---

## 📌 Cómo usarlo

1. Abre los notebooks en tu entorno Jupyter.
2. Ejecuta las celdas para crear instancias de la clase y probar cada método.
3. Experimenta agregando productos, clientes y realizando compras.
4. Revisa el feedback para entender detalles y posibles mejoras.

---

## 🙌 Agradecimientos

Este ejercicio ayuda a consolidar conocimientos fundamentales de POO aplicados a un sistema realista de e-commerce, ideal para entrevistas técnicas y práctica en Python.

---

¡Disfruta explorando y mejorando tu Tienda Online! 💻🛒✨

