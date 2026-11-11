# Investigación de Ciberseguridad: técnicas ofensivas contra LLMs

Proyecto de la asignatura **Técnicas de investigación de la ciberseguridad** (U-TAD, Ingeniería del Software, curso 2026-2027).

**Autor:** Antonio De Mateo Bodegas

## Tema

Análisis de técnicas ofensivas contra modelos de lenguaje (LLM):

- **Jailbreaking** (eje principal)
- **Envenenamiento de datos** (*data poisoning*) y puertas traseras
- **Ataques adversariales** sobre texto

## Estructura del repositorio

| Carpeta | Contenido | Fecha |
|---|---|---|
| [`01_Trabajo_previo_charlas`](01_Trabajo_previo_charlas) | Análisis de seis charlas de seguridad (2024-2025) sobre jailbreaks y data poisoning. Base del proyecto. | Sep-oct 2026 |
| [`02_Entrega1_Memoria_diseno`](02_Entrega1_Memoria_diseno) | Primera entrega: memoria de diseño (pregunta, objetivos, hipótesis, alcance, metodología y cronograma). | 13-oct-2026 |
| [`03_Entrega2_Memoria_seguimiento`](03_Entrega2_Memoria_seguimiento) | Segunda entrega: memoria de seguimiento con los experimentos de jailbreaking, resultados y planificación actualizada (Word y PDF). | 10-nov-2026 |

## Resumen de resultados (2ª entrega)

| Sistema | Pruebas | Resultado |
|---|---|---|
| Lakera Agent Breaker, nivel 1 | 1 | Superado (100/100) |
| Lakera Agent Breaker, nivel 2 | ~13 | No superado (máximo 5/100, fuga parcial) |
| ChatGPT, Gemini y Claude (escenario con clave inventada) | 18 | 0 revelaciones |

Todas las pruebas se hicieron con cuentas propias, sobre una plataforma diseñada para ser atacada o con datos inventados, sin contenido dañino.

## Próximos pasos (3ª entrega, enero 2027)

- Jailbreaking: ataques en varios turnos, contexto largo e inyección indirecta.
- Experimentos controlados en local de data poisoning y ataques adversariales.
