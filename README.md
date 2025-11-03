# ⚙️ Optimisation d’une ligne d’assemblage – Projet C

> Projet académique visant à **analyser et optimiser une ligne d’assemblage industrielle** à l’aide d’algorithmes de gestion de précédences et d’exclusions entre tâches.  
> Objectif : équilibrer les postes de travail, réduire les temps de cycle et améliorer la productivité globale.

---

## 🎯 Objectif du projet
Ce projet a pour but de modéliser le fonctionnement d’une **chaîne d’assemblage**, puis d’y appliquer des algorithmes pour :
- Identifier les **contraintes de précédence** entre tâches,  
- Gérer les **incompatibilités et exclusions**,  
- Déterminer un **ordre de production optimal**,  
- Réduire les **temps d’attente** et **déséquilibres** entre les postes.

---

## 🧩 Structure du projet
Optimisation-ligne-assemblage/
├── main.c # Programme principal
├── exclusions_et_cycle.c # Gestion des exclusions et détection des cycles
├── exclusions_et_precedences.c # Analyse combinée des exclusions et précédences
├── precedences_et_cycle.c # Vérification des cycles de dépendance
├── exclusion.h # Headers associés
├── exclusions_et_cycle.h
├── exclusions_et_precedences.h
├── precedences_et_cycle.h
├── CMakeLists.txt # Fichier de build (CLion / CMake)
├── .gitignore # Fichiers à exclure
└── README.md

# 🧠 Fonctionnement général

1. **Lecture des données d’entrée** : liste des tâches, durées et contraintes de précédence.  
2. **Création du graphe de dépendances** (chaîne de production).  
3. **Détection des cycles** pour garantir la validité du processus.  
4. **Application des exclusions** (tâches incompatibles sur un même poste).  
5. **Optimisation et équilibrage** de la ligne pour réduire le temps total de cycle.

---

## 💻 Technologies utilisées
- **Langage :** C  
- **IDE :** CLion / Code::Blocks  
- **Méthodes :** Analyse des précédences, gestion des exclusions, recherche de cycles  
- **Outils :** CMake, Visual Studio Code (facultatif)

---

## 🧮 Exemple d’application
- Ligne de production composée de N tâches (T1, T2, T3, …).  
- Le programme calcule automatiquement :  
  - Les **contraintes de précédence** entre tâches,  
  - Les **cycles potentiels**,  
  - Et les **affectations optimales** pour minimiser le temps de production total.  

---

## 📈 Résultats attendus
- Réduction du **temps de cycle global**  
- Meilleur **équilibrage des postes**  
- Suppression des **goulots d’étranglement**  
- Amélioration de la **productivité totale de la ligne**


