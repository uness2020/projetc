# projetc
 Houmine Nada Youness Fangari
les fonctions utilisee dan ce projet 
1: fonction pour saisir un nom:
la fonction prend un pointeur vers un tableau de characteres en parametre, elle affiche un message, ensuite la fonction fgets est pour lire l entree de lutilisateur, et aussi supprime le caractere de nouvelle lign(en remplacent ce caractere par un caractere null)
2: fonction dajout dun produit:
cette fonction prend en parametre un pointeur vers une structure "produitlist" apelee "list" est une structure"product" appelee"product", if(liste->cont<Max)=verification si la liste est <Max,
liste->products[liste->count++)=produit ,si cest le cas la fonction ajoute le produit a la liste en utilisant "count" pour determiner la position ou le produit doit etre ajouter.
3:la fonction afficher la liste: cette fonction prend en parametre un structure, elle affiche  le [titre] et puis  les details [de chaque produit dans un format tableaux] chaque colone presente un attribut du produit .
4: fonction de sauvegarder :
cette fonction prend en parametre une structure , FILE*file = fopen( file name,"w") = utilisee pur ouvrir un fichier dans le but d ecrire , FILE*file est pour declarer un pointeur de type file nomee file et fopen prend deux arguments :filename une chaine de caracteres qui presente le nom du fichier et le deuxsieme  w est un mode douverture signifie que le fichier  sera ouvert en mode ecriture.
5:foction pour la recherche  d un produit par nom :
cette fonction affiche  les produits correspandants par le nom " if (strcmp(list.products[i].name, productName) == 0)" verifie si le nom de produit dans la liste correspandant au nom donnee
"strcmp" compare les nom deux chaines de caracteres est retune 0 si sont identique donc la fonction sera vrai. ET LA MAIME CHOSE POUR LA FONCTION DE RECHERCHE PAR NOM DUTILISATEUR.
6: FOCTION DE COMPARAISON :
cette fontion prends deux pointeurs vers des structures de produit(a et b) et les convertit en pointeurs de type "const struct product",(prod a->name et prod b->name): si les noms sont identiques la fonction return 0 , si a<b elle return valeur negative et si le contraire elle returne une valeur positive, cela permet de trier  les produits par ordre alphabetiques de leur nom . ET meme chose piour la fonction de comparaisont prix unitaire.
7:fonction de tri:
cette fonction utilise la fonction [qsort"fonction de tri rapide en c": pour effectuer le tri ],qsort prend les parametres suivant: liste->count: le nbr delements de tableau ,liste-> products: un pointeur vers le tableau de produit , sizeof est la taille de chaque element , compare by name est la fonction de comparaion oar nom 
