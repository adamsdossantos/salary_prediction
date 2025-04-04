# Previsão de Remuneração de Profissionais de TI

Este projeto utiliza Streamlit para criar uma aplicação web interativa que prevê o salário anual de profissionais de tecnologia com base nos dados da pesquisa Stack Overflow 2024.

## Sobre o Projeto

A aplicação foi construída com foco em acessibilidade e facilidade de uso. Com poucos cliques, o usuário pode estimar a remuneração baseada em:

- País de atuação
- Nível de educação
- Anos de experiência
- Faixa etária
- Setor de atuação (indústria)

O modelo de machine learning utilizado para prever o salário é um XGBoost Regressor, treinado com variáveis transformadas e combinadas para melhorar a performance, como:

- Education + Country
- Country + Industry
- Years of Experience + Age
- Entre outras interações úteis para modelagem.

## Como Executar Localmente

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio
```

2. Instale as dependências (recomenda-se o uso de ambiente virtual):

```bash
pip install -r requirements.txt
```

3. Certifique-se de que o diretório pkl_files contenha o arquivo regressor.pkl.

4. Rode a aplicação com Streamlit:
```bash
streamlit run salary_prediction.py
```
## Tecnologias e Bibliotecas

- Python

- Streamlit

- XGBoost

- scikit-learn

- Optuna

- category_encoders

- numpy

- pickle

## Licença

Este projeto está licenciado sob a licença MIT.






