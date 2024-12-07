# Activitat 2: Estructura del repositori Subversion

## Estructura recomanada
Per al desenvolupament iteratiu i incremental, proposo la següent estructura de carpetes al repositori Subversion:

```
/projecte
│
├── /trunk
│   └── Codi principal (el codi actiu en desenvolupament i amb funcionalitats estables)
│
├── /branches
│   ├── /fase1
│   ├── /fase2
│   ├── /fase3
│   ├── /fase4
│   └── /fase5
│
└── /tags
    ├── /v1.0
    ├── /v2.0
    ├── /v3.0
    ├── /v4.0
    └── /v5.0
```

## Justificació
- **Trunk:** Emmagatzema la versió principal i més actual del codi.
- **Branches:** Conté les branques separades per a cada fase o funcionalitat en desenvolupament.
- **Tags:** Es fan servir per guardar versions estables del producte al final de cada iteració.

Aquest disseny permet un desenvolupament ordenat i una traçabilitat clara entre versions i iteracions.
