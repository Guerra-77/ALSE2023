# ALSE2023
Cambio 1
~~~~~
Creacion ssh:
$ ssh-keygen -t ed25519 -C "your_email@example.com"
Generating public/private ALGORITHM key pair

start the ssh-agent in the background
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519
