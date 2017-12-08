Creating a New Repo using hub

  Set up:

Add SSH public key to github
https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/

copy ~/.ssh/id_rsa.pub to github website




$mkdir /path/to/project

$cd /path/to/project

  initialize git

$ git init

  add files

$ cat < hello-world.py

#!/usr/bin/python

print('hello, world')

Ctrl-D

  add to staging

$ git add .

  commit

$ git commit -m "It begins."

  create new project on github with name of current directory

$ hub create -d "Title"

  push to remote

$ git push origin master

