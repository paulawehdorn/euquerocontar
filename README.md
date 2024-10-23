# {Nome do projeto}

## 1. Introdução

## 2. Sobre o projeto

### 2.1. Por que este projeto é importante?

### 2.2. O que vamos entregar?
Ao final da pesquisa, vamos entregar um relatório de explanação inspirado no [boletim trimestral](https://www.institutomariadapenha.org.br/assets/downloads/boletim_trimestral_outubro_dezembro_2020.pdf) publicado pelo [Instituto Maria da Penha](https://www.institutomariadapenha.org.br/projetos/boletins-trimestrais.html).

Levar em consideração o conteúdo abaixo:
- Análise descritiva: Examinar os dados históricos.
- Análise preditiva: Previsões futuras baseadas em modelos de ML.
- Análise diagnóstica: Identificar fatores que contribuem para os casos de Violência contra a Mulher.
- Análise prescritiva: Recomendações de ações baseadas nas previsões.

## 3. Como vamos trabalhar?

### 3.1. Gerenciamento e organização do projeto:
- Gerenciamento: Utilizaremos [trello](https://trello.com/invite/b/66ef0e1fe720fb6cddce853a/ATTI5d6f8b18e0da09e2cbb555ebbc9d120231DF5806/projeto-eqc) e framework [SCRUM](https://www.scrum.org/resources/what-scrum-module) para gerenciamento ágil do projeto;
- Organização: Adotaremos o framework [DM-CRISP](https://www.datascience-pm.com/crisp-dm-2/) para estruturação das etapas de ciência de dados.

### 3.2. Fontes de dados:
- Os dados utilizados neste projeto são reais; 
- Extraídos do site da [Secretaria da Segurança Pública do estado do Rio Grande do Sul](https://www.ssp.rs.gov.br/estatisticas);
- Publicados pela Segurança Pública em formato aberto, conforme previsão da Lei nº 15.610, de 29 de abril de 2021, a partir de outubro do mesmo ano.
  
### 3.3. Atributos que influenciam a previsão:
- O dicionário de dados encontra-se no [item 8](#8-dicionário-de-dados).

### 3.4. Métrica de desempenho:

## 4. Conclusões

## 5. Próximos passos

## 6. Tecnologias Utilizadas

- Python;
- Pandas, Numpy, Matplotlib, Seaborn, Scikit-Learn;
- Pickle;
- Streamlit;
- Visual Studio Code;
- Git e Github.

## 7. Requisitos de Sistema

Para recriar o ambiente virtual Python, execute os seguintes comandos:

```bash
conda create -n eqc python=3.12.4
conda activate eqc
pip install -r requirements.txt
```

## 8. Dicionário de dados

FEATURE	| DESCRIPTION | TYPE | DETAIL
-- | -- | -- | --

## 9. Estrutura de Pastas
```plaintext
├── data
│   ├── 
│   └── 
├── img
├── models
├── notebooks
│   └── relatorio_rs_poa_canoas.ipynb
├── README.md
└── requirements.txt