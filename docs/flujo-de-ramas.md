# Flujo de ramas

```
feature/CDU-XX-*  ──PR──▶  develop  ──PR──▶  staging  ──PR──▶  main
                                                 ▲                ▲
hotfix/*  ───────────────────────────────────────┴────────────────┘
```

| Rama | Uso | Recibe PR desde |
|------|-----|-----------------|
| `main` | Producción | `staging`, `hotfix/*` |
| `staging` | Pruebas / QA | `develop`, `hotfix/*` |
| `develop` | Integración | `feature/CDU-XX-*`, `fix/*`, `chore/*`, `docs/*`, `hotfix/*` |
| `feature/CDU-XX-<nombre>` | Trabajo de un caso de uso | - |

Reglas que valida el workflow **Validar flujo de ramas**:

- Un PR solo puede ir al destino permitido en la tabla.
- El título de un PR desde `feature/CDU-XX-*` debe incluir `CDU-XX`.

El workflow **Seguimiento de CDU** actualiza el estado del issue del CDU:
`estado:en-desarrollo` → `estado:integrado-develop` → `estado:en-staging` → `estado:liberado` (se cierra).
Para que un PR de `develop → staging` o `staging → main` mueva un CDU, menciona `CDU-XX` en el título, la descripción o en los commits.

## Cómo trabajar un CDU

```bash
git fetch origin
git switch feature/CDU-04-dispensacion-completa
# ... cambios ...
git commit -m "CDU-04: asignación PEPS de lotes"
git push
gh pr create --base develop --title "CDU-04: asignación PEPS de lotes"
```
