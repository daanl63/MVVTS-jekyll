# Migration of MV & VTS sites to Jekyll Project - 17/9/2025

** HOW TO MAKE CHANGES **

Easiest way is in Github by using the online editor.

More advanced is using a CLI or VS configured to be able to connect to remote repository using ssh.

- On local machine:
  - make sure you have installed git & jekyll
  - in a new directory, create an empty repository:
    - ```git init```
    - set Git settings to connect to upstream (Github) repository:
    - ```git config remote.origin.url "git@github.com:daanl63/MVVTS-jekyll.git"```
    - you may need to have a ssh key to manipulate the remote repository -> connect the author
    - find out about the name of the right branch, e.g. in this case 'master' or a dev branch
    - clone the repo and cd to the clone'd repo
    - ```git clone https://github.com/daanl63/MVVTS-jekyll.git```
    - check status:
    - ```git status```
    - or check the config:
    - ``` git config -l```
    - if you do a ```git pull``` it should say ```Already up to date```
    - make some changes, e.g. edit ```index.html``` or other files
  
  
