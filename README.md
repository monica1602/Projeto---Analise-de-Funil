# Projeto de Análise de Dados Análise de Funil

## Descrição do Projeto
Este projeto envolve a análise do comportamento dos usuários em um aplicativo de uma startup que vende produtos alimentícios. O objetivo é entender como os usuários interagem com o aplicativo, desde a entrada até a compra, e tomar decisões baseadas nos dados coletados. O processo começou com uma análise de funil de vendas para identificar como os usuários progridem nas etapas do processo de compra e onde eles tendem a desistir.
A seguir, foi realizado um teste A/A/B para avaliar o impacto de uma alteração no design do aplicativo, especificamente a mudança nas fontes. Dois grupos de controle, que mantiveram as fontes antigas, e um grupo de teste, que foi exposto ao novo design com fontes alteradas, foram comparados. O objetivo era verificar se a mudança nas fontes afetaria negativamente a experiência do usuário e, consequentemente, as taxas de conversão.
A análise comparativa entre os dois grupos de controle (A) é crucial, pois permite avaliar se há diferenças significativas que possam afetar a validade dos resultados. Caso sejam identificadas discrepâncias entre os grupos de controle, isso pode revelar fatores externos que influenciam os comportamentos dos usuários e ajudar a ajustar a metodologia para futuros testes. Além disso, essa comparação ajuda a determinar o tempo e o volume de dados necessários para garantir resultados precisos e confiáveis ao realizar outros testes.
A decisão final sobre a mudança no design será tomada com base nas conclusões do teste A/A/B, priorizando a melhoria da experiência do usuário e o aumento das conversões no aplicativo.

## As tarefas são:
- Realizar um teste A/B: Executar o teste A/B para comparar o desempenho dos dois grupos de controle (grupo A com fontes antigas) e o grupo de teste (grupo B com fontes novas). O teste permitirá avaliar o impacto das mudanças no design, especificamente nas fontes, sobre as métricas de comportamento dos usuários no aplicativo.
- Comparar estatisticamente o desempenho dos grupos: Analisar os dados coletados de cada grupo, usando testes estatísticos (como o teste t de Student) para verificar se as diferenças observadas nas taxas de conversão, no comportamento dos usuários ou em outras métricas de interesse são significativas. Isso ajudará a entender se a mudança no design teve um impacto real nas interações e conversões.
- Analisar as mudanças no resultado do funil de vendas: Examinar as etapas do funil de vendas antes e depois da alteração no design. Isso envolve observar como os usuários se comportam ao longo do funil, desde a visita ao aplicativo até a conclusão da compra, e identificar se houve aumento ou queda em qualquer uma das etapas, como taxa de abandono ou melhoria nas taxas de conversão.
- Analisar os resultados em gráficos: Utilizar gráficos e visualizações para mostrar as diferenças no comportamento dos usuários entre os grupos. Gráficos de barras, linhas ou funil podem ser úteis para ilustrar como os grupos de controle e o grupo de teste se comportaram em diferentes etapas do processo de compra e como as métricas-chave mudaram com a alteração do design.

## Dicionário de dados
Cada linha do registro (também referido como log) é uma ação do usuário ou um evento
- logs_exp_us.csv
  - 'EventName': nome do evento
  - 'DeviceIDHash': identificador de usuário exclusivo
  - 'EventTimestamp': hora do evento
  - 'ExpId': número do experimento: 246 e 247 são os grupos de controle, 248 é o grupo de teste

## Ferramentas e Bibliotecas utilizadas
- Python: Linguagem principal utilizada para análise, versátil e eficiente para manipulação de dados, construção de modelos e execução de tarefas de análise de dados.
- Pandas: Biblioteca essencial para manipulação e análise de dados, especialmente para trabalhar com estruturas de dados como DataFrames e séries, permitindo fácil leitura, limpeza, filtragem e transformação dos dados.
- Matplotlib: Biblioteca de visualização de dados amplamente utilizada para criar gráficos estáticos, como gráficos de barras, linhas e dispersão.
- Numpy: Biblioteca fundamental para trabalhar com arrays multidimensionais e operações matemáticas em grande escala. É amplamente usada para realizar cálculos rápidos e eficientes com grandes volumes de dados.
- Seaborn: Biblioteca de visualização de dados baseada no Matplotlib, fornece uma interface de alto nível para a criação de gráficos informativos e bonitos, como gráficos de dispersão e gráficos de densidade.
- Scipy: Biblioteca que fornece funções matemáticas e científicas, como operações de álgebra linear, otimização, estatísticas, integração e processamento de sinais, entre outras.
- Plotly.express: Biblioteca para criar visualizações rápidas e interativas, como gráficos de linha, dispersão, barras, mapas, entre outros, com foco em visualizações interativas em tempo real.
- Datetime: Biblioteca para manipulação e análise de datas e horários, útil para trabalhar com timestamps, intervalos de tempo e conversiones entre fusos horários.

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
- Através da visualização dos gráficos, foi possível identificar padrões claros no comportamento dos usuários durante as etapas do funil de vendas.
- A análise do funil permitiu entender em quais etapas os usuários estavam sendo perdidos, ajudando a direcionar melhorias nos processos.
- Os resultados do teste A/A/B mostraram que o grupo de teste (B), que utilizou as novas fontes, obteve um desempenho superior em comparação com os dois grupos de controle (A1 e A2), confirmando que as mudanças implementadas no design do site foram eficazes na otimização do funil de vendas.

## Aprendizados
- Análise de dados: Identificação de padrões e insights relevantes a partir dos dados disponíveis.
- Qualidade dos dados: Garantia da consistência e integridade dos dados, identificando valores ausentes ou inconsistências.
- Tratar os dados modificando tipos de colunas, nome das colunas, valores ausentes: Preparação dos dados para análise, corrigindo e ajustando os dados conforme necessário.
- Construção e análise de gráficos: Utilização de ferramentas de visualização para criar gráficos que ajudem na interpretação dos dados e insights.
- Teste A/A/B: Realização de um teste para comparar o desempenho de diferentes grupos (A1, A2 e B) e determinar se as mudanças são eficazes.
- Comparação estatística de grupos de teste: Análise comparativa entre os grupos de controle e o grupo de teste para verificar a significância dos resultados.
- Análise do funil de vendas: Estudo do comportamento do usuário ao longo do funil de vendas para identificar onde ocorrem perdas e oportunidades de melhoria.

## Contexto real
- Empresas que desejam implementar mudanças em seus produtos e precisam entender como essas alterações afetarão o comportamento de seus usuários.
- Novas empresas que buscam compreender o impacto de novos produtos ou mudanças em produtos existentes no mercado e no comportamento dos consumidores.
- Investidores potenciais que estão avaliando a viabilidade de investimentos em mudanças de produtos e querem entender os riscos e benefícios associados a essas alterações.
  
## Como executar o Projeto
- Clone o repositório
- Navegue até o diretório do projeto
- Abra o proejto no seu IDE favorito
- Instale as dependências
- Execute o script principal
