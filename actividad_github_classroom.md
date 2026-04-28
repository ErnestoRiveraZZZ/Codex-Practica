# Actividad: Propuesta Documentada de Práctica Temática en Entorno de Sistemas

## 1) Título de la práctica
**Diseño de Práctica Temática Pequeña: Sistemas en Terminal (ARM64, C, Python o Bash)**

> Puedes adaptar el título final a tu tema específico. Ejemplos válidos:
> - “Mini Toolkit en ARM64”
> - “Asistente de Estudio en Terminal”
> - “Reporteador de Información del Sistema”
> - “Organizador de Archivos”
> - “Juego de Aprendizaje en Línea de Comandos”

---

## 2) Descripción general
En esta actividad **vas a diseñar y documentar** la propuesta de una práctica temática pequeña para un curso de arquitectura de computadoras, programación de sistemas o fundamentos de software en terminal.

### Objetivo principal
Antes de programar a gran escala, tu prioridad será:
- definir claramente el problema,
- justificar por qué tu solución es útil,
- proponer una estructura limpia de repositorio,
- y establecer un plan de pruebas realista.

### Lenguaje principal (elige solo uno)
- ARM64 Assembly
- C
- Python
- Bash

### Alcance y restricciones
- El proyecto debe ser **pequeño y realizable** en poco tiempo.
- Evita ideas que requieran:
  - frameworks grandes,
  - APIs pagadas,
  - bases de datos,
  - servicios en la nube,
  - contenedores,
  - dependencias complejas.
- Si eliges **ARM64 Assembly**, se recomienda únicamente para programas **muy pequeños** (por ejemplo: operaciones básicas, parsing simple de argumentos, salida formateada en terminal).

> Esta tarea evalúa principalmente tu capacidad de **documentación, planeación y diseño técnico inicial**.

---

## 3) Entregables del estudiante
Tu repositorio debe incluir como mínimo los siguientes archivos:

- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`

Carpetas opcionales (si decides incluir prototipo):
- `src/`
- `scripts/`
- `tests/`

### Contenido esperado por archivo

#### `README.md`
Debe incluir:
1. Nombre del proyecto.
2. Resumen corto (3–6 líneas).
3. Lenguaje elegido y justificación breve.
4. Estado del proyecto (solo propuesta / propuesta + prototipo mínimo).
5. Instrucciones rápidas para revisar la documentación.

#### `docs/propuesta.md`
Debe incluir:
1. **Problema a resolver**.
2. **Objetivo general** y 2–4 objetivos específicos.
3. **Alcance** (qué sí hará y qué no hará).
4. **Usuarios objetivo**.
5. **Requerimientos funcionales mínimos** (3–6 puntos).
6. **Requerimientos no funcionales** (simplicidad, portabilidad, claridad de uso, etc.).
7. **Justificación técnica del lenguaje**.
8. **Riesgos y limitaciones**.

#### `docs/caso_de_uso.md`
Debe incluir:
1. Contexto del caso de uso.
2. Actor principal.
3. Precondiciones.
4. Flujo principal paso a paso.
5. Flujo alterno o de error.
6. Resultado esperado.

#### `docs/estructura_repositorio.md`
Debe incluir:
1. Árbol del repositorio.
2. Explicación del propósito de cada carpeta/archivo.
3. Convenciones de nombres (archivos, scripts, pruebas).
4. Estrategia mínima de mantenimiento (cómo crecer el proyecto sin desorden).

#### `docs/plan_de_pruebas.md`
Debe incluir:
1. Estrategia de validación básica.
2. Lista de casos de prueba (mínimo 5).
3. Formato de evidencia esperada (salida en terminal, capturas, logs simples).
4. Criterios de aceptación.

---

## 4) Estructura recomendada del repositorio
Usa como base la siguiente estructura mínima:

```text
nombre-del-proyecto/
├── README.md
├── docs/
│   ├── propuesta.md
│   ├── caso_de_uso.md
│   ├── estructura_repositorio.md
│   └── plan_de_pruebas.md
├── src/
│   └── main.<ext>
├── scripts/
│   └── run.sh
└── tests/
    └── test_plan.md
```

> `<ext>` depende del lenguaje elegido:
> - Assembly: `.s`
> - C: `.c`
> - Python: `.py`
> - Bash: `.sh`

---

## 5) Reglas de diseño de la propuesta
1. **Proyecto pequeño**: que se pueda explicar y prototipar sin infraestructura compleja.
2. **Enfoque en terminal**: interacción por línea de comandos.
3. **Claridad documental**: documentos legibles, con encabezados y listas.
4. **Coherencia técnica**: el caso de uso, el plan de pruebas y la estructura deben coincidir entre sí.
5. **Viabilidad académica**: el alcance debe ser realista para una práctica corta.

---

## 6) Criterios de evaluación sugeridos (rúbrica)
Puntaje total: **100 puntos**

- **Calidad de la propuesta técnica (30 pts)**
  - Problema, objetivos, alcance y justificación bien definidos.
- **Caso de uso (20 pts)**
  - Flujo principal y alternos claros, completos y consistentes.
- **Estructura del repositorio (20 pts)**
  - Organización, convenciones y mantenibilidad.
- **Plan de pruebas (20 pts)**
  - Casos relevantes, medibles y alineados al objetivo.
- **Claridad de redacción y formato (10 pts)**
  - Ortografía, orden y legibilidad.

---

## 7) Sugerencias de temas pequeños (opcionales)
Elige **uno** o propón uno equivalente:
- Verificador de argumentos y banderas en CLI.
- Mini conversor de unidades en terminal.
- Organizador simple de archivos por extensión.
- Reporteador básico de información del sistema.
- Quiz de comandos Linux en modo texto.

---

## 8) Entrega
1. Sube todos tus archivos al repositorio asignado en GitHub Classroom.
2. Verifica que los archivos obligatorios estén en la ruta correcta.
3. Incluye en `README.md` una sección llamada **“Cómo revisar esta propuesta”** con enlaces internos a tus documentos.

---

## 9) Nota final para el estudiante
Esta práctica califica tu capacidad para **pensar como arquitecto/a de software desde el inicio**: definir, acotar, justificar y planear antes de codificar. Una propuesta simple, coherente y bien documentada vale más que una idea grande e incompleta.
