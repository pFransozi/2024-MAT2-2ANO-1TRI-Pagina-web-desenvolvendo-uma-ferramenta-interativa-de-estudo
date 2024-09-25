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

## Para Saber Mais

* A importância da Classe Container: Para desenvolver páginas web com boa aparência, layout organizado, flexíveis e de fácil gerenciamento, é necessário que a construção de nossos códigos seja organizada e estruturada, permitindo que o conteúdo da página seja adaptável para diferentes dimensões de tela. Para obtermos esse resultado, o uso de Containers é uma alternativa com diversas vantagens, como:
  * Separação Lógica do Conteúdo: ao utilizarmos seções, facilitamos a leitura do usuário da página e também a leitura do código-fonte;
  * Controle de Layout: o uso de containers nos permite ter maior controle sobre o funcionamento de diferentes partes do layout dos elementos da página web;
  * Facilidade de Manutenção: com a setorização do código, é mais fácil encontrar possíveis erros, o que possibilita um código menos propenso a bugs e evita efeitos indesejados durante a execução da página;
* Criando espaçamento entre os elementos: Entre as formas mais conhecidas para adicionar espaçamento em uma página web estão as propriedades: 
  * `margin`, para adicionar um espaçamento externo a um elemento;
  * `padding`, para adicionar um espaçamento interno a um elemento. 
  * Ambas podem ser aplicadas nas direções superior, inferior, esquerda ou direita, como já vimos em aulas anteriores. Além dessas opções, há também o uso do Flexbox, um modelo de layout que organiza os elementos de uma aplicação com grande capacidade de alinhamento. Com o uso do Flexbox, é possível ajustar o espaçamento entre elementos usando margens, preenchimento ou a propriedade `justify-content`.
* Construindo uma identidade visual coerente: o efeito de simetria pode ser produzido em uma página web ao utilizarmos as propriedades de distribuição flexbox para controlar o espaço entre itens flexíveis. Dentre essas propriedades, podemos ressaltar:
  * `flex-grow`: essa propriedade especifica a proporção de espaço que um item deve ocupar em relação aos outros itens dentro do mesmo contêiner. Assim, quando o contêiner se expande, os itens com valores maiores de `flex-grow` aumentam mais do que os itens com valores menores. Se temos dois itens no mesmo contêiner e um item tem `flex-grow`: 1 e o outro tem `flex-grow`: 3, o segundo item crescerá três vezes mais do que o primeiro quando o contêiner expandir;
  * `flex-shrink`: a propriedade `flex-shrink` define a capacidade de um item flexível diminuir de tamanho, caso necessário, quando o espaço disponível diminui. Assim, se o contêiner encolher, os itens com valores maiores de `flex-shrink` diminuirão menos do que os itens com valores menores. Por exemplo, se temos dois itens no mesmo contêiner e um item tem `flex-shrink`: 2 e o outro tem `flex-shrink`: 1, o primeiro item diminuirá duas vezes mais do que o segundo quando o contêiner encolher;
  * `flex-basis`: A propriedade `flex-basis` especifica o tamanho inicial de um item flexível antes de distribuir o espaço restante. Dessa forma, é preciso estabelecer o tamanho base do item antes de aplicar as regras de crescimento ou encolhimento. Por exemplo, se um item possui `flex-basis: 100px`, ele começará com 100 pixels de largura antes de considerar o espaço adicional disponível.

## Links

[Fonts Bai Jamjuree](https://fonts.google.com/specimen/Bai+Jamjuree?query=Bai+Jamjuree);