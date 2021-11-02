
# Comandos Git 

## Gerar a chave SSH

 - Criar SSH na Máquina: ssh-keygen -t rsa -b 4096 -C
   "analurandis@hotmail.com.br"
 - Criar um agente: $ eval $(ssh-agent -s)
 -  Adicionar a chave ao agente ssh-add ~/.ssh/id_rsa
 -  Copiando a chave: clip < ~/.ssh/id_rsa.pub
 - Com a chave criada adicione no GitHub:https://github.com/settings/keys


**1. Git Clone**
Comando usado para criar uma cópia do repositório desejado na pasta de destino
- git clone [urldoreposito] 
- git clone [urldorepositorio] [nomedapasta]
- git clone git@github.com:analurandis/dio-github.git

**2. Git add**
Comando usado para adicionar os arquivos, pastas a base do commit
- git add . Adiciona todos os arquivos modificados incluidos
- git add PASTA Adiciona todos os arquivos de uma pasta específica 

**3. Git Commit**
Comando utilizado para efetivar o commit no repositório local
- git commit - m "Mensagem da descrição do commit"

**4. Git Push**
comando utilizado para enviar os commits para o repositório online
- git push

**5. Git Pull**
Comando utilizado para atualizar os arquivos e repositório online para o local

- git pull