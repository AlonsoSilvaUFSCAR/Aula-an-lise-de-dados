# Aula-analise-de-dados
1. Análise sobre a possibilidade de início dos incêndios florestais do estado de São Paulo às margens das ferrovias.
Este projeto tem o intuito de comprovar através de análise de dados espaciais que parte dos incêndios que afetaram o estado de São Paulo no ano de 2024, com maior concentração no mês de agosto tiveram início na malha férrea.

2. Coleta e organização de dados.
   Para esta atividade foram utilizados os seguintes dados:

   * Malha férrea do Brasil no formato shapefile
  - https://www.gov.br/antt/pt-br/assuntos/ferrovias/declaracao-de-rede/declaracao-de-rede-2024/malha-ferroviaria-federal-shp.zip/view

   * Focos de incêndio detectados pelo Banco de dados de queimadas do INPE limitados pelo períodode 01 de maio de 2024 a 30 de novembro de 2024, por se tratar do período com maior incidência de focos.
  - https://terrabrasilis.dpi.inpe.br/queimadas/bdqueimadas/#mapa

   * Análise da direção dos ventos através da base de dados do INMET, através de pesquisas nas bases meteorológicas com a finalidade de indentificar para onde soprava os ventos no dia dos incêndios, dando indicios da dinâmica do fogo, pois as chamas seguem a direção dos ventos.
  - https://tempo.inmet.gov.br/TabelaEstacoes/A001

3. Processamento dos dados.

   Para processamento dos dados foi utilizado o software livre QGIS, 
