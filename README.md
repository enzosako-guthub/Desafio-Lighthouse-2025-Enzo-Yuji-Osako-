# Desafio-Lighthouse-2025-Enzo-Yuji-Osako-
# Análise de Filmes e Previsão de Nota IMDB 

Este projeto explora um dataset com 1000 filmes do IMDB para descobrir insights sobre o que contribui para o sucesso de um filme. Além da análise exploratória, um modelo de Machine Learning foi treinado para prever a nota do IMDB com base nas características dos filmes.

### Sobre o Projeto

O trabalho foi dividido em duas etapas principais, refletidas nos notebooks:

* `1- Analise_Exploratoria.ipynb`: Focado na limpeza, tratamento e análise exploratória dos dados. É aqui que os dados brutos são transformados em informação e os gráficos são gerados.
* `2- Modelagem.ipynb`: Contém todo o processo de construção do modelo de Machine Learning, desde o teste de diferentes algoritmos (baseline) até o treinamento do modelo final e sua aplicação em uma nova previsão.
* `imdb_rating_predictor.pkl`: O modelo `RandomForestRegressor` final, treinado e pronto para uso.

**Tecnologias:** Python, Pandas, Scikit-learn, Matplotlib e Seaborn.

### Como Rodar o Projeto

Para executar os notebooks em sua máquina local, siga os passos abaixo.

**Pré-requisitos:**
* Python 3.x
* Pip

**Passos:**

1.  **Clone este repositório:**
    ```bash
    git clone <URL-DO-SEU-REPOSITORIO-GIT>
    cd <NOME-DA-PASTA-DO-PROJETO>
    ```

2.  **Crie e ative um ambiente virtual:**
    ```bash
    # Comando para criar o ambiente
    python -m venv venv

    # Ative o ambiente (no Windows)
    .\venv\Scripts\activate
    
    # Ative o ambiente (no macOS/Linux)
    source venv/bin/activate
    ```

3.  **Instale as dependências:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Inicie o Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
    Isso abrirá o Jupyter no seu navegador. Agora é só abrir os arquivos `.ipynb` e executar as células.

---
*Como alternativa, os notebooks podem ser executados no [Google Colab](https://colab.research.google.com/), fazendo o upload dos arquivos `.ipynb` e do dataset `.csv` para o ambiente.*
