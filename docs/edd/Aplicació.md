# Resolució: Elecció del Llenguatge de Programació per al Projecte

Un company ens ha plantejat una idea de projecte que implica el desenvolupament d'una aplicació mòbil que posi en contacte persones amb interessos comuns a la seva zona per organitzar quedades i esdeveniments. La seva proposta inclou tant una **aplicació mòbil** com un **sistema de servidor** per gestionar connexions a través d'Internet.

## Claus de Resolució:

### 1. **Part Client** (Aplicació Mòbil)
   - L'aplicació que utilitzaran els usuaris als seus dispositius mòbils. Es pot desenvolupar amb diverses tecnologies segons si es vol crear una aplicació **nativa** o **multiplataforma**:
   
   - **Opcions de Llenguatge**:
     - **Nadiu (Android/iOS)**:
       - **Android**: **Kotlin** o **Java**
       - **iOS**: **Swift**
     - **Multiplataforma**:
       - **React Native** (JavaScript/TypeScript)
       - **Flutter** (Dart)
       - **Ionic** (HTML, CSS, JavaScript)

   - **Recomanació**: Si es vol una solució multiplataforma, **React Native** o **Flutter** serien bones opcions, ja que permeten desenvolupar una única base de codi per a Android i iOS. Si el projecte es limita a una sola plataforma, aleshores Kotlin (per a Android) o Swift (per a iOS) serien més adequats.

### 2. **Part Servidor** (Backend)
   - Aquesta part s'encarregarà de gestionar les connexions entre usuaris, la base de dades i la lògica de negoci. El servidor podria estar desenvolupat amb qualsevol tecnologia que gestioni serveis web i APIs.
   
   - **Opcions de Llenguatge**:
     - **Node.js** (JavaScript/TypeScript)
     - **Python** (amb frameworks com Django o Flask)
     - **Ruby** (Ruby on Rails)
     - **Java** (Spring Boot)
     - **C#** (ASP.NET)
   
   - **Recomanació**: **Node.js** és una opció popular gràcies a la seva compatibilitat amb **JavaScript**, que pot facilitar el desenvolupament si s'usa **React Native** per al client. Si es busca una solució robusta i provada, **Python** o **Java** serien opcions segures.

## Conclusió
Per al desenvolupament d'aquesta aplicació mòbil amb part client i part servidor, es podria utilitzar:

1. **Per a l'aplicació mòbil**: **React Native** o **Flutter** per desenvolupar per a Android i iOS amb una única base de codi.
2. **Per a la part del servidor**: **Node.js** amb **Express** (si es tria React Native), o bé **Python** amb **Django** per una solució escalable i senzilla de mantenir.

Aquestes tecnologies ofereixen una combinació poderosa per desenvolupar tant el front-end com el back-end de manera eficient.
