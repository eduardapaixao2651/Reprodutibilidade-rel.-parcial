# Análise Exploratória de Dados – COVID-19
## Comparação dos Casos e Óbitos por COVID-19 entre as Regiões Nordeste e Sul do Brasil (2020)

Este repositório contém os arquivos utilizados na Análise Exploratória de Dados (AED) desenvolvida para a disciplina de Estatística Aplicada à Biologia da Universidade Federal de Sergipe (UFS).

---

## Objetivo

Comparar o comportamento dos casos confirmados e dos óbitos por COVID-19 entre as regiões Nordeste e Sul do Brasil durante o ano de 2020, utilizando técnicas de estatística descritiva e visualização gráfica.

---

## Fonte dos Dados

**Base de dados:** COVID-19 Brasil por Municípios

**Autor:** Wesley Cota

**Repositório:**
https://github.com/wcota/covid19br

**Arquivo utilizado:**

```
cases-brazil-cities-time_2020.csv.gz
```

**Download direto**

https://raw.githubusercontent.com/wcota/covid19br/master/cases-brazil-cities-time_2020.csv.gz

**Data de acesso**

30 de maio de 2026

**Licença**

CC BY 4.0

---

## Estrutura do Projeto

```
Projeto_COVID_AED/
│
├── dados/
│   ├── cases-brazil-cities-time_2020.csv.gz
│
├── graficos/
│   ├── 01_histogramas.png
│   ├── 02_boxplots.png
│   ├── 03_dispersao.png
│   ├── 04_serie_temporal.png
│   ├── 05_barras_mensais.png
│   └── 06_cv_estabilidade.png
│
├── scripts/
│   └── analise_covid_nordeste_sul.py
│
├── relatorio.pdf
│
└── README.md
```

---

## Requisitos

Python 3.10 ou superior

Bibliotecas:

- pandas
- numpy
- matplotlib

---

## Instalação

Clone o repositório:

```bash
git clone https://github.com/SEU-USUARIO/Projeto_COVID_AED.git
```

Entre na pasta:

```bash
cd Projeto_COVID_AED
```

Instale as dependências:

```bash
pip install pandas numpy matplotlib
```

ou

```bash
pip install -r requirements.txt
```

---

## Como executar

Entre na pasta dos scripts:

```bash
cd scripts
```

Execute:

```bash
python analise_covid_nordeste_sul.py
```

No Linux ou Mac:

```bash
python3 analise_covid_nordeste_sul.py
```

---

## Saídas geradas

O programa cria automaticamente a pasta

```
graficos/
```

e salva:

- Histogramas
- Boxplots
- Dispersão
- Série temporal
- Barras mensais
- Coeficiente de variação

Também imprime no terminal:

- inspeção da base;
- estatísticas descritivas;
- limpeza dos dados;
- limitações;
- informações para reprodução da análise.

---

## Etapas realizadas

1. Importação da base de dados.
2. Seleção dos estados das regiões Nordeste e Sul.
3. Conversão da coluna de datas.
4. Tratamento de valores ausentes.
5. Remoção de duplicatas.
6. Correção de valores negativos.
7. Agregação diária por região.
8. Cálculo das estatísticas descritivas.
9. Construção dos gráficos.
10. Exportação das figuras.

---

## Reprodutibilidade

Todas as análises foram realizadas utilizando Python.

Os gráficos e estatísticas podem ser reproduzidos executando o script disponibilizado neste repositório.

---

## Referência

COTA, W. *Monitoring the number of COVID-19 cases and deaths in Brazil at municipal and federative units level.* SciELO Preprints, 2020.

DOI:
10.1590/SciELOPreprints.362

Disponível em:

https://github.com/wcota/covid19br
