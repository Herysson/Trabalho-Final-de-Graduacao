# O que a Metodologia deve conter

1. **Objetivo e questões/hipóteses**
   Explique o que você pretende demonstrar/avaliar e formule perguntas ou hipóteses testáveis.

2. **Tipo de pesquisa e desenho do estudo**
   Classifique e detalhe o desenho: experimento controlado, quasi-experimento, estudo de caso, survey, design science, revisão sistemática (SLR), benchmark de sistemas, modelagem matemática/otimização etc. Descreva variáveis independentes/dependentes, fatores e tratamentos (quando houver).

3. **Ambiente, materiais e implementação**

* Hardware: CPU/GPU, RAM, armazenamento, rede.
* Software: SO, bibliotecas (com versões), frameworks, compiladores, solvers.
* Arquitetura/algoritmos: descreva como a solução foi construída (pseudocódigo, diagramas, parâmetros/hiperparâmetros, critério de parada).
* Disponibilize repositório de código/artefatos (link/DOI) e como executar.

4. **Dados (fontes e preparação)**

* Origem dos dados ou instâncias (públicos vs. coletados, critérios de seleção).
* Tamanho, distribuição, balanceamento, limpeza e pré-processamento (normalização, tokenização, feature engineering).
* Divisão treino/validação/teste, k-fold, *hold-out*, *time split*.
* Para SI/estudos com pessoas: amostragem, perfil dos participantes, instrumentos (roteiros, questionários) e anexos.

5. **Procedimentos experimentais / protocolo**

* Passo a passo reproduzível (random seeds, ordem de execução, número de repetições, *warm-up*).
* Baselines e estado-da-arte comparados; justificativa da escolha.
* Estudos de ablação; *hyperparameter tuning* (espaço de busca e estratégia: grid, random, Bayesian).
* Para sistemas: *workloads* (TPC-C, YCSB etc.), cenários, taxas de requisição, *cold/warm cache*.

6. **Métricas e critérios de avaliação**

* ML/Visão/PLN: accuracy, precision/recall/F1, AUC, log-loss, BLEU/ROUGE, mAP.
* Regressão/previsão: MSE/RMSE/MAE, MAPE, R².
* Otimização/OR: valor ótimo, *optimality gap*, tempo, nós de B\&B, memória.
* Sistemas: throughput, latência (p50/p95/p99), uso de CPU/memória, energia.
* Software eng.: cobertura de testes, defeitos/KLOC, esforço, produtividade, usabilidade (SUS), manutenção.

7. **Análise estatística**

* Testes adequados (t, Mann-Whitney, ANOVA/ANCOVA, Kruskal-Wallis), *post-hoc*, correção de múltiplos testes.
* Nível de significância, intervalos de confiança, tamanho de efeito (Cohen’s d, Cliff’s delta).
* Verificação de pressupostos (normalidade, homogeneidade).

8. **Ameaças à validade e mitigação**

* Interna (viés de seleção, aleatorização), externa (generalização), de construção (métricas corretas?), de conclusão (poder estatístico).
* O que você fez para reduzir cada risco (randomizar, *blinding*, replicações, *pilot study*).

9. **Ética, LGPD e consentimento** (quando aplicável)

* Aprovação de comitê de ética; consentimento informado; anonimização/pseudonimização; minimização de dados; base legal de tratamento; armazenamento seguro.

10. **Reprodutibilidade e disponibilidade**

* Seeds, versões, scripts, *container* (Docker), manifesto de execução, *artifact evaluation*.
* Onde estão código, dados e instâncias (DOI/zenodo/figshare/GitHub tag).

