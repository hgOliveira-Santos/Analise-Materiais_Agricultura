
# Análise de Dados de Matérias-Primas Agrícolas

Este projeto utiliza Python para realizar uma análise exploratória em um conjunto de dados de matérias-primas agrícolas. Ele aborda o tratamento de dados, visualizações e respostas a perguntas específicas relacionadas aos preços e variações percentuais.

## Estrutura do Projeto

1. **Importação de Bibliotecas**:
   - `numpy` e `pandas` para manipulação e análise de dados.
   - `seaborn` e `matplotlib` para visualizações.

2. **Carregamento e Exploração Inicial**:
   - Leitura do conjunto de dados a partir de um arquivo CSV.
   - Inspeção inicial do DataFrame, incluindo análise de tipos de dados e valores nulos.

3. **Tratamento de Dados**:
   - Substituição de caracteres `%`, `-` e `,` para padronização.
   - Conversão de colunas para tipos apropriados (`float`, `datetime`).
   - Remoção de valores nulos e configuração da coluna `Month` como índice.

4. **Análise Exploratória e Visualização**:
   - Mapas de calor para identificar correlações entre preços e variações percentuais.
   - Visualizações específicas para matérias-primas, como lã grossa, algodão e borracha.

5. **Perguntas Respondidas**:
   - **Q1:** Qual a variação normal do preço de cada matéria-prima?
   - **Q2:** Qual matéria-prima tem o menor preço ao longo dos anos?
   - Comparação entre os preços do algodão e da borracha.

## Como Executar

1. Certifique-se de que você possui o Python 3.x instalado.
2. Instale as dependências listadas no notebook (`numpy`, `pandas`, `matplotlib`, `seaborn`).
3. Carregue o notebook (`.ipynb`) no Jupyter Notebook ou JupyterLab.
4. Execute cada célula sequencialmente para reproduzir a análise.

## Visualizações

O projeto gera os seguintes gráficos:
- Mapas de calor para correlações de preços e variações percentuais.
- Gráficos de linha para tendências de preços ao longo do tempo.
- Histogramas para distribuição das variações percentuais.

## Dados

O conjunto de dados analisado é armazenado no arquivo `agricultural_raw_material.csv`, contendo informações como:
- Preços de matérias-primas agrícolas.
- Variações percentuais mês a mês.

---

