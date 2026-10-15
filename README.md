# UNO MÁS

Démo jouable d'un UNO vertical pour smartphone, de 2 à 6 joueurs.

- `docs/index.html` : le jeu complet (une seule page, sans serveur à maintenir).
- Les coups transitent par le relais public gratuit [ntfy.sh](https://ntfy.sh) (HTTPS, sans compte), ce qui marche en Wi-Fi comme en 4G.

## Jouer

Une fois GitHub Pages activé (Settings → Pages → branche `main`, dossier `/docs`), le jeu est à l'adresse
`https://saturday92.github.io/UNO-MAS/`. Aucun compte n'est nécessaire :

1. L'hôte ouvre la page et appuie sur « Créer une partie en ligne ».
2. Il envoie le lien d'invitation (ou le code de 4 lettres) aux autres joueurs, jusqu'à 5.
3. Chaque joueur ouvre le lien, l'hôte l'accepte, puis le joueur appuie sur « Je suis prêt ».
4. L'hôte appuie sur « Lancer la partie » quand tout le monde est prêt.

Le mode « Sur ce téléphone » (2 à 6 joueurs) marche sans réseau.

## Règles maison

- Sur un +2 : contre avec un +2. Sur un +4 : contre avec un +4. Pas de +4 sur un +2 ni de +2 sur un +4. Celui qui ne peut plus contrer pioche tout.
- Carte piochée jouable : on peut la poser tout de suite, sinon le tour passe.
- Interdit de finir sur une carte spéciale : on la pose, mais on pioche 1.
- Plusieurs Inversions se posent d'un coup.
- Plusieurs cartes du même chiffre (couleurs identiques ou non) se posent d'un coup dès que l'une est jouable.
- On peut toujours piocher, même avec une carte jouable.
- Si quelqu'un pioche alors qu'il avait une carte jouable, n'importe quel autre joueur peut l'accuser tant qu'il n'a pas rejoué : +2 pour lui. Fausse accusation : l'accusateur pioche 2.
- Le téléphone vibre quand c'est ton tour (en ligne). Aucune vibration quand quelqu'un tombe à une carte, il faut le repérer soi-même (Android ; l'iPhone ne gère pas la vibration).
- À 2 joueurs, Passe et Inversion font rejouer. À 3 ou plus, Passe fait sauter le suivant et Inversion change le sens.
