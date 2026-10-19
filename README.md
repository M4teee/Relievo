# Relievo

**Del contenido visual a la exploración táctil.**

Relievo es una aplicación orientada a la creación de marcos táctiles mediante fabricación digital. Su objetivo es facilitar la generación de piezas imprimibles en 3D que combinen una abertura para incorporar modelos físicos con descripciones en texto convencional y Braille en español.

El proyecto busca explorar cómo las tecnologías de modelado 3D, la impresión 3D y la traducción Braille pueden utilizarse para crear recursos accesibles, educativos y explorables mediante el tacto.

> **Estado del proyecto:** en etapa inicial de planificación y desarrollo.

## Objetivos

- Generar geometrías preparadas para la impresión 3D.
- Incorporar descripciones en español y su correspondiente representación en Braille.
- Crear marcos con una abertura central para alojar modelos tridimensionales independientes.
- Simplificar el proceso de preparación y exportación de piezas.
- Construir una base extensible para incorporar nuevas formas de generar contenido táctil.

## Alcance previsto

### Versión 1 — Generación de marcos táctiles

La primera versión estará enfocada en generar marcos de dimensiones predefinidas, con una abertura central pasante y un sector inferior destinado a una descripción en texto convencional y Braille en relieve.

Las piezas podrán exportarse en formato STL para su preparación e impresión mediante herramientas de fabricación digital.

Los modelos 3D que acompañen a cada marco se crearán o conseguirán por separado: esta versión no incluirá conversión de imágenes a modelos tridimensionales.

### Evolución futura

La arquitectura se diseñará teniendo en cuenta posibles ampliaciones, entre ellas:

- Conversión de imágenes en relieves o geometrías tridimensionales.
- Personalización de dimensiones y proporciones.
- Adaptación del marco al formato del contenido.
- Vista previa de las piezas generadas.
- Nuevas opciones de personalización y exportación.

Estas funcionalidades forman parte de la visión futura del proyecto y no se consideran implementadas en la versión inicial.

## Enfoque técnico

Relievo se desarrollará de manera incremental, priorizando la corrección geométrica, la generación de archivos imprimibles y la validación de las piezas físicas.

Las decisiones sobre tecnologías, bibliotecas y arquitectura se documentarán a medida que se definan y validen durante el desarrollo.

## Principios de desarrollo

- **Accesibilidad:** el contenido táctil debe ser útil y legible para las personas destinatarias.
- **Precisión geométrica:** las piezas deben respetar sus dimensiones y contar con una malla adecuada para la impresión.
- **Validación física:** los resultados digitales deben contrastarse con impresiones reales.
- **Modularidad:** las funcionalidades deben poder evolucionar sin reescribir innecesariamente el sistema.
- **Simplicidad:** priorizar soluciones comprensibles y mantenibles antes que complejidad innecesaria.
- **Documentación:** registrar las decisiones técnicas, los criterios de diseño y las limitaciones conocidas.

## Estado y limitaciones

Relievo es un proyecto en desarrollo. Las dimensiones, la geometría, el tamaño de los puntos Braille y los criterios de distribución del texto deberán validarse mediante pruebas técnicas y físicas.

La generación de Braille no implica, por sí sola, que una pieza cumpla con todos los estándares de accesibilidad. Se deberán verificar la tabla de traducción utilizada, las dimensiones físicas y la legibilidad táctil antes de considerar validado el resultado.


---

*Relievo — Diseñando para ver con las manos.*
