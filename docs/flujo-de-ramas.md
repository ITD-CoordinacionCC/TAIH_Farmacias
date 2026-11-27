# Flujo de ramas

```
feature/<integrante>  --PR-->  develop  --PR-->  staging  --PR-->  main
                                                    ^                ^
hotfix/*  ------------------------------------------+----------------+
```

| Rama | Uso | Recibe PR desde |
|------|-----|-----------------|
| `main` | Producción | `staging`, `hotfix/*` |
| `staging` | Pruebas / QA | `develop`, `hotfix/*` |
| `develop` | Integración | `feature/<integrante>`, `fix/*`, `chore/*`, `docs/*`, `hotfix/*` |
| `feature/<integrante>` | Trabajo de cada integrante sobre sus CDU | - |

Cada integrante tiene su rama y su carga de trabajo en `docs/cargas/<integrante>.md`.

Reglas que valida el workflow **Validar flujo de ramas**:

- Un PR solo puede ir al destino permitido en la tabla.
- El título de un PR desde `feature/<integrante>` debe incluir los CDU que entrega (`CDU-XX`).

El workflow **Seguimiento de CDU** actualiza el estado del issue de cada CDU mencionado en el título,
la descripción o los commits del PR:
`estado:en-desarrollo` -> `estado:integrado-develop` -> `estado:en-staging` -> `estado:liberado` (se cierra).

## Cómo trabajar

```bash
git fetch origin
git switch feature/<tu-usuario>
git pull origin develop          # traer lo último de develop
# ... cambios ...
git commit -m "CDU-04: asignación PEPS de lotes"
git push
gh pr create --base develop --title "CDU-04: asignación PEPS de lotes"
```

Entrega por PR cada CDU (o un grupo pequeño de CDU) en cuanto esté listo, sin esperar a terminar toda la carga.
