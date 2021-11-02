
# Comandos Git 

## Gerar a chave SSH
Criar SSH na Máquina: ssh-keygen -t rsa -b 4096 -C "analurandis@hotmail.com.br"
Criar um agente: $ eval $(ssh-agent -s)
ssh-add ~/.ssh/id_rsa
Copiando a chave: clip < ~/.ssh/id_rsa.pub
Com a chave criada adicione no GitHub:https://github.com/settings/keys




**1. Git Clone**
Comando usado para criar uma cópia do repositório desejado na pasta de destino
git clone [urldoreposito] 
git clone [urldorepositorio] [nomedapasta]
