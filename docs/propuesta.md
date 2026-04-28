# Propuesta de actividad (GitHub Classroom + micropráctica)

## Título
**Mini-ALU en ARM64 con macros y validación básica**

## Contexto
En sistemas embebidos es común operar datos en bajo nivel con recursos limitados. Esta práctica simula una mini unidad aritmético-lógica usando Assembly ARM64 y documentación profesional en GitHub.

## Objetivo de aprendizaje
Al finalizar, el estudiante podrá:
- Escribir y organizar un programa pequeño en ARM64 Assembly.
- Definir y usar al menos una macro reusable.
- Aplicar control de flujo con comparaciones y saltos.
- Validar comportamiento con pruebas simples reproducibles.

## Micropráctica técnica propuesta
Implementar programa que lea dos operandos predefinidos en memoria/registros y ejecute un menú interno de operaciones:
1. Suma.
2. Resta.
3. AND bit a bit.
4. OR bit a bit.
5. Comparación (mayor/igual/menor) con código de estado.

## Macro obligatoria (ejemplo)
Macro de impresión de resultado o de carga de constantes:
```asm
.macro LOAD_IMM reg, val
    mov \reg, #\val
.endm
```

## Restricciones de implementación
- Núcleo obligatorio en ARM64 Assembly.
- Capa opcional mínima: Bash para compilar/ejecutar.
- No usar Python.
- Sin frameworks pesados ni servicios pagados.
- Código principal sugerido: máximo 150 líneas.

## Evidencias esperadas
- Captura de salida en terminal.
- Bitácora breve de casos probados.
- Pull Request con descripción técnica y decisiones.
