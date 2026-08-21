# Fundamentos do Web Design: HTML, CSS e JavaScript
Um caderno temático estruturado para consolidar os pilares do desenvolvimento web front-end, utilizando inteligência artificial como ferramenta de curadoria, síntese e aprendizado acelerado.

## 1. Contexto e Objetivos
Assunto de Interesse: Fundamentos do Web Design (HTML, CSS e JavaScript).

Motivação: No ecossistema atual de desenvolvimento de software, compreender a base da criação de interfaces é essencial não apenas para designers e front-enders, mas para qualquer engenheiro full-stack. Este caderno temático foi estruturado para consolidar a compreensão semântica do HTML, o sistema de estilização moderna do CSS (incluindo Flexbox, Grid e responsividade) e a interatividade orientada a eventos com JavaScript.

Objetivos de Estudo:

Dominar a estruturação de documentos web acessíveis e semanticamente corretos.

Compreender a aplicação prática de layouts modernos utilizando CSS.

Entender a manipulação básica do DOM e a lógica assíncrona com JavaScript.

Estabelecer um fluxo eficiente de estudos utilizando o NotebookLM para gerar resumos, glossários e guias de revisão rápida.

## 2. Curadoria de Fontes
Para alimentar este estudo e garantir embasamento técnico sólido, foram selecionadas 3 fontes abertas de referência na área:

MDN Web Docs - Introdução ao HTML — Guia oficial e definitivo sobre a estrutura básica e semântica de páginas web.

MDN Web Docs - CSS: Primeiros Passos — Documentação fundamental sobre seletores, cascata, herança e modelos de caixa.

JavaScript.info - The Modern JavaScript Tutorial — Referência completa sobre a linguagem, cobrindo desde fundamentos lógicos até manipulação de elementos no navegador.

## 3. Engenharia de Prompts e "Cicatrizes" (Troubleshooting)
Esta seção documenta a evolução dos prompts utilizados para extrair o máximo de precisão e utilidade das fontes carregadas.

Tentativa 1 (Prompt Simples):

Prompt: "O que é HTML, CSS e JavaScript?"

Resultado Obtido: Uma resposta genérica de nível introdutório, superficial e sem conexão prática com os arquivos enviados.

Dificuldade / Cicatriz: Falta de contexto técnico e granularidade. A IA não direcionou o foco para boas práticas de estruturação e semântica.

Tentativa 2 (Prompt Estruturado):

Prompt: "Com base nas fontes enviadas, explique a relação de dependência entre a semântica do HTML, a separação de responsabilidades no CSS e a manipulação do DOM pelo JavaScript. Apresente em formato de tópicos técnicos."

Resultado Obtido: Uma explicação clara conectando a árvore DOM, a estilização em cascata e o comportamento dinâmico.

Dificuldade / Cicatriz: A resposta foi muito extensa. Foi necessário refinar o comando para focar em casos de uso práticos e resumos acionáveis.

Tentativa 3 (Prompt Final Otimizado):

Prompt: "Atue como um Engenheiro Front-End Sênior. A partir das fontes, crie um resumo técnico comparativo destacando por que a separação entre conteúdo (HTML), apresentação (CSS) e comportamento (JS) é crítica para a manutenibilidade de aplicações web modernas."

Resultado Obtido: Excelente nível de profundidade técnica, ideal para compor o guia de estudos final.

## 4. Miniguia de Estudo (Entrega Final)
📌 Resumos Estruturados
HTML (Estrutura e Semântica): O HTML define o esqueleto da aplicação. O uso de tags semânticas (<header>, <main>, <section>, <footer>, <article>) é obrigatório não apenas para a acessibilidade (leitores de tela), mas para o SEO e a legibilidade do código por outros desenvolvedores.

CSS (Apresentação e Layout): Responsável por dar identidade visual e adaptabilidade. O domínio do Modelo de Caixa (Box Model), Flexbox para alinhamentos unidimensionais e CSS Grid para layouts bidimensionais elimina a necessidade de hacks legados.

JavaScript (Comportamento e Dinamismo): Atua diretamente sobre o Document Object Model (DOM). Permite escutar eventos do usuário ( cliques, envios de formulários), manipular estilos em tempo de execução e consumir dados assíncronos.

# 📖 Glossário de Conceitos
DOM (Document Object Model): Representação em árvore estruturada do documento HTML criada pelo navegador, permitindo que linguagens como o JavaScript acessem e modifiquem o conteúdo, estrutura e estilo da página.

Cascata e Especificidade (CSS): Regras que determinam qual regra de estilo será aplicada a um elemento quando há conflitos. A especificidade calcula o "peso" do seletor (IDs > Classes > Tags).

Box Model: Conceito central do CSS que dita que todo elemento HTML é representado como uma caixa retangular composta por margem (margin), borda (border), preenchimento (padding) e conteúdo (content).

Event Bubbling (Borbulhamento de Eventos): Comportamento padrão em que um evento disparado em um elemento filho se propaga para cima através de seus ancestrais na árvore DOM.

# 🔄 Prompts Reutilizáveis para Futuras Revisões
Guarde estes prompts para utilizar em sessões futuras de estudo e revisão no NotebookLM:

Para criar flashcards:

"Com base nas fontes deste caderno, elabore 5 perguntas de múltipla escolha focadas em pegadinhas comuns sobre [assunto específico, ex: Especificidade do CSS], acompanhadas do gabarito comentado."

Para revisão rápida (cheat sheet):

"Gere um resumo em formato de tópicos (bullet points) contendo apenas as propriedades e conceitos essenciais de [HTML/CSS/JS] que eu preciso memorizar para entrevistas técnicas."

Para fixação de código:

"Explique o erro lógico mais comum cometido por iniciantes ao manipular o DOM com JavaScript, utilizando um exemplo prático de código errado vs. código corrigido."

## Link de acesso ao caderno base no NotebookLM: [NotebookLM - Fundamentos do Web Design](https://notebook.google.com/notebook/893a920b-8930-4fde-9fe0-0fa4e2b15bd4)
