# Desafío - Veterinaria JS

Este proyecto es una pequeña aplicación backend desarrollada en Node.js que permite registrar y leer citas de atención en una veterinaria. La aplicación utiliza el sistema de archivos para almacenar y recuperar las citas en un archivo JSON.

## Requisitos

- Node.js instalado en tu máquina.

## Instalación

1. Clona este repositorio en tu máquina local:

   - en tu consola escribe:
   git clone https://github.com/tu-usuario/veterinaria-js.git

2. Navega al directorio del proyecto:
  - en tu consola escribe:
   cd veterinaria-js

3. Instala las dependencias necesarias:
  - npm install

Uso
La aplicación se ejecuta desde la línea de comandos y permite dos operaciones principales: registrar y leer.

Registrar una nueva cita
Para registrar una nueva cita, utiliza el siguiente comando:

en tu consola (en este caso de Visual studio code ) :

node index.js registrar <nombre> <edad> <tipo> <color> <enfermedad>

<nombre>: Nombre del animal.
<edad>: Edad del animal.
<tipo>: Tipo de animal.
<color>: Color del animal.
<enfermedad>: Enfermedad o síntoma del animal.

Ejemplo:

en tu consola (en este caso de Visual studio code ):
node index.js registrar Benito "2 años" perro blanco vómitos

Para leer todas las citas registradas, utiliza el siguiente comando:

Escribe en la consola:
node index.js leer

Esto mostrará en la consola todas las citas que se han registrado hasta el momento.
