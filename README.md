# ALAN_FURQUIM_DDF_TECH_022025
Case técnico base da empresa Dadosfera

Documento criado para responder os itens propostos no arquivo enviado.

## Item 0 - Sobre Agilidade e Planejamento
Apresentação em vídeo disponível no [youtube](https://youtu.be/da4mnRyytIM).
<br>
Foi criado um kanban board utilizando [um quadro no Trello](https://trello.com/b/5Ulenlp0/case-tecnico) para melhor organização dos status das diferentes tarefas.

## Item 1 - Sobre a Base de Dados
Para selecionar a base de dados, além de verificar sua adequação à proposta, também garanti que fosse suficientemente completa para viabilizar o desenvolvimento das etapas seguintes.
A base de dados escolhida foi a [Brazilian E-Commerce Public Dataset](https://www.kaggle.com/datasets/jayeshsalunke101/brazilian-ecommerce-public-dataset?select=olist_order_items_dataset.csv), do kaggle.<br>
Nesse dataset temos diversas tabelas diferentes, como apresentado na imagem a seguir. Cada uma delas tem diferentes informações sobre produtos, venda, vendedor, pagamento e reviews.
![alt text](imgs/tds_bases.png)
<br><br>
Para o desenvolvimento do case, foram selecionadas apenas 4 das 8 bases disponíveis, pois já continham dados suficientes para a execução dos itens necessários. As bases escolhidas abrangem informações sobre produtos, pedidos e reviews, conforme ilustrado na imagem abaixo.
![alt text](imgs/bases.png)
<br><br>
Para unificar todos os dados em uma única tabela, foi utilizado um [notebook](/notebooks/concat_bases.ipynb), que carrega os diferentes dataframes e realiza a junção entre eles utilizando a biblioteca Pandas.
<br><br>

## Item 2.1 - Sobre a Dadosfera - Integrar
Com os dados devidamente selecionados, o arquivo foi enviado para a plataforma Dadosfera. O dataset está disponível no seguinte [link](https://app.dadosfera.ai/pt-BR/catalog/data-assets/aeeaf646-2a8a-4a97-903f-138582a1c5ac).
<br><br>

## Item  3 - Sobre a Dadosfera - Explorar
Nesta etapa, foram adicionadas tags à tabela para facilitar sua localização. Além disso, foi elaborada uma breve descrição sobre seu conteúdo, incluindo um resumo de cada coluna presente no dataset.
![alt text](imgs/desc_tabela.png)
<br><br>

## Item 4 - Sobre Data Quality
Essa etapa foi realizada dentro de um [notebook](notebooks\concat_bases.ipynb), onde temos uma análise exploratória dos dados que garante a consistência e qualidade.
<br><br>

## Item 5 - Sobre o uso de GenAI e LLMs - Processar
Esse item está parcialmente concluído, também se encontra dentro de um [notebook](notebooks\concat_bases.ipynb), em suas últimas células.
<br><br>

## Item  7 - Sobre Análise de Dados - Analisar
Entrei problemas ao realizar o item 7. Não consegui acessar o portal da Metabase com minha senha.<br>
Tentei alterar a senha e tentar novamente mas também nao deu certo. Estou [aguardando suporte do time dadosfera](/imgs/suporte.png) no momento, em até 2 horas após eu conseguir realizar o login, irei completar esse item!