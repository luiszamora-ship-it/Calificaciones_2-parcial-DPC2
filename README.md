# Consulta de calificación parcial

Sitio sencillo para que las y los estudiantes consulten su calificación parcial ingresando su matrícula.

## Cómo actualizar calificaciones

1. Abrir el archivo `index.html`.
2. Localizar la sección de JavaScript donde se define `const CALIFICACIONES = [...]`.
3. Sustituir o agregar registros con el formato:

```js
{
  matricula: "2023XXXX",
  nombre: "Nombre Apellido Apellido",
  grupo: "7° A",
  parcial: 9.5
}
