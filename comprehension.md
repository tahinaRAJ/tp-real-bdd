# Compréhension

## Maintenant compris
### Insertion de données depuis avec des dump d'un fichier tar.gz 
/opt/lampp/bin/mysql -u root -p employees < employees.sql


### Par fonction
#### get_all_lines
Cette fonction retourne toutes les lignes de la requete sql et les transforme en tableau associative. On a remarqué l'usage de mysqli_free_result permettant de liberer la mémoire. 

#### get_one_line
Cette fonction retourne la premiere ligne de la requete avec mysqli_fetch_assoc avec mysqli_free_result

#### get_departments_except
L'utilisation de <> qui signifie l'exception. On prend tout sauf condition == x







## Pas encore compris
