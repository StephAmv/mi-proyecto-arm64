# Plantilla de Propuesta de Tarea (GitHub Classroom)

## 1) Título de la práctica temática
**Diseña tu propio título** para una micropráctica (proyecto pequeño), por ejemplo:
- **Mini Toolkit en ARM64**
- **Asistente de Estudio en Terminal**
- **Reporteador de Información del Sistema**
- **Organizador de Archivos**
- **Juego de Aprendizaje en Línea de Comandos**

> **Indicaciones:** El título debe reflejar claramente el problema que quieres resolver y el entorno de uso (terminal/local).

---

## 2) Descripción general de la actividad
En esta actividad, **tú (estudiante)** vas a diseñar la propuesta de un proyecto técnico **pequeño** con enfoque en **documentación y planeación**. La meta es definir una idea viable antes de escribir mucho código.

### Lenguaje principal (elige uno)
- ARM64 Assembly
- C
- Python
- Bash

> **Recomendación importante:** Si eliges **ARM64 Assembly**, limita tu alcance a programas **muy pequeños** (una sola funcionalidad central, entradas simples y salida en terminal).

### Prioridad de la actividad
1. Justificar el caso de uso.
2. Documentar alcance y límites.
3. Diseñar estructura de repositorio.
4. Proponer plan de pruebas.
5. Implementar solo lo mínimo necesario (si aplica).

### Restricciones del proyecto
- Debe ser **pequeño y realizable** en poco tiempo.
- Sin frameworks grandes.
- Sin APIs pagadas.
- Sin bases de datos.
- Sin nube ni contenedores.
- Sin dependencias complejas.

---

## 3) Entregables del estudiante
Tu repositorio debe incluir, **como mínimo**, estos archivos:

- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`
- opcional: `src/`
- opcional: `scripts/`
- opcional: `tests/`

### Contenido esperado por archivo

#### `README.md`
- Nombre del proyecto.
- Problema que resuelve (2–4 párrafos).
- Lenguaje principal y justificación breve.
- Instrucciones mínimas para ejecutar (si hay código).
- Estado del proyecto: propuesta / prototipo.

#### `docs/propuesta.md`
- Objetivo general.
- Alcance (qué sí incluye).
- Fuera de alcance (qué no incluye).
- Lista de funcionalidades mínimas (MVP).
- Riesgos técnicos y cómo mitigarlos.

#### `docs/caso_de_uso.md`
- Usuario objetivo.
- Contexto de uso (cuándo y para qué se usa).
- Flujo principal paso a paso.
- Entradas/salidas esperadas.
- Ejemplo concreto.

#### `docs/estructura_repositorio.md`
- Árbol de carpetas propuesto.
- Propósito de cada carpeta/archivo.
- Convenciones de nombres.

#### `docs/plan_de_pruebas.md`
- Casos de prueba funcionales básicos.
- Pruebas de error/entrada inválida.
- Resultado esperado por caso.
- Evidencia sugerida (captura de terminal, logs breves, etc.).

---

## 4) Estructura recomendada del repositorio
Usa como base esta estructura mínima:

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

> `<ext>` depende del lenguaje elegido: `s` (ARM64), `c`, `py` o `sh`.

---

## 5) Alcance sugerido por lenguaje (para mantenerlo pequeño)

### ARM64 Assembly
- 1 funcionalidad principal (ej. operación aritmética simple, conversión o validación básica).
- 1 entrada simple y 1 salida clara.
- Máximo recomendado: 100–150 líneas comentadas.

### C
- Programa de consola modular pequeño (1–3 archivos `.c/.h`).
- Sin bibliotecas externas complejas.

### Python
- Script CLI con funciones bien separadas.
- Solo librería estándar.

### Bash
- Automatización pequeña (validar archivos, resumir directorio, menú simple).
- Scripts portables y comentados.

---

## 6) Criterios de evaluación (enfoque documentación)
- **40%** Calidad de documentación (claridad, orden, redacción técnica).
- **25%** Coherencia del caso de uso y alcance.
- **20%** Estructura del repositorio y convenciones.
- **15%** Plan de pruebas realista y verificable.

> El código implementado suma valor, pero en esta actividad la prioridad es el diseño documentado.

---

## 7) Formato de entrega en GitHub Classroom
1. Completa los archivos requeridos.
2. Sube cambios al repositorio asignado.
3. Asegúrate de que los nombres de archivos coincidan exactamente.
4. Incluye un último commit con mensaje sugerido:
   - `docs: propuesta inicial de micropráctica temática`

---

## 8) Checklist rápido del estudiante
- [ ] Definí un título claro y temático.
- [ ] Elegí un lenguaje principal y lo justifiqué.
- [ ] Delimité alcance y fuera de alcance.
- [ ] Documenté caso de uso con flujo principal.
- [ ] Propuse estructura de repositorio.
- [ ] Redacté plan de pruebas funcional y de errores.
- [ ] (Opcional) Añadí prototipo mínimo en `src/`.

---

## 9) Nota final
Piensa en esta actividad como el **diseño profesional de una práctica**, no como una carrera por escribir mucho código. Una propuesta clara, pequeña y bien documentada vale más que un proyecto grande e incompleto.
