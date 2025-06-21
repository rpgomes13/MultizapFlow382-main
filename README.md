dpkg-reconfigure tzdata

sudo apt-get update && sudo apt-get upgrade -y && reboot
adduser deploy
Insira a senha 2151014
Repita a senha 2151014
adduser deploy sudo
APERTAR O ENTER
APERTAR O ENTER
APERTAR O ENTER
APERTAR O ENTER
APERTAR O ENTER
Y
cd /home
apt install git && git clone  https://github.com/rpgomes13/MultizapFlow382-main.git
User do Github: rpgomes13
Token do Github: 
cd /home/MultizapFlow382-main
chmod +x instalar_primaria instalar_nova_instancia && ./instalar_primaria
0
DIGITE a senha DEPLOY 2151014
empresa01
999
999
DIGITE O SITE PARA O FRONTEND https://QUALQUER-NOME.SEUDOMINIO.com.br
DIGITE O SITE PARA O BACKEND https://QUALQUER-NOME.SEUDOMINIO.com.br
3001
4001
5001

INSTALAÇÃO FINALIZADA APÓS GERAÇÃO DOS CERTIFICADO SSL
COMANDO PARA BUILDAR O BACKEND
cd /home/deploy/empresa01/backend && npm install && npm run build
sudo su deploy pm2 restart all

COMANDO PARA BUILDAR O FRONTEND
cd /home/deploy/empresa01/frontend && npm i --f && npm run build
###############################################################################################

PERSONALIZAÇÃO - LINECHAT

TROCAR NOME APP MÓVEL

frontend/public/manifest.json

Troque pelo nome da sua empresa

linhas: 2 e 3

------------------------------------------

LOGO DA TELA DE LOGIN 

frontend/public
logo.png

------------------------------------------

PERSONALIZAÇÃO INTERNA
----------------------
frontend\src\pages\Login/index

TROCAR CAPA DO SISTEMA
Linha: 24 (link do arquivo)
Modelo 1 - https://i.ibb.co/bjWb8wtF/20250619-1156-Chatbot-no-Futuro-Digital-remix-01jy4azzb1fhfr62wpj150st74.png

Modelo 2 - https://i.ibb.co/9mrhK8xN/20250619-1156-Chatbot-no-Futuro-Digital-remix-01jy4azzb0fnqsfbcs1d0a9sex.png


TROCAR NÚMERO WHATSAPP TELA INICIAL
Linha:295

TROCAR ÍCONE DO WHATSAPP
Linha: 298 - https://i.ibb.co/rRckh8MF/favicon-256x256.png



Comando no TERMINAL

cd /home/deploy/empresa01/frontend && npm i --f && npm run build

----------------------------------------
PRONTO FINALIZADO!




