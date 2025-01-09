# Projeto de Análise de Dados Análise de Funil

## Descrição do Projeto
Esse projeto é sobre uma startup que vende produtos alimentícios e para isso é preciso analisar o comportamento do usuário para o aplciativo da empresa. Primeiro, foi feito uma análise de funil de vendas. Para descobrir como os usuários chegam à etapa de compra e quantos ficam nas etapas anteriores. Em seguida, analisar os resultados do teste A/A/B. Isso foi feito, pois os designers gostariam de alterar as fontes de todo o aplicativo, mas os gerentes temem que os usuários achem o novo design intimidador. E a decisão será tomada com base nos resultados de um teste A/A/B. Os usuários são divididos em três grupos: dois grupos de controle recebem as fontes antigas e um grupo de teste recebe as novas para descobrir qual conjunto de fontes produz melhores resultados.
Observação: a criação de dois grupos A tem custos vantagens. Pode-se adaptar um princípio segundo a qual só estará confiante na precisão de nossos testes quando os dois grupos de controle forem semelhantes. Se houver diferenças significativas entre os grupos A, isso pode ajudar a descobrir fatores que podem distorcer os resultados. A comparação de grupos de controle também nos informa de quanto tempo e dados precisaremos ao executar outros testes.

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

## Ferramentas e Bibliotecas utilizadas
- Python: Linguagem principal utilziada para a análise
- Pandas: Biblioteca para manipulação e análise de dadosw
- Matplotlib: Biblioteca para gerar gráficos
- Numpy: Bilbioteca que permite trabalhar com objetos multidimensionais, como matrizes e sequências
- Seaborn: Biblioteca de visualizações de dados
- Scipy: Biblioteca que fornece uma manipulação conveniente e rápido de um array N-dimencional
- Ploty.express: Biblioteca que permite criar visualizações rápidas e eficientes
- Datetime: Biblioteca para manipulação de datas e horas

## Imagens

### Tabela dados
<img src="https://github.com/user-attachments/assets/465f962d-3465-4047-baf7-d6f6d53db428" alt="Projeto 11" width="200"/>

### Tabela tipos de eventos
<img src="https://github.com/user-attachments/assets/029eb9d8-dd3d-41b5-be82-f551afed0520" alt="Projeto 11" width="200"/>

### Data
<img src="https://github.com/user-attachments/assets/e6b5bdc3-22f7-456e-b408-1f80d385b67f" alt="Projeto 11" width="200"/>

### Tabela grupos
<img src="https://github.com/user-attachments/assets/3d308a6c-2e59-45ee-8342-35147282572c" alt="Projeto 11" width="200"/>

### p-value
<img src="https://github.com/user-attachments/assets/b0bbdb19-7c8a-4f72-9162-d5a7fc96caff" alt="Projeto 11" width="200"/>

### Teste A/A
<img src="https://github.com/user-attachments/assets/3b0b9eeb-bf0c-4492-a7d0-b081096d526f" alt="Projeto 11" width="200"/>

### Teste A/B
<img src="https://github.com/user-attachments/assets/f39f830c-9ed5-447e-a35c-34138eabe799" alt="Projeto 11" width="200"/>

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

## Contexto real
- Empresas que desejam fazer mudanças e querem saber como seus usuários irão reagir
- Novas empresas que desejam entender como funciona o mercado com novos produtos ou com mudanças em produtos já existentes
- Possíveis investidores que querem saber se vale a pena investir em alguma mudança de algum produto
  
## Como executar o Projeto
- Clone o repositório
- Navegue até o diretório do projeto
- Abra o proejto no seu IDE favorito
- Instale as dependências
- Execute o script principal
