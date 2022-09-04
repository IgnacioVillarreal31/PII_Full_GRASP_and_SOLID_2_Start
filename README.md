# PII Full GRASP and SOLID
## FIT
### Universidad Católica del Uruguay

En este programa trabajaremos con recetas de cocina que involucran ingredientes y equipamiento.

## Desafío(s)

Para imprimir una receta se necesita información de la receta pero también se necesita saber cómo y dónde imprimir.

➡️ **Crear una clase ConsolePrinter para imprimir las recetas en la consola en lugar que las recetas se impriman a sí mismas.**

➡️ **¿Qué patrones o principios usan para determinar cómo implementar este cambio? Escriban la respuesta en comentarios en el código.**
Usando principio srp determinamos que ConsolePrinter no debia de estar junto a la clase Recipe debido a que hacia que la clase tuviera mas de una responsabilidad.