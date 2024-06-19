# analise-exploratoria-brasilia-8-de-janeiro
Análise exploratória do estudo de caso sobre os eventos de 8 de janeiro em Brasília

Este repositório contém um notebook Jupyter com uma análise exploratória de um banco de dados coletado por API tweepy, de uma conta que organizou uma caravana para eventos que ocorreram em Brasília no dia 8 de janeiro. O objetivo principal é entender melhor os dados coletados sobre esses evento através de técnicas de análise de dados e visualização.

## Conteúdo do Notebook

### Carregamento e Inspeção dos Dados
- **Upload do Arquivo**: Carregamento do arquivo de dados `eas_info_br.xlsx` utilizando a biblioteca `google.colab`.
- **Visualização Inicial dos Dados**: Visualização das primeiras linhas e informações gerais do DataFrame.
- **Estatísticas Descritivas**: Geração e exibição de estatísticas descritivas para os atributos numéricos do DataFrame.

### Visualização dos Dados
- **Criação de Histogramas**: Utilização das bibliotecas `matplotlib` e `seaborn` para criar histogramas mostrando a distribuição das contagens de retweets, favoritos e respostas.

## Como Usar

1. **Clonar o Repositório**:
   ```bash
   git clone https://github.com/seu-usuario/analise-exploratoria-brasilia-8-de-janeiro.git
2. Navegar até o Diretório do Repositório:
    cd analise-exploratoria-brasilia-8-de-janeiro
3. Abrir o Notebook com Jupyter:

   jupyter notebook Analise_Exploratoria_Estudo_de_Caso_Brasilia_8_de_Janeiro.ipynb

Requisitos
Python 3.x
Jupyter Notebook
Bibliotecas Python necessárias: pandas, matplotlib, seaborn (listadas no início do notebook)
