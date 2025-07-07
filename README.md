Ce dépôt contient un simple jeu de casse-briques en html5/Javascript
Ce code est trouvé sur https://github.com/end3r/Gamedev-Canvas-workshop/blob/gh-pages/lesson10.html, l'objectif de ce dépôt était d'utiliser git et github, 
pour ensuite etudier le script et comment fonctionne-t-il
voici le détail de plusieurs fonctions utilisés dans le script:


document.getElementById("myCanvas")
Permet d'accéder à un élément HTML par son id. Ici, il récupère le <canvas> pour dessiner dessus avec JavaScript.


ctx.arc(x, y, radius, startAngle, endAngle)
Fonction du contexte 2D du canvas qui trace un cercle (ou un arc). Elle est utilisée ici pour dessiner la balle.


ctx.clearRect(x, y, width, height)
Efface la zone spécifiée du canvas. Elle est utilisée à chaque frame pour ne pas laisser de traces derrière la balle ou les briques.


requestAnimationFrame(draw)
Fonction qui demande au navigateur de redessiner à la prochaine frame. Elle permet d’animer le jeu de façon fluide et optimisée.
