# Tienda en Línea Smart-X

## Descripción general
Este proyecto consiste en una aplicación de consola desarrollada en Java que simula el funcionamiento básico de una tienda en línea. El sistema permite a un usuario iniciar sesión, administrar un monedero virtual, visualizar productos disponibles, gestionar un carrito de compras y realizar compras con validación de saldo y control de stock.

El proyecto fue diseñado priorizando la claridad del flujo lógico y la separación de responsabilidades entre clases, dejando abiertas posibles mejoras futuras como el manejo de cantidades por producto, entre otros.

## Funcionalidades
- Inicio de sesión de usuario
- Monedero virtual con control de saldo
- Visualización de productos disponibles
- Agregar, ver y retirar productos del carrito
- Cálculo automático del total de la compra
- Validación de stock y saldo
- Finalización de compra

## Reglas de funcionamiento
- Un producto sólo puede ser agregado al carrito si su stock es mayor a cero
- El stock de los productos se reduce únicamente al confirmar la compra
- Si el saldo del monedero es insuficiente, la compra no se realiza
- El carrito se vacía automáticamente después de completar una compra
- Todas las interacciones con el sistema se realizan a través de un menú en consola

## Estructura del proyecto
- `Usuario`: Manejo de datos del usuario
- `Monedero`: Administración del saldo
- `Producto`: Información y control de stock
- `Carrito`: Gestión de productos y compras
- `Main`: Menú principal e interacción con el usuario

## Tecnologías utilizadas
- Java
- Programación Orientada a Objetos
- Scanner
- Consola (CLI)

## Ejecución del proyecto
1. Abrir el proyecto en un entorno de desarrollo compatible con Java
2. Ejecutar la clase `Main`
3. Seguir las instrucciones del menú en consola

## Capturas 

1. ![Captura_1](https://github.com/MontesX/Tienda_en_linea_Smart-X/blob/main/captura_1.png)
2. ![Captura_2](https://github.com/MontesX/Tienda_en_linea_Smart-X/blob/main/captura_2.png)
3. ![Captura_3](https://github.com/MontesX/Tienda_en_linea_Smart-X/blob/main/captura_3.png)
4. ![Captura_4](https://github.com/MontesX/Tienda_en_linea_Smart-X/blob/main/captura_4.png)
5. ![Captura_5](https://github.com/MontesX/Tienda_en_linea_Smart-X/blob/main/captura_5.png)
6. ![Captura_6](https://github.com/MontesX/Tienda_en_linea_Smart-X/blob/main/captura_6.png)

## Autor 
Desarrollado por **Paúl Montes** (MontesX)
- Ejercicio académico - Java 

Contacto: 
- [LinkedIn](https://www.linkedin.com/in/montessx/)
