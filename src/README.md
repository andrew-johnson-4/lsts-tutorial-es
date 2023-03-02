## Introducción

**LSTS** es un asistente para demostraciones matemáticas y a veces un lenguaje de programación.
LSTS está diseñado para asistir el razonamiento en pruebas matemáticas.
Podría incluso ser un lenguaje de programación para aquellos valientes que se lo propongan. LSTS es:

* Ligero. [LSTS] consta de tan sólo 3K líneas de código Rust sin dependencias.
* Rápido. Los [benchmarks] de LSTS se asemejan a los de Rust mismo en tiempo de compilación y eficiencia.
* Familiar. La [sintaxis] le resultará parecida a la Coq, ML, o Haskell.

[LSTS]: https://github.com/andrew-johnson-4/LSTS
[Benchmarks]: perf/statistics.md
[sintaxis]: guide/syntax.md

### Audiencia objetivo

Este tutorial y manual de referencia ha sido compilado para personas con amplia experiencia en matemáticas o programación que están en busca de nuevos retos.
LSTS es todo menos promedio.
Aún faltan numerosas funcionalidades por desarrollar, presentes en productos comparables con rendimiento superior.
Con suerte esta guía te ayudará a encontrar algo inspirador, y próximamente te ayudará a encontrar algo útil.
Puedes ayudarnos a mejorar más rápidamente [sugiriendo mejoras o realizando preguntas](https://github.com/andrew-johnson-4/LSTS/issues).

### Contribuyendo

LSTS es libre y de código abierto. Puedes encontrar el código fuente en
[GitHub](https://github.com/andrew-johnson-4/LSTS), y puedes enviar problemas o sugerencias en el
[seguidor de incidencias de GitHub](https://github.com/andrew-johnson-4/LSTS/issues). LSTS se apoya en su comunidad para la corrección de bugs y agregar nuevas 
características: si te gustaría contribuir, por favor lee el
[Código de Conducta](https://github.com/andrew-johnson-4/LSTS/blob/main/CODE_OF_CONDUCT.md) y considera abrir un nuevo
[pull request](https://github.com/andrew-johnson-4/LSTS/pulls).

### Licencia

El código de LSTS y su documentación se liberan bajo la
[licencia MIT](https://github.com/andrew-johnson-4/LSTS/blob/main/LICENSE).
