# Análise da Evasão e Permanência em Cursos de TI no Ensino Superior Brasileiro (2014–2024)

Este repositório contém o código-fonte, scripts de ETL e materiais associados ao artigo **“Análise da evasão e permanência em cursos de Tecnologia da Informação no ensino superior brasileiro sob perspectivas temporal, regional e sociodemográfica”**.

A pesquisa utiliza os microdados do **Censo da Educação Superior (INEP)** no período de **2014 a 2024**, com foco em cursos da área de **Computação e Tecnologias da Informação e Comunicação (TIC)**, aplicando técnicas de **Business Intelligence (BI)** para estruturação, modelagem e visualização de indicadores relacionados à evasão e permanência acadêmica.

---

## Objetivo

Disponibilizar uma solução analítica reprodutível para:

- tratamento e filtragem de microdados do INEP;
- construção de base integrada (série histórica 2014–2024);
- modelagem analítica (Data Warehouse / Star Schema);
- apoio à visualização interativa de indicadores.

---

## 📊 Indicadores

Indicadores trabalhados:

- **Taxa de evasão**
- **Taxa de conclusão**
- **Taxa de permanência**

---

## Fonte dos Dados

Os dados utilizados provêm dos microdados públicos disponibilizados pelo INEP: https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/censo-da-educacao-superior

- **Censo da Educação Superior – Microdados (2014 a 2024)**  
- Arquivos utilizados:
  - Cadastro de Cursos (`MICRODADOS_CADASTRO_CURSOS`)
  - Cadastro de IES (`MICRODADOS_CADASTRO_IES`)
 
---

## 🧱 Estrutura do projeto

```bash
evasao-ti-bi/
│
├── datasets/              # Bases de dados utilizadas (raw e tratadas)
├── scripts/               # Scripts de tratamento/ETL e análises
└── README.md
