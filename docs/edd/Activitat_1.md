
# Activitat 1: Desenvolupament col·laboratiu

## Mecanismes Utilitzats

Per a facilitar el treball col·laboratiu entre Joan i Miquel, utilitzaríem un sistema de control de versions (SCV). Aquest mecanisme permet gestionar diferents versions del codi font i coordinar canvis de manera eficient. Concretament, Subversion (SVN) seria una opció adequada per a aquest tipus de col·laboració.

### Justificació de l'elecció
- **Historial de versions:** Permet recuperar versions anteriors del codi font.
- **Treball paral·lel:** Facilita que diversos desenvolupadors puguin treballar en diferents parts del projecte sense conflictes.
- **Gestió de conflictes:** Ajuda a identificar i resoldre conflictes quan dos usuaris modifiquen els mateixos fitxers.

## Procediment Detallat

1. **Preparació inicial:**
    - Crear un repositori central a Subversion.
    - Organitzar les carpetes en el repositori: `trunk/`, `branches/`, i `tags/`.

2. **Treball diari dels desenvolupadors:**
    - **Actualització inicial:**
        - Cada desenvolupador ha de fer un `svn up` per sincronitzar el seu directori local amb el repositori.
    - **Desenvolupament:**
        - Modificar els fitxers de codi font segons les tasques assignades.
    - **Comprovació d'estat:**
        - Utilitzar `svn st` per comprovar quins fitxers han canviat.
    - **Resolució de conflictes (si escau):**
        - Si hi ha conflictes, resoldre'ls manualment abans de continuar.
    - **Commit dels canvis:**
        - Utilitzar `svn ci -m "Descripció dels canvis"` per enviar els canvis al repositori central.

3. **Procediment de validació:**
    - Realitzar revisions de codi entre els desenvolupadors per assegurar la qualitat.

Aquest procediment assegura que Joan i Miquel poden treballar de manera sincronitzada i eficient.
