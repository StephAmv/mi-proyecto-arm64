# Caso de uso

## Nombre
**Evaluar operaciones lógicas/aritméticas para rutina embebida de diagnóstico**

## Actor principal
Estudiante desarrollador de firmware inicial.

## Escenario
Una tarjeta ARM64 requiere validar rápidamente operaciones base para una rutina de diagnóstico antes de integrar periféricos.

## Precondiciones
- Toolchain ARM64 disponible (ej. `as`, `ld`, o `gcc` cruzado).
- Repositorio de GitHub Classroom clonado.
- Estructura mínima del proyecto creada.

## Flujo principal
1. Definir dos operandos de prueba en registros.
2. Ejecutar secuencia de operaciones ALU.
3. Guardar resultados en registros dedicados o memoria.
4. Emitir código de estado final (0=ok, 1=error de validación).
5. Registrar evidencia en PR.

## Flujos alternos
- **A1:** Si la operación seleccionada no está soportada, devolver estado de error.
- **A2:** Si un resultado no coincide con valor esperado, marcar falla en pruebas.

## Postcondiciones
- Se demuestra dominio básico de instrucciones ARM64.
- Se evidencia uso de macro y control de flujo.
- Queda trazabilidad del trabajo en commits y PR.
