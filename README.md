palette
=======

Installer votre distrib xBuntu grâce à un Buntufile !

Le formalisme du Buntufile est inspiré du Berksfile :  http://berkshelf.com/ et
du Gemfile http://bundler.io/ mais dans les virgules :

    source 'clef' 'dépôt'
    deb curl
    deb docker.io 0.8

## Installation
Avant d'installer **palette** vous devez installer **ShellFactory** :
https://github.com/cchaudier/shellfactory

Pour installer **palette**:

    git clone git://github.com/artisanslogiciel/palette.git 

Puis modifier votre profile (~/.bash_profile, ~/.bashrc, ~/.zshrc etc.) avec la ligne suivante :

    export PATH=$PATH:$HOME/palette
