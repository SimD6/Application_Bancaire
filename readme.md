Ce projet présente une **application web full-stack** développée par Simon Goudeau, permettant de centraliser, catégoriser et anticiper ses dépenses bancaires de manière totalement personnalisée.

# Fonctionnalités principales : 
- Connexion aux comptes bancaires via Open Banking (Nordigen)
- Analyse et catégorisation automatique des transactions
- Suivi budgétaire mensuel
- Provisionnement des dépenses à venir (Maisons, Voitures, etc.)
- Personnalisation avancée : catégories, couleurs, icônes, etc.

# Pourquoi cette application ? 
Les solutions existantes sont limitées. Cette app répond à des besoins concrets non couverts par le marché : 
1. Aucune application ne permet de provisionner facilement ses dépenses annuelles (Vacances, Impôts, etc.)
2. Les interfaces des apps classiques ne sont pas pensées pour un suivi quotidien du budget
3. Le niveau de personnalisation est très faible dans les apps grand public
4. Ce projet a aussi été l'occasion pour moi de mettre en pratique mes compétences de développement cloud en sortie de formation

# Technologie utilisée : 
- Firebase (service d'authentification, base de donnée en temps réelle)
- Nordigen pour la récupération des informations sur les transactions 
- FastAPI pour le backend
- React, Tailwind CSS pour le frontend

# Aperçus de l'application : 

### Page "Transactions"
<img width="1949" height="785" alt="Capture d’écran 2025-07-12 112229" src="https://github.com/user-attachments/assets/592e8128-7811-48b0-95f5-38bbeb4e23cf" />
Recherche, trie par montant/date, changement de catégorie, ajout de commentaire

### Page "Catégories"
<img width="2244" height="1243" alt="Capture d’écran 2025-07-12 111805" src="https://github.com/user-attachments/assets/684f8db4-723c-418f-9c05-6fe182468276" />
Interface optimisée pour catégoriser rapidement chaque transaction. 1 click suffit pour catégoriser la prochaine transaction

### Page "Provisions"
<img width="1801" height="805" alt="Capture d’écran 2025-07-12 115704" src="https://github.com/user-attachments/assets/e8e079ea-b423-4387-a690-5b5f81044564" />
Permet de définir un objectif annuel à provisionner (ex. voiture à 5000€). L'app répartit automatiquement la somme sur la période souhaitée.

### Page "Budget"
<img width="2233" height="1187" alt="Capture d’écran 2025-07-12 111924" src="https://github.com/user-attachments/assets/aa284134-e2aa-4d4b-bac8-1e20020c53c8" />
Définit un budget mensuel pour chaque catégorie. Visualisation claire avec graphique circulaire et barres de suivi.


# Prochainement : 
- Système de notifications ("Vous avez 20 transactions à catégoriser")
- Ajouter de la catégorisation automatique (Eviter que l'utilisateur ait à catégoriser chaque mois les dépenses régulières)
- Vue du budget Annuel (Offrir la possibilité de prendre encore plus de recul)
- Centraliser Investissement/Emprunt

# Me contacter : 
Pour plus de détails, vous pouvez me contacter, je serais ravi de répondre à vos questions : 
[Linkedin](https://www.linkedin.com/in/simon-goudeau/)
goudeau.simon@gmail.com
