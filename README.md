# IMC-py
Calculando IMC com Python

(http://www.mariomedeiros.eti.br/artigos/index.php?article37/calculando-imc-com-python)

No dia 2016-10-07 publiquei um post sobre uma aplicação pequena em Java, que calcula o IMC.

Está neste link:

http://www.mariomedeiros.eti.br/artigos/index.php?article36/calculando-imc-com-java

Como eu havia mencionado no post do IMC-Java, eu não programo em java e nem sou muito amigo desta linguagem. Por que? Simples, não gosto de java. Reconheço que tem sua utilidades e funcionalidades, que resolve vários tipos de problemas, e até posso utilizar para situações específicas. Mas isso não faz com que eu passe a gostar de Java.

Para não ficar com esse código somente em Java, procurei uma linguagem que eu gosto, apesar de pouquíssimo conhecimento, para reescrever o código.

Pensei em fazer em shell script/bash, mas utilizei o Python para isso.

Vi que é portável entre Linux, Mac e ruwindows. Como fiz anteriormente em Java e testei no ruwindows, pensei em fazer também em uma linguagem que pudesse ter essa particularidade. Me lembrei do Python.

Então fui lendo, lembrando, aprendendo e ficou até que razoável e super simples, básico.

Escrito em Python 2.7.6 e em Linux, rodou certinho.

Já em ruwindows ……… (hahahahahahahahaha!!!!!!!)

Tentei rodar uma vez, e o treko deu erro de sintaxe e outros erros mais escabrosos que no meu nível intelectual e paciência com a plataforma M$, me fez simplesmente desistir de tentar mais de alguns minutos. Se alguém quiser pegar o código e ajustá-lo para que funcione no ruwindows, fique a vontade. Eu não vou fazer nenhuma tentativa para tal.

Rodou no Linux então está ótimo. Não rodou no ruwindows? Azar!!!

É para funcionar, é Linux. É para ter dor de cabeça, é ruwindows!!

Para rodar a aplicação é necessário ter o python instalado. Todas as distros já possuem por padrão, mas caso não tenha, instale pelo gerenciador de pacotes da sua distro.

No final deixei o link com o código fonte para rodar a aplicação.

Baixe o arquivo, descompacte em um diretório qualquer e no terminal digite no diretório onde descompactou o arquivo:

python IMC-Py.py

Coloque os valores de peso e altura conforme solicitado e no final será mostrado o resultado.

Bem simples e básico.

Roda em moto texto, mas é possível rodar em modo gráfico com botões e janelas, mas não estudei nem pesquisei muito sobre isso. Existem bibliotecas disponíveis que trabalham com Python tranquilamente. Mas vai ficar para uma outra oportunidade. Pelo pouco que vi, é um tanto mais detalhado do que eu esperava e então requer mais estudo por parte deste Klingon Velho para isso.

Outras forma de rodar o arquivo são:

1 – deixá-lo como arquivo executável utilizando chmod +x IMC-Py.py;

2 – como root colocá-lo em /usr/bin/ e atribuir chmod 777 IMC-Py.py e rodar de qualquer diretório. Em qualquer dos casos, pra ficar mais bunitinhu, mude o nome do arquivo para imc sem extensão, que ficará mais simples de chamar pelo terminal em qualquer diretório.

De qualquer forma acima mencionado, o arquivo vai rodar sem problemas.

Caso encontre algum bug ou erro, pode informar que tentarei corrigir. Se quiser corrigir e/ou melhorar a aplicação (sempre tem como melhorar, da mesma forma que sempre tem como piorar), fique a vontade para tal. Segue a filosofia OpenSource.

Pacote de Instalaçâo do script IMC-py

Aqui, no github, eu adicionei um arquivo .deb para distros Linux com base em Debian.
O nome do arquivo é imc_0.1.all.deb
Para instalar, acesse como root, e digite o comando dpkg -i imc_0.1.all.deb
Depois como usuário comum, é só digitar num terminal, imc
