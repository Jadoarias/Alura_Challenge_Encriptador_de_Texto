# Encriptador de Texto - Challenge Alura Latam

Este proyecto es una aplicación web que permite encriptar y desencriptar texto, desarrollada como parte del primer desafío propuesto por Alura Latam en colaboración con Oracle Next Education (ONE).

## Descripción del Proyecto

El objetivo de este encriptador es convertir texto ingresado por el usuario en una versión cifrada y luego poder revertir el proceso para obtener el texto original. Este reto pone a prueba los conocimientos adquiridos en los cursos de JavaScript, HTML5 y CSS3.

## Reglas de Encriptación

Las llaves de encriptación utilizadas son las siguientes:
- La letra "a" se convierte en "ai".
- La letra "e" se convierte en "enter".
- La letra "i" se convierte en "imes".
- La letra "o" se convierte en "ober".
- La letra "u" se convierte en "ufat".

## Requisitos

- Solo debe funcionar con letras minúsculas.
- No deben utilizarse letras con acentos ni caracteres especiales.
- Debe ser posible convertir una palabra a su versión encriptada y viceversa.

### Ejemplos

- `gato` => `gaitober`
- `gaitober` => `gato`

## Características Adicionales

- Un botón para copiar el texto encriptado/desencriptado, emulando la funcionalidad de `Ctrl+C` o la opción "copiar" del menú del navegador.

## Tecnologías Utilizadas

- HTML5
- CSS3
- JavaScript

## Desarrollo del Proyecto

### 1. Estructura HTML
Se comenzó con la creación de la estructura básica de la página web utilizando HTML5. Esta etapa incluyó la configuración de campos de entrada para el texto, botones para encriptar y desencriptar, y un área para mostrar los resultados.

### 2. Estilos CSS
Para la apariencia de la página, se utilizó CSS3. Se diseñó una interfaz limpia y simple, asegurando que fuera responsiva y fácil de usar en diferentes dispositivos.

### 3. Lógica de JavaScript
La funcionalidad principal de encriptar y desencriptar se implementó en JavaScript. Se definieron las reglas de encriptación y se crearon funciones para procesar el texto según estas reglas, garantizando que el texto se pueda convertir correctamente de y hacia su versión encriptada.
