# UNO MÁS

Démo jouable d'un UNO vertical pour smartphone, à 2 joueurs.

- `docs/index.html` : le jeu complet (une seule page, sans serveur à maintenir).
- Les coups transitent par le relais public gratuit [ntfy.sh](https://ntfy.sh) (HTTPS, sans compte), ce qui marche en Wi-Fi comme en 4G.

## Jouer

Une fois GitHub Pages activé (Settings → Pages → branche `main`, dossier `/docs`), le jeu est à l'adresse
`https://saturday92.github.io/UNO-MAS/`. Aucun compte n'est nécessaire :

1. Le joueur 1 ouvre la page et appuie sur « Créer une partie en ligne ».
2. Il envoie le lien d'invitation (ou le code de 4 lettres) au joueur 2.
3. Le joueur 2 ouvre le lien : la partie démarre sur les deux téléphones.

Le mode « Jouer à 2 sur ce téléphone » marche sans réseau.

## Règles maison

- Sur un +2 : contre avec un +2 ou un +4. Sur un +4 : contre avec un +4. Celui qui ne peut plus contrer pioche tout.
- Carte piochée jouable : on peut la poser tout de suite, sinon le tour passe.
- Interdit de finir sur une carte spéciale : on la pose, mais on pioche 1.
- Plusieurs Inversions se posent d'un coup.
- Plusieurs cartes du même chiffre (couleurs identiques ou non) se posent d'un coup dès que l'une est jouable.
- On peut toujours piocher, même avec une carte jouable.
- Si quelqu'un pioche alors qu'il avait une carte jouable, l'adversaire peut l'accuser tant qu'il n'a pas rejoué : +2 pour lui. Fausse accusation : l'accusateur pioche 2.
- Le téléphone vibre quand c'est ton tour (en ligne) et chez les deux joueurs quand quelqu'un tombe à une carte (Android ; l'iPhone ne gère pas la vibration).
- À 2 joueurs, Passe et Inversion font rejouer.
