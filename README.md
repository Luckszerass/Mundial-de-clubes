# Mundial de clubes
Exercício proposto na semana 2 de vizualização computacional do curso de Ciencia de Dados da Univesp


*Contém auxilio de IA 
Foi proposto um planejamento com base no modelo Munzner antes de fazer o DataViz, utilizei o Copilot para me auxiliar na organização e também na escolha de um gráfico:

Níveis do Modelo de Munzner e Tipologia de Tarefas
Domínio:

Informação de Domínio: Clubes campeões do Campeonato Mundial Interclubes de futebol masculino e o número de títulos que cada um possui.

Objetivo: Mostrar quais são os campeões e quantos títulos cada um tem de forma clara e visualmente atraente.

Descritivo e Abstrato:

Resumo da Tarefa: Identificar e contar os campeões ao longo dos anos, visualizando os dados de forma que seja fácil comparar a quantidade de títulos de cada clube.

Tipo de Dados: Dados temporais (anos) e categóricos (nomes dos clubes).

Tarefas Abstratas: Agregação (soma de títulos por clube), Classificação (ordenar clubes pelo número de títulos) e Comparação (visualizar diferença de títulos entre clubes).

Visualização:

Representação Visual: Gráfico de barras horizontais, onde cada barra representa um clube e a extensão da barra representa a quantidade de títulos.

Interação: Possibilidade de destacar ou filtrar clubes específicos, se desejado.

Codificação: Cor e comprimento das barras para indicar a quantidade de títulos.


*O Notebook teste.ipynb foi feito por IA, onde estava fazendo testes para saber qual seria o ideal antes de por a mão na massa e ultilizei de estudo para saber mais sobre a biblioteca  matplotlib

# Ultilizei nesse projeto:

- Jupyter Notebooks
- Power BI
- Microsoft Copilot.
- Pandas
- matplotlib

# Exercício proposto:
Um jornal vai fazer uma matéria sobre os clubes campeões do Campeonato Mundial Interclubes de futebol masculino. Essa matéria precisa de uma visualização que consiga mostrar quais são os campeões e quantos títulos cada um tem. Use o Modelo de Munzner combinado com a tipologia multinível de abstração de tarefas para fazer o planejamento da visualização, descrevendo o planejamento dessa análise em cada um dos níveis. Em seguida, construa uma visualização que atenda às necessidades da matéria. Use a ferramenta de visualização de sua preferência para construir a solução.

O conjunto de dados contém as colunas ANO (do título) e CAMPEÃO (nome do clube), e está disponível em:

https://raw.githubusercontent.com/higoramario/univesp-com400-visualizacao-computacional/main/semana-2-exercicio-apoio-2-campeoes-mundiais.csv

Observação: nos anos de 1975 e 1978 não houve disputa de mundial e no ano de 2000 houve dois campeonatos mundiais.

