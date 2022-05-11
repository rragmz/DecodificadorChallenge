# Encriptador de texto
Este es el primer desafío propuesto por Alura Latam en el marco del Programa ONE. Las tecnologías que se utilizan son: HTML, CSS y JavaScript. #challengeonecodificador2

Veamos al programa en acción:
https://user-images.githubusercontent.com/78104919/167878559-0225ba32-87bd-43aa-963a-92c1687fc47c.mp4

## Descripción
Realizar una aplicación que encripta textos para intercambiar mensajes secretos con otras personas que sepan el secreto de la encriptación utilizada.

Las "llaves" de encriptación que utilizaremos son las siguientes:

- La letra "e" es convertida para "enter"
- La letra "i" es convertida para "imes"
- La letra "a" es convertida para "ai"
- La letra "o" es convertida para "ober"
- La letra "u" es convertida para "ufat"

## Requisitos
- Debe funcionar solo con letras minúsculas
- No deben ser utilizados letras con acentos ni caracteres especiales
- Debe ser posible convertir una palabra para la versión encriptada también devolver una palabra encriptada para su versión original.

Por ejemplo:
gato  => g**ai**t**ober**
g**ai**t**ober** => gato

La página debe tener campos para:
- inserción del texto que será encriptado o desencriptado, y el usuario debe poder escoger entre las dos opciones.
- El resultado debe ser mostrado en la pantalla.

## Extras
- Un botón que copie el texto encriptado/desencriptado para la sección de transferencia, o sea que tenga la misma funcionalidad del ctrl+C o de la opción "copiar" del menú de las aplicaciones.
- Personal: Permitir el ingreso de acentos y mayúsculas utilizando funciones que modifiquen texto, convirtiéndolo en minúsculas y vocales sin tildes.
