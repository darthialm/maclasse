# Ma classe — suivi du comportement en classe

Outil pour tablette ou téléphone : en deux touches, tu notes une remarque ou un point positif. L'outil te dit quand un palier est atteint, et c'est toi qui fais la saisie sur École Directe.

## Ce que fait l'outil
- **Classes et salles** : plusieurs salles (rangées, îlots, en U), un plan par classe et par salle. Pour changer quelqu'un de place, tu glisses son prénom, ou tu touches un élève puis une place. Il y a aussi un placement automatique : élèves avec aménagements devant, élèves à séparer.
- **Saisie** : tu touches un élève, puis un motif (remarques, positifs, faits graves), avec une précision facultative. Le bouton « Annuler » rattrape une erreur.
- **Paliers** (modifiables dans ⚙️) :
  - 3 remarques dans la semaine, ou un fait grave : **observation à saisir sur École Directe**. Remise à zéro le lundi.
  - 5 positifs en 14 jours : **encouragement à saisir**.
  - « ✔ Saisi » remet le compteur à zéro. « Copier le texte » prépare le texte à coller dans École Directe.
- **Aménagements** (fiche de l'élève) : tu choisis les motifs qui sont notés mais pas comptés. Le palier positif descend à 3, et l'outil te rappelle de valoriser l'élève. Ils n'apparaissent jamais sur la fiche parents. N'écris jamais de diagnostic.
- **Suivi de la classe** : qui reprendre, qui encourager, qui valoriser, les élèves « pas vus » depuis 14 jours, et l'équilibre entre positifs et remarques de la semaine.
- **Fiche parents** : uniquement l'élève concerné, avec les faits datés. Tu peux l'imprimer, l'enregistrer en PDF ou la montrer sur l'écran.

## Sécurité et RGPD
- **Tout reste sur l'appareil.** Rien n'est envoyé sur internet.
- Les données sont **chiffrées avec ton code**, que tu choisis à la première ouverture. Le **code de secours** affiché à ce moment-là sert si tu oublies ton code : note-le sur papier.
- **Écran neutre** (une horloge) : il s'affiche avec 🔒, après 3 minutes sans toucher l'écran, et dès que tu changes d'appli.
- **Sauvegarde** : 🔐 → « Sauvegarder maintenant ». Le fichier est chiffré : range-le sur ton ordinateur ou une clé USB. L'outil te le rappelle chaque semaine. Pense aussi à refaire une sauvegarde après avoir changé ton code.
- **Fin d'année** : 🔐 → « Effacer toutes les remarques ».

## Mettre en ligne (GitHub Pages)
1. Dans ton dépôt GitHub, crée un dossier `maclasse`. Dans « Add file » → « Upload files », glisse **tous les fichiers** : `index.html`, `sw.js`, `manifest.webmanifest`, `icon.svg`, `icon-192.png`, `icon-512.png`.
2. Ouvre l'adresse de ton site suivie de `/maclasse/` sur la tablette.
3. Ajoute l'outil à l'écran d'accueil : bouton Partager → « Sur l'écran d'accueil » sur iPad, menu → « Ajouter à l'écran d'accueil » sur Android. Il marche ensuite sans internet.

Le code est public sur GitHub, mais les données ne sont jamais en ligne : elles restent chiffrées sur ta tablette.

Un collègue qui ouvre la même adresse sur son appareil a son propre outil, vide, avec son propre code.
