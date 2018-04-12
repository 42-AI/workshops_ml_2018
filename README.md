# ateliers-ml

## Installation de python et de ses modules

Nous utiliserons Anaconda, qui permet de préinstaller tous les modules de data science de Python. Vous devrez installer Anaconda le sgoinfre. Pour ce faire:

  -Allez dans le sgoinfre et créez un dossier au nom de votre login, avec le chmod en 700:

    cd /sgoinfre/goinfre/Perso
    mkdir VOTRE_LOGIN
    chmod 700 VOTRE_LOGIN

  -Allez dans le dossier créé et téléchargez-y Anaconda

    cd VOTRE_LOGIN
    curl -o anaconda3.sh https://repo.continuum.io/archive/Anaconda3-5.0.1-MacOSX-x86_64.sh
    sh anaconda3.sh
  
  -ATTENTION!! Durant l'exécution du script d'installation, il faut indiquer le chemin d'installation approprié

    /sgoinfre/goinfre/Perso/VOTRE_LOGIN/anaconda3

  -Dans votre fichier .zshrc (ou alternative), ajoutez la ligne suivante:

    export PATH="/sgoinfre/goinfre/Perso/VOTRE_LOGIN/anaconda3/bin:$PATH"

  -Réinitialisez votre terminal

    $> source ~/.zshrc

  -Vérifiez que l'opération a bien été effectuée

    $> which python
    /sgoinfre/goinfre/Perso/VOTRE_LOGIN/anaconda3/bin/python
