 					WELCOME !

	This README compiles all the commands studied during the 'shell' projects.

				Shell, navigations :

man : Permet de visionner les contenus d'une documentation formatée pour être exploitable par 'man'.

pwd : Affiche le chemin absolu du répertoire de travail actuel.

ls : Liste les fichiers et répertoires dans le répertoire courant.

cd : Change le répertoire de travail courant.

less : Affiche le contenu d'un fichier page par page.

touch : Change les timestamps d'un fichier ou crée des fichiers vides.

cp : Copie des fichiers ou des répertoires.

mv : Déplace ou renomme des fichiers ou des répertoires.

rm : Supprime des fichiers ou des répertoires.

mkdir : Crée des répertoires.

rmdir : Supprime des répertoires vides.

				Shell, basics :

less : Utilitaire permettant de visualiser le contenu d'un fichier texte une page a la fois.

file : Permet de déterminer le type d'un fichier.

ln : Utilisé pour créer des liens (links) entre fichiers. Les liens peuvent être symboliques (symlinks) ou physiquehard links).

type : Affiche le type d'une commande dans le shell, indiquant si c'est une commande intégrée (builtin), un alias, une fonction ou un exécutab

which : Localise l'emplacement d'un exécutable en cherchant dans les répertoires listés dans la variable d'environnement PA

help : Fournit des informations sur les commandes intégrées (built-in) du shel

				Shell, permissions :

chmod : Modifie les permissions d'un fichier ou d'un répertoire.

sudo : Permet a un utilisateur autorisé d'exécuter une commande avec les privilèges d'un autre utilisateur (par défaut, l'utilisateur

su : Permet de changer d'utilisateur dans le shell courant.

chown : Modifie le propriétaire et/ou le groupe d'un fichier ou d'un répertoir

chgrp : Modifie le groupe d'un fichier ou d'un répertoire

id : Affiche les informations sur l'utilisateur et les groupes.

groups : Affiche les groupes auxquels appartient un utilisateur.

whoami : Affiche le nom d'utilisateur de l'utilisateur actuel.

adduser : Ajoute un nouvel utilisateur au système. Cette commande est souvent plus conviviale que userad.

useradd : Ajoute un nouvel utilisateur au système. Elle est souvent utilisée avec des options spécifiques pour définir les paramètres de l'utilisa

addgroup : Ajoute un nouveau groupe au système

				Shell, I/O Redirections and filters : 

echo : Affiche une ligne de texte dans le terminal.

cat : Affiche le contenu d'un ou plusieurs fichiers.

head : Affiche les premières lignes d'un fichier.

tail : Affiche les dernières lignes d'un fichier.

find : Recherche des fichiers dans un répertoire et ses sous-répertoires selon des critères spécifiq

wc : Compte les lignes, les mots et les caractères dans un fichier

sort : Trie les lignes d'un fichier texte.

uniq : Filtre les lignes répétées consécutivement dans un fichier, souvent utilisé a'sort'.

grep : Recherche des motifs dans un fichier.

tr : Traduit ou supprime des caractères.

rev : Renverse chaque ligne de l'entrée.

cut : Extrait des sections de chaque ligne d'un fichier.

passwd : Change le mot de passe d'un utilisateur.

				Shell, init files, variables and expansions :

printenv : Affiche les variables d'environnement et leurs valeurs.

set : Affiche ou définit des variables d'environnement et des options du shell

unset : Supprime des variables d'environnement ou des fonctions de shell.

export : Définit des variables d'environnement pour les rendre disponibles aux processus enfant.

alias : Crée ou affiche des alias de commandes.

unalias : Supprime des alias définis.

. : Exécute un script dans le shell courant.

source : Exécute un script dans le shell courant. Identiqe a la commande '.' 

printf : Formatte et affiche des données selon un format spécifi


