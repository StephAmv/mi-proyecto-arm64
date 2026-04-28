# Plan de pruebas

## Objetivo
Verificar que la micropráctica ARM64 ejecute correctamente 5 operaciones básicas con resultados esperados.

## Alcance
Pruebas funcionales de:
1. Suma
2. Resta
3. AND
4. OR
5. Comparación

## Preparación
- Compilar programa ARM64.
- Definir operandos iniciales (ejemplo: A=12, B=5).
- Registrar resultados observados.

## Casos de prueba

| ID | Entrada | Operación | Resultado esperado |
|---|---|---|---|
| CP-01 | A=12, B=5 | Suma | 17 |
| CP-02 | A=12, B=5 | Resta | 7 |
| CP-03 | A=12, B=5 | AND | 4 |
| CP-04 | A=12, B=5 | OR | 13 |
| CP-05 | A=12, B=5 | Comparación | A>B (código 1) |

## Criterios de aceptación
- 5/5 casos con valor correcto.
- Código ensamblado sin errores.
- Macro utilizada al menos una vez.

## Evidencia mínima
- Salida de terminal por caso o bloque de casos.
- Nota de incidencias y correcciones.
