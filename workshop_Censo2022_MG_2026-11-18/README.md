# Workshop | Manipulação de Dados do Censo Demográfico 2022 com Python

**Universidade Federal de Viçosa (UFV) | 18 de novembro de 2026**

Este repositório reúne os materiais utilizados no workshop de **Manipulação de Dados do Censo Demográfico 2022 com Python**, com foco na exploração, organização, tratamento e análise de dados censitários por meio do Google Colab.

A atividade utiliza dados do Censo Demográfico 2022, disponibilizados pelo Instituto Brasileiro de Geografia e Estatística (IBGE), organizados para o estado de Minas Gerais na escala dos setores censitários.

O objetivo é apresentar procedimentos de manipulação de dados que possam ser aplicados em pesquisas acadêmicas, diagnósticos territoriais e análises urbanas.

---

## 1. Objetivos

O workshop tem como objetivo introduzir os participantes à manipulação de dados censitários utilizando a linguagem Python, em ambiente Google Colab.

Entre os conteúdos previstos, destacam-se:

- Introdução ao ambiente Google Colab e às principais bibliotecas de manipulação de dados.
- Importação e exploração de bases de dados.
- Identificação de variáveis, tipos de dados e unidades territoriais.
- Seleção e filtragem de registros e variáveis.
- Tratamento de dados e identificação de valores ausentes.
- Organização, agregação e análise de informações censitárias.
- Exportação de bases de dados e resultados.

---

## 2. Base de dados utilizada

O workshop utilizará um banco de dados elaborado a partir dos resultados do Universo do Censo Demográfico 2022, publicados pelo IBGE.

O conjunto de dados foi integrado e organizado em formato Parquet, contemplando variáveis de diferentes arquivos temáticos do Censo.

### Características do banco

| Característica | Descrição |
|---|---|
| Fonte original | IBGE — Censo Demográfico 2022 |
| Abrangência geográfica | Minas Gerais |
| Unidade territorial | Setor censitário |
| Número de municípios | 853 |
| Número de setores censitários | 51.387 |
| Número de variáveis | 1.356 |
| Formato | Parquet (.parquet) |
| Tamanho aproximado | 28,50 MB |
| Identificador territorial | `CD_SETOR` |
| Código da unidade da Federação | `CD_UF = 31` |

### Conjuntos temáticos integrados

| Conjunto | Número de variáveis |
|---|---:|
| BASICO | 38 |
| DOM1 | 89 |
| DOM2 | 406 |
| DOM3 | 148 |
| DEM | 36 |
| PAR | 182 |
| COR | 95 |
| ALF | 362 |
| **Total** | **1.356** |

O banco foi estruturado para permitir a exploração conjunta de diferentes características demográficas, domiciliares e territoriais dos setores censitários mineiros.

**Observação:** os dados correspondem a informações agregadas por setor censitário, e não a registros individuais de pessoas ou domicílios.

---

## 3. Materiais do workshop

Os seguintes materiais serão disponibilizados neste diretório:

| Arquivo | Descrição | Situação |
|---|---|---|
| `UNIVERSO_2022_MG.parquet` | Banco de dados de Minas Gerais, com 51.387 setores e 1.356 variáveis | Preparado para publicação |
| `DICIONARIO_COMPLETO_2022_MG.xlsx` | Dicionário de variáveis, descrições, fontes e indicadores de disponibilidade dos dados | Preparado para publicação |
| `workshop_Censo2022_MG.ipynb` | Notebook com os códigos, orientações e exercícios práticos do workshop | Em elaboração |

Os arquivos serão incorporados progressivamente ao repositório.

---

## 4. Ambiente computacional

As atividades práticas serão realizadas no **Google Colab**, ambiente que permite executar códigos Python diretamente pelo navegador, sem necessidade de instalação local.

**Ferramentas previstas:**

- Python
- Google Colab
- Pandas
- Bibliotecas complementares para análise e visualização de dados

Para acompanhar a atividade, recomenda-se possuir uma conta Google e acesso à internet.

### Como utilizar os materiais

1. Acesse o notebook do workshop, quando disponibilizado.
2. Abra o arquivo no Google Colab.
3. Execute as células conforme as orientações apresentadas.
4. Utilize o banco de dados e o dicionário para desenvolver os exercícios propostos.
5. Salve uma cópia do notebook em seu próprio Google Drive, caso deseje preservar as alterações realizadas.

---

## 5. Fonte dos dados e documentação

Os dados originais utilizados neste workshop foram produzidos e disponibilizados pelo **Instituto Brasileiro de Geografia e Estatística (IBGE)**, no âmbito do Censo Demográfico 2022.

O banco disponibilizado neste repositório corresponde a uma versão integrada e organizada dos dados para o estado de Minas Gerais, preparada para fins didáticos.

A integração dos arquivos, a organização do conjunto de dados e a sistematização do dicionário de variáveis foram realizadas por Priscila Kauana Barelli Forcel.

**Fonte original:**

Instituto Brasileiro de Geografia e Estatística (IBGE). Censo Demográfico 2022.

Site: https://www.ibge.gov.br/

O uso dos dados deve considerar as definições das variáveis, as unidades territoriais, as limitações de divulgação e a documentação metodológica disponibilizada pelo IBGE.

---

## 6. Responsável pela atividade

**Priscila Kauana Barelli Forcel**  
Arquiteta e Urbanista | Mestre e Doutoranda em Engenharia Urbana

Programa de Pós-Graduação em Engenharia Urbana (PPGEU)  
Universidade Federal de São Carlos (UFSCar)

**E-mail:** priscilaforcel@ufscar.br  
**GitHub:** https://github.com/PriscilaForcel

---

*Material desenvolvido para fins didáticos, com o objetivo de apoiar a aprendizagem e a aplicação de técnicas de manipulação e análise de dados censitários.*
