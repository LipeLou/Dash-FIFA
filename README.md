# ⚽ FIFA 23 Official Dataset - Streamlit Dashboard

Este é um projeto simples de estudo desenvolvido para aprender e praticar o framework [Streamlit](https://streamlit.io/) utilizando Python.

O dashboard explora o **FIFA 23 Official Dataset**, permitindo a visualização de estatísticas de jogadores e times de futebol de forma interativa.

## 📋 Funcionalidades

O projeto é composto por três páginas principais:

1.  **🏠 Home**: 
    - Apresentação do projeto e do dataset.
    - Link direto para a fonte dos dados no Kaggle.
    - Carregamento inicial e cache dos dados na sessão.

2.  **🏃‍♂️ Players**:
    - Seleção de clube e jogador.
    - Visualização detalhada do jogador (Foto, Overall, Valor de Mercado, Salário, Atributos Físicos).

3.  **⚽ Teams**:
    - Visão geral do elenco de cada clube.
    - Tabela interativa com estatísticas dos jogadores (Overall, Idade, Salário, Contrato, etc.).

## 🛠️ Tecnologias Utilizadas

- **Python**: Linguagem principal.
- **Streamlit**: Para criação da interface web interativa.
- **Pandas**: Para manipulação e análise dos dados.

## 🚀 Como Rodar o Projeto

O projeto está rodando na nuvem. Basta acessar o link: [ "dash-fifa23.streamlit.app" ]( "dash-fifa23.streamlit.app" )

## 📂 Estrutura do Projeto

- `1_🏠_home.py`: Página principal da aplicação.
- `pages/`: Contém as páginas adicionais do dashboard.
  - `2_🏃‍♂️_players.py`: Página de detalhes dos jogadores.
  - `3_⚽_teams.py`: Página de detalhes dos times.
- `datasets/`: Pasta contendo o arquivo CSV com os dados (`CLEAN_FIFA23_official_data.csv`).
- `requirements.txt`: Lista de bibliotecas Python necessárias.

## 📊 Fonte dos Dados

Os dados utilizados neste projeto foram obtidos no Kaggle:
[FIFA 23 Official Dataset](https://www.kaggle.com/datasets/kevwesophia/fifa23-official-datasetclean-data)

---
*Projeto desenvolvido para fins de estudo.*
