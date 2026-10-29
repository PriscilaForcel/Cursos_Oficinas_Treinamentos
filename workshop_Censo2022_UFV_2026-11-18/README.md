# Workshop | Análise de dados urbanos com o Censo Demográfico 2022 no Google Colab

**Estatística, visualização e mapas**

## 1. Apresentação

Este diretório reúne materiais didáticos, bases de dados e recursos computacionais associados ao workshop *Análise de dados urbanos com o Censo Demográfico 2022 no Google Colab: estatística, visualização e mapas*, realizado no âmbito do Programa de Pós-Graduação em Arquitetura e Urbanismo da Universidade Federal de Viçosa (UFV).

A atividade tem como objetivo capacitar participantes para a análise aplicada de dados do Censo Demográfico 2022, utilizando Python e Google Colab, com ênfase nos estudos urbanos e de infraestrutura.

O workshop explora diferentes escalas de análise dos dados censitários, especialmente os agregados por setores censitários, e suas possibilidades para a investigação das desigualdades intraurbanas.

## 2. Programação

**Introdução à manipulação e análise de dados censitários**

- Introdução ao ambiente Google Colab e ao ecossistema Python.
- Utilização das bibliotecas Pandas e NumPy.
- Importação e exploração de bases do Censo Demográfico 2022.
- Limpeza, organização e tratamento de dados.
- Estatística descritiva aplicada a variáveis socioeconômicas e domiciliares.

**Análise espacial e aplicações de aprendizado de máquina em estudos urbanos**

- Introdução à análise espacial com GeoPandas e Folium.
- Integração de dados censitários e informações territoriais.
- Noções metodológicas de desagregação de dados em pequenas áreas.
- Estruturação de variáveis explicativas e introdução a modelos preditivos interpretáveis.
- Construção e interpretação de mapas temáticos.
- Discussão sobre as potencialidades e limitações das ferramentas computacionais para o planejamento urbano.

## 3. Base de dados

Para as atividades práticas, foi organizado um banco de dados com resultados do Universo do Censo Demográfico 2022, disponibilizados pelo Instituto Brasileiro de Geografia e Estatística (IBGE).

O banco integra informações de oito conjuntos temáticos e contempla os setores censitários de Minas Gerais.

| Característica | Informação |
|---|---|
| Fonte original | IBGE — Censo Demográfico 2022 |
| Abrangência | Minas Gerais |
| Escala territorial | Setor censitário |
| Municípios | 853 |
| Setores censitários | 51.387 |
| Variáveis | 1.356 |
| Formato | Parquet |
| Tamanho aproximado | 28,50 MiB |
| Identificador principal | `CD_SETOR` |

**Conjuntos integrados:** BASICO, DOM1, DOM2, DOM3, DEM, PAR, COR e ALF.

Os dados correspondem a informações agregadas territorialmente, não a registros individuais de pessoas ou domicílios.

## 4. Materiais disponíveis

| Material | Descrição | Acesso |
|---|---|---|
| Banco de dados | Universo do Censo 2022 — Minas Gerais | [Baixar Parquet](./dados/UNIVERSO_2022_MG.parquet) |
| Dicionário de variáveis | Descrições, fontes e informações de disponibilidade das 1.356 variáveis | [Baixar Excel](./dicionario/DICIONARIO_COMPLETO_2022_MG.xlsx) |
| Dicionário em CSV | Versão para processamento computacional | [Baixar CSV](./dicionario/DICIONARIO_COMPLETO_2022_MG.csv) |
| Notebook do workshop | Códigos, orientações e exercícios práticos | Em elaboração |

O notebook será incorporado a este diretório após sua preparação.

## 5. Requisitos para participação

- Conhecimentos básicos de Python e da biblioteca Pandas.
- Conta Google para utilização do Google Colab.
- Acesso à internet.

O workshop é gratuito, com vagas limitadas, conforme as informações de inscrição divulgadas pela UFV.

## 6. Fonte dos dados e procedimentos de organização

**Fonte original:** Instituto Brasileiro de Geografia e Estatística (IBGE). Censo Demográfico 2022 — Resultados do Universo.

O banco disponibilizado foi preparado a partir da integração de arquivos temáticos dos resultados do Universo, com recorte territorial para Minas Gerais e organização em formato Parquet.

O dicionário reúne descrições das variáveis e informações estatísticas sobre sua disponibilidade nos setores censitários mineiros.

A integração dos arquivos, a organização do banco e a sistematização do dicionário foram realizadas por Priscila Kauana Barelli Forcel.

Os usuários devem consultar a documentação original do IBGE para a correta interpretação das variáveis, dos códigos especiais e das limitações de divulgação.

## 7. Vinculação acadêmica e apoio à pesquisa

Priscila Kauana Barelli Forcel é arquiteta e urbanista, mestre e doutoranda em Engenharia Urbana pelo Programa de Pós-Graduação em Engenharia Urbana da Universidade Federal de São Carlos (PPGEU/UFSCar).

Sua participação no segundo encontro está relacionada aos métodos e procedimentos de análise territorial e aprendizado de máquina desenvolvidos no âmbito de sua pesquisa de doutorado, apoiada pela Fundação de Amparo à Pesquisa do Estado de São Paulo (FAPESP).

**Apoio à pesquisa:** FAPESP — Processo nº 2025/08490-4.

As opiniões, hipóteses e conclusões ou recomendações expressas neste material são de responsabilidade dos autores e não necessariamente refletem a visão da FAPESP.

## 8. Contato

**Priscila Kauana Barelli Forcel**  
Programa de Pós-Graduação em Engenharia Urbana — UFSCar

E-mail: priscilaforcel@ufscar.br  
GitHub: https://github.com/PriscilaForcel

---

*Materiais de apoio à formação em análise de dados censitários, geoprocessamento e aplicações computacionais para estudos urbanos.*
