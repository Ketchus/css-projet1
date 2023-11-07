# css-projet1
1. Header
    -----------------
  Pour faire le header, j'ai fait du css en utilisant 
  - display: flex;
  - justify-content: space-between;
  - align-items: center
    
    
2. Navbar
    -----------------
  Pour faire la barre de navigation, j'ai utilisé boostrap et css(pour que le design soit ressemblant, j'ai ajouter des couleurs, ajouter l'image en fond,... )
  - pour nav j'ai utilisé nav-justified
  - pour l'ul principale j'ai utilisé nav nav-pills nav-fill flex-column flex-md-row
  - pour les li de cet ul j'ai utilisé nav-item dropdown
  - pour les ul de ces li, j'ai utilisé dropdown-menu pour un menu déroulant
  - pour les li de l'ul dropdown-menu j'ai fait dropdown-item
    
3. UL entre nav et section
   -----------------
  Pour faire cette partie, j'ai utilisé boostrap et css(pour que le design soit ressemblant, j'ai ajouter les bonnes couleurs,enlever le style du lien,... )
  - pour cet ul j'ai utilisé list-inline
  - et pour ces li, jai fait list-inline-item
    
4. section
   -----------------
  Pour faire le main de section, j'ai utilisé uniquement du css pour le style et du grid pour disiver cette partie en tableau de 3 lignes et 3 colonnes répartie comme suit:
  - la main prend uneligne(la première) et 2 colonnes(les 2 première)
  - le aside prend 3 lignes et une colonne(la dernière)
    
5. Footer
   -----------------
  Et enfin pour le footer, j'ai utilisé boostrap et css(pour personalier le deseign pour que ce soit ressemblant: ajout de puces coloré aux liste, mettre un espaces entre les éléments,... )
  - pour l'ul principale j'ai utilisé list-inline et ajouter un padding-left de 50px
  - pour les li de cet ul j'ai utilisé list-inline-item
  - pour les ul de ces li, j'ai utilisé list-unstyled
  - pour chaque liens de cette liste(2 ème ul)
    
6. Responsive
   -----------------
   Globalement j'ai utiliser un @media juste pour aligner les éléments du header en une colonne, changer le display des div du main pour faire un alignement superposé pareillement pour section et les list-inline du footer sinon vu que
   bootsrap gère le responsive, je n'ai quasiment rien eu à faire.

