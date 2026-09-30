# Guia Prático: Estruturação e Escrita de TCC e Artigos em Computação

Escrever um Trabalho de Conclusão de Curso (TCC) ou um artigo científico na área de Ciência da Computação e Sistemas de Informação não precisa ser um processo caótico. As melhores publicações internacionais (como IEEE, ACM e Elsevier) seguem um padrão claro chamado **IMRAD** (*Introduction, Methods, Results, and Discussion*).

Este guia ajudará você a organizar suas ideias, estruturar seu documento e escrever com lógica narrativa.

---

## 1. A Regra de Ouro: A Ordem de Escrita Não é a Ordem de Leitura

Um erro muito comum é tentar escrever o TCC da primeira à última página. A redação científica é um processo de "dentro para fora". Comece pelas evidências que você produziu e, a partir delas, construa a história que as sustenta.

**Siga esta sequência na hora de sentar e escrever:**

1. **Métodos e Resultados:** Documente o que você fez, a arquitetura que criou e os dados que obteve enquanto o código ainda está fresco na memória. Crie os gráficos e tabelas primeiro; o texto servirá para explicá-los.
2. **Discussão:** Analise criticamente os seus resultados. Como o seu sistema performou?
3. **Introdução:** Agora que você sabe exatamente o que o trabalho entregou, escreva a introdução focando no problema do mundo real que justifica o que você acabou de apresentar.
4. **Referencial Bibliográfico:** Escreva a revisão da literatura como uma base de sustentação. Ela deve fornecer os conceitos necessários e comprovar a "lacuna" que o seu trabalho preencheu.
5. **Conclusão:** Resuma as descobertas de forma objetiva.
6. **Título e Resumo (Abstract):** Deixe para o final. O resumo é a "vitrine" do seu projeto e só pode ser escrito quando tudo estiver consolidado.

---

## 2. Estrutura Detalhada e Lógica Narrativa

Abaixo, veja como construir cada seção do seu trabalho para garantir fluidez e rigor científico.

### 1. Introdução
* **A Lógica:** É um funil. Você começa falando do contexto geral (o domínio do problema), afunila para a dor específica que ninguém resolveu direito ainda, e finaliza apresentando a sua solução.
* **O que deve ter:**
  - *Contexto e Motivação:* Qual é o cenário atual?
  - *Problema e Lacuna:* O que falta no estado da arte ou na indústria?
  - *Objetivos e Proposta:* O que você fez para resolver isso?
  - *Contribuições:* Uma lista (em *bullet points*) com as entregas exatas do seu trabalho (ex: "Um novo algoritmo de recomendação", "Uma arquitetura de microsserviços para o contexto X").

### 2. Referencial Bibliográfico e Trabalhos Relacionados
* **A Lógica:** Aqui você prova duas coisas: (1) que você domina a teoria por trás do seu projeto e (2) que a sua proposta é, de alguma forma, superior ou diferente do que já existe.
* **O que deve ter:**
  - *Fundamentação Teórica:* Explique apenas os conceitos e tecnologias estritamente necessários para o leitor entender sua solução. Não faça um "dicionário" de termos aleatórios.
  - *Trabalhos Relacionados:* Analise estudos recentes (últimos 5 anos) que tentaram resolver o mesmo problema que você.
  - *Comparação:* Evidencie onde os trabalhos anteriores falham ou são limitados.

### 3. Métodos (A Proposta / Arquitetura)
* **A Lógica:** Deve ser um **manual de replicação**. Um colega da computação deve ser capaz de ler esta seção e recriar o seu sistema ou experimento.
* **O que deve ter:**
  - *Visão Geral:* Explicação de alto nível do sistema ou algoritmo.
  - *Arquitetura/Modelagem:* Diagramas de classes, fluxo de dados, arquitetura em nuvem, etc.
  - *Setup Experimental:* Se for o caso, detalhe de onde vieram os dados, tecnologias utilizadas e ambiente de hardware/software.
  - *Métricas de Avaliação:* Como você vai provar que o trabalho deu certo? (Tempo de resposta, uso de CPU, precisão, recall, etc.).

### 4. Resultados
* **A Lógica:** Direta, factual e neutra. Apenas apresente os fatos. Não emita opiniões nesta seção.
* **O que deve ter:**
  - *Apresentação dos Dados:* Exiba as métricas que você coletou.
  - *Validação:* Mostre que o software atendeu aos requisitos ou que o algoritmo convergiu.
  - *Uso de Elementos Visuais:* Guie o leitor através de tabelas e gráficos. O texto deve referenciar a imagem (ex: "Como visto na Figura 3...").

### 5. Discussão
* **A Lógica:** Aqui você interpreta os dados. É a hora de responder: "O que esses números que eu acabei de apresentar realmente significam?".
* **O que deve ter:**
  - *Análise Crítica:* Por que o desempenho foi bom ou ruim?
  - *Comparação:* Compare seus resultados diretamente com os "Trabalhos Relacionados" da Seção 2.
  - *Limitações:* Todo bom artigo aponta suas próprias falhas. O que o seu sistema não consegue fazer? Houve viés nos dados?

### 6. Conclusão
* **A Lógica:** Uma recapitulação rápida e confiante. Sem novas citações, sem novos gráficos.
* **O que deve ter:**
  - Confirmação de que o objetivo principal foi alcançado.
  - Resumo de 1 ou 2 parágrafos sobre as descobertas de maior impacto.
  - *Trabalhos Futuros:* O que o próximo aluno pode investigar a partir de onde você parou?

---

## 3. Dicas de Ouro para Figuras e Tabelas

Na Ciência da Computação, textos longos cansam. Avaliadores adoram boas representações visuais. Utilize:

1. **Visão de Contexto (Introdução):** Um desenho simples que mostre o problema do mundo real e onde o seu software se encaixa.
2. **Tabela de Trabalhos Relacionados:** Faça uma matriz onde as linhas são os autores/artigos pesquisados e as colunas são as funcionalidades. A última linha deve ser a sua proposta, mostrando (com marcações "X") que ela cobre mais funcionalidades que as demais.
3. **Diagramas Robustos (Métodos):** Utilize padrões da indústria. Faça diagramas BPMN para fluxos de processos de negócio, ou diagramas UML limpos para arquiteturas de software. Ferramentas sugeridas: *Draw.io*, *Lucidchart* ou *PlantUML*.
4. **Gráficos de Desempenho (Resultados):** Utilize gráficos de linha ou barra para mostrar, por exemplo, o tempo de execução do sistema conforme a carga de dados aumenta.
5. **Tabelas Limpas:** Evite grades completas. O padrão acadêmico exige tabelas limpas, sem as linhas verticais separando as colunas (pesquise sobre o formato *booktabs* se for utilizar LaTeX).

---
*Lembre-se: Um bom trabalho acadêmico em computação não é aquele que usa as palavras mais difíceis, mas sim aquele que resolve um problema complexo de forma tão lógica e estruturada que parece simples.*
