# Validación interna del Tutor de lengua española en NotebookLM

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21071263.svg)](https://doi.org/10.5281/zenodo.21071263)

Este repositorio documenta la validación interna experta del cuaderno de NotebookLM «Tutor de lengua española». El objetivo es comprobar el comportamiento del prototipo ante un banco de preguntas piloto antes de su posible uso con alumnado.

La validación no es un estudio de impacto ni mide aprendizaje real. La unidad de análisis es cada pregunta-respuesta generada por el cuaderno.

## Estructura

- `01_diseno_cuaderno/`: documentación de diseño y despliegue.
- `02_fuentes_y_registros/`: fuentes, registros e informes de ejecución.
- `03_banco_preguntas/`: banco de preguntas piloto.
- `04_respuestas_notebooklm/`: respuestas originales generadas por el cuaderno.
- `05_rubricas/`: rúbrica homogénea, equivalencias y evaluaciones por subbloque.
- `06_matrices_codificacion/`: matriz caso x dimensión e incidencias codificadas.
- `07_resultados_agregados/`: resultados calculados e informe actualizado.
- `08_guia_empleo/`: guía de empleo del prototipo.
- `09_revision_y_control/`: controles de entrada, coherencia, auditoría D6 y pendientes de publicación.

## Metodología

La evaluación aplica una rúbrica homogénea de siete dimensiones: D1 corrección lingüística, D2 diagnóstico, D3 socratismo o adaptación, D4 claridad, D5 matices, D6 fidelidad documental y D7 transferencia, aplicación o seguridad.

Los resultados proceden de la matriz homogénea corregida `06_matrices_codificacion/matriz_codificacion_caso_dimension.csv`. La auditoría D6 revisó los casos en los que el tutor declaraba falta o insuficiencia de fuente y aun así ofrecía una regla, explicación o recomendación sustantiva.

Para revisar o reproducir la evaluación, lea primero `05_rubricas/plantilla_evaluacion_homogenea_tutor_lengua.md`, después las evaluaciones homogéneas, la auditoría `09_revision_y_control/auditoria_D6_fidelidad_documental.md` y finalmente la matriz corregida.

## Ficheros principales

- `03_banco_preguntas/Banco preguntas piloto.md`
- `04_respuestas_notebooklm/`
- `05_rubricas/plantilla_evaluacion_homogenea_tutor_lengua.md`
- `06_matrices_codificacion/matriz_codificacion_caso_dimension.csv`
- `06_matrices_codificacion/incidencias_codificadas.csv`
- `07_resultados_agregados/resultados_agregados.csv`
- `07_resultados_agregados/informe_validacion_interna_resultados_homogeneo.md`
- `09_revision_y_control/auditoria_D6_fidelidad_documental.md`
- `09_revision_y_control/pendientes_publicacion.md`

## Advertencia metodológica

Los resultados describen el rendimiento del prototipo en una evaluación experta interna. No deben interpretarse como evidencia de mejora en la escritura del alumnado.

## Licencia

Este repositorio se publica bajo licencia **Creative Commons Attribution 4.0 International (CC BY 4.0)**, salvo indicación contraria.

Esto permite copiar, distribuir, adaptar y reutilizar los materiales, incluso con fines comerciales, siempre que se cite adecuadamente la autoría.

Cita recomendada:

> Hernández Pardo, B. (2026). *Validación interna del Tutor de lengua española en NotebookLM* [Repositorio de datos, rúbricas, matrices e informes de validación interna]. Zenodo. https://doi.org/10.5281/zenodo.21071263

Los materiales de terceros mencionados en registros de fuentes, referencias bibliográficas o documentación auxiliar conservan sus propias condiciones de uso.
