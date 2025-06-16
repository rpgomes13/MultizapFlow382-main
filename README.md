whaticket22-Flowbuilder 3.8.2

sudo apt-get update && sudo apt-get upgrade -y && reboot


adduser deploy

Insira a senha
2151014

Repita a senha
2151014

adduser deploy sudo

APERTAR O ENTER

APERTAR O ENTER

APERTAR O ENTER

APERTAR O ENTER

APERTAR O ENTER

Y

cd /home

apt install git && git clone https://github.com/rpgomes13/MultizapFlow382-main.git

User do Github: rpgomes13

Token do Github: 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

cd /home/MultizapFlow382-main

chmod +x instalar_primaria instalar_nova_instancia && ./instalar_primaria

0

DIGITE a senha DEPLOY
2151014

empresa01

999

999

DIGITE O SITE PARA O FRONTEND
https://QUALQUER-NOME.SEUDOMINIO.com.br

DIGITE O SITE PARA O BACKEND
https://QUALQUER-NOME.SEUDOMINIO.com.br

3001

4001

5001

--------------------------------------------------------------

INSTALAÇÃO FINALIZADA APÓS GERAÇÃO DOS CERTIFICADO SSL
--------------------------------------------------------------------------

COMANDO PARA BUILDAR O BACKEND

cd /home/deploy/empresa01/backend && npm install && npm run build

sudo su deploy 
pm2 restart all 

--------------------------------------------------------------------

COMANDO PARA BUILDAR O FRONTEND

cd /home/deploy/empresa01/frontend && npm i --f && npm run build


###############################################################################################
