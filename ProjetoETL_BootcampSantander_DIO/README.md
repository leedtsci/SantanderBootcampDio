# Projeto ETL – Pipeline de Vendas

## 📄 Descrição
Pipeline ETL desenvolvido em Python como parte do Bootcamp Santander 2025, com foco em boas práticas de extração, validação, transformação e carregamento de dados a partir de um arquivo CSV fictício de vendas.

## 🎯 Objetivo
Demonstrar a construção de um pipeline ETL simples, organizado e documentado, utilizando Python e bibliotecas amplamente adotadas no mercado.

## 🗂️ Estrutura do Projeto
O projeto possui a seguinte estrutura
```
ProjetoETL/
│
├── data/
│   ├── vendas_clean.csv
│   └── vendas_raw.csv
│
├── notebooks/
│   └── projeto_ETL_2025.ipynb
│
├── .env
├── README.md
└── requirements.txt
```

## Requisitos
- Python 3.11 ou superior

- Bibliotecas Externas:
    - pandas
    - python-dotenv

## 🔄 Pipeline ETL
Explicação resumida das etapas:
- Extract: leitura e validação inicial dos dados.
- Transform: tratamento, padronização e validações.
- Load: gravação da base final tratada.

## 🧪 Tecnologias Utilizadas
- Python 3.11+
- pandas: manipulação e transformação dos dados
- python-dotenv: gerenciamento de variáveis de ambiente
- VS Code
- Jupyter Notebook

## 🚀 Como Executar o Projeto
1. Clone este repositório para sua máquina local.
2. Crie e ative um ambiente virtual Python (recomendado).
3. Instale as dependências do projeto:
```
    pip install -r requirements.txt
```
4. Configure o arquivo .env.
5. Execute o notebook Jupyter.


## 📊 Dados
Dataset fictício de vendas contendo informações de produto, categoria, quantidade e valores, utilizado exclusivamente para fins educacionais.

## ✅ Conclusão
Este projeto evidencia a importância do processo ETL na preparação de dados confiáveis e organizados, servindo como base para análises e tomadas de decisão em projetos de dados.