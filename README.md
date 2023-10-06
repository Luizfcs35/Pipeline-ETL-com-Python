
# Explorando IA Generativa em um Pipeline de ETL com Python

Projeto Desenvolvido com o Objetivo em tornar o processo de atualização de `status` de uma lista de usuários automatizada.

Construímos um pipeline ETL eficaz, começando com a simples extração de IDs de usuários de uma planilha, seguindo para uma transformação inovadora com a IA do GPT-4 da OpenAI, no projeto desenvolvido usei o `gpt-3.5-turbo` e culminando no carregamento desses dados utilizaremos a API criada no bootcamp 'Santander Dev Week 2023'.

### Extract:

- Foi extraido os IDs de uma lista `csv` de clientes, Através do consumo de uma API , foi acessado informações detalhadas de cada cliente, tendo como referência os identificadores listados no arquivo csv.

### Transform:

- Foi utilizada a API do **ChatGPT** da **OpenAI** para elaborar mensagens de marketing altamente personalizadas para cada cliente. 
O objetivo principal é ressaltar a importancia em manter uma boa estratégia financeira para os negócios e gerenciar seu patrimônio.

### Load: 

- Para o carregamento das `Mensagens` de cada cliente na API, foi utilizada uma função com o objetivo de criar uma mensagem personalizada e organizada conforme cada requisição segundo a lista.

## Conclusão

A importância em manter um sistema de informações ricas e inteligentes de maneira dinâmica usando a `IA`, explorando diversas formas neste contexto, Traz uma imensa idéia de possiblidades e desafios na **Ciencia de Dados.**
