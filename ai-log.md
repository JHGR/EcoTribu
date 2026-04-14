# Declaratoria de Uso de Inteligencia Artificial - Eco Tribu Digital

**Proyecto:** Eco Tribu Digital  
**Hackathon:** HackODS UNAM 2026  
**Equipo:** Jhoana Rojas, Jhonatan Grajales, Julio Treviño  
**Fecha:** 13 de abril de 2026

---

## 1. Filosofía de uso

En Eco Tribu Digital adoptamos la IA como un **acelerador de trabajo**, no como un sustituto del criterio del equipo. Nuestra postura parte de tres principios:

1. **Supervisión activa:** toda salida generada por IA fue revisada, cuestionada y ajustada por al menos un integrante del equipo antes de integrarse al proyecto.
2. **Decisiones propias:** la selección de fuentes de datos, la hipótesis central, la narrativa del storytelling y las conclusiones del análisis son decisiones humanas documentadas en este archivo.
3. **Reproducibilidad:** los prompts usados se registran de forma que cualquier persona pueda replicar o auditar el proceso.

---

## 2. Herramientas utilizadas

| Herramienta | Versión / Plataforma | Tareas asignadas |
|---|---|---|
| GitHub Copilot (Claude Sonnet 4.6) | VS Code - Chat | Redacción de documentación, estructuración del README, revisión de código |
| ChatGPT | GPT-4o (web) | Exploración inicial de fuentes de datos, validación de conceptos ecológicos |

---

## 3. Registro de uso por tarea

### 3.1 Estructuración del README y documentación

**Tarea delegada a IA:** Mejorar redacción de secciones, eliminar emojis, redactar perfiles de equipo con base en los datos biográficos reales proporcionados por el equipo.

**Decisión propia:** El equipo definió los roles, la narrativa del proyecto y la pregunta central. La IA solo pulió la redacción.

**Prompt reproducible:**
```
Ayúdame a redactar las descripciones del equipo para el README de un hackathon. 
Los perfiles son:
- Jhoana Rojas: Licenciada en Ciencias de la Comunicación, estudiante de Pedagogía.
- Julio Treviño: Licenciado en Comercio Internacional, estudiante de Sistemas Computacionales.
- Jhonatan Grajales: Ingeniero en Sistemas Computacionales con experiencia en proyectos 
  desde levantamiento de requerimientos hasta salida a producción.
El proyecto trata sobre el impacto del cambio climático en la biodiversidad de México.
Asigna roles coherentes con cada perfil sin inventar información.
```

**Ajuste realizado por el equipo:** Se verificó que los roles asignados por la IA correspondieran con las responsabilidades reales que cada integrante acordó asumir durante el hackathon.

---

### 3.2 Exploración de fuentes de datos

**Tarea delegada a IA:** Identificar conjuntos de datos abiertos disponibles en CONABIO, INEGI y Portal UNAM relacionados con especies en riesgo y variables climáticas en México.

**Decisión propia:** El equipo evaluó cada fuente sugerida, verificó su vigencia, accesibilidad y licencia, y seleccionó las que efectivamente se descargaron y utilizan en el análisis.

**Prompt reproducible:**
```
¿Qué datasets de datos abiertos existen en México que permitan cruzar 
registros de especies animales con variables climáticas (temperatura, precipitación)?
Enfócate en fuentes oficiales: CONABIO, INEGI, Portal de Datos Abiertos UNAM.
Proporciona nombre del dataset, URL de descarga y formato de archivo si lo conoces.
```

**Ajuste realizado por el equipo:** Varias fuentes sugeridas estaban desactualizadas o no disponibles públicamente. El equipo validó cada URL de manera directa antes de incluirla en el diccionario de metadatos.

---

### 3.3 Limpieza y procesamiento de datos

**Tarea delegada a IA:** Sugerencia de pasos de limpieza (manejo de valores nulos, normalización de nombres de especies, joins entre datasets) y generación de código base en Python/R.

**Decisión propia:** El equipo revisó y adaptó cada fragmento de código. Se definieron los criterios de limpieza (qué registros eliminar, qué imputar) a partir del contexto del análisis, no de la sugerencia automática.

**Prompt reproducible:**
```
Tengo un dataframe en Python con columnas: [nombre_especie, estado, año, temperatura_max, 
precipitacion_anual, estatus_conservacion]. Hay valores nulos en temperatura_max (~15%) 
y nombres de especies con variaciones ortográficas. 
Sugiere un pipeline de limpieza apropiado para análisis exploratorio de biodiversidad.
```

---

## 4. Decisiones que la IA no tomó

Las siguientes decisiones fueron tomadas exclusiva y explícitamente por el equipo:

- **Pregunta central del proyecto:** definida en sesión de equipo antes de consultar cualquier herramienta de IA.
- **Selección de los ODS 13 y 15:** decisión previa al hackathon, basada en el interés y conocimiento del equipo.
- **Narrativa del storytelling:** la estructura de inicio (panorama general) → desarrollo (patrones de riesgo) → conclusión (especies más vulnerables) fue diseñada por Jhoana desde su formación en comunicación.
- **Interpretación de los hallazgos:** las conclusiones sobre qué patrones son relevantes y qué implican para la política ambiental son reflexiones del equipo.
- **Diseño visual del tablero:** paleta de colores, tipografía y disposición de gráficas fueron decisiones estéticas del equipo.

---

## 5. Reflexión final del equipo

El uso de IA en este proyecto nos permitió enfocarnos en lo que realmente importa: entender los datos y construir una narrativa con impacto. Usamos la IA para reducir fricción en tareas de redacción y código repetitivo, pero en ningún momento delegamos el pensamiento crítico. Cada salida fue cuestionada y muchas fueron rechazadas o reescritas. Consideramos que la IA es una herramienta poderosa que exige mayor rigor, no menor.
