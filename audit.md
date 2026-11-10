## Audits des choses qui ne vont pas

Il n'y a pas de .gitignore dans lequel devtrait se trouver des ficher comme .env et .depot

Il faut en créer un


Il n'y a pas de fichier README avec des instructions de lancement.

Il faut en créer un


## Si le dépot avait déjà été public

Il aurait fallu changer les lien API et autres données contenues dans le .env car il n'y avait aucun .gitignore


Défaut	                                                        Où	                        Pourquoi c’est un problème

target/Panier.class commité	                                    commit « fix 2 »	        sortie de compilation, non versionnable
src/Panier.java.bak	                                            commit « fix 2 »	        copie de sauvegarde qui double le code source
Messages init, modifs, fix, final VRAI, ça marche ???, wip	    tout l’historique	        on ne sait pas ce que chaque commit change
Deux identités pour le même développeur	                        Marc Durand et m.durand	    git shortlog -sne compte deux personnes
Branche morte test-marc	                                        un commit wip	            branche oubliée
Deux branches sur la même ligne	                                nouvelle-tva, arrondi	    conflit à venir
