# Projet de fin de semestre (Python pour le Data Scientist) : "Quelle est la meilleure destination pour prendre l’avion de Paris ?"

*Hélène Bonneau-Chloup & Laura Brahmi - 2A ENSAE  2021 2022*

### Présentation de notre sujet 

Nous souhaitons étudier les prix des billets d’avions au départ de Paris à destination des plus grandes villes du monde (Londres, New-York, Tokyo …). Pour cela, nous allons utiliser les prix des vols disponibles sur le site de Kayak (webscraping), distinguer les compagnies low-cost des compagnies traditionnelles, horaire de départ, escales… Mais aussi la date de départ qui sera le paramètre de notre programme final qui donnera en sortie :

* la destination la moins chère de façon absolue
* la destination la moins chère par kilomètre parcouru
pour les compagnies “low cost” et les compagnies “traditionnelles” en prenant des allers simples au départ d’un des trois aéroports de Paris selon Kayak : Paris Orly, Paris Charles de Gaulle et l’aéroport de Beauvais.

Nous chercherons ainsi à savoir si le prix des billets d’avion dépend de la distance parcourue entre la ville de départ et la ville d’arrivée. Nous représenterons une partie de nos résultats à travers une carte du monde qui illustrera les prix les moins chers au départ de Paris à une date donnée.

Afin de voir les différents déterminants du prix d’un billet d’avion, nous réaliserons également des régressions linéaires du prix en fonction de la distance, des horaires, des escales, des bagages, du type de la compagnie : low-cost ou traditionnelle, des émissions de CO2…

Nous mettons également à disposition les tables csv (*dataframe_projet_python_01-02_01-03.csv* et *pays_continent.csv*) que nous avons utilisées, elles sont disponible dans le github.
