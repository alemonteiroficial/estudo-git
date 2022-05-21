# Repositorio de estudo-git

Repositorio para aprender os primeiros passos de comandos GIT


Fala Galera, considerando que você já tem o git instalado. 

Primeiro crie seu repositório. 

Clique no símbolo de + no topo da tela e depois em New Repository. Preencha um nome e uma descrição para o projeto e clique em Create repository.

Com seu repositório criado no github, agora vamos subir seus arquivos pra lá.

Navegue até a pasta do seu repositório local e dentro dela use o comando:

git init

isso vai transformar a sua pasta em um projeto git, nada será altarado na pasta.

Agora vamos linkar seu projeto com o seu repositório no github, pra isso você vai usar o comando git remote add origin https://github.com/user/repo.git. 

Use o link do seu projeto criado em New Repository.

Agora vamos subir os arquivos para Github. 

Use o comando:
git add .
para adicionar todos os arquivos do projeto. Crie um commit inicial com o comando:
git commit -m "primeiro commit" 
complete a sequencia solicitando o upload para sua branch master com o comando:
push git push origin master.

Espero ter ajudado,

