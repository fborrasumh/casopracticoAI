# CasoPrácticoAI

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21423193.svg)](https://doi.org/10.5281/zenodo.21423193)

**Aplicación:** https://fborrasumh.github.io/casopracticoAI/

Genera un **caso práctico completo y listo para clase**: objetivos, el caso con sus datos, preguntas por niveles de Bloom, solución modelo, rúbrica y tres variantes. Ocho tipos de actividad: caso narrativo, problema cuantitativo, supuesto práctico, caso Harvard, role-play, proyecto corto, análisis crítico y debate o seminario. Aplicación de un solo fichero (`index.html`), sin servidor.

## Novedades de la versión 2.0

- Recorrido guiado con el estilo de Forja, con los tipos de actividad en tarjetas y seis ejemplos para empezar.
- Contexto completo: los agentes de preguntas y de solución reciben el caso entero con sus datos. La v1 les pasaba solo los primeros 500 o 600 caracteres.
- Verificación independiente: en los resultados numéricos, otro agente resuelve el problema sin ver la solución y la app compara con un margen del 1 %. Las discrepancias se marcan.
- Pesos comprobados con código: los de las preguntas y la rúbrica se ajustan a 100 % con aviso.
- Versión estudiante (caso y preguntas) y versión docente (además, objetivos, solución, verificación, rúbrica, variantes y notas), en pantalla, en Word y en PDF.
- Cada sección se puede editar o rehacer con una indicación, y cualquier variante propuesta se convierte en un caso nuevo.
- Caso de ejemplo completo que se ve sin clave.
- Texto generado escapado, contexto geográfico conservado y clave compartida del catálogo (`ia_openai_key`).
- Se mantienen la importación de SyllabusAI, el editor de prompts y el historial, compatible con la v1.

## Los agentes

| Agente | Qué hace |
|---|---|
| Diseño pedagógico | Objetivos, competencias y notas para el docente |
| Caso y datos | El caso o enunciado con sus datos clave y el reto central |
| Preguntas | Preguntas de nivel progresivo según Bloom, con pesos |
| Solución | Respuesta modelo pregunta por pregunta, con resultado final |
| Verificación | Resuelve por su cuenta lo cuantitativo; la app compara |
| Rúbrica | Criterios con cuatro niveles y pesos |
| Variantes | Versión más sencilla, avanzada e interdisciplinar |

## Privacidad

Los casos se guardan en el navegador (IndexedDB). El texto viaja a OpenAI con la clave del profesor.

## Cómo citar

Borrás Rocher, F. (2026). *CasoPrácticoAI* (versión 2.0.0) [Software]. Universidad Miguel Hernández de Elche. https://doi.org/10.5281/zenodo.21423193

El DOI es el de concepto: apunta siempre a la última versión. GitHub ofrece la cita en APA y BibTeX con el botón *Cite this repository*, a partir de `CITATION.cff`.

Forma parte del catálogo [Herramientas IA para la academia](https://fborrasumh.github.io/ia/).

## Licencia

MIT © 2026 Fernando Borrás Rocher · Universidad Miguel Hernández de Elche.
