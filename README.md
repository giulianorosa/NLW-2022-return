### NLW 2022 - RETURN

## DIA 1

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

- Utilizamos no CSS o * {} para resetar nossa página, para tirar os padrões dos navegadores e adicionar nossa configuração para ser igual a todos.
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