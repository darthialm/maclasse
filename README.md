# Ma classe — suivi du comportement en classe

Outil pour tablette ou téléphone : en deux touches, tu notes une remarque ou un point positif. L'outil te dit quand un palier est atteint, et c'est toi qui fais la saisie sur École Directe.

## Ce que fait l'outil
- **Salles libres** : tu pars d'un modèle (rangées, îlots, en U, ou salle vide), puis tu fais glisser chaque table et le bureau où tu veux. Touche une table pour changer son nombre de places, la tourner, la dupliquer ou la supprimer. Deux tables ne peuvent pas se chevaucher.
- **Placer les élèves** : ✏️ Modifier le plan → « Placer les élèves ». La liste des élèves est à côté du plan : glisse un prénom sur une place, d'une place à une autre pour échanger deux élèves, ou dans la liste pour le retirer. Le placement automatique met les élèves avec aménagements devant et sépare ceux qu'il faut séparer.
- **Bouger les tables depuis le cours** : ✏️ → « Bouger les tables ». Les élèves suivent leur table. Une salle sert à toutes tes classes, et chaque classe a son propre plan dans chaque salle.
- **Saisie** : tu touches un élève, puis un motif (remarques, positifs, faits graves), avec une précision facultative. Le bouton « Annuler » rattrape une erreur.
- **Motif d'abord, puis les élèves** : tous les motifs sont affichés au-dessus du plan. Touche un motif (il passe en bleu), puis chaque élève concerné : c'est noté à chaque fois, sans autre étape. « ✕ Arrêter » pour revenir à la saisie normale.
- **Jauge de classe** (🏆) : chaque point positif fait avancer la jauge de 1. Chaque remarque la fait reculer (½ point par défaut, réglable : 0, ½ ou 1). Tu peux ajouter des bonus pour toute la classe (＋1, ＋3). L'écran affiche l'objectif, la récompense et le ratio positifs / remarques, sans aucun prénom : il peut être projeté. Quand la jauge est pleine, « Récompense donnée » lance une nouvelle manche.
- **Enlever une remarque** : touche l'élève, puis « ✕ Enlever » dans la liste « Noté cette semaine ». Pour une remarque plus ancienne : « Voir sa fiche » → Historique → ✕. Un bouton « Annuler » permet de revenir en arrière.
- **Distribution des feuilles** : le bouton 📄 dans la barre du cours indique les 2 élèves qui distribuent aujourd'hui (ils ont aussi 📄 sur le plan). Ça tourne tout seul **une fois par jour**, par ordre alphabétique : au premier cours de la journée avec cette classe ; les autres cours du même jour gardent les mêmes élèves. Les jours sans cours et les vacances ne sautent personne. Touche le bouton pour remplacer un absent, choisir quelqu'un d'autre ou passer aux suivants tout de suite.
- **Paliers** (modifiables dans ⚙️) :
  - 3 remarques dans la semaine (remise à zéro le lundi) : **un travail en plus à chaque fois**, et selon le délai :
    - la 1re fois : seulement le travail en plus ;
    - si ça recommence **la semaine juste après** : **mise en garde** (+ travail en plus) ;
    - si ça recommence **plus tard**, ou après une mise en garde : **observation sur École Directe** (+ travail en plus). Ensuite, on repart de zéro.
  - Un fait grave : **observation à saisir sur École Directe** tout de suite.
  - Tout ce qu'il y a à faire est dans 📋 Suivi. La fiche de l'élève indique aussi ce qui arrivera s'il atteint le palier cette semaine.
  - 5 positifs en 14 jours : **encouragement à saisir**.
  - « ✔ Fait » / « ✔ Saisi » remet le compteur à zéro. « Copier le texte » prépare le texte à coller dans École Directe.
- **Aménagements** (fiche de l'élève) : tu choisis les motifs qui sont notés mais pas comptés. Le palier positif descend à 3, et l'outil te rappelle de valoriser l'élève. Ils n'apparaissent jamais sur la fiche parents. N'écris jamais de diagnostic.
- **Suivi de la classe** : qui reprendre, qui encourager, qui valoriser, les élèves « pas vus » depuis 14 jours, et l'équilibre entre positifs et remarques de la semaine.
- **Fiche parents** : uniquement l'élève concerné, avec les faits datés. Tu peux l'imprimer, l'enregistrer en PDF ou la montrer sur l'écran.

## Sécurité et RGPD
- **Tout reste sur l'appareil.** Rien n'est envoyé sur internet.
- Les données sont **chiffrées avec ton code**, que tu choisis à la première ouverture. Le **code de secours** affiché à ce moment-là sert si tu oublies ton code : note-le sur papier.
- **Code** : il n'est pas redemandé quand tu changes d'onglet ou d'appli. Il l'est seulement après 15 minutes sans utiliser l'outil (réglable de 2 min à la fin de la journée), si tu fermes l'onglet, ou quand tu touches 🔒.
- **🙈 Masquer** : cache l'écran derrière une horloge, sans code. Pour revenir, maintiens le doigt appuyé une seconde. Pratique quand un élève s'approche.
- Garde le verrouillage de ta tablette activé (code ou empreinte).
- **Sauvegarde** : 🔐 → « Sauvegarder maintenant ». Le fichier est chiffré : range-le sur ton ordinateur ou une clé USB. L'outil te le rappelle chaque semaine. Pense aussi à refaire une sauvegarde après avoir changé ton code.
- **Fin d'année** : 🔐 → « Effacer toutes les remarques ».

## Mettre en ligne (GitHub Pages)
1. Dans ton dépôt GitHub, crée un dossier `maclasse` (ou remplace les fichiers s'il existe déjà). Dans « Add file » → « Upload files », glisse **tous les fichiers** : `index.html`, `sw.js`, `manifest.webmanifest`, `icon.svg`, `icon-192.png`, `icon-512.png`.
2. Ouvre l'adresse de ton site suivie de `/maclasse/` sur la tablette.
3. Ajoute l'outil à l'écran d'accueil : bouton Partager → « Sur l'écran d'accueil » sur iPad, menu → « Ajouter à l'écran d'accueil » sur Android. Il marche ensuite sans internet.

Le code est public sur GitHub, mais les données ne sont jamais en ligne : elles restent chiffrées sur ta tablette.

Un collègue qui ouvre la même adresse sur son appareil a son propre outil, vide, avec son propre code.
