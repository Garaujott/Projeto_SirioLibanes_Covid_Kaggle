<!--- https://www.markdownguide.org/basic-syntax/
-->

# Repositório do Projeto de Internação COVID-19 Sírio-Libanês


# :building_construction: **EM CONSTRUÇÃO**
<!---
    Adicionar imagem
-->

## Introdução

Este projeto utiliza os dados disponibilizados pelo Hospital Sírio-Libanês no Kaggle para a partir deles, desenvolver um modelo que seja capaz de prever a necessidade de internação dos pacientes da forma mais rápida possível, ou seja, logo no primeiro atendimento do paciente.

## Dados

Os dados utilizados são dados de pacientes com COVID-19 que foram atendidos nas unidades de São Paulo e Brasília do Hospital Sírio-Libanês. A base foi disponibilizada pelo próprio hospital através da plataforma [Kaggle](https://www.kaggle.com/S%C3%ADrio-Libanes/covid19).

### Pré-processamento dos dados

O pré-processamento realizado na base consistiu em:

* <u>Utilização do MinMaxScaler</u>, deixando as variáveis entre -1 e 1 (etapa realizada pela equipe do Hospital)
* 
* <u>Consolidação do outcome ('internação ou não') de cada visita do paciente em uma observação única </u>, de modo que considera-se apenas os dados da primeira visita (janela 0-2) para realização da previsão. Optou-se por essa abordagem pelo fato de que o interesse aqui é prever o mais cedo possível se o paciente irá necessitar de internação em UTI ou não.

## Modelagem


<!---
    Explicar o tipo de modelo utilizado
-->

## 