
# Activitat 3: Comparació i ordres d'RCS i Subversion

## Diferències entre RCS i Subversion

| Característica      | RCS                          | Subversion                 |
|---------------------|------------------------------|----------------------------|
| **Tipus**           | Control de versions local    | Control de versions centralitzat |
| **Col·laboració**   | No és adequat per a equips   | Permet treball col·laboratiu |
| **Historial**       | Local, només disponible en un sistema | Central, accessible a tots |
| **Escalabilitat**   | Limitat a projectes petits   | Adequat per a projectes grans |

## Ordres i Descripció

### RCS
- **`co`**: Extrau una còpia de treball d'un fitxer gestionat per RCS.
- **`ci`**: Enregistra els canvis en el fitxer al repositori local d'RCS.

### Subversion (SVN)
- **`svn co`**: Crea una còpia de treball del repositori central.
- **`svn ci`**: Envia els canvis al repositori central.
- **`svn st`**: Mostra l'estat dels fitxers de la còpia local en relació al repositori.
- **`svn add`**: Afegeix fitxers nous al sistema de control de versions.
- **`svn up`**: Sincronitza la còpia local amb el repositori central.

### Comparació d'ordres
Les ordres `co` i `ci` d'RCS són similars a les ordres `svn co` i `svn ci`, però amb una diferència clau:
- **RCS**: Operacions exclusivament locals.
- **SVN**: Operacions implicant un repositori centralitzat, adequat per a col·laboració.
