### NLW 2022 - RETURN

## DIA 1

## Método para aprendizado da Rocketseat

- Foco
- Prática
- Grupo

## Fundamentos Web

# O que é Programar ?

    - Ensinar o computador.

# Como ensinamos o computador ?

    - Com linguagens de programação.

# O que é Front-End ?

    - Parte visual do projeto. É a parte apresentada ao cliente final (usuário).

# O que é Back-End ?

    - Parte lógica do projeot. É a parte por trás do projeto.

# Como é feita a comunicação entre Front e Back ?

    - Via HTTP
    - Via URL
    - Troca de Dados

# Tecnologia Front-End ?

    - Nesse projeto iremos utilizar como base HTML, CSS, Javascript.

- Quando criarmos nossa primeira página, utilizamos por padrão o IP 127.0.0.1 (Localhost), através da porta 5500

- Podemos inserir comentário nos arquivos HTML através da tag "<!-- -->".
  - Tudo que estiver dentro da tag de comentário, nao será apresentado em sua página, porém vemos quando apertamos (na tela do Browser) com o botão direito do mouse, INSPECIONAR.

# O que significa HTML ?

    - HyperText Markup Language.
        - Texto que recebemos todos tipos de arquivos possíveis, tais como Vídeos, áudios, links etc.

# Como inserimos uma marcação(tag) ?

    - Inserimos a tag com a abertura <> e fechamos com </>.
        - Exemplo
            - Tag H1
                - <h1>UM TEXTO</h1>

# Aninhamento

    - Uma tag pode conter mais que uma tag, não podemos abrir e fechar a Tag com níveis diferentes
        - Exemplo CORRETO !
            <div>
                <h1>UM TEXTO</h1>
            </div>

        - Exemplo INCORRETO !!!!!
            <div>
                <h1>UM TEXTO</div>
                </h1>

- Tags HTML são sempre colocados na ordem que programamos, um abaixo do outro
  - Se criarmos um <h4>TEXTO 1</h4>
  - Depois um <h1>TEXTO 2</h1>
    - O resultado será a tag H4 na primeira posição e o H1 na segunda posição, e assim por diante

# Atributos OBRIGATÓRIOS na imagem

    - Utilizamos a tag IMG para inserção de imagens em nosso código HTML
        - Todas tags possuem atributos opcionais, porém a tag IMG possui um atributo que é OBRIGATÓRIO, o atributo SRC
        - SRC vem de SOURCE - Significado bem "Brasileirado" pra isso, "ONDE ESTÁ ESSE ATRIBUTO?" (hehe)
        - Como dito, podemos chamar, fazer uma comunicação com os atributos, via HTML ou URL
        - Podemos procurar através de um arquivo salvo em nossa máquina, ou até mesmo um link na internet
        - No caso de um arquivo em nossa máquina, utilizamos os código "/"
        - Quando precisamos pular de uma pasta a outra, usamos "/" se estiver na mesma pasta, ou "../" se estiver em uma pasta acima.(Caso esteja 2 casas ou mais acima, vamos acrescentando a mesma sintaxe)
        - 2 Casas: '../../'
        - 3 Casas: '../../../' E assim por diante
    - Atributo ALT da imagem
        - Utilizado para text alternativo
            - Utilizamos para descrever a imagem caso ela:
                - Não carregue a imagem
                - Para utilizar o leitor de tela(Caso seja um cliente com problema visual)
                - Utilizado para pesquisa no Google para encontrar seus ALTS para demonstrar as buscas (SEO)
                    - Search Engine Optimization
                - Quando paramos o mouse em cima da imagem apresenta o texto alternativo

### TAGS PRINCIPAIS

    - HTML
        - Tag onde fica todo o código do projeto
    - HEAD
        - Tag onde fica toda parte de script, stilização, as tags meta do código, e título de seu projeto.
    - BODY
        - Tag onde agrega todo código do seu projeto que é apresentado ao usuário final.

### O que é CSS ?

    - Cascading Style Sheets
    - Apresentação visual para o cliente
    - Estilo ao HTML

## Como escrever as declarações?

    - Criamos um arquivo separado, geralmente com o nome Style.css
    - Iniciamos chamando a tag, abrimos e fechamos {}.
    - Dentro colocamos o comando, dois pontos(:) e a propriedade.
    - EXEMPLO
        - h4 {
            color: green;
        }
    - Podemos selecionar as tags através de:
        - Nome da Tag (NomeDaTag)
        - ID da tag (#)
        - Classe da Tag(.)

## BOAS PRÁTICAS

- Aconselhável utilizar apenas 1 H1 para cada página

  - Não é proibido, porém aconselhável
  - H1 é utilizado em texto Principal da página, geralmente o título do texto
  - H2 utilizado para subtítulos, subsessões
  - Tags H2 até H6 podemos utilizar em várias partes da página

- No CSS Utilizamos o seguinte comando no :root

  - font-size: 62.5%
  - Temos por padrão em WEB 16px, com esse comando, abaixamos tudo para 10px.
  - Quando for inserir tamanho na página, utilizamos a medida REM, para deixar a página toda acessível.

- Utilizamos o display para configurar o posicionamento de nossa pagina.

  - Por padrão temos Display: Block para h1, h2, p.
    - Display: Block joga a próxima tag para baixo da anterior
  - Por padrão temos Display: inline para button, img
    - Display: inline deixa apenas no tamanho da tag, deixando o restante dos itens com Display inline também do lado, até completar o tamanho da imagem.

- Utilizamos no CSS o \* {} para resetar nossa página, para tirar os padrões dos navegadores e adicionar nossa configuração para ser igual a todos.
  - Geralmente zeramos o margin e padding dos projetos.
    - margin: 0
    - padding: 0
  - Usamos também um atributo chamado box-sizing como border-box para deixar nossa tela com a soma desde a borda
    - EXEMPLO
      - Quando precisamos de um BOX com width: 375 e adicionamos o padding: 20, será somado 40(20 da esqueda e 20 da direita) a largura final, pois soma tudo. Largura do BOX nesse caso ficou de 415.
      - Utilizando o atributo box-sizing: border-box, será somado desde o início da borda até o final.
      - Ficaria com um width: 335 e padding: 20. Nesse caso teríamos o BOX com 375 automaticamente.

### BÔNUS

## BOX MODEL

- Estrutura de uma Caixa:
  - Content
    - Seria o Conteúdo da Caixa
  - Temos a altura e largura definidos por
    - Height: Altura
    - Width: Largura
  - Temos o tamanho INTERNO definido por
    - Padding
  - Temos a borda da caixa definido por
    - Border
  - Temos o tamanho EXTERNO definido por
    - Margin

## O que é FIGMA ?

    - É uma ferramenta utilizado por profissionais UI/UX para estilização de algum projeto ou produto a criar.
        - UI - User Interface
        - UX - User Experience
    - Possuimos outras ferramentas com por exemplo Photoshop.
    - NÃO FAZ PARTE DO DIA A DIA DO PROGRAMADOR(A) A UTILIZAÇÃO DESSA FERRAMENTA PARA CRIAÇÃO, APENAS PARA VISUALIZAÇÃO DO ESTILO QUE O PO/PM GOSTARIA DE POSSUIR SEU PROJETO
        - PO - Product Owner
        - PM - Product Manager

## DIA 2

# Pra que ser as Class ?

    - Serve para classificar nossas tags
    - Um modo de diferenciar esse tag das demais tags do código
    - Usamos o ponto (.) no arquivo CSS para referenciar as estilizações para aquela tag (Seletor de Classe)

# Como criar Tag HTML via CSS ?

    - Criamos a partir de um comando chamado BEFORE.
        - Ou seja, tudo que estiver ANTES da tag que referenciamos, receberá as configurações impostas nesse css

# Como selecionar uma tag filha específica para alteração ?

    - Através do comando nth-child(), podemos selecionar qual tag queremos
        - Exemplo
            - Em nosso código, no NAV temos 2 SVG
            - Quando queremos selecionar o primeiro NAV do comando, usamos o:
                - nav.scroll svg:nth-cild(1), assim selecionamos apenas o primeiro filho svg do nav
            - Para selecionar o segundo seria com a mesma sintaxe
                - nav.scroll svg:nth-child(2), e assim por diante

## INICIANDO COM JAVASCRIPT

# Como funciona o Javascript

    - Ele funciona da Esqueda para Direita
    - Linha a Linha
    - Ele é Síncrono

# Quais os tipos primitivos que temos em Javascript ?

    - String - Palavras
        - Varchar - Podemos encontrar em algumas aplicações com o nome de VARCHAR, onde utilizamos para Banco de Dados
    - Number - Números
    - Boolean - Retorna apenas Verdadeiro ou Falso

# Quais as boas práticas em Javascript (linguagens de programação em geral) ?

    - Uso em Inglês
    - Usamos o Camel Case
        - Devemos utilizar dessa forma para seguir as boas práticas da programação:
            - Tudo junto
            - Primeira letra minúscula
            - Início de outra palavra maiúscula
    - Nomes intuitivos, curtos e descritivos

# O que são Funções em Javascript ?

    - Criar sequências de passos para aplicação
    - Executa a sequência

# O que são os Objetos em Javascript ?

    - Seria uma construção de propriedades e Funcionalidades
        - Neles temos os Atributos e Métodos
            - Exemplo
                - Possuimos uma bicicleta, onde pesa 50kg e é da cor Amarela, uso ela para pedalar
                    - Objeto: Bicicleta
                    - Atributo: Peso e Cor
                    - Método: Pedalar
        - Criamos com {props:"Valor"}

# Fluxos alternativos em aplicações

    - Uso do IF em nossa aplicação
        - São condições
            - Se estiver certo, faça isso
            - Se não, não faça
                - Exemplo
                    - if(chover) {
                        console.log('Vou ficar em casa')
                    } else {
                        console.log('Vou jogar bola')
                    }
                - Se Chover, fico em casa. Se não, vou jogar bola.

# Como inserimos o Javascript em nosso sistema ?

    - Utilizamos a tag script dentro do nosso código
        - Podemos inserir tanto no Head quanto no Body

# Como criamos uma função ?

    - Para criar uma função em Javascrip, utilizamos a palavra FUNCTION no início do código, e damos um nome para essa função
        - Exemplo
            - function nomeDaFunção() {}

## BÔNUS

- Usamos margin-inline para referenciar margem do eixo X (horizontal)

  - Ao invés de utilizar margin-left e margin-right, o margin-inline já referencia a esses dois atributos

- Usamos o margin-block para referenciar margem do eixo Y (vertical)

  - Ao invés de utilizar margin-top e margin-bottim, o margin-block já referencia a esses dois atributos

- O display flex se referencia apenas por 1 eixo, X (horizontal) ou Y (vertical)

  - Display flex por padrão temos o alinhamento em linha(horizontal), onde está relacionado com o eixo X.
  - Podemos alterar utilizando a configuração flex-direction, colocando em column(vertical), onde passará a ser relacionado com o eixo Y.

- Temos também o eixo Z, o eixo Z é o eixo tridimensional, o eixo que trás a imagem para fora.

# O que é DOM ?

    - Document Object Model
        - Modelagem do nosso documento para o Javascript
            - Toda essa modelagem tem a modelagem PAI que seria o WINDOW

## DIA 3

# O que é Scrollreveal ?

    - É uma biblioteca onde conforme vamos dando Scroll em nossa página, conforme vamos andando na página, ele vai abrindo todo o conteúdo com um efeito.

# O que é uma biblioteca ?

    - É um conjunto de funções já criadas por terceiros que usamos em nossas aplicações para facilitar nosso desenvolvimento do dia a dia

# BONUS

- Aprendemos a utilização de padronização em CSS

- Utilizamos as tags SECTION, utilizada para dar apresentar os pedaços da página

- Adicionamos âncoras

- Eventos de click no menu

- Criação de Rolagem Suave utilizando o Smooth

## Dia 4

- Ajustamos o carregamento da função onScroll() dentro do main.js
  - Utilizamos o window.addEventListener('event', função)
    - Evitamos o erro do console, onde estava procurando a função antes de terminar o carregamento da página
- Realizamos o Rodapé com FOOTER
- Padronizamos o buttom
  - adicionamos o hover
- Ajustamos as imagens
- Adicionamos o backToTopBack, para voltar ao início do Site
- Adicionamos a mudança de cores rápidas para o site todo
- Realizamos mudança de cores também nas imagens do site
  - Utilizamos o formato svg
    - fill
    - stroke
  - # FORMATOS DE IMAGENS .PNG E .JPG NÃO POSSUEM ESSES ATRIBUTOS PARA REALIZAR ESSAS MUDANÇAS
- Adicionamos o link para contato via whatsapp: www.wa.me/DDIDDDTELEFONE

## Dia 5

- Ajuste de tela
    - de 320 a 500
    - de 1024 acima

- CSS Media queries
    - @media
        - Inserir pontos de quebra(breakpoints)

- Restruturar HTML para ter colunas.
    - Usando display: grid

- CSS Flex(avançado)

- Lógica avançada
    - .querySelector()
    - .getAttribute('class')
    - operadores lógicos
        - &&
        - ||
    - operadores de comparação
        - <=
        - =>
        - >
        - <
        - ===
        - ==
    - operador de negação
        - !
- Argumento da função
- Colocar o objeto no Github, com link acessível
    - Corrigir ou modificar código direto no GitHub usando o . (ponto final)