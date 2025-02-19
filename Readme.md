# Conception
Conception sans développement.

## 1. Le cahier des charges
[Voir cahier des charges](1.%20Cahier%20des%20charges.pdf)

## 2. Le diagramme de Cas d’Utilisation (use case)
![Voir diagramme](./2.%20Diagramme%20des%20cas%20d'utilisation.drawio.png)

## 3. Une charte graphique succincte
[Voir charte](3.%20Charte%20graphique.md)

## 4. Les maquettes de l’application et l’enchainement des écrans avec le logiciel de votre choix. 
Ne faire qu’une seule maquette de type zoning par type d’interface utilisateur et au moins deux maquettes incluant la charte graphique.

### Écrans

**Accueil** :
- Accueil des invités ![invité](./Maquettes/Accueil%20-%20invité.png "Accueil invité")
- Accueil des employés ![employé](./Maquettes/Accueil%20-%20employé.png "Accueil employé")


**Consultation** :
- liste des documents par un lecteur ![liste des documents ](./Maquettes/Consultation%20-%20documents%20-%20invité.png "liste des documents par un lecteur")
- liste des documents par un employé ![Liste des documents](./Maquettes/Consultation%20-%20documents%20-%20employé.png "liste des documents par un employé")
- liste des prêts d'un usager ![liste des prêts d'un usager](./Maquettes/Consultation%20-%20prêts.png "liste des prêts d'un usager")
- liste des lecteurs ![Liste des lecteurs](./Maquettes/Consultation%20-%20lecteurs.png "Liste des lecteurs")
- liste des employés ![Liste des employé](./Maquettes/Consultation%20-%20employés.png "Liste des employés")

**CRUD** :
- personne (lecteur / bénévole / employé) ![Création d'une personne](./Maquettes/Création%20personne%20-%20employé.png "CRUD d'une personne")
- document (livre / CD-Rom / journal / microfilm) ![CRUD d'un document](./Maquettes/Création%20document%20-%20employé.png "CRUD d'un document") 
- prêt ![CRUD d'un prêt](./Maquettes/Création%20prêt%20-%20employé.png "CRUD d'un prêt")

**Connexion** : 
- employé ![Connexion d'un employé](./Maquettes/Connexion%20-%20invité.png "Connexion d'un employé")

### Enchaînement des écrans

**Connexion d'un employé**

Accueil invité | Connexion | Accueil employé
---------------|-----------|----------------
![](./Maquettes/Accueil%20-%20invité.png) | ![](./Maquettes/Connexion%20-%20invité.png) | ![](./Maquettes/Accueil%20-%20employé.png)  

**Création lecteur**
Accueil employé | Formulaire personne | Liste des lecteurs
----------------|---------------------|--------------------
![](./Maquettes/Accueil%20-%20employé.png) | ![](./Maquettes/Création%20personne%20-%20employé.png) | ![](./Maquettes/Consultation%20-%20lecteurs.png)

**Création document**
Accueil employé | Formulaire document | Liste des documents
----------------|---------------------|--------------------
![](./Maquettes/Accueil%20-%20employé.png) | ![](./Maquettes/Création%20document%20-%20employé.png) | ![](./Maquettes/Consultation%20-%20documents%20-%20employé.png)

**Prêt d'un document**
Accueil employé | Formulaire prêt | Liste des prêts d'un lecteur
----------------|-----------------|-----------------------------
![](./Maquettes/Accueil%20-%20employé.png) | ![](./Maquettes/Création%20prêt%20-%20employé.png) | ![](./Maquettes/Consultation%20-%20prêts.png)

## 5. Le dictionnaire de données, les règles de gestion et d’organisation, le MCD et le MLD
- [Voir dictionnaire de données](5.%20Dictionnaire%20de%20données.md)
- [Voir règles de gestion](5.%20Règles%20de%20gestion.md)
- [Voir règles d'organisation](5.%20Règles%20d'organisation.md)
- Voir le modèle conceptuel des données
    ![Voir le MCD](5.%20MCD.jpg "Modèle Conceptuel des Données")
- [Voir le modèle logique des données](5.%20MLD.md)


##  6. Le diagramme de Classes des classes Métier

##  7. Le diagramme de séquence et le diagramme d’activité pour un emprunt de CD