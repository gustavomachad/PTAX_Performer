# Performer – PTAX

Processo responsável por consumir os itens da fila gerada pelo Dispatcher e registrar os dados em um arquivo CSV localizado na pasta `Output` do projeto.  
Cada execução adiciona uma nova linha ao arquivo, contendo data, moeda, cotação de compra, cotação de venda e a origem da informação.

## Requisitos
- UiPath Studio / Assistant
- Conexão com Orchestrator e fila criada
- Pasta `Output` na raiz do projeto

## Execução
1. Rodar primeiro o Dispatcher
2. Em seguida, rodar o Performer
3. Verificar o arquivo `PTAX_Cotacoes.csv` gerado em `/Output`
