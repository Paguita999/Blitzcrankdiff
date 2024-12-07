# Activitat 3: Comparació entre RCS i Subversion

## Diferències entre RCS i Subversion
| Característica              | RCS                         | Subversion                    |
|-----------------------------|-----------------------------|-------------------------------|
| **Tipus de repositori**     | Local                       | Centralitzat                  |
| **Treball col·laboratiu**   | Difícil                     | Suport complet per equips     |
| **Historial de versions**   | Només un fitxer a la vegada | Historial de múltiples fitxers|
| **Rendiment**               | Ràpid en fitxers locals     | Més lent però versàtil        |

## Ordres i funcionalitat
### RCS
- `co`: Obté una còpia del fitxer del repositori local per treballar-hi.
- `ci`: Comprova i guarda els canvis al repositori local.

### Subversion
- `svn co`: Clona un repositori sencer (Checkout).
- `svn ci`: Puja els canvis al repositori central (Commit).
- `svn st`: Mostra l'estat dels fitxers locals (State).
- `svn add`: Afegeix nous fitxers al repositori.
- `svn up`: Actualitza els fitxers locals amb els canvis del repositori.

## Diferències en `co` i `ci`
- En **RCS**, `co` i `ci` treballen amb un fitxer a la vegada, sempre localment.
- En **Subversion**, `co` i `ci` gestionen múltiples fitxers i sincronitzen amb un repositori central, facilitant el treball en equip.
