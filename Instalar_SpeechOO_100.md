# Instalação do SpeechOO no Linux #

## Passo 1 ##
Instale as dependências necessárias para rodar o projeto. Podem ser instaladas pelo terminal nos Ubuntus com o comando abaixo:

sudo apt-get install libpulse-dev flex sox

## Passo 2 ##

Baixe os arquivos para reconhecimento neste link: http://www.laps.ufpa.br/falabrasil/files/coruja_for_speechoo-1.0.0.tar.gz

Extraia o arquivo **coruja\_for\_speechoo-1.0.0.tar.gz** que você baixou para a sua home(por exemplo, /home/fulano).

**Obs**:Uma pasta chamada **coruja\_jlapsapi** será criada na sua home após a extração.

**Obs**:O arquivo **speech.properties** também será gerado na sua home automaticamente na primeira execução do SpeechOO

## Passo 3 ##

Após baixar o arquivo SpeechOO-1.0.0.oxt nesta mesma página na aba **Downloads**, clique duas vezes sobre o arquivo para instalá-lo, espere o plugin ser adicionado para então fechar a janela. Em seguida, reinicie o libreoffice e ele estará pronto para o uso clicando no microfone no topo da tela.

## Executando o SpeechOO pela linha de comando ##

Para executar o SpeechOO pela linha de comando, é necessário digitar no terminal o seguinte comando "libreoffice3.6 --writer" (podendo variar em 3.5, 3.4, dependendo da versão instalada no seu sistema) e quando aparecer a tela do writer apenas clique no microfone no topo da tela como foi descrito no passo 2.