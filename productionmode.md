# Instalar a aplicação em modo de produção em um servidor na nuvem!

### Tutorial de implementação no Heroku
https://www.youtube.com/watch?v=B8IrK2H9WkM

### Repositório configurado para deploy no Heroku
https://github.com/carromeu/fundamentus

### Repositório com modificações consideráveis 
https://github.com/felipemarkson/fundamentus

https://github.com/AdilsonAngelo/fundamentus

# Instalar em servidor da Heroku

Use essa versão,já atualizada e preparada para o Heroku:
https://github.com/carromeu/fundamentus

Video ensinando o processo:
https://www.youtube.com/watch?v=B8IrK2H9WkM&feature=youtu.be

Entre no Heroku crie um novo app.

Se conecte ao heroku,usando o CLI deles ou de outra forma descrita no site deles.

Vou usar o CLI deles.

heroku login

Inicie o git:

git init

Linkar o git ao seu repositório

heroku git:remote -a NOME-DA-APLICAÇAO

No meu caso:

heroku git:remote -a meu-app-fundaments

Agora adicione no Git:

git add .

Faça o primeiro commit:

git commit -m "frist commit"

Envie tudo e finalize o processo:

git push heroku master

Após esse processo se tudo estiver certo o Heroku irá começar a instalação e configuração do aplicativo:

Se tudo der certo você terá um retorno confirmando o processo com sucesso
e informando o link para acesso








# Instalar em servidor ubuntu 18.4 na AWS

 apt install python3-pip
 
 pip3 install -r required.txt
 
 python3 server.py   

