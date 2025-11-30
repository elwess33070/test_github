** Wissem Mihoub : MI2B

** Projet : Application CRUD pour la gestion des étudiants - Ajouter, modifier, supprimer et consulter des fiches étudiants. Données sauvegardées localement. Tri, recherche et filtres. Animations CSS. Travail sur DOM et persistance locale.

- Ce premier commit introduit la structure de base de la page web en HTML, avec une organisation claire des sections, une répartition cohérente des classes et des identifiants, ainsi qu’une nomination logique de l’ensemble des attributs. Les principales difficultés rencontrées ont été de définir la meilleure structure possible pour organiser la page et de nommer correctement tous les attributs afin de garantir une architecture propre, maintenable et prête pour les prochaines étapes du développement.

-2 ème commit : L’ajout du style a permis d’unifier toute la page avec une interface moderne, sombre et cohérente, comprenant la mise en forme des boutons, tableaux, modales et zones interactives. Une petite animation « fade-in » a été intégrée pour rendre l’apparition des éléments plus fluide et agréable visuellement. Un système de responsive design a également été ajouté pour adapter automatiquement l’interface aux écrans plus petits, notamment en ajustant la largeur de la modale, la réorganisation des contrôles et l’adaptation de la barre de recherche en pleine largeur sur mobile.
La principale difficulté rencontrée a été de trouver un style adéquat qui reste à la fois esthétique, lisible et compatible avec tous les éléments de l’application.

-3ème commit : declaration de toutes les constantes pour js et initialisation des fonctions.

- 4ème commit : Ajout des fonctions render et openModal.

- 5ème commit : fin du projet. 

Le principal défi a été d’identifier une interface optimale : un design clair, moderne et intuitif, capable de faciliter la gestion des étudiants tout en conservant une cohérence entre mobile et desktop. Le projet a également été l’occasion de découvrir les notions de UI/UX et de comprendre leur rôle essentiel dans la création d’expériences fluides et agréables pour l’utilisateur. La sauvegarde locale a été assurée via une interaction directe avec le DOM : chaque modification du tableau (ajout, suppression, édition) met à jour la structure JavaScript, ensuite enregistrée dans le localStorage afin de restaurer automatiquement les données au rechargement de la page, sans recours à un serveur externe.