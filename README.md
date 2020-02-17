# silene-geonature
Ce dépôt sert à rassembler et organiser les tickets concernant le projet de migration vers GeoNature de *silene.eu*.  
Nous utiliserons pour cela le système de tickets de Github.  

## Comment saisir un nouveau ticket ?
1. Rendez-vous sur la [page de gestion des tickets de ce dépôt Github](https://github.com/cbn-alpin/silene-geonature/issues) et ouvrez un nouveau ticket (bouton "*New issue*").
1. Saisissez un titre court ("*Title*") et représentatif du problème
1. Saisissez une description plus détaillée sous l'onget "*Write*". Et agrémentez ce texte de copie d'écran en glissant/déposant vos fichiers dans le même espace.
1. Dans la colonne de droite, sélectionnez un label de type **outils** préfixé par **o:** pour localiser votre problème.
1. Sélectionner éventuellement d'autres labels.
1. Valider l'ajout de votre ticket avec le bouton "*Submit new issue*".

## Gestion des labels

Nous utiliserons les labels suivant :

- Effort
- Priorite
- Public
- Info
- Status
- Type

### Effort [e] (#d4c5f9)

Permet d'indiquer le temps nécessaire pour fermer le ticket. Une note de 1 (failble) à 3 (important).
Les labels disponibles sont :
- **e:1** : demande une effort faible.
- **e:2** : demande une effort moyen.
- **e:3** : demande une effort important.

### Priorité [p] (#f7c6c7)

Permet d'indiquer l'importance d'un ticket vis à vis des autres et donc l'ordre de traitement.
Les labels disponibles sont :
- **p:bloquant** (#e11d21): le problème décrit dans le ticket bloque le fonctionnement normal du système.
- **p:haut**
- **p:normal**
- **p:bas**


### Outils [o] (#c7def8)

Permet d'indiquer le principal outil concerné par le ticket :
- **o:geonature** : l'application GeoNature dans son ensemble (https://expert.silene.eu)
  - **o:gn:accueil** : le module "Accueil" de GeoNature
  - **o:gn:meta** : le module "Métadonnées" de GeoNature
  - **o:gn:synthese** : le module "Synthèse" de GeoNature
  - **o:gn:occtax** : le module "OccTax" de GeoNature
  - **o:gn:validation** : le module "validation" de GeoNature
  - **o:gn:export** : le module "export" de GeoNature
- **o:atlas** : l'application Atlas de GeoNature (https://nature.silene.eu)
- **o:usershub** : l'application Usershub (https://usershub.silene.eu)
- **o:taxhub** : l'application Taxhub (https://taxhub.silene.eu)
- **o:cms** : le CMS Wordpress (https://cms.silene.eu)


### Info [i]

Permet d'ajouter des informations complémentaires au ticket.  
Non utilisé pour l'instant.

### Status [s]

Permet d'indiquer l'état d'un ticket à un moment donné.
Les labels disponibles sont :
- **s:en-cours** : le ticket est en cours de traitement.
- **s:complement** : le ticket nécessite un complément d'information pour être traité.
- **s:discussion** : le ticket nécessite un choix qui doit être discuté.

### Type [t] (#bfe5bf)

Permet d'indiquer le type de ticket.
Les lables disponibles sont :
- **t:bug**
- **t:fonctionnalite**
- **t:idee**
- **t:amelioration**
- **t:question**
- **t:support**
- **t:tache**

## Gestion des Milestones

Nous utiliserons 3 types de millestones ouvertes au maximum en parallèles :

- **En cours** : ce qui est en cours de traitement. Lorsque la millestones est complétée, elle est fermée. Une nouvelle peut alors être ouverte est alimenté par des tickets de la millestones "*Prochainement*".
- **Prochainement** : cette millestones ne sera jamais fermée. Elle contient tous les tickets à traiter utlérieurement.
- **Non traités** : cette millestones ne sera jamais fermée. Elle contient tous les tickets de type idée ou qui n'ont pas vocation a être traité.


## Sources
[How to manage a project using Github](http://blog.zot24.com/how-to-manage-a-project-using-github/)
