# Avaliación comparativa de modelos de lingua na xestión da tradución de expresións multipalabra (EMP) en galego

Este repositorio contén os datos e resultados asociados ao meu traballo de fin de mestrado. O seu obxectivo é avaliar comparativamente o rendemento de tres sistemas de tradución automática (Nós-MT, Vicuna 7B GPTQ e Google Translate) na xestión de expresións multipalabra (EMP) en lingua galega.

## Sobre o estudo

Dada a complexidade das EMP, cuxo significado non sempre é deducible das súas partes, o estudo analiza como modelos baseados na arquitectura Transformer as traducen. A metodoloxía combinou unha avaliación automática (métrica BLEU) cunha análise manual detallada, centrándose na fidelidade semántica e a adecuación idiomática das traducións.

## Resultados destacados

Os resultados cuantitativos e cualitativos obtidos indican o seguinte rendemento en traducións correctas de EMP:

* **Google Translate:** 87,70%
* **Nós-MT:** 78,64%
* **Vicuna 7B GPTQ:** 65,37%

Detectáronse erros recorrentes, como a tradución literal e a mala interpretación da polisemia contextual, especialmente en expresións idiomáticas e composicionais de baixa frecuencia.

## Conclusións principais

O estudo subliña a necesidade de mellorar os recursos e estratexias para o tratamento das EMP en galego, destacando o potencial da especialización lingüística nos modelos de tradución automática.

## Estrutura do repositorio

O recurso principal deste repositorio é unha **folla de cálculo (.xlsx)** que contén:

* O dataset de EMP utilizado.
* As traducións xeradas por Nós-MT, Vicuna 7B GPTQ e Google Translate.
* As traducións de referencia manuais.
* A avaliación cualitativa detallada das traducións dos sistemas.
* As puntuacións BLEU obtidas.
* A clasificación dos tipos de erro atopados nas traducións dos sistemas.

## Palabras chave

expresións multipalabra, lingua galega, avaliación de modelos, tradución automática, procesamento da linguaxe natural.

## Licenza

© **Inés Freire Candame, 2025**. Todos os dereitos reservados.
Prohibida estritamente a reprodución, distribución, modificación ou uso deste contido con calquera fin e por calquera medio sen autorización expresa por escrito da autora.
