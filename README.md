# 🦟 FATEC Cidadã: Pipeline de Dados e Tratamento de Focos de Dengue (Ourinhos)

Repositório oficial da equipe para o processamento, limpeza e engenharia de dados dos registros de campo de combate à dengue no município de Ourinhos (período de março a setembro).

## ⚙️ Sobre o Projeto
Este repositório tem como objetivo centralizar o tratamento ético e estruturado dos dados brutos coletados pelos agentes de endemias. O pipeline garante a consistência temporal e espacial, eliminando inconsistências e preparando a base para análises preditivas, modelagem e integração com banco de dados relacional.

## 📂 Estrutura do Repositório

```text
projeto-dengue-fatec/
│
├── dados/
│   ├── dados_dengue_mes3.csv ... mes9.csv  # (Opcional/Backup)
│   └── dados_dengue_tratados_finais.csv     # 🛡️ Base oficial tratada (Somente Leitura)
│
├── notebooks/
│   └── pipeline_tratamento_dengue.ipynb     # Código principal em Python (Google Colab)
│
└── README.md                                # Documentação do projeto
