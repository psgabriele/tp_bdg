# TP_ BDG
O presente trabalho prático visa colocar em prática conceitos e princípios discutidos ao
longo da disciplina, usando dados e situações reais. O trabalho será baseado em dados
de votação, mantidos pelo Tribunal Superior Eleitoral, e publicados em seu portal de
dados abertos (https://dadosabertos.tse.jus.br/).

Especificações
1. Aquisição de dados
a. Identificação e conhecimento da fonte primária: TSE, conforme descrito
acima;
b. Identificação de fontes de dados geográficos para espacialização dos
dados eleitorais; obtenção e verificação de qualidade.
c. Obtenção de dados censitários municipais: escolher temas e fonte.
d. Aquisição de dados do tema complementar.
2. Construção do BDG e Engenharia de Dados
Nesta parte, espera-se que os dados sejam analisados de forma exploratória,
de modo a adquirir conhecimento e estatísticas básicas sobre o conteúdo. É
uma atividade típica de engenharia de dados, dentro da Ciência dos Dados.
a. Organizar, filtrar, agregar, etc. os dados da adquiridos, formando
tabelas geográficas e convencionais relacionadas a elas. Apresentar um
esquema OMT-G do BD formado.
b. Importar os dados, de modo que características geográficas possam ser
usadas nas análises.
c. Executar quaisquer transformações necessárias nos dados originais, de
modo a prepará-los para as análises.
d. Análise exploratória – Verificar, por exemplo:
i. Ocorrência de dados faltantes
ii. Limitações dos dados
iii. Necessidade de correção de problemas de padronização nas
colunas
iv. Verificação das faixas de variação dos valores das variáveis,
estatísticas básicas sobre as variáveis (média, desvio padrão,
etc.), valores possíveis de atributos categóricos
v. Análise crítica do conteúdo disponível

3. Análise
a. Autocorrelação espacial: dados de candidatos escolhidos, ex. um
candidato com votação regionalizada, um candidato com votação
ampla; candidato eleito versus candidato não-eleito
b. Autocorrelação espacial em nível agregado: agregar os dados em
microrregiões (IBGE), e refazer a análise de autocorrelação espacial.
Observar e reportar preservação ou alteração do comportamento
constatado na análise anterior
c. Correlação com dados socioeconômicos: verificar se existe correlação
entre a votação de alguns candidatos escolhidos pelo grupo e

características socioeconômicas dos municípios, e se essa correlação é
espacializada
d. Correlação com dados da fonte adicional escolhida pelo grupo
e. Autocorrelação espacial por partido, na votação para deputado
federal: escolher um grupo pequeno de partidos mais representativos, e
compará-los
f. Análise extra: à escolha do grupo (p. ex. comparação entre duas ou
mais eleições, formação de grupos de partidos alinhados politicamente,
agrupamento de municípios de perfil semelhante)

4. Visualização
(Discutiremos em sala alternativas de visualização para esses tipos de dados.)
Incluir na descrição da visualização:
a. Propósito da visualização
b. Escolha do plano de fundo
c. Escolha de parâmetros gráficos/visuais
d. Processo de produção (software, recursos, opções relevantes)
