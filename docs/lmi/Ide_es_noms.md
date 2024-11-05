# xmlns
- **xmlns:android:** Prefix utilitzat per referir-se als atributs de l'espai de noms d'Android.
- **http://schemas.android.com/apk/res/android:** És l’espai de noms propi d'Android. No és una URL que es pugui visitar, sinó una convenció per identificar els atributs estàndards d'Android ***(com android:name, android:label, etc.)***.
## Per què és important?
- **Organització i claredat:** L'espai de noms evita conflictes quan diferents atributs podrien tenir noms similars o idèntics.
- **Compatibilitat i validació:** Android sap com interpretar atributs com ***android:layout_width*** gràcies a aquesta declaració d'espai de noms.
- **Desenvolupament modular:** Si fas servir llibreries externes que afegeixen atributs propis, aquests atributs poden tindre el seu propi espai de noms per evitar col·lisions amb els atributs estàndard d'Android o d'altres llibreries.