# Evaluación Módulo 1: Sistema de Gestión de Tienda Online

Este repositorio contiene la solución a la evaluación del Módulo 1 del programa de Data Analytics Part Time de Adalab. 
El proyecto es una aplicación simulada en Python que gestiona las operaciones básicas de una tienda online, incluyendo inventario, registro de clientes y procesamiento de compras.

La implementación utiliza funciones, bucles (`for`, `while`) y estructuras de datos fundamentales como listas de diccionarios (para el inventario) y diccionarios anidados (para los clientes).

---

## 🛠️ Requisitos del Sistema

Para ejecutar este código, necesitas tener instalado:

* **Python 3.x**
* **Jupyter Notebook** (recomendado usar la extensión en Visual Studio Code, aunque puede ejecutarse en cualquier entorno Jupyter).

---

## 🚀 Cómo Arrancar el Proyecto

Sigue estos pasos para poner en marcha el sistema y probar las funcionalidades:

### 1. Clonación del Repositorio

Clona este repositorio en tu máquina local usando Git:

```bash
git clone https://github.com/Adalab/bda-modulo-1-evaluacion-final-leiremarinas-sys.git
cd nombre-del-repositorio
2. Ejecución del Código
Abre el fichero de la evaluación ([Tu_fichero_de_evaluacion].ipynb) en Visual Studio Code o en tu entorno Jupyter preferido.

El código está estructurado en celdas separadas por secciones:

a. Inicialización de Datos
Ejecuta la primera celda para inicializar las variables globales: INVENTARIO, CLIENTES y VENTAS_TOTALES.

b. Definición de Funciones
Ejecuta la celda donde se definen todas las funciones (agregar_producto, ver_inventario, realizar_compra, etc.).

c. Interacción (Prueba)
Una vez que todas las funciones están definidas, puedes probar el sistema llamando a la función principal de compra.

Para iniciar el proceso interactivo de compra

realizar_compra()


Funcionalidades Clave

ver_inventario()	Muestra el stock y precios actuales.
agregar_producto()	Añade stock o un nuevo producto al INVENTARIO.
realizar_compra()	Permite la interacción con el cliente, actualiza el inventario y calcula el coste total.
calcular_valor_inventario()	Calcula el valor monetario total del stock.


