# Regressão Logística com Streamlit

Este projeto treina um modelo de regressão logística e implementa uma interface com Streamlit para realizar previsões em novos dados. O pipeline de pré-processamento e o modelo são salvos em um arquivo `.pkl` para uso posterior.

## Estrutura do Projeto

- **train_and_save_model.py**: Treina e salva o modelo.
- **app.py**: Interface Streamlit para carregar o modelo e prever novos dados.
- **requirements.txt**: Dependências do projeto.
- **README.md**: Instruções gerais.

## Requisitos

Tenha Python 3.6 ou superior instalado. Para instalar as dependências, execute:

```bash
pip install -r requirements.txt
```

## Treinamento do Modelo

Execute o script `train_and_save_model.py` para treinar e salvar o modelo:

```bash
python train_and_save_model.py
```

O modelo será salvo como `model_final.pkl`.

## Executando a Aplicação Streamlit

Para rodar a interface:

```bash
streamlit run app.py
```

## Uso da Aplicação

1. Faça upload do arquivo `model_final.pkl`.
2. Envie um arquivo CSV com os dados a serem escorados.
3. A aplicação exibirá as previsões e permitirá baixar um CSV com os resultados.

## Estrutura Esperada do CSV

- `sexo`
- `posse_de_veiculo`
- `posse_de_imovel`
- `tipo_renda`
- `educacao`
- `estado_civil`
- `tipo_residencia`
- `qtd_filhos`
- `idade`
- `tempo_emprego`
- `qt_pessoas_residencia`
- `renda`
