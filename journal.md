Tout  les    fichier de starter  serais   en  Working Directory  malgré   le repo git  initier  en sont  sein
donc
untracked/untracked

Réponse  réelle  après  git status
Untracked files:

&#x20; (use "git add <file>..." to include in what will be committed)

&#x20;       README.md

&#x20;       pom.xml

&#x20;       src/



nothing added to commit but untracked files present (use "git add" to track)



Après    modification  du  read me  il apparait  maintenant   deux   quand on  fais  git status

premièrement dans le standing  area Unmodified
et sa seconde apparition comme  dans  le  stating arée modified

Apres  le commit Ajoute README.md et le  reste  que le second  quand on fait  git status

apparition comme  dans  le  stating arée modified

oatti@Laptop-oreste MINGW64 \~/Downloads/inventaire/starter (main)

$ git log --oneline

c82b296 (HEAD -> main) Complète le README

8811a65 Ajoute le README

oatti@Laptop-oreste MINGW64 \~/Downloads/inventaire/starter (main)

$ git status

On branch main

nothing to commit, working tree clean



oatti@Laptop-oreste MINGW64 \~/Downloads/inventaire/starter (main)

$



oatti@Laptop-oreste MINGW64 \~/Downloads/inventaire/starter (main)

$ git ls-files --eol script.sh

i/none  w/none  attr/text eol=lf        script.sh



oatti@Laptop-oreste MINGW64 \~/Downloads/inventaire/starter (main)

$


non avec  git merge feature-a je n'attend pas  de  commit  de  fusion

puis que le  main  n'a pas  avancée


avance rapide,
   commit de fusion oui c'est ce que j'attend 


oatti@Laptop-oreste MINGW64 ~/Downloads/inventaire/merge-lab (main)
$ git push
To https://github.com/Etsero4next/demo-git-oreste.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/Etsero4next/demo-git-oreste.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. If you want to integrate the remote changes,
hint: use 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

oatti@Laptop-oreste MINGW64 ~/Downloads/inventaire/merge-lab (main)
$


