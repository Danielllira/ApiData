# Projeto - Fase 1

Criei este documento com o objetivo de explicar o processo de desenvolvimento relatar algumas dificuldades no caminho e principalmente, te guiar a como rodar esse projeto com sucesso

## Passo a passo de como rodar o projeto

### Inicializar Ambiente Virtual

A primeira parte é a inicializaçao da nossa api, para isso, é preciso ativar o ambiente virtual, nele foi instalado algumas das libs utilizadas nesse projeto; São elas:

flask==2.0.3
flask-restful==0.3.9
werkzeug==2.0.3

Para iniciar o ambiente virtual escreva no terminal:

Para MacOS/Linux:
source env/bin/activate

Para Windows:
env\Scripts\activate

### Executar a API

Para executar a nossa api, é necessario navegar até o nossa pasta 'api' usando o comando **cd api** (verifique se você já no diretorio do projeto, use **pwd**) e após isso, execute o script usando python **api_fase01.py**

Para verificar se foi executado com sucesso, vá até o endereço local http://localhost:5001/country

Os dados devem estar presentes em formato json

### Coleta desses dados

Para seguir para a fase de coleta desses dados, abrimos um novo terminal para que a nossa api continue rodando no terminal atual.

Nesse novo terminal podemos seguir para o nosos notebook **script.ipynb** e seguir o flow

Observação: Eu não instalei o pandas e request no ambiente virtual pois o arquivo estava muito grande, e o maximo permitido na entrega é 40mb, então por gentileza, siga a instrução no notebook para a instalação dessas libraries.

Obrigado
