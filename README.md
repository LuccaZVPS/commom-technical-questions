# Perguntas comuns em entrevistas técnicas

### 1 - O que é DOM?

O DOM é a sigla de Document Object Model. O DOM é uma cópia da arvore de elementos de uma interface HTML. Graças ao DOM, podemos manipular elementos da interface através do Javascript.

### 2 - Quais a diferença do html5 pro html4?

- O HTML5 possuí mais tags. Tags como o Footer, Article, Audio e Video não estão disponíveis em outras versões HTML.

- O HTML4 não tem suporte para nenhuma tag de multimídia.

- O HTML4 não tem suporte ao Canvas.

- O HTML5 tem suporte para navegação offline.

### 3 - Quantas tags de h1 existem?

Apenas uma.

### 4 - Qual a diferença de div para um spam?

- O Span deve ser utilizado para divisões a nível de linha.

- A Div deve ser utilizada para criar divisões entre blocos de tags.

- O Span não gera uma quebra de linha ao ser adicionado.

### 5 - Cite algumas técnicas de SEO

- Utilizar a meta tag Description.
- Utilizar a meta tag Title.
- Utilizar tags HTML de forma semântica.
- Utilizar texto alternativo em imagens.
- Usar as tags de Heading.
- Descrever os elementos do site através do Shchema markup.

### 6 - Cite técnicas pra deixar um site mais performático.

### 7 - Cite algumas técnicas de acessibilidade.

- Moderar no uso de cores.
- Usar tags de maneira semântica
- Texto alternativo em imagens.
- Links com textos descritivos. Evite colocar o famoso "clique aqui".
- Use Label nos inputs

### 8 - Como você estrutura sua aplicação?

——

### 9 - que é SASS?

O SASS é um pré-processador CSS. Uma ótima opção para melhorar nossa produtividade com o CSS.

Motivos para usar SASS:

- nested syntax.
- separar nosso código em blocos com o mixin.
- boa documentação.
- partials.

### 10 - Qual a diferença de position: relative e absolute?

- Se adicionarmos o position relative em um elemento, sua posição continuará a mesma. Se pergarmos este mesmo elemento e adicionarmos uma propiedade "Left" com 20 px de valor, o elemento irá se mover 20px para a esquerda da sua posição inicial. Sendo assim, toda atribuição de posição(top,bottom,left,right) terá como ponto de partida a posição inicial do elemento.

- Já com position absolute, as propiedades de direção terão como ponto de partida o próprio body da página ou seu elemento pai(se estiver com position relative).

### 11 - Qual a diferença entre classe e id?

O ID deve ser utilizado para nomear um elemento de forma única, sem que hajam ids repetidos. Já as classes permitem nomear múltiplos elementos com o mesmo nome.

### 12 - Pq o CSS Modules é tão vantajoso?

Permite utilizarmos nomes de classes iguais em diferentes arquivos css sem que haja conflitos de propiedade.

### 13 - Quais as boas práticas que você utiliza na hora de escrever CSS?

- Poupar código com o uso de variáveis.
- Evitar divs vazias com propiedade after e before.
- Propriedades shorthand.
- mobile first.

### 14 - Quando podemos usar o before ou after?

As propriedades after e before devem ser útilizadas para evitarmos tags vazias em nosso código HTML.

——

### 15 - Qual a diferença de DOM pra o Virtual DOM?

- O DOM sempre está sincronizado com nosso código HTML. Ao alteramos o DOM, o conteúdo HTML da página será alterado logo em seguida.
- O DOM virtual é uma cópia em mémoria do DOM. Todas as alterações feitas no DOM virtual são "passadas" para o DOM quando o estado da nossa aplicação for alterado.

-

### 16 - O que é hook?

São funções nativas do React que nos permitem utilizar o estado, ciclo de vida e outras funcionalidades em nossa aplicação.

### 17 - Como funciona o useEffect?

- Função nativa do React que recebe dois parâmetros.
- O primeiro parâmetro é uma função e o segundo é um array de dependências.
- Sempre que o valor de uma dependência for alterada, a função passada no primeiro parâmetro será disparada.
- Se passarmos um array de dependências vazio, a função do primeiro parâmetro será disparada apenas uma vez, quando o componente for renderizado.

### 18 - Quando devemos usar o useCallback?

Devemos utilizar o useCallback para evitar renderizações desnecessárias nos componentes que estão recebendo uma função callback por props.

### 19 - Qual a diferença de um componente funcional e componente utilizando classe?

- Um componente funcional é uma função com um unico argumento chamado "props" e retorna um elemento React.
- Um componente de classe é uma classe que estende a classe React.Component e dessa forma, obtem todos os seus métodos. Retorna um elemento React através do método render.
  ——

### 20 - Como funciona uma promise?

- Promises são classes que permitem a criação de funções assíncronas.
- Possuí o método estático "Resolve" que cria uma promise resolvida
- Possuí o método estático "Reject" que criar uma promise rejeitada.

### 21 - Qual a diferença de promise pra async await?

Aombos possuem a mesma capacidade e função. Porém, o Async/Await possuí uma sintaxe mais agradável, torna possível escrever código assíncrono como se fosse síncrono e possibilita o uso de try-catch para tratamento de erros.

### 22 - O que é uma closure?

Closure é a forma de fazer com que variáveis dentro de uma função sejam privadas e persistentes.

### 23 - Qual a diferença entre um for e um map?

- O método for retorna void.
- O método Map retorna um novo array.

### 24 - Como o método reduce funciona?

O método reduce tem como função iterar uma lista de elementos e retornar um único valor com base nos elementos contidos na lista.

### 25 - Qual a feature que você mais gosta do es7?

O método "includes" para verificar se um determinado valor está dentro de uma lista.

### 26 - Como o webpack funciona?

O webpack é um empacotador de códigos. Tem como função juntar arquivos Javascript que são utilizados dentro do navegador.
Para configurarmos o webpack precisamos definir as seguintes propriedades:

- Entry: ponto de entrada da aplicação, é aqui onde estará o carregamento inicial e toda lógica por trás da aplicação.
- Output: local onde será gerado nosso bundle contendo todos os modulos da aplicação.

### 27 - Me explica a pirâmide de testes. Testes unitários, integração e end to end e quais ferramentas podemos utilizar para cada uma dessas fases.

### 28 - Pq code splitting é tão importante?

### 29 - O que é uma função pura?

### 30 - O que é Babel?

### 31 - Como o promise race funciona?

### 32 - Por que você gosta de typescript? Quais são as vantagens?
