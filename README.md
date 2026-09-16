# Miniguia-de-estudos-NotebookLM
tema: conceitos básicos de Java Script

**Índice**

1. Contexto e Objetivos
2. Curadoria de Fontes
3. Engenharia de Prompts e Ajustes
4. Miniguia de Estudo

**Contexto e Objetivos**

Neste projeto, decidi aproveitar a oportunidade para melhorar meus estudos quanto aos fundamentos de Java Script, pondo em prática o que estudei sobre engenharia de prompts. 
Utilizei fontes variadas, desde vídeo aulas até guias de empresas amplamente reconhecidas na área, com a ideia de que a teoria em conjunto com ensino mais didático, formularia uma boa base de dados para um mini guia de estudos.
Meus principais objetivos com esse material é de consolidar meu aprendizado, usando o NotebookLM ( Gemini LM ) como ferramenta, utilizando de suas opções de estudo para maximizar as maneiras de aprendizagem, com intenção de encontrar a ideal para respectivas situações.

**Curadoria de Fontes**

( "O manual de JavaScript para iniciantes" - FreeCodeCamp )
https://www.freecodecamp.org/portuguese/news/o-manual-de-javascript-para-iniciantes/
( "Noções básicas de JavaScript" - MDN Web Docs )
https://developer.mozilla.org/pt-BR/docs/Learn_web_development/Getting_started/Your_first_website/Adding_interactivity
( "Curso de Javascript 🟨" - Rafaella Ballerini )
https://youtu.be/Z7mnxUI4u00?si=GvQTjdbHEaWGUivH
https://youtu.be/kwOPAQJDGyI?si=hP2_Q_TbGVfgDYcr
https://youtu.be/c-D7uV2CiFQ?si=tIFRuyg-1TQxgFcN
https://youtu.be/IuCZPOk5EXo?si=JV-IpezfW_jIb8RT
https://youtu.be/RjfhRZXB_U8?si=p55CAzwUXx9TRcld
https://youtu.be/rvBdC3Ziwg8?si=2ZmbX7OKUvJEQlPh

**Engenharia de Prompts e Ajustes**

1° tentativa 
"explique os fundamentos de JS. (intro)
separe os conteúdos por módulos,
faça uma lista com os caracteres,
em seguida contextualize e explique de forma didatica,
adicione exemplos práticos.(saída)"
inicialmente fiz apenas um prompt simples, pedindo o mínimo necessário para conseguir a resposta que queria, utilizando apenas uma introdução, acompanhada por um modelo de saída simples.  

2° tentativa 
"explique os fundamentos de JS.(intro)
um mini guia para estudos para alguém que está tendo os primeiros contatos com a linguagem.(contexto)
separe os conteúdos por módulos,
faça uma lista com os caracteres,
em seguida contextualize e explique de forma didática,
adicione exemplos práticos.(saída)
evite usar termos de natureza técnica nos exemplos e explicações (pode adiciona-los como curiosidade).(limitações)"
aqui já havia percebido que poderia melhorar a reposta, adicionei mais tópicos a estrutura do meu prompt, querendo refinar a reposta, buscando explicações mais claras, e uma organização um pouco diferente, tirando os termos técnicos das explicações e adicionando abaixo, com uma explicação mais detalhada. 

3° tentativa(final)
"explique os fundamentos de JS.(intro)
um mini guia para estudos para alguém que está tendo os primeiros contatos com a linguagem, mas já tenha certo conhecimento de outras e Logica de programação.(contexto)
separe os conteúdos por módulos,
faça uma lista com os caracteres,
em seguida contextualize e explique de forma didática,
adicione exemplos práticos.(saída)
evite usar termos de natureza técnica nos exemplos ( pode adiciona-los como curiosidade ).(limitações)"
a 2° estava boa, mas não estava tão interligada com o meio em que estou, então adicionei um pouco mais de contexto e consegui um ótimo resultado.

**Miniguia de Estudo**

"Este **mini guia de estudos** foi estruturado para quem já tem noção de lógica de programação e de outras linguagens, focando nas particularidades e nos conceitos centrais do **JavaScript**.

---

### 🔣 Lista de Caracteres e Símbolos em JavaScript

Abaixo estão os símbolos que formam a sintaxe da linguagem e o papel que desempenham:

*   `;` **(Ponto e vírgula)**: Utilizado para marcar o fim de uma instrução. Em JavaScript, a inclusão de ponto e vírgula ao final das linhas é **opcional** na maioria dos casos, pois o interpretador consegue reconhecer o fim das instruções.
*   `=` **(Sinal de atribuição)**: Guarda um valor ou informação dentro de um espaço reservado na memória.
*   `==` / `===` **(Testes de igualdade)**: Comparam dois valores. *(💡 Curiosidade técnica: o operador `==` compara apenas os valores realizando conversão implícita de tipos, enquanto o `===` faz a igualdade estrita sem converter os tipos).*
*   `!=` / `!==` **(Testes de diferença)**: Verificam se dois valores não são iguais.
*   `()` **(Parênteses)**: Delimitam condições de teste e envolvem informações enviadas para a execução de tarefas.
*   `{}` **(Chaves)**: Delimitam um bloco agrupado de instruções ou definem a estrutura de uma ficha de dados.
*   `[]` **(Colchetes)**: Utilizados para criar listas de itens e para buscar um item específico através do seu número de posição.
*   `.` **(Ponto)**: Permite acessar propriedades, detalhes internos ou ações associadas a uma estrutura ou elemento.
*   `,` **(Vírgula)**: Separa itens em uma lista ou múltiplos dados enviados para uma ação.
*   `""` / `''` / `` ` `` **(Aspas duplas, simples e crases)**: Envolvem trechos de texto. As crases permitem intercalar dados de forma direta no texto.
*   `${}` **(Interpolação em crases)**: Estrutura usada dentro de textos com crase para inserir dados dinâmicos.
*   `//` / `/* */` **(Barras de nota)**: Indicam anotações explicativas no código que o computador ignora completamente ao rodar o programa.
*   `+`, `-`, `*`, `/`, `%`, `**` **(Operadores matemáticos)**: Executam somas (ou junção de textos com `+`), subtrações, multiplicações, divisões, resto da divisão (`%`) e potenciação (`**`).
*   `&&`, `||`, `!` **(Conectores lógicos)**: Representam as condições **E** (`&&`), **OU** (`||`) e a injeção de negação/inversão **NÃO** (`!`).
*   `=>` **(Seta)**: Sintaxe enxuta para indicar a criação de uma ação.

---

### 📚 Módulos de Estudo dos Fundamentos

---

#### Módulo 1: Armazenamento e Natureza dos Dados

Em JavaScript, os espaços de memória usados para guardar informações funcionam como **caixas etiquetadas**. A linguagem trata dados de duas formas fundamentais: referências fixas e referências flexíveis.

*   **Valores Fixos**: Usados para guardar dados que não devem ser substituídos ao longo da execução.
*   **Valores Flexíveis**: Usados para guardar dados que mudam ao longo do tempo.
*   **Variabilidade de Conteúdo**: Uma mesma caixa pode guardar diferentes tipos de dados (como um texto, um número ou um valor de verdadeiro/falso) sem precisar especificar o tipo previamente.

##### Exemplo Prático
```javascript
// Criando uma referência fixa para o nome da aplicação
const nomeDoSistema = "Gerenciador de Compras";

// Criando uma referência flexível para a contagem de itens
let totalDeItens = 0;

// O usuário adicionou um item, atualizamos a caixinha
totalDeItens = 1;
```

> 💡 **Curiosidade Técnica**: Na terminologia da linguagem, a criação de variáveis é feita com as palavras-chave `const` (para referências constantes que não permitem reatribuição), `let` (para variáveis com escopo de bloco) e `var` (forma legada com escopo de função e sujeita a *hoisting*). Os tipos de dados dividem-se em **tipos primitivos** (*string*, *number*, *boolean*, *null*, *undefined*, *symbol*) e **objetos**.

---

#### Módulo 2: Comparações, Operações e Textos

Diferente de algumas linguagens que convertem tipos automaticamente durante comparações, o JavaScript possui regras específicas de verificação rigorosa.

Além disso, a união de textos com dados pode ser feita concatenando as partes com o sinal `+` ou através de textos delimitados por crases, onde os dados são inseridos diretamente dentro da marcação `${}`.

##### Exemplo Prático
```javascript
let precoOriginal = 100;
let desconto = 15;
let precoFinal = precoOriginal - desconto;

let clienteValido = true;
let nomeCliente = "Carlos";

// Montando o texto final com crases e inserção direta
let mensagem = `Olá ${nomeCliente}, o preço final da sua compra é R$ ${precoFinal}.`;
```

> 💡 **Curiosidade Técnica**: O recurso de montagem de textos com crases é chamado de *template literals*. Ao comparar valores, o uso de `===` é chamado de **igualdade estrita**, pois impede a conversão implícita de tipos (*type coercion*) que ocorre ao utilizar `==`.

---

#### Módulo 3: Tomada de Decisões, Repetições e Visibilidade

As estruturas de decisão e repetição controlam o fluxo da aplicação:

*   **Testes de Condição**: Executam um bloco de instruções caso uma regra seja atendida; caso contrário, podem seguir por um caminho alternativo.
*   **Laços de Repetição**: Iteram sobre uma sequência de passos enquanto uma condição for satisfeita ou até percorrer todos os itens de uma lista.
*   **Visibilidade**: Tudo o que é criado dentro de um bloco delimitado por chaves `{}` só fica visível e acessível dentro daquele próprio bloco.

##### Exemplo Prático
```javascript
// Teste de decisão simples
let campoDeEntrada = "";

if (campoDeEntrada === "") {
  // Executado se estiver em branco
  let aviso = "Por favor, preencha o campo!";
} else {
  // Executado se houver conteúdo
  let aviso = "Dados salvos com sucesso!";
}

// Repetição percorrendo uma lista de tarefas
const afazeres = ["Estudar", "Fazer exercícios", "Ler"];

for (let item of afazeres) {
  // Repete a exibição para cada item da lista
}
```

> 💡 **Curiosidade Técnica**: As estruturas condicionais utilizam o bloco `if...else`. Para repetições, o JavaScript oferece variações como o laço tradicional `for` (composto por inicializador, condição e incremento), o laço `while`, o `do...while` e o `for...of`. A restrição de visibilidade dentro das chaves chama-se **escopo de bloco** (*block scope*).

---

#### Módulo 4: Blocos de Ação Reutilizáveis (Funções)

Quando uma sequência de passos precisa ser reaproveitada em vários pontos do programa, ela é agrupada sob uma **receita de ação com nome**. Ao chamar o nome dessa ação, todas as suas instruções internas são executadas e um valor pode ser devolvido ao final.

O JavaScript permite definir essas ações na sintaxe tradicional ou em formatos mais modernos e enxutos utilizando a **seta (`=>`)**.

##### Exemplo Prático
```javascript
// Definindo uma receita de ação tradicional que recebe dois valores e devolve a soma
function somarValores(valorA, valorB) {
  return valorA + valorB;
}

// Criando a mesma ação usando o formato de seta
const multiplicarValores = (a, b) => a * b;

// Executando as ações
let resultadoSoma = somarValores(10, 20); // Retorna 30
let resultadoMultiplicacao = multiplicarValores(4, 5); // Retorna 20
```

> 💡 **Curiosidade Técnica**: Blocos reutilizáveis são chamados de **funções** (`functions`). Os dados recebidos entre parênteses são os **parâmetros** (ou argumentos) e a palavra-chave `return` especifica o valor de retorno. As funções declaradas com a seta `=>` são chamadas de *Arrow Functions* e possuem sintaxe anônima com retorno implícito em instruções de linha única.

---

#### Módulo 5: Coleções de Dados (Listas e Fichas)

Para organizar conjuntos complexos de informações sem criar dezenas de referências soltas, o JavaScript fornece duas estruturas principais:

1.  **Listas Ordenadas**: Conjuntos de elementos em fila delimitados por colchetes `[]`, onde cada item ocupa uma posição numerada que se inicia do número **zero (`0`)**.
2.  **Fichas de Detalhes**: Conjuntos de propriedades organizadas dentro de chaves `{}` sob a estrutura de **rótulo e valor**.

##### Exemplo Prático
```javascript
// Criando uma lista ordenada de frutas
const listaDeFrutas = ["Maçã", "Banana", "Mamão"];

// Acessando o primeiro item da lista (posição 0)
let primeiraFruta = listaDeFrutas; // "Maçã"

// Adicionando um novo item ao final da lista
listaDeFrutas.push("Melancia");

// Criando uma ficha de detalhes de um produto
const produto = {
  nome: "Teclado",
  preco: 150,
  emEstoque: true
};

// Acessando um detalhe da ficha
let nomeDoProduto = produto.nome; // "Teclado"
```

> 💡 **Curiosidade Técnica**: As listas são chamadas de **Arrays** e suas posições são chamadas de **índices** (*index*). Métodos integrados como `.push()` adicionam elementos ao final e `.splice()` altera/remove itens. As fichas são **Objetos** (compostos de pares chave-valor). Importante notar que objetos e arrays são passados por **referência na memória** e não por cópia de valor.

---

#### Módulo 6: Interatividade com a Página Web

No ambiente do navegador, o JavaScript acessa a estrutura da página HTML a partir de um comando centralizador (`document`). Ele consegue buscar elementos, alterar textos na tela, ler dados digitados pelo usuário e reagir a eventos (como cliques em botões).

##### Exemplo Prático
```javascript
// Buscando um elemento da tela pelo seu identificador
const caixaDeTexto = document.getElementById("mensagem");
const botaoEnviar = document.getElementById("meuBotao");
const campoDeInput = document.getElementById("inputTarefa");

// Configurando uma reação para quando o usuário clicar no botão
botaoEnviar.onclick = () => {
  // Lê o valor digitado no campo de entrada
  let textoDigitado = campoDeInput.value;
  
  // Altera o texto exibido na tela
  caixaDeTexto.textContent = `Você digitou: ${textoDigitado}`;
};
```

> 💡 **Curiosidade Técnica**: A representação da página HTML acessível via código é conhecida como **DOM (Document Object Model)**. Funções como `getElementById()` e `querySelector()` selecionam elementos na árvore do DOM. As reações a ações do usuário utilizam **manipuladores de eventos** (*event handlers* / `addEventListener`), e as entradas de formulário são lidas através da propriedade `.value` do elemento.

---

💡 **Qual destes módulos você gostaria de aprofundar primeiro com exemplos práticos ou pequenos exercícios de fixação?**"

Prompt: 
"explique os fundamentos de JS.
um mini guia para estudos para alguém que está tendo os primeiros contatos com a linguagem.
separe os conteúdos por módulos,
faça uma lista com os caracteres,
em seguida contextualize e explique de forma didática,
adicione exemplos práticos.
evite usar termos de natureza técnica nos exemplos e explicações (pode adiciona-los como curiosidade)"

**Prompt utilizado:**
"explique os fundamentos de JS.
um mini guia para estudos para alguém que está tendo os primeiros contatos com a linguagem.
separe os conteúdos por módulos,
faça uma lista com os caracteres,
em seguida contextualize e explique de forma didática,
adicione exemplos práticos.
evite usar termos de natureza técnica nos exemplos e explicações (pode adiciona-los como curiosidade)"

