# Projet de Web Sémantique

Descriptif des fichiers :

- Inference/ : Contient les fichiers nécéssaires pour les inférences avec Fuseki<br>
- construct_and_data/ : Contient notre dataset CSV source et la requête SPARQL construct utilisée pour le formater en RDF Turtle avec TARQL
- data_EffectifsEtusSup/ : Contient le dataset CSV source provenant des données d'un autre groupe ainsi que la requête SPARQL construct utilisée pour le formater en RDF Turtle
- tarql/ : Contient le programme TARQL compilé par nos soins et laissé ici pour plus de commodité, exécutable à l'adresse ./tarql/target/appassembler/bin/tarql
- turtle/ : Contient nos fichiers Turtle, c'est-à-dire les graphes RDF générés de nos datasets ainsi que la description VoID de nos données
- queries.sparql : Fichier contenant nos requêtes SPARQL
- README.md : this
