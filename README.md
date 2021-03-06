# Boas vindas ao repositório do projeto Lições Aprendidas!

Esse projeto foi realizado em outubro de 2020 por @brunacamposxx e avaliado pela @trybe

### 🗒ANTES DE COMEÇAR A DESENVOLVER:

1. Clone o repositório
  * `git clone https://github.com/brunacamposxx/lessons-learned`.
  * Entre na pasta do repositório que você acabou de clonar:
    * `cd lessons-learned`

---

## Requisitos do projeto

### 💡Veja o exemplo a seguir de como o projeto pode se parecer depois de pronto. Lembre-se que você pode ~~e deve~~ ir além para deixar o projeto com a sua cara e impressionar à todos!

![exemplo](./exemplo.png)


## ⚠️ Leia-os atentamente e siga à risca o que for pedido. Em particular, **atente-se para os nomes de _ids_ que alguns elementos de seu projeto devem possuir**. ⚠️

O não cumprimento de um requisito, total ou parcialmente, impactará em sua avaliação.

---

### 👀Observações importantes:

* Os requisitos do seu projeto são avaliados automaticamente, sendo utilizada a resolução de tela de `1366 x 768` (1366 pixels de largura por 768 pixels de altura).

  * #### ⚠️ Logo, recomenda-se desenvolver seu projeto usando a mesma resolução, via instalação [deste plugin](https://chrome.google.com/webstore/detail/window-resizer/kkelicaakdanhinjdeammmilcgefonfh?hl=en) do `Chrome` para facilitar a configuração da resolução. ⚠️

* Atente-se para o tamanho das imagens que você utilizará neste projeto. **Não utilize imagens com um tamanho maior que _500Kb_.**
  * #### ⚠️ Utilize uma ferramenta [como esta](https://picresize.com/pt) para redimensionar as imagens. ⚠️

  * Caso a avaliação falhe com alguma mensagem de erro parecida com `[409:0326/130838.878602:FATAL:memory.cc(22)] Out of memory. size=4194304`, provavelmente as imagens que você está utilizando estão muito grandes. Tente redimensiona-las para um tamanho menor.

* Para verificar se a sua avaliação foi computada com sucesso, você pode verificar os **detalhes da execução do avaliador**.

  * Na página do seu _Pull Request_, acima do "botão de merge", procure por _**"Evaluator job"**_ e clique no link _**"Details"**_;

  * Na página que se abrirá, procure pela linha _**"Cypress evaluator step"**_ e clique nela;

  * Analise os resultados a partir da mensagem _**"(Run Starting)"**_;

  * Caso tenha dúvidas, consulte [este vídeo](https://vimeo.com/420861252) ou procure as pessoas instrutoras.

* Você tem liberdade para adicionar novos comportamentos ao seu projeto, seja na forma de aperfeiçoamentos em requisitos propostos ou novas funcionalidades, **desde que tais comportamentos adicionais não conflitem com os requisitos propostos**.

  * Em outras palavras, você pode fazer mais do que for pedido, mas nunca menos.

* Contudo, tenha em mente que **nada além do que for pedido nos requisitos será avaliado**. _Esta é uma oportunidade de você exercitar sua criatividade e experimentar com os conhecimentos adquiridos._

---

## Requisitos Obrigatórios:

Você deve criar um site que com uma série de informações a respeito do que você aprendeu nos últimos três blocos, estilizado de forma apropriada.

**Em outras palavras, uma página de `Lessons Learned`**;

**Lembre-se de verificar sua página no [achecker](https://achecker.ca/checker/index.php).**

## Requisitos do projeto

### 1 - O corpo da página deve possuir uma cor de fundo específica

- Possuir cor de fundo: rgb(253, 251, 251)

### 2 - Seu site deve possuir uma barra superior com um título

- A barra deve possuir o ID "cabecalho"

- O elemento com o id `cabecalho` deve ser fixo no topo da página, com a propriedade top tendo `0px`

- O título deve estar dentro da barra e possuir o ID "titulo", além de ser uma tag `h1`

### 3 - A página deve possuir uma foto sua

- A foto deve ser inserida utilizando uma tag `img` com o ID "minha_foto"

### 4 - A página deve possuir uma lista de lições aprendidas

- A lista deve ser numerada e possuir o ID "licoes_aprendidas"

- A lista deve possuir 10 itens

### 5 - A página deve possuir uma lista de lições que ainda deseja aprender

- A lista **não** deve ser numerada e deve possuir o ID "licoes_a_aprender"

- A lista deve possuir 10 itens

### 6 - A página deve possuir um rodapé

- O rodapé deve utilizar a tag `footer` e possuir o ID "rodape"

### 7 - A página deve possuir pelo menos um link externo

- A configuração desse link deve ser feita para abrir em uma nova aba do navegador

### 8 - Crie um artigo sobre seu aprendizado

- A `tag` `article` devem ser utilizadas

- O artigo deve ter mais de 300 letras e menos de 600

### 9 - Crie uma seção que conta uma passagem sobre seu aprendizado

- A `tag` `aside` deve ser utilizada

- A seção deve ter mais que 100 letras e menos que 300

### 10 - Torne o seu site mais acessível e melhore seu ranqueamento em mecanismos de busca na Web aplicando os elementos HTML de acordo com o sentido e propósito de cada um deles

- A página deve possuir um elemento `article`

- A página deve possuir um elemento `header`

- A página deve possuir um elemento `nav`

- A página deve possuir um elemento `section`

- A página deve possuir um elemento `aside`

- A página deve possuir um elemento `footer`

### 11 - Seu site deve passar sem problemas na verificação de semântica do site achecker

## Requisitos Bônus:

### 12 - Adicione uma tabela à página

- A página deve possuir uma tabela

### 13 - Brinque com o Box model!

- Altere `margin`, `padding` e `border` dos elementos para ver, na prática, como esses atributos influenciam e melhoram a visualização dos componentes

### 14 - Altere atributos relacionados as fontes

- Altere o tamanho da letra

- Altere a cor da letra

- Altere o espaçamento entre as linhas

- Altere o `font-family`

### 15 - Faça com que seu artigo e seção sobre aprendizados fiquem um ao lado do outro

- Utilizar a classe 'lado-esquerdo'

- Utilizar a classe 'lado-direito'

- Verificar se os elementos com as classes lado-direito e lado-esquerdo estão posicionados corretamente

---

## Dicas

- Para fazer este projeto você deverá atribuir a barra superior o `position: fixed;`. Leia mais sobre ele [aqui](https://www.w3schools.com/css/css_positioning.asp).

- Para colocar sua página no [GitHub Pages](https://pages.github.com/), não é necessário remover o conteúdo que já está lá, você pode apenas adicionar essa nova página. Para isso, todo o conteúdo desse projeto deve ser colocado em uma pasta `/projetos/lessons-learned`.

---

#VQV 🚀
