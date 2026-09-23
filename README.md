[README.md](https://github.com/user-attachments/files/32546997/README.md)
# Proyecto-Programacion-Estructurada-
Repositorio para el proyecto


# DiscVault – Sistema de Control de Inventario y Ventas para Tienda de Discos

## Descripción
DiscVault es un proyecto académico de una aplicación de escritorio desarrollada en Python con interfaz gráfica en Qt. El sistema está pensado para ayudar a pequeñas tiendas de discos independientes a llevar su control de catálogo, registrar sus ventas de forma sencilla y consultar reportes básicos de cuántos discos han vendido.

## Problemática
En muchas tiendas pequeñas de discos todavía se anota todo a mano en libretas o notas de papel. Esto provoca desorden: no se sabe cuántos álbumes quedan realmente en inventario, se cometen errores al cobrar y es muy difícil saber cuánto dinero se vendió al mes. Buscar una venta vieja para aclarar algo con un cliente también quita mucho tiempo.

## Objetivo
Desarrollar un programa sencillo en Python con interfaz gráfica que permita guardar el catálogo de álbumes, registrar ventas descontando automáticamente el inventario (stock) y consultar reportes mensuales de dinero y discos vendidos.

## Integrantes y Roles
* **Alejandro Medina** – Diseñador y Tester
* **Karina Ochoa** – Desarrolladora
* **Nicole Cárdenas** – Tester
* **Ángel Hernández** – Desarrollador

## Funcionalidades previstas
* **Registrar álbumes:** Guardar discos nuevos con su código, título, artista, precio y cuántas unidades hay en inventario.
* **Ver catálogo:** Mostrar la lista de todos los discos disponibles con sus datos.
* **Registrar una venta:** Procesar una venta con un código único y restar en automático las unidades vendidas del inventario.
* **Buscar venta:** Buscar una transacción anterior usando su código.
* **Reporte del mes:** Ver el total de dinero juntado y cuántos discos se vendieron en el mes.

## Tecnologías
* **Python:** Lenguaje que estamos aprendiendo en la materia para escribir la lógica y las funciones del programa.
* **Qt (PySide / PyQt):** Herramienta para diseñar las pantallas e interfaz visual.
* **Git y GitHub:** Para guardar nuestro proyecto, llevar el control de cambios y trabajar en equipo sin encimar nuestro código.

## Estructura del proyecto
```text
disc-vault-system/
│
├── main.py                 # Archivo principal para ejecutar el programa
├── README.md               # Explicación general del proyecto
│
├── ui/                     # Carpeta para las pantallas e interfaz visual
├── logica/                 # Carpeta para las funciones y validaciones
└── datos/                  # Carpeta donde guardaremos la información (JSON / CSV)
