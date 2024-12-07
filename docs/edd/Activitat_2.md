
# Activitat 2: Estructura del repositori per a Subversion

## Proposta d'Estructura

Per a un projecte iteratiu i incremental de cinc fases, proposo utilitzar l'estructura de carpetes següent al repositori Subversion:

```
/project-name/
    trunk/
    branches/
        phase-1/
        phase-2/
        phase-3/
        phase-4/
        phase-5/
    tags/
        version-1.0/
        version-2.0/
        version-3.0/
        version-4.0/
        version-5.0/
```

### Justificació de l'Estructura
- **`trunk/`**: Contindrà el codi principal del projecte en desenvolupament actiu.
- **`branches/`**: Cada fase tindrà la seva branca per a treballar de manera paral·lela i permetre proves independents.
- **`tags/`**: Emmagatzemarà versions estables del producte després de completar cada fase.

## Procediment per a cada iteració
1. Crear una branca nova dins de `branches/` per a la fase actual.
2. Desenvolupar la funcionalitat corresponent a la fase en aquesta branca.
3. Realitzar proves i validar els canvis.
4. Fusionar la branca amb el `trunk/` una vegada completada.
5. Crear una nova etiqueta (tag) a `tags/` per identificar la versió estable.
