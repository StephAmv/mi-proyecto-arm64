# Estructura sugerida del repositorio

```text
.
├─ README.md
├─ docs/
│  ├─ propuesta.md
│  ├─ caso_de_uso.md
│  ├─ estructura_repositorio.md
│  ├─ plan_de_pruebas.md
│  └─ reflexion_ia.md
├─ src/
│  └─ main.s
└─ run.sh
```

## Descripción breve
- `src/main.s`: núcleo ARM64 con 3–5 funcionalidades y al menos 1 macro.
- `run.sh` (opcional): compila/ejecuta sin tooling complejo.
- `docs/`: definición académica, pruebas y reflexión.

## Convenciones recomendadas
- Commits pequeños y descriptivos.
- Mensajes en español técnico claro.
- Una rama por feature.
- PR con checklist de pruebas.
