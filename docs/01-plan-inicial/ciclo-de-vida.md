# 🔄 Ciclo de Vida del Proyecto en la etapa 1:

## Enfoque seleccionado 

> **ITERATIVO**

## Justificación de la elección

>En la etapa de producción se adopta un enfoque iterativo debido a que el proyecto presenta un nivel alto de incertidumbre y complejidad, lo que dificulta definir completamente los requisitos desde el inicio. En este contexto, los objetivos y características del producto se van definiendo progresivamente a medida que se obtiene nueva información a lo largo del desarrollo.
>
> Además, el proyecto requiere la construcción de prototipos o versiones parciales que permitan validar ideas, funcionalidades y decisiones de diseño. Esto implica que el desarrollo no sigue una secuencia rígida, sino que se organiza en ciclos sucesivos donde cada iteración aporta aprendizaje y permite realizar ajustes, reduciendo así el riesgo de errores en etapas avanzadas.
>
> Por otro lado, la retroalimentación de los interesados cumple un rol fundamental, ya que cada versión del producto es evaluada y utilizada para mejorar la siguiente. Esto resulta especialmente importante cuando existen múltiples perspectivas o cuando las necesidades pueden evolucionar con el tiempo, haciendo necesario un enfoque flexible y adaptable.
>
> Finalmente, aunque este enfoque puede implicar mayores tiempos y costos, permite obtener un producto final más alineado con las expectativas y necesidades reales, siendo especialmente adecuado en contextos donde el aprendizaje continuo y la adaptación son clave para el éxito del proyecto.


## Árbol de decisión

```mermaid
flowchart TD
    A{{"¿Los requisitos\nson estables?"}}
    B{{"¿El equipo tiene\nexperiencia en ágil?"}}
    C{{"¿El entorno admite\nentregas incrementales?"}}

    A -- Sí --> P["✅ Predictivo\n(Cascada)"]
    A -- No --> B
    B -- Sí --> D["✅ Adaptativo\n(Scrum / Kanban)"]
    B -- No --> C
    C -- Sí --> H["✅ Híbrido"]
    C -- No --> P

    style P fill:#1E3A5F,stroke:#64B5F6
    style D fill:#1B5E20,stroke:#81C784
    style H fill:#5D4037,stroke:#FFB74D
```

> **Decisión del grupo:** La rama del arbol que aplica a la primer etapa es la PREDICTIVA, ya que los requisitos para construir el programa en realidad virtual son estables, ya que sería mostrar un modelo del cuerpo humano manipulable a traves de los hápticos.

## Fases del proyecto

```mermaid
flowchart LR
    F1["📌 Fase 1\n[Análisis de requisitos]"]
    F2["📌 Fase 2\n[Diseño del sistema]"]
    F3["📌 Fase 3\n[Desarrollo / Construcción]"]
    F4["📌 Fase 4\n[Validación técnica]"]

    F1 --> F2 --> F3 --> F4 
```
| Fase | Nombre | Objetivo | Criterio de salida |
|------|--------|----------|-------------------|
| 1 | Análisis de requisitos | Definir las necesidades del sistema junto con el asesor médico | Requisitos documentados y validados |
| 2 | Diseño del sistema | Establecer la arquitectura, componentes y funcionamiento del equipo| Diseño aprobado |
| 3 | Desarrollo / Construcción | Implementar y ensamblar el sistema según el diseño | Prototipo funcional construido |
| 4 | Validación técnica | Verificar que el sistema cumpla con los requisitos definidos | Sistema validado por el asesor médico |

---



# 🔄 Ciclo de Vida del Proyecto en la etapa 2:

## Enfoque seleccionado

> **Adaptativo**

## Justificación de la elección

> En la etapa de mantenimiento se opta por un enfoque adaptativo debido al alto nivel de incertidumbre asociado a los cambios que pueden surgir durante el uso del sistema. A diferencia de la etapa de producción, aquí el producto ya está en funcionamiento y es utilizado por usuarios reales, lo que genera nuevas necesidades y ajustes continuos.
> 
> El nivel de riesgo es bajo, lo que permite implementar cambios de manera más flexible sin comprometer significativamente la estabilidad del sistema. Esto favorece un enfoque iterativo e incremental, donde se realizan múltiples entregas basadas en mejoras y actualizaciones.
> 
> La retroalimentación en esta etapa proviene directamente de los usuarios, lo cual es clave para adaptar el sistema a sus necesidades reales. Este tipo de feedback es dinámico y muchas veces impredecible, lo que refuerza la necesidad de un enfoque adaptable.
> 
> En consecuencia, el desarrollo se orienta a responder rápidamente a los cambios, priorizando la mejora continua y la capacidad de adaptación por sobre la planificación rígida, características centrales del enfoque adaptativo.


## Árbol de decisión

```mermaid
flowchart TD
    A{{"¿Los requisitos\nson estables?"}}
    B{{"¿El equipo tiene\nexperiencia en ágil?"}}
    C{{"¿El entorno admite\nentregas incrementales?"}}

    A -- Sí --> P["✅ Predictivo\n(Cascada)"]
    A -- No --> B
    B -- Sí --> D["✅ Adaptativo\n(Scrum / Kanban)"]
    B -- No --> C
    C -- Sí --> H["✅ Híbrido"]
    C -- No --> P

    style P fill:#1E3A5F,stroke:#64B5F6
    style D fill:#1B5E20,stroke:#81C784
    style H fill:#5D4037,stroke:#FFB74D
```

> **Decisión del grupo:**  La rama del arbol que aplica a la segunda etapa es la ADAPTATIVA, ya que los requisitos no son estables porque los usuarios que entrenarán con el simulador podrán proponer mejoras durante su uso. Además, el equipo sí tendrá experiencia en ágil ya que la adaptación al cambio es rápida y la colaboración se mantiene constante. 



## Fases del proyecto

```mermaid
flowchart LR
    F1["📌 Fase 1\n[Monitoreo del sistema]"]
    F2["📌 Fase 2\n[Recolección de feedback]"]
    F3["📌 Fase 3\n[Actualización / Mejora]"]
    F4["📌 Fase 4\n[Validación con usuarios]"]

    F1 --> F2 --> F3 --> F4
```

| Fase | Nombre | Objetivo | Criterio de salida |
|------|--------|----------|-------------------|
| 1 | Monitoreo del sistema | Evaluar el desempeño del sistema en uso real | Datos de uso y problemas identificados |
| 2 | Recolección de feedback | Obtener sugerencias y necesidades de los usuarios | Feedback documentado |
| 3 | Actualización / Mejora | Implementar cambios y mejoras en el sistema | Versión actualizada del sistema |
| 4 | Validación con usuarios | Verificar que las mejoras resuelvan los problemas detectados | Aprobación de los usuarios y correcto funcionamiento |

---

*Cátedra Gestión de Proyectos · FIUNER · 2026*
