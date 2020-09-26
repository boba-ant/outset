# outset
Nous considérons un système d’information composé deux entités Cours, Semestre.
Nous considérons qu’un cours est donné par un nom et une description. Chaque cours est associé
à un unique semestre. Notre entité Semestre a deux attributs : nom de la formation et nom du semestre.
Cet entraînement permet une manipulation des relations entre différentes Entités ( OneToMany, ManyToOne, OneToOne, ManyToMany) 
Pour avoir le format Markdown:
-installer avec le composer notre Markdown avec la commande :
composer require cebe/markdown
Ensuite modifier la Classe Controller pour rajouter un parser de type Markdown, mais surtout préciser le nouveau service
dans notre dossier config/dans le fichier services.yaml qui est aussi une Classe
