# 🧠 Miniguia de Estudos: Lógica de Programação com NotebookLM

> Projeto do desafio da DIO: usar IA como ferramenta de **aprendizagem ativa**, criando um Caderno Temático no NotebookLM a partir de fontes abertas, com curadoria, prompts documentados e um miniguia final.

---

## 1. Contexto e Objetivos

**Tema escolhido:** Lógica de Programação (fundamentos de algoritmos).

**Por que este tema?** Lógica de programação é a base de qualquer linguagem (Python, JavaScript, Java, C#...). Quem domina a lógica aprende qualquer linguagem mais rápido, e é a habilidade que sustenta todo o resto da carreira em tecnologia.

**Objetivos de estudo:**
- Entender o que é um algoritmo e como transformar um problema em passos ordenados.
- Dominar os blocos básicos: variáveis, operadores, condicionais, laços, vetores e funções.
- Conseguir ler e escrever algoritmos em pseudocódigo e fluxograma.
- Aprender a usar o NotebookLM para revisar, tirar dúvidas e gerar exercícios com base em fontes confiáveis.

---

## 2. Curadoria de Fontes

Fontes abertas em texto/PDF carregadas no NotebookLM:

| # | Fonte | Tipo | Link | Por que escolhi |
|---|-------|------|------|-----------------|
| 1 | Apostila – Curso de Lógica de Programação (IFFluminense, 2019) | PDF | [Link](https://educapes.capes.gov.br/bitstream/capes/560827/2/Apostila%20-%20Curso%20de%20L%c3%b3gica%20de%20Programa%c3%a7%c3%a3o.pdf) | Material didático estruturado em módulos, com quizzes e gabaritos. Licença Creative Commons BY-NC 4.0. |
| 2 | Apostila – Introdução à Lógica de Programação (UNESP/FEG) | PDF | [Link](https://www.feg.unesp.br/Home/Pesquisa23/inovee/oficinatecnologica/apostila---introducao-a-logica-de-programacao.compressed.pdf) | Linguagem simples, boa para os conceitos iniciais (lógica, linguagem de programação, instruções). |
| 3 | Apostila – Lógica de Programação (Unicamp, Paulo Sérgio de Moraes) | PDF | [Link](https://sistemas.eel.usp.br/docentes/arquivos/5840003/241/Apostila-LogicadeProgramacao.pdf) | Curso básico completo, com exercícios ao final de cada capítulo. |
| 4 | Lógica de programação: o que é (Blog Locaweb) | Artigo | [Link](https://www.locaweb.com.br/blog/temas/codigo-aberto/logica-de-programacao-o-que-e) | Visão moderna e prática, com exemplos do dia a dia e relação entre lógica e algoritmos. |

**Critérios de seleção:** conteúdo em português, acesso gratuito, origem confiável (instituições de ensino) e fontes que se complementam (duas mais formais, uma mais completa e uma mais prática).

> ⚠️ Confira a licença de cada material antes de redistribuir. Neste repositório eu **apenas linko** as fontes.

---

## 3. Engenharia de Prompts e "Cicatrizes"

> Em cada teste, registrei o prompt, o resultado, o problema encontrado e a versão melhorada.
> **Substitua os campos `[preencher]` pelo que realmente aconteceu no seu NotebookLM.** O que o mercado valoriza é o seu raciocínio real.

### Teste 1: Entender o conceito central

- **Prompt v1:** `O que é lógica de programação?`
- **Resultado v1:** `[preencher: a resposta veio genérica? citou as fontes?]`
- **Problema encontrado:** `[preencher]`
- **Prompt v2:** `Com base apenas nas fontes, explique o que é lógica de programação em até 5 linhas, para um iniciante, e diga qual fonte usou em cada ideia.`
- **Resultado v2 e referências:** `[preencher]`
- **Aprendizado:** Pedir formato, tamanho, público e citação de fonte tende a dar respostas mais úteis e verificáveis.

### Teste 2: Diferença entre lógica, algoritmo e programa

- **Prompt v1:** `Qual a diferença entre lógica e algoritmo?`
- **Prompt v2:** `Monte uma tabela comparando lógica de programação, algoritmo e programa, com definição e um exemplo do cotidiano para cada um.`
- **Resultado / referências:** `[preencher]`
- **Problema encontrado:** `[preencher]`

### Teste 3: Estruturas de controle

- **Prompt v1:** `Explique if e while.`
- **Prompt v2:** `Explique estruturas condicionais e de repetição usando pseudocódigo. Dê um exemplo de cada, com o problema resolvido passo a passo.`
- **Resultado / referências:** `[preencher]`
- **Problema encontrado:** `[preencher: por exemplo, as fontes usam pseudocódigos diferentes (Portugol, VisuAlg)?]`

### Teste 4: Conflito entre fontes

- **Prompt:** `Existe alguma diferença de abordagem ou terminologia entre as fontes sobre algoritmos? Aponte onde divergem.`
- **Resultado / referências:** `[preencher]`

### Teste 5: Prática ativa

- **Prompt v1:** `Me dê exercícios de lógica.`
- **Prompt v2:** `Crie 5 exercícios de lógica de programação em ordem crescente de dificuldade (sequência, condicional, laço, vetor, função), sem resposta. Depois eu envio as minhas soluções para você corrigir.`
- **Resultado / referências:** `[preencher]`

### 🩹 Cicatrizes (troubleshooting)

Registre aqui, com suas palavras, o que deu errado e como resolveu. Pontos que vale observar durante os testes:

- [ ] A IA respondeu com conhecimento geral em vez de usar as fontes? → Reforcei com "com base apenas nas fontes".
- [ ] A resposta veio longa e sem estrutura? → Pedi formato (tabela, tópicos, limite de linhas).
- [ ] Houve termo que não aparece nas fontes? → Conferi a citação e o trecho original.
- [ ] Fontes com pseudocódigos diferentes geraram confusão? → Pedi para padronizar um só formato.

---

## 4. Miniguia de Estudo (Entrega Final)

> Rascunho baseado nos conceitos tratados nas fontes. Valide e ajuste com as respostas do seu NotebookLM.

### 4.1 Resumos estruturados

#### 1) O que é lógica de programação e algoritmo
- **Lógica de programação** é a habilidade de analisar um problema e descrevê-lo como uma sequência ordenada de passos. Ela independe da linguagem.
- **Algoritmo** é a sequência finita de passos bem definidos que resolve um problema (a "receita"). A lógica é o raciocínio usado para construí-lo.
- O computador só executa o que é instruído, então o algoritmo precisa ser **claro, ordenado e sem ambiguidade**.
- Um algoritmo pode ser representado por **descrição narrativa**, **fluxograma** ou **pseudocódigo**.

#### 2) Dados: variáveis, constantes e tipos
- **Variável:** espaço na memória com nome, cujo valor pode mudar.
- **Constante:** valor que não muda durante a execução.
- **Tipos de dados comuns:** inteiro, real, texto (caractere/string) e lógico (verdadeiro/falso).
- **Entrada e saída:** ler dados do usuário e mostrar resultados.

#### 3) Operadores e expressões
- **Aritméticos:** `+`, `-`, `*`, `/`, resto da divisão.
- **Relacionais:** `=`, `<>`, `>`, `<`, `>=`, `<=` (resultam em verdadeiro ou falso).
- **Lógicos:** `E`, `OU`, `NÃO`, usados para combinar condições.

#### 4) Estruturas de controle
- **Sequencial:** as instruções executam uma após a outra.
- **Condicional (decisão):** executa um caminho conforme uma condição.
- **Repetição (laço):** repete um bloco enquanto uma condição valer ou por um número de vezes.

```text
// Exemplo em pseudocódigo: média de um aluno
leia nota1, nota2
media <- (nota1 + nota2) / 2
se media >= 7 entao
    escreva "Aprovado"
senao
    escreva "Reprovado"
fimse
```

```text
// Exemplo de repetição: soma de 1 a 10
soma <- 0
para i de 1 ate 10 faca
    soma <- soma + i
fimpara
escreva soma
```

#### 5) Estruturas de dados e modularização
- **Vetor (array):** conjunto de valores do mesmo tipo acessados por índice.
- **Matriz:** vetor com mais de uma dimensão (linhas e colunas).
- **Função/procedimento:** bloco reutilizável com um nome, que pode receber parâmetros e devolver um resultado. Evita repetição e organiza o código.

#### 6) Teste e depuração
- **Teste de mesa:** simular o algoritmo no papel, passo a passo, acompanhando os valores das variáveis.
- **Depuração:** encontrar e corrigir erros. Existem erros de **sintaxe** (escrita) e de **lógica** (o programa roda, mas o resultado está errado).

### 4.2 Glossário

| Termo | Definição |
|-------|-----------|
| Algoritmo | Sequência finita e ordenada de passos para resolver um problema. |
| Lógica de programação | Raciocínio usado para organizar e encadear instruções que resolvem um problema. |
| Pseudocódigo | Forma de escrever algoritmos em linguagem próxima da humana, sem depender de uma linguagem real. |
| Fluxograma | Representação gráfica do algoritmo com símbolos e setas. |
| Variável | Espaço nomeado na memória cujo valor pode mudar. |
| Constante | Valor fixo durante a execução. |
| Tipo de dado | Categoria do valor (inteiro, real, texto, lógico). |
| Operador | Símbolo que realiza uma operação (aritmética, relacional ou lógica). |
| Expressão | Combinação de valores, variáveis e operadores que resulta em um valor. |
| Condicional | Estrutura que escolhe um caminho conforme uma condição (`se/senão`). |
| Laço (loop) | Estrutura que repete instruções (`para`, `enquanto`, `repita`). |
| Vetor | Coleção de elementos do mesmo tipo acessados por posição (índice). |
| Matriz | Vetor de duas ou mais dimensões. |
| Função | Bloco de código reutilizável, com nome, que pode receber parâmetros e retornar valor. |
| Parâmetro | Dado enviado a uma função para ela trabalhar. |
| Entrada / Saída | Leitura de dados do usuário / exibição de resultados. |
| Sintaxe | Regras de escrita de uma linguagem. |
| Bug | Erro no programa que causa comportamento incorreto. |
| Depuração (debug) | Processo de localizar e corrigir erros. |
| Teste de mesa | Simulação manual da execução do algoritmo para verificar se está correto. |
| Recursividade | Técnica em que uma função chama a si mesma para resolver um problema em partes menores. |
| Compilador / Interpretador | Programas que traduzem o código para uma forma que o computador executa. |

### 4.3 Prompts reutilizáveis para revisão

Copie, troque o que está entre `[colchetes]` e use no NotebookLM:

1. **Explicação simples:** `Explique [conceito] para um iniciante, em até 5 linhas, usando um exemplo do dia a dia e citando a fonte.`
2. **Comparação:** `Compare [conceito A] e [conceito B] em uma tabela com definição, quando usar e exemplo.`
3. **Passo a passo:** `Resolva o problema "[enunciado]" em pseudocódigo, explicando cada linha.`
4. **Quiz:** `Crie 5 perguntas de múltipla escolha sobre [tópico], com gabarito e justificativa de cada alternativa.`
5. **Correção:** `Vou enviar meu algoritmo para "[problema]". Aponte erros de lógica, sugira melhorias e NÃO reescreva tudo, apenas me dê dicas.`
6. **Teste de mesa:** `Faça o teste de mesa deste algoritmo com as entradas [valores], mostrando o valor das variáveis a cada passo.`
7. **Revisão espaçada:** `Faça 10 flashcards (pergunta e resposta curta) dos principais conceitos de [tópico].`
8. **Checagem de fontes:** `Onde as fontes divergem sobre [tema]? Cite os trechos e as fontes.`
9. **Plano de estudo:** `Monte um plano de 2 semanas para praticar [tópico], com 30 minutos por dia, indo do básico ao intermediário.`
10. **Resumo de véspera:** `Resuma em 1 página os pontos mais importantes de [tópico] que eu preciso lembrar.`

---

## 5. Aprendizados

- Prompts específicos (formato, público, limite, exigência de fonte) rendem respostas muito melhores do que perguntas soltas.
- Conferir as citações do NotebookLM é essencial para não confiar cegamente na IA.
- Pedir exercícios e correção transforma a IA em um **tutor**, não em um "resolvedor de tarefas".
- `[preencher com suas conclusões pessoais]`

---

## 6. Como reproduzir

1. Crie um caderno no [NotebookLM](https://notebooklm.google.com/).
2. Adicione as fontes da seção 2.
3. Execute os prompts da seção 3 e compare com meus resultados.
4. Use os prompts da seção 4.3 para revisar.

---

**Autor:** Felipe
