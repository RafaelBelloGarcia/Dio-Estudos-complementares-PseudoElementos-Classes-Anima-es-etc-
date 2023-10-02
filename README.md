# Dio-Pseudo_Ementos_e_Pseudo_Classes

<div style="background-color: yellow; border: solid 2px; padding-left: 10px;">Pseudo Elementos:</div>

<br>

<strong>Com os pseudo elementos ou as pseudo classes, podemos usar elementos extras, sem a necessidade de declaração no HTML.</strong>

<br>

Identificamos por: <aside style="background-color: yellow; border:solid 1px; width: 230px; height: 30px; padding-left: 10px;"><strong style="letter-spacing:8px;">::palavra-chave</strong></aside>

<div style="letter-spacing:2px; border: solid 8px; padding: 20px;">**a) ::firt-letter (seleciona a primeira letra da primeira linha

color, background, margin, padding, border, font e propriedades de texto

b) ::first-line (seleciona a primeira linha de texto)

color, background, font e propriedades de texto.

c) ::backdrop (estiliza o plano de fundo em modo tela cheia)

tag video + controls, tag sorurse

\*\*d) ::marker (estiliza os topicos ou elementos de uma lista (li) ou a flecha de um elemento summary

color, content, while-space, font, animation, transition

\*\*e) ::placeholder (estiliza o placeholder)

color, font, background, text

f) ::selection (permite estilizar a seleção de textos no navegador)

color, background-color, text

g) ::file-selection-button (permite estilizar a seleção de textos no navegador - vai estilizar o botão upload de arquivos)

\*\*h) ::before (estiliza o elemento filho anterior/é como se fosse criada uma "div" anterior ao elemento)

content, color, background, margin, padding, etc.

\*\*i) ::after (estiliza o elemento filho posterior/é como se fosse criada uma "div" posterior ao elemento)

content, color, background, margin, padding, etc.

</div>

<div style="background-color: yellow; border: solid 2px; padding-left: 10px;">Pseudo Classes:</div>

<br>

<strong>Com os pseudo classes podemos usar elementos extras, adicionando estados especiais aos elementos.</strong>

<br>

Identificamos por: <aside style="background-color: yellow; border:solid 1px; width: 230px; height: 30px; padding-left: 10px;"><strong style="letter-spacing:8px;">:palavra-chave</strong></aside>

a) :hover (estiliza quando o mouse passa por cima do elemento do HTML)

ex: button

*b) :active (estiliza o elemento quando estiver "ativado")

ex: button e tag link 'a'

*c) :focus, :focus-within e :focus-visible (estiliza e dá foco nos elementos "focados")

*d) :target (estiliza os elementos alvo)

e) :enable e :disable (estiliza o elemento habilitado ou desabilitado no HTML)

f) :link e :visited (estilizam elementos ainda não "clicados" e também os já "visitados")

g) :place-holder-shown (estiliza o elemento em placeholder que está sendo exibido)

*h) :checked e :indeterminate (estiliza o elemento)

ex: box-shadow, accent-color, radio-button

*i) :valid, :invalid, :in-range e :out-of-range (estiliza elementos input)

*j) :required e :optional (estiliza inputs tb)

k) :-webkit-autofill (autocolpletar)

i) :root (referencia o elemento raiz da arvore de elementos(é o HTML))

j) :nth-child(numero ou odd ou even ou 2n ou 3n ou 3n+1) e :nth-of-type(numero ou odd ou even ou 2n ou 3n ou 3n+1) (estiliza o elemento filho de acordo com a ordem ou índice)

obs: even é par; odd é ímpar; 2n de dois em dois; 3n de três em três; 3n+1 inicia no numero 1 e pula de tres em tres, por exemplo.

k) :first-of-type e :last-of-type (estiliza os primeiros e os ultimos elementos de um tipo específico)

l) :nth-last-child e :nth-last-of-type (estiliza o ultimo elemento filho de acordo com a posição do elemento ou do tipo)

m) :only-child (estiliza um elemento que não possui outro irmão/é filho único)

n) :only-of-type (estiliza um elemento que não possui outro irmão do mesmo tipo/é filho único daquele tipo)

o) :empty (estiliza um elemento vazio/sem estilização)

obs: divs vazias e ex: ::before content: '' são entendidos pelo programa como conteúdos vazios.

p)* :is (ele procura os elementos dentro do elemento e os estiliza)

ex: post is(h2, li, .red) {
    color: red
}

q) :where (funciona como o :is, contudo, pela especificidade, o :is vai prevalecer quando houver concorrencia entre o :is e :where)

r) :not (o not vai fazer com que a estilização do elemento/classe/etc seja ignorada)

ex: post p:not(.irrelevante) {
    color: red;
}

s) :has (ele vai estilizar somente nos elementos que contENHAM a tag/classe/id como parâmentro)

ex: gallery div:has(classe/tag)

obs: pode usar o not aqui também. Vai aplicar contrariamente a regra!

ex: ex: gallery div:not(:has(classe/tag))