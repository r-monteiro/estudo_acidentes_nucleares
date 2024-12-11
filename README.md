# estudo_acidentes_nucleares
Análise de Dados sobre Incidentes em Usinas Nucleares - ESTUDO PRÁTICO PYTHON

1. Importação de bibliotecas: O código utiliza matplotlib, pandas, seaborn e plotly para análise e visualização de dados.
2. Carregamento de dados: Um arquivo CSV chamado "nuclear.csv" é lido para um DataFrame.
3. Pré-processamento de dados:
Conversão da coluna 'Date' para o tipo datetime.
Renomeação da coluna "INES\nlevel" para "INES LEVEL".
4. Visualizações:
4.1 Mapa de dispersão mostrando locais de acidentes nucleares.
4.2 Gráfico de barras comparando mortes diretas e indiretas por localização.
4.3 Gráfico de linha exibindo ocorrências por data.
4.4 Boxplot da latitude dos incidentes.
4.5 Gráfico de barras mostrando ocorrências por categoria e nível INES.
4.6 Gráficos de barras para mortes indiretas e diretas por nível INES.
4.7 Gráfico de barras do número de mortes indiretas por localização.
5. Análises Realizadas
Exploração inicial dos dados: shape, colunas, descrição estatística, informações gerais e verificação de valores nulos e duplicados.
Distribuição geográfica: Utilização de um mapa para visualizar a localização dos incidentes nucleares.
Análise temporal: Exame da frequência de ocorrências ao longo do tempo.
Categorização: Estudo das ocorrências por categoria e nível INES (International Nuclear Event Scale).
Impacto humano: Análise das mortes diretas e indiretas relacionadas aos incidentes, considerando a localização e o nível INES.
