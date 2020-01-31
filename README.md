# demo_snake
Une demo de snake

Elle évoluera en fonction de mon apprentissage.
Voici la liste des actions qui y seront faites :

- Faire l'aire de Jeu. Utiliser Canvas ?
        source => <canvas></canvas>,  getContext() 
        https://developer.mozilla.org/fr/docs/Tutoriel_canvas/Utilisation_de_base

- Le Snake sera un tableau. Il mangera des bonbon (des divs). Dès qu'un bonbon sera mangé, la tableau aura une "tableau.push()" en plus (+1). Il se verra affiché avec une div ou pixel en plus.

- Faire un bouton " Start " qui mettra le snack en route.

- Définir ou trouve la valeur que renvoit les touches : Haut, Bas,Gauche, Droite.
        source = > document.onkeydown = logKey;
        https://developer.mozilla.org/en-US/docs/Web/API/Document/keydown_event

- Rendre dynamique la première partie du Snake.
        source => window.cancelAnimationFrame(). => Pour effet d'arreter l'animation...
         https://developer.mozilla.org/en-US/docs/Web/API/window/requestAnimationFrame

- Trâmes envisageable => 1 - Le snake est lançé.
                         2 - Le programme détécte une touche pressée et enregistre cette valeur.
                         3 - Il arrête le mouvement et donne comme nouvelle valeur de direction, la valeur enregistrée en étape 2. 
                             200px => 199pw => 198 px ...ect ect
                               
        
       
