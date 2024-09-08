# Projeto de Análise de Dados Análise de Funil

## Descrição do Projeto
Este projeto consiste em uma análise do funil de vendas de uma empresa fictícia que está testando possível mudanças em seu site. Para isso, foi realizado um teste A/B, em que os usuários foram divididos em dois grupo de controle (A1 e A2) e um grupo de teste (B). O objetivo é saber se com as mudanças, o funil de vendas do grupo B teria um desempenho superior

## As tarefas são:
- Realizar um teste A/B
- Comparar estatisticamente o desempenho dos grupos
- Analisar as mudanças no resultado do funil de vendas
- Analisar os resultados em gráficos

## Dicionário de dados
Cada linha do registro (também referido como log) é uma ação do usuário ou um evento
- logs_exp_us.csv
  - 'EventName': nome do evento
  - 'DeviceIDHash': identificador de usuário exclusivo
  - 'EventTimestamp': hora do evento
  - 'ExpId': número do experimento: 246 e 247 são os grupos de controle, 248 é o grupo de teste

## Ferramentas e Bibliotecas utilziadas
- Python: Linguagem principal utilziada para a análise
- Pandas: Biblioteca para manipulação e análise de dadosw
- Matplotlib: Biblioteca para gerar gráficos
- Numpy: Bilbioteca que permite trabalhar com objetos multidimensionais, como matrizes e sequências
- Seaborn: Biblioteca de visualizações de dados
- Scipy: Biblioteca que fornece uma manipulação conveniente e rápido de um array N-dimencional
- Ploty.express: Biblioteca que permite criar visualizações rápidas e eficientes
- Datetime: Biblioteca para manipulação de datas e horas

## Resultados
- Através dos gráficos, foi possível ver como os usuários se comportam
- Através do funil foi possível saber onde estamos perdendo usuários
- Os resultados indicaram que o grupo de teste (B) teve um desempenho melhor em comparação com os dois grupos de controle (A1 e A2) e com isso confirmando a hipótese inicial de que as mudanças no site foram eficientes para melhorar o funil de vendas

## Aprendizados
- Análise de dados
- Qualidade dos dados
- Tratar os dados modificando tipos de colunas, nome das colunas, valores ausentes
- Construção e análise de gráficos
- Teste A/A/B
- Comparação estatísticas de grupos de teste
- Análise do funil de vendas

## Como executar o Projeto
- Clone o repositório
- Navegue até o diretório do projeto
- Abra o proejto no seu IDE favorito
- Instale as dependências
- Execute o script principal
