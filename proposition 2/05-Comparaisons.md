---
title: "05-Comparaisons"
theme: "solarized"
revealOptions:
  transition: "slide"
  slideNumber: true
  touch: true
  titre: "05-Comparaisons"
sources: 
    - ""

---
<style>
table, th, td{
  border: 1px solid;
}

th{
  background: white;
}
</style>
# Comparaisons

---
<div class="container-col">
  <div class="container-row">
        <div>MySQL</div>
        <div>
            <img src="https://upload.wikimedia.org/wikipedia/fr/thumb/6/62/MySQL.svg/1200px-MySQL.svg.png" width="200px">
        </div>
    </div>
    <div class="container-row">
        <div>Redis</div>
        <div>
            <img src="https://cdn.worldvectorlogo.com/logos/redis.svg" width="200px">
        </div>
    </div>
    <div class="container-row">
        <div>Cassandra</div>
        <div>
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5e/Cassandra_logo.svg/2560px-Cassandra_logo.svg.png" width="200px">
        </div>
    </div>
    <div class="container-row">
        <div>MongoDB</div>
        <div>
            <img src="https://www.svgrepo.com/show/303232/mongodb-logo.svg" width="200px">
        </div>
    </div>
    <div class="container-row">
        <div>Elasticsearch</div>
        <div>
            <img src="https://seeklogo.com/images/E/elasticsearch-logo-C75C4578EC-seeklogo.com.png" width="100px">
        </div>
    </div>
</div>

----
### Comparaisons: Général
| Nom | MySQL | Redis | Cassandra | MongoDB | Elasticsearch |
|-----|-------|---|---|---|---|
|Type primaire| relationnel|Clé-valeur|Colonne|Document|Colonne|
|Type secondaire| X | X | X | X | Document, Moteur de recherche|
|Premiére sortie|1995|2009|2008|2009|2010|
| CAP | CA | AP | AP/CP | CP/AP | AP |

----
### Comparaisons: Génréral
| Nom | MySQL | Redis | Cassandra | MongoDB | Elasticsearch |
|-----|-------|---|---|---|---|
|Langage| C/C++|C|Java|C/C++, JS| Java|
|OpenSource|Oui|Oui|Oui|Oui|Oui|
|Developpeur|Oracle|Redis project|Apache (Aciennement Facebook)|MongoDB|Elastic|

----
### Comparaisons: Langage
| Nom | MySQL | Redis | Cassandra | MongoDB | Elasticsearch |
|-----|-------|---|---|---|---|
|Schema de donnée| Oui | Non | Oui | libre | semi |
|SQL | Oui | Non | proche | supporté | Non |
| QL | SQL | Redis | CQL | MQL | REST |
| indexation | Oui | restraint | restraint | Oui | total |

----
### Comparaisons: Fonctionnalités
| Nom | MySQL | Redis | Cassandra | MongoDB | Elasticsearch |
|-----|-------|---|---|---|---|
|Transaction| ACID | Non | Non | Oui | Non |
|Stockage type| HDD | RAM | HDD | HDD | HDD+RAM|
| Persistance| Oui | Snapshot | Oui | Oui | OUI |
| Clé secondaire | Oui | Non | Non | Oui | Non |

----
### Comparaisons: Clusterisation
| Nom | MySQL | Redis | Cassandra | MongoDB | Elasticsearch |
|-----|-------|-------|-----------|---------|---------------|
|Cluster|Horizontal|Sharding|Sharding|Sharding|Sharding|
|MasterNode|Proxy|Non|Non|Oui|Oui|
|CalculeNode|Non|Non|Non|Non|Oui|

----
### Comparaisons: Consomation
| Nom | MySQL | Redis | Cassandra | MongoDB | Elasticsearch |
|-----|-------|-------|-----------|---------|---------------|
|CPU|Moyen|Faible|Faible|Faible|Fort|
|RAM|Faible|Trés haut|faible|haut|trés haut|
|HDD|Moyen|trés faible|Moyen|Moyen|Haut|
|Réseau|Faible|Moyen|Haut|Haut|Haut|

----
### Comparaisons: Vitesse
| Nom | MySQL | Redis | Cassandra | MongoDB | Elasticsearch |
|-----|-------|-------|-----------|---------|---------------|
|Lecture simple|Rapide|Trés rapide|lent|moyen|lent|
|Lecture complexe| lent|X|lent|rapide|rapide|
|Jointure| moyen | X|X|lent|X|
|Aggrégation| rapide | X | trés rapide |moyen | rapide |

----
### Comparaisons: Vitesse
| Nom | MySQL | Redis | Cassandra | MongoDB | Elasticsearch |
|-----|-------|-------|-----------|---------|---------------|
|Ecriture| moyen | trés rapide | lent | rapide | lent* |
|injestion**| moyen | haut | trés haut | moyen | moyen* |
|Update|moyen|trés rapide|lent|rapide|lent*|
|delete|moyen|trés rapide|lent|rapide|moyen|

<div style="font-size:20px">
  * depend du nombre de DataNode<br>
  ** nombre de requêtes d'écriture avant saturation. 
</div>

----
### Comparaisons: Classement db-engines
| Nom | MySQL | Redis | Cassandra | MongoDB | Elasticsearch |
|-----|-------|-------|-----------|---------|---------------|
|db-engine global|2|6|11|5|7|
|db-engine catégorie|1|1|1|1|1|

----
### Comparaisons: Classement db-engines
| Nom | MySQL | Redis | Cassandra | MongoDB | Elasticsearch |
|-----|-------|-------|-----------|---------|---------------|
|stackoverflow popularity|1|6|12|4|9|
|stackoverflow loved%|51.35%|70.71%|42.66%|60.28%|56.70%|
|stackoverflow want | 5|3|7|2|4|