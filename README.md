# 👶📊 EBAC - Análise de Dados SINASC RO 2019 📈✨

Este repositório contém o projeto desenvolvido como parte do curso **Cientista de Dados Profissional da EBAC (Escola Britânica de Artes Criativas e Tecnologia)**. O objetivo principal deste exercício é a manipulação, limpeza e análise exploratória de dados de nascidos vivos (SINASC) do estado de Rondônia, referentes ao ano de 2019. 🇧🇷

## 📂 Conteúdo do Repositório

* **`Mod5Ex_aulas_01a03.ipynb`**: O notebook Jupyter 📓 que contém todo o código desenvolvido para a resolução das questões propostas. Este notebook inclui:
    * Carregamento e inspeção inicial dos dados. 🧐
    * Seleção e limpeza de colunas específicas (`IDADEMAE`, `CONSULTAS`, `DTNASC`). 🧹
    * Criação de novas variáveis (`DTNASC_JAN`). ➕
    * Análise de distribuição (`IDADEMAE`, `CONSULTAS`). 📈
    * Cálculo de estatísticas descritivas (média e mediana). 🔢
    * Análise de frequência de nascimentos por mês. 🗓️
    * Gráficos de dispersão e boxplots para explorar relações entre variáveis. 📉📦
    * Renomeação das colunas para o padrão `snake_case` para padronização. 🐍
* **`SINASC_RO_2019.csv`**: O conjunto de dados original utilizado para a análise, referente aos nascidos vivos em Rondônia no ano de 2019, fornecido pelo DataSUS. 💾
* **`Estrutura_SINASC_para_CD.pdf`**: O dicionário de dados (ou metadados) que descreve cada coluna do arquivo SINASC, essencial para entender o significado das variáveis. 📖

## 🎯 Objetivo do Exercício

O principal objetivo deste módulo foi aplicar conhecimentos em:

* Manipulação de DataFrames com `pandas`. 🐼
* Limpeza e tratamento de dados (duplicados, nulos). 🧼
* Engenharia de features (criação de novas colunas). 🛠️
* Visualização de dados com `matplotlib` e `seaborn` para análise exploratória. 📊🎨
* Cálculo de estatísticas descritivas. ✍️
* Padronização de nomes de colunas. ✨

## 🚀 Como Executar o Projeto

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/SEU_USUARIO_GITHUB/EBAC_Analise_SINASC_RO.git](https://github.com/SEU_USUARIO_GITHUB/EBAC_Analise_SINASC_RO.git)
    ```
    (Lembre-se de substituir `SEU_USUARIO_GITHUB` pelo seu nome de usuário no GitHub).
2.  **Navegue até o diretório do projeto:**
    ```bash
    cd EBAC_Analise_SINASC_RO
    ```
3.  **Certifique-se de ter as bibliotecas necessárias instaladas:**
    ```bash
    pip install pandas matplotlib seaborn numpy
    ```
4.  **Abra o notebook Jupyter:**
    ```bash
    jupyter notebook Mod5Ex_aulas_01a03.ipynb
    ```
    O notebook será aberto no seu navegador, e você poderá executar as células de código para replicar a análise. ✅

