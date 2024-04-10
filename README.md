# Site estatico cloudformation

 Este é um projeto que cria uma infraestrutura na aws para hospedagem de site estatico junto com uma pipeline que permite uma integração continua. 

##

Como funciona:

1. A partir do momento que é feito uma alteração na branch main deste repositório uma esteira de eventos (pipeline) começará a funcionar.

2. A pipeline irá fazer um download de todo o codigo da branch main, a qual foi configurada.

3. A pipeline em seguida vai enviar todo este codigo para um bucket configurado para hospedagem de sites estaticos



