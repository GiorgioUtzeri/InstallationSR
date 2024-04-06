
# ReadMe : Utilisation des outils de compilation et informations complémentaires

Vous retrouverez ci-dessous les lignes de commande permettant la bonne conversion des fichiers avec l'outil pandoc pour les fichiers markdown. Ces commandes doivent être exécutées dans un terminal ayant comme répertoire courant le répertoire contenant le fichier `rendu.md`.

## Conversion du fichier Markdown en PDF

La conversion en PDF se fait à l'aide de la commande :

**pandoc -f markdown metadata.yaml rendu.md -t pdf -o rendu.pdf --template=monmodele.tex**

Pour la conversion du fichier en PDF, nous utilisons un modèle de styles LaTeX.

## Conversion du fichier en HTML

La conversion en HTML se fait à l'aide de la commande :

**pandoc -f markdown metadata.yaml images_html.md rendu.md -t html -o rendu.html --standalone --toc --toc-depth=5 --css template.css**

Pour la conversion du fichier en HTML, nous utilisons un modèle de styles CSS.

## Auteurs et informations complémentaires

Ce rapport a été rédigé par Mathys MULLIER et Giorgio UTZERI. Bien que Baptiste GUILLOU faisait partie du groupe au début de cette SAé, il a décidé de quitter le BUT Informatique à la fin de l'année et a donc signé une décharge pour alléger ses cours. Il n'a donc réellement pas fait partie de ce travail et le travail n'a été réalisé au final qu'à deux.