# 2024-MAT2-2ANO-3TRI-Pagina-web-desenvolvendo-uma-ferramenta-interativa-de-estudo

## Introdução

Projeto realizado junto ao 2 ano do EM na disciplina de Matemática II baseado no curso "Página web: desenvolvendo uma ferramenta interativa de estudo" da Alura.

## Rúbricas

* **Aula 01**
  1. Criar uma pasta para um projeto e como criar um arquivo HTML no VS Code;
  2. Fazer uso de atalhos de teclado do VS Code para criar a estrutura base em HTML de uma página web;
  3. Adicionar elementos e tags para personalizar o conteúdo de uma página web;
  4. Utilizar a classe container para organizar conteúdos em HTML;
* **Aula 02**
  1. Criar uma pasta chamada assets para organizar arquivos de estilo, como o arquivo style.css;
  2. Adicionar o link do arquivo CSS ao documento HTML por meio do atalho link:css, para aplicar os estilos criados à uma aplicação;
  3. Estilizar os elementos do rodapé de uma página web com as propriedades CSS;
  4. Instalar e selecionar fontes para os textos de uma aplicação web.

## Ideias

* **Aula 01**
  * Por que usar contêineres?
    * Separação Lógica do Conteúdo: ao utilizarmos seções, facilitamos a leitura do usuário da página e também a leitura do código-fonte;
    * Controle de Layout: o uso de containers nos permite ter maior controle sobre o funcionamento de diferentes partes do layout dos elementos da página web;
    * Facilidade de Manutenção: com a setorização do código, é mais fácil encontrar possíveis erros, o que possibilita um código menos propenso a bugs e evita efeitos indesejados durante a execução da página;
* **Aula 02**
  * Criando espaçamentos entre os elementos:
    * margin, para adicionar um espaçamento externo a um elemento, e padding, para adicionar um espaçamento interno a um elemento. Ambas podem ser aplicadas nas direções superior, inferior, esquerda ou direita, como já vimos em aulas anteriores;
    * Flexbox, um modelo de layout que organiza os elementos de uma aplicação com grande capacidade de alinhamento. Com o uso do Flexbox, é possível ajustar o espaçamento entre elementos usando margens, preenchimento ou a propriedade justify-content;
* **Aula 03**
  * Alterar a disposição dos elementos em tela utilizando a propriedade `flex`;
  * Estilizar elementos com CSS utilizando seletores;
  * Aplicar as propriedades `flex-grow` e `flex-basis` para dispor os elementos de modo responsivo;
  * Utilizar a função `calc()` para dimensionar elementos com precisão.
* **Aula 04**
  * Adicionar uma imagem ao plano de fundo de uma aplicação;
  * Utilizar variáveis globais de cor em propriedades CSS;
  * Alterar o peso das fontes nos textos de diferentes elementos da aplicação.
* **Aula 05**
  * Utilizar a pseudo-classe `:hover` para criar um efeito ao passar com o cursor do mouse sobre um elemento;
  * Adicionar as propriedades `transform` (transformação) e `transition` (transição) para criar o efeito de transição e rotação em um elemento;
  * Fazer uso da propriedade `backface-visibility` para controlar se a parte de trás de um elemento deve ser exibida ao usuário;
  * Alterar espaçamentos internos (`padding`) e externos (`margin`) de um elemento para criar espaçamento entre conteúdos.
* **Aula 06**
  * Adicionar novos cartões em HTML reaproveitando trechos de código;
  * Alterar o espaçamento e alinhamento de elementos de uma aplicação utilizando propriedades CSS;
  * Criar arquivos com extensão `.js` por meio do VS Code;
  * Construir o esboço de uma função em JavaScript e repassar parâmetros para a construção automatizada de elementos de uma página web.
* **Aula 07**
  * Vincular o link de arquivos JavaScript ao documento index.html;
  * Criar funções em JavaScript para receber parâmetros necessários e desenvolver uma ação;
  * Utilizar o `console.log()` para exibir os parâmetros de uma função no console do navegador e testar se a integração dos arquivos JavaScript está funcionando corretamente;
  * Acessar as ferramentas do desenvolvedor no navegador através da opção Inspecionar do menu de contexto para verificar a saída dos parâmetros dos cartões no console.
* **Aula 08**
  * Declarar variáveis do tipo `let` em JavaScript para acessar e manipular elementos HTML existentes em uma página web;
  * Criar novos elementos HTML dinamicamente através do JavaScript, utilizando o método `document.createElement()`;
  * inserir conteúdo HTML dentro de elementos criados dinamicamente através da propriedade `.innerHTML`;
  * Anexar novos elementos criados pelo JavaScript à página web usando o método `appendChild`.







## Para Saber Mais

* **Aula 01**
  * A importância da Classe Container: Para desenvolver páginas web com boa aparência, layout organizado, flexíveis e de fácil gerenciamento, é necessário que a construção de nossos códigos seja organizada e estruturada, permitindo que o conteúdo da página seja adaptável para diferentes dimensões de tela. Para obtermos esse resultado, o uso de Containers é uma alternativa com diversas vantagens, como:
    * Separação Lógica do Conteúdo: ao utilizarmos seções, facilitamos a leitura do usuário da página e também a leitura do código-fonte;
    * Controle de Layout: o uso de containers nos permite ter maior controle sobre o funcionamento de diferentes partes do layout dos elementos da página web;
    * Facilidade de Manutenção: com a setorização do código, é mais fácil encontrar possíveis erros, o que possibilita um código menos propenso a bugs e evita efeitos indesejados durante a execução da página;
* **Aula 02**
  * Criando espaçamento entre os elementos: Entre as formas mais conhecidas para adicionar espaçamento em uma página web estão as propriedades: 
    * `margin`, para adicionar um espaçamento externo a um elemento;
    * `padding`, para adicionar um espaçamento interno a um elemento. 
    * Ambas podem ser aplicadas nas direções superior, inferior, esquerda ou direita, como já vimos em aulas anteriores. Além dessas opções, há também o uso do Flexbox, um modelo de layout que organiza os elementos de uma aplicação com grande capacidade de alinhamento. Com o uso do Flexbox, é possível ajustar o espaçamento entre elementos usando margens, preenchimento ou a propriedade `justify-content`.
* **Aula 03**
  * Construindo uma identidade visual coerente: o efeito de simetria pode ser produzido em uma página web ao utilizarmos as propriedades de distribuição flexbox para controlar o espaço entre itens flexíveis. Dentre essas propriedades, podemos ressaltar:
    * `flex-grow`: essa propriedade especifica a proporção de espaço que um item deve ocupar em relação aos outros itens dentro do mesmo contêiner. Assim, quando o contêiner se expande, os itens com valores maiores de `flex-grow` aumentam mais do que os itens com valores menores. Se temos dois itens no mesmo contêiner e um item tem `flex-grow`: 1 e o outro tem `flex-grow`: 3, o segundo item crescerá três vezes mais do que o primeiro quando o contêiner expandir;
    * `flex-shrink`: a propriedade `flex-shrink` define a capacidade de um item flexível diminuir de tamanho, caso necessário, quando o espaço disponível diminui. Assim, se o contêiner encolher, os itens com valores maiores de `flex-shrink` diminuirão menos do que os itens com valores menores. Por exemplo, se temos dois itens no mesmo contêiner e um item tem `flex-shrink`: 2 e o outro tem `flex-shrink`: 1, o primeiro item diminuirá duas vezes mais do que o segundo quando o contêiner encolher;
    * `flex-basis`: A propriedade `flex-basis` especifica o tamanho inicial de um item flexível antes de distribuir o espaço restante. Dessa forma, é preciso estabelecer o tamanho base do item antes de aplicar as regras de crescimento ou encolhimento. Por exemplo, se um item possui `flex-basis: 100px`, ele começará com 100 pixels de largura antes de considerar o espaço adicional disponível.
* **Aula 04**
  * Variáveis de Cor: Criar variáveis para cores em CSS é uma boa prática de programação e pode ser especialmente útil para quem está começando a programar e deseja manter as coisas organizadas e fáceis de entender:
    * Consistência: O uso de variáveis de cor garante que as mesmas cores sejam usadas em todo o site, evitando diferenças indesejadas;
    * acilidade de Manutenção: Se precisar mudar uma cor usada em vários lugares, você só precisa alterar a variável uma vez;
    * Legibilidade e Organização do Código: Variáveis de cor tornam o CSS mais fácil de ler e entender. Documentação Implícita: Nomes descritivos para as variáveis ajudam a entender para que cada cor é usada.
    * Reutilização: Facilita a reutilização de estilos em diferentes partes do site, promovendo componentes reutilizáveis.
    * Redução de Erros: Ajuda a evitar erros ao garantir o uso consistente das mesmas cores. Procure estabelecer variáveis de cor para criar códigos limpos e cheios de estilo.
* **Aula 05**
  * Pseudo-classes, Transições e Transformações: Quando estamos aprendendo sobre desenvolvimento web, entender como estilizar nossas páginas de forma dinâmica e atrativa é essencial. Para isso, a linguagem de estilização CSS nos apresenta várias alternativas, dentre elas:
    * `:hover`: Ao adicionarmos essa palavra-chave a um seletor CSS, podemos criar um efeito sobre um elemento quando o cursor do mouse passar sobre ele. No exemplo abaixo, ao passarmos o mouse sobre o botão, ele adquire a cor rosa.
      ```
      button:hover {
      background-color: pink;
      }
      ```
    * `transforme`: Essa propriedade nos permite aplicar uma série de transformações a um elemento, como mover, girar, escalar e inclinar. Podemos associá-la a propriedade rotate para girar um elemento em torno de um ponto fixo definido, como no exemplo:
      ```
      div {
      transform: rotate(45deg);
      }
      ```
    * `transition`: Já, a propriedade transition permite que as mudanças de estilo em um elemento ocorram de forma suave e projetada durante um período de tempo especificado, criando o efeito de animação sem a necessidade do JavaScript. No exemplo abaixo, estabelecemos que o tempo para que um determinado evento ocorra, como a mudança da cor de fundo do botão, seja de 0.3 segundos e que a transição deverá ser suave.
      ```
      button {
      transition: background-color 0.3s ease;
      }
      ```
* **Aula 08**
  * Métodos em JavaScript: Quando uma página web é carregada por um navegador, ele cria uma representação em árvore dessa página, chamada DOM. Essa representação possui uma hierarquia, e cada elemento HTML é chamado de nó. Cada nó pode ter "filhos" (outros elementos contidos neles) e "pais" (elementos que os contêm). Para modificar esses nós, podemos utilizar métodos JavaScript, que são funções associadas a um objeto ou uma variável.
    * `getElementById`: Este método permite que você encontre um elemento específico pelo seu ID. Por exemplo:
      ```
      let container = document.getElementById('container')

      ```
      Nesse trecho de código, procuramos pelo id container.
    * `innerHTML`: Este método permite que você obtenha ou altere o conteúdo HTML de um elemento. Por exemplo:
      ```
      cartao.innerHTML = `
              <div class="cartao__conteudo">
              <!-- Código omitido… -->
              </div>
              `
      ```
    * `createElement`: Este método cria um novo elemento HTML, mas não o adiciona automaticamente à página. Por exemplo:
      ~~~html
      let cartao = document.createElement('article')

      ~~~
    * `appendChild`: Este método insere um novo nó “filho” (elemento) na estrutura do DOM de um documento. Por exemplo:
      ```
      container.appendChild(cartao)

      ```
      O código acima insere a variável cartao como um elemento “filho” de container.


## Links

[Fonts Bai Jamjuree](https://fonts.google.com/specimen/Bai+Jamjuree?query=Bai+Jamjuree)

[Guia de animações em CSS: o que são e quais são os principais benefícios](https://www.alura.com.br/artigos/animacoes-em-css#:~:text=As%20propriedades%20CSS%20de%20anima%C3%A7%C3%A3o,ou%20outra%20linguagem%20de%20programa%C3%A7%C3%A3o)

[Mais sobre DOM e métodos HTML](https://www.w3schools.com/js/js_htmldom.asp)