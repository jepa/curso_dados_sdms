# Curso de limpeza e análise de dados para realizar modelos de distribuição de espécies

-   Data, 4 a 8 de novembro de 2024

# Ministrantes

-   [Brunno Oliveira](oliveirabrunno.wordpress.com) - Centro de Sínteses e Análises em Biodiversidade, França.

brunno.eco[at]gmail.com

-   [Juliano Palacios](www.julianopalacios.com) - Institute for the Oceans and Fisheries da Universidade da Colúmbia Britânica.

j.palacios[at]oceans.ubc.ca

# Resumo

Neste curso, exploramos a importância da análise de dados na modelagem da distribuição de espécies em ambientes naturais. Discutimos diferentes bases de dados, métodos de limpeza e preparação de dados, e algoritmos para prever onde diferentes espécies podem ser encontradas, considerando fatores como clima e habitat. Analisamos dados, discutimos ferramentas como sistemas de informação geográfica (SIG) e abordagens de modelagem, como MaxEnt e modelos de nicho ecológico.

**Veja o final deste documento para os pre-requisitos**

# Carga horaria

O Curso será impartido de Segunda a Sexta das 9:00 às 12:00hrs que serão divididas em uma a 1.5 horas de teoria e 1-2 horas de prática. Haverá práticas à tarde todos os dias para que os alunos avancem no seu próprio ritmo. Espera-se que os alunos completem a tarefa da tarde antes de cada aula.

# Conteudo

1.  Teoria de nicho ecológico e distribuição de espécies

    i.  Nicho ecológico e distribuição de espécies

2.  Modelos de Distribuição de Espécies (MDE)

    i.  Tipos de modelos Padronização para criação dos modelos

3.  Bases de dados disponíveis para biologia / ecologia

    i.  Principais bases de dados de ocorrências

    ii. Principais bases de dados ambientais

    iii. Como interagir com as bases

    iv. Download de dados ambientais e de ocorrência

4.  Análise e preparo de dados em R

    i.  Dados geoespaciais

    ii. Dados de ocorrências

    iii. Limpeza de dados de ocorrência

5.  Introdução a Modelos de Distribuição de Espécies em R

    i.  Ajuste de MDE

    ii. Avaliação dos modelos

    iii. Predicao de modelos Apresentação de resultados (mapas)

# Pré-Requisitos

O curso completo será impartido no R e GitHub. É preferível que o aluno tenha algum conhecimento prévio em R e GitHub. Faremos um refresco sobre pacotes-chave (por exemplo, tidyverse, ggplot2, etc.), e a totalidade do curso estará disponível no repositório do GitHub.

## Antes do curso

- Instalar a versão de [R version 4.4.1 (2024-06-14) -- "Race for Your Life"](https://www.r-project.org/)

- Instalar o [RStudio](https://www.rstudio.com/)

- Caso precisar, aqui tem um [tutorial de GitHub](https://docs.github.com/pt/get-started/start-your-journey/hello-world)

-   Java Para instalar o pacote rJava no R para rodar o MaxEnt será necessário instalar o Java. [Siga esses passos](https://www.java.com/pt-BR/)

-   *Packages*, Dentro do projeto do curso, execute o seguinte código no terminal para instalar todos os pacotes necesarios para o curso:
  
  `source(paste0(here(),"/sessoes/funcoes_de_apoio/instalar_pacotes.R"))`

Caso nao funcionar, navegue ate o arquivo, abra e execute o script de forma manual

# Referencias 

- Parte do material de este curso foi baseado no curso de [Mauricio Vancine](https://mauriciovancine.github.io/workshop-r-sdm/01_slides/slides_workshop_r_sdm.html#1) e nos [slides](https://mauriciovancine.github.io/slides/slides-sdm-esalq/slides-sdm-esalq.pdf)
- [R for Data Science (2e)](https://r4ds.hadley.nz/)
- [Modelos Ecológicos e a Extinção da Megafauna: clima e homem na América do Sul](https://files.cercomp.ufg.br/weby/up/672/o/Paleoecologia_completo.pdf)
- [Species Distribution Modelling of Bigfoot Encounters Across North America](https://www.cfholbert.com/blog/bigfoot-sdm/)
- [Understanding F1 Score, Accuracy, ROC-AUC, and PR-AUC Metrics for Models](https://www.deepchecks.com/f1-score-accuracy-roc-auc-and-pr-auc-metrics-for-models/)
- [How to explain the ROC curve and ROC AUC score?](https://www.evidentlyai.com/classification-metrics/explain-roc-curve)

# Participantes do curso
Jay
