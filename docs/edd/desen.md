# Activitat 1: Desenvolupament Col·laboratiu

## Mecanismes recomanats
Per tal de facilitar el treball col·laboratiu entre Joan i Miquel, és essencial utilitzar un sistema de control de versions (SCV) modern com Git o Subversion. Aquest tipus d'eines permeten:

- **Control de versions**: Gestionar els canvis al codi font de manera eficient.
- **Treball paral·lel**: Cadascú pot treballar en les seves funcionalitats sense interferir amb l'altre.
- **Resolució de conflictes**: Possibilitat d'integrar canvis de manera controlada.
- **Historial de canvis**: Registre de totes les modificacions realitzades, permetent revertir a versions anteriors si cal.

## Procediment de treball
1. **Clonar o actualitzar el repositori:**
   - Cada desenvolupador ha de començar el dia actualitzant el codi amb els canvis més recents del repositori.
   - Git: `git pull`
   - Subversion: `svn up`

2. **Crear una branca de treball:**
   - Per a evitar conflictes, cada funcionalitat o tasca hauria de desenvolupar-se en una branca separada.
   - Git: `git checkout -b funcionalitat`
   - Subversion: Es pot crear una carpeta específica dins de `/branches`.

3. **Treballar en el codi:**
   - Desenvolupar i provar les funcionalitats en local.
   - Fer commits regularment per guardar els canvis:
     - Git: `git add` i `git commit`
     - Subversion: `svn ci`

4. **Integrar els canvis:**
   - Abans d'integrar els canvis a la branca principal, fusionar els canvis més recents de la branca principal.
     - Git: `git merge main`
     - Subversion: Actualitzar la branca amb `/trunk` i comprovar conflictes.

5. **Revisió i aprovació:**
   - Una vegada la funcionalitat està completa, enviar una sol·licitud de revisió de codi (Pull Request o Merge Request).

6. **Fusionar a la branca principal:**
   - Integrar els canvis aprovats al codi principal.

Aquest procediment garanteix col·laboració fluida i una integració segura de funcionalitats.
