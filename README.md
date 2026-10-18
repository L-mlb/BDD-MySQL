# BDD MySQL
Création d'une base de données fonctionnelle avec ses requêtes sur MySQL. Ce projet s'inscrit dans le cadre d'un projet scolaire effectué en groupe avec d'autres camarades.

### Attention ! 
--> Les requêtes doivent être exécutées chacune dans un fichier différent et non dans un même fichier à la suite, car sinon tous les tableaux ne s'affichent pas ! 

--> Pour ouvir le fichier "MCD + MLD" il faut avoir l'application Looping

--------------------------------------------------------

# Projet Base de Données ClearData – Gestion des capteurs de gaz
---

## 🌍 Contexte
Le ministère de la Transition Écologique veut centraliser les données sur la qualité de l’air dans les grandes villes françaises.  
Les données actuelles sont dispersées dans différents tableurs régionaux, ce qui rend leur exploitation difficile.  

L’objectif : créer une **base de données relationnelle fiable**, centralisée et facilement interrogeable pour stocker :  
- Mesures de pollution atmosphérique  
- Agences régionales et leur personnel  
- Capteurs et relevés  
- Rapports d’analyse  

---

## 🛠️ Objectifs du projet
- Gérer les **agences régionales**, leurs employés (techniques et administratifs), et leurs rôles  
- Stocker les **données mensuelles** de capteurs mesurant différents gaz polluants (CO₂, CH₄, HFC…)  
- Associer ces données à des **rapports d’analyse**  
- Permettre **consultation, ajout et suppression** des données  
- Produire des **résumés et requêtes analytiques** pour les besoins décisionnels  

---

## 💾  Peuplement
- 13 régions, 2 villes par région  
- 14 agences, 41 employés minimum  
- 6 capteurs par ville, 2 relevés par capteur → **312 relevés**  
- 10 rapports minimum  

---

## 🔍 Requêtes SQL réalisées
1. Liste de toutes les agences  
2. Personnel technique de l’agence de Bordeaux  
3. Nombre total de capteurs déployés  
4. Rapports publiés entre 2018 et 2022  
5. Concentrations de CH4 dans certaines régions et mois  
6. Agents techniques gérant les GESI  
7. Titres et dates des rapports sur CH4 (ordre anti-chronologique)  
8. Mois avec concentration minimale de HFC par région  
9. Moyenne des concentrations par gaz pour Ile-de-France en 2020  
10. Taux de productivité des agents administratifs à Toulouse  
11. Rapports liés à un gaz donné (paramétrable)  
12. Régions avec plus de capteurs que de personnel  

---

## 📊 Résultats
- Base fonctionnelle et testable  
- Requêtes analytiques opérationnelles  
- Contraintes d’intégrité respectées  
- Données réalistes et cohérentes avec le cahier des charges  
