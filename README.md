# Spotify_Project_Fame_Predict


# Previsão de Popularidade de Músicas no Spotify

## Descrição do Projeto
Este projeto tem como objetivo criar um modelo preditivo de machine learning capaz de antecipar a popularidade de músicas no Spotify. Utilizando um conjunto de dados com mais de 100 mil músicas contendo características acústicas e metadados, o modelo fornecerá insights valiosos para otimizar decisões de investimento e estratégias de marketing em uma grande gravadora.

## Estrutura do Projeto

O projeto está estruturado da seguinte forma:

1. **Exploração dos Dados**: Análise exploratória (EDA) para entender os dados, identificar padrões e realizar visualizações.
2. **Limpeza dos Dados**: Tratamento de valores nulos, outliers e codificação de variáveis categóricas.
3. **Formulação de Hipóteses**: Três hipóteses formuladas para explicar fatores que influenciam a popularidade de uma música.
4. **Seleção de Features**: Escolha das features mais relevantes com base na análise exploratória e nas hipóteses.
5. **Construção do Modelo**: Desenvolvimento de diferentes modelos de machine learning, com ajuste fino de hiperparâmetros.
6. **Avaliação do Modelo**: Avaliação do desempenho do modelo com base em métricas como acurácia, precisão, recall e F1-score.
7. **Submissão**: Criação de um arquivo CSV contendo as previsões da popularidade das músicas no conjunto de testes.

## Dados

Os dados consistem em mais de 100 mil músicas com os seguintes tipos de informações:

- **Características acústicas**: Energia, Valência, Tempo, etc.
- **Metadados**: Gênero, Ano de Lançamento, etc.
- **Índice de Popularidade**: Medido diretamente pelo Spotify.

Os dados estão divididos em dois arquivos:
- `train.csv`: Conjunto de dados de treinamento com as features e o valor de popularidade (target).
- `test.csv`: Conjunto de dados de teste onde as previsões devem ser feitas.

## Dependências

As principais bibliotecas utilizadas neste projeto são:

- `pandas`: Manipulação e análise de dados.
- `numpy`: Operações matemáticas e manipulação de arrays.
- `matplotlib` e `seaborn`: Visualização de dados.
- `scikit-learn`: Algoritmos de machine learning e ferramentas para ajuste fino de hiperparâmetros.

Instale as dependências com:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Instruções de Execução

1. **Clone o repositório**:

```bash
git clone https://github.com/seu-usuario/seu-projeto.git
cd seu-projeto
```

2. **Abra o Jupyter Notebook**:

Execute o comando abaixo para abrir o notebook no seu navegador:

```bash
jupyter notebook
```

3. **Execute o notebook**: 
   - No notebook, siga as etapas de exploração, limpeza, seleção de features e construção do modelo.
   - Certifique-se de seguir as instruções passo a passo para gerar o arquivo CSV final contendo as previsões da popularidade.

4. **Submissão**:
   - Após treinar o modelo, gere o arquivo CSV no formato adequado e faça a submissão conforme as regras.

## Avaliação

Os modelos serão avaliados com base nos seguintes critérios:

- **Limpeza e Tratamento de Dados**: Incluindo tratamento de valores nulos e outliers.
- **Exploração e Visualização dos Dados**: Qualidade da análise exploratória e visualizações.
- **Formulação de Hipóteses**: Justificativa e relevância das hipóteses formuladas.
- **Seleção de Features**: Escolha e justificativa das features usadas no modelo.
- **Construção e Avaliação do Modelo**: Desempenho do modelo em termos de acurácia e outras métricas.
- **Finetuning de Hiperparâmetros**: Otimização do desempenho do modelo.
- **Documentação e Apresentação**: Clareza e organização do código e notebook.

## Contribuições

Contribuições são bem-vindas! Para contribuir:

1. Faça um fork do projeto.
2. Crie uma nova branch: `git checkout -b minha-feature`.
3. Faça suas modificações e commit: `git commit -m 'Minha nova feature'`.
4. Envie para o repositório remoto: `git push origin minha-feature`.
5. Crie um Pull Request.

## Licença

Este projeto é licenciado sob a licença MIT. Consulte o arquivo `LICENSE` para mais informações.

---

Esse README cobre as principais informações e é um bom ponto de partida para documentar seu projeto!