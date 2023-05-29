[Nesse tópico vou estudar sobre a estrutura do HTML]()

* Vou colocar a extensão Live Server para não ter que dar F5 na página que eu estou editando. 

* Criando um arquivo index.html

* ALT + Shift + f -> para formatar o texto em varias linhas 

# Primeiro vamos ver sobre as Tags:

- Tag com corpo:
abrimos com esse sinal <> e fechamos </> assim:
Exemplo:
<head>
    <outra_tag>
    <tag_sem_corpo>
    </outra_tag>
</head>

** Pode ter tag com corpo com atributos dentro:
<head atributo = "valor" >

</head>

- Tag sem corpo:
<nome_da_tag atributo = "valor">


# Como criar uma estrutura HTML

(Qual é o tipo desse HTML ?)
<!doctype html>
Obs> html é case insensitive

(Tag raiz)
<html>

</html>

(Tag head)
<head>
    <title>Nome_na_aba_site</title>
</head>

(Codificação de bits para escrever um arquivo)
Codificação de caracteres para ler emotes,acentos e etc
Para isso manda um metadado(dados sobre os dados/ informações adicionais)
<meta charset="" >

(Tag body)
Corpo da Página
<body>
</body>

# Validar o html

[validate html](https://validator.w3.org/) -> site para validar o html

# Atalho para criar um documento html no vscode

apenas colocar "!" na primeira linha

# TAGS

* h1 -> header -> cabeçalho > titulo
* p -> paragrafo 
* span -> inline | precisa do css para modificar
* br -> break -> quebra linha | não tem corpo
* style -> onde coloca o CSS dentro do HTML -> Fica dentro da tag head
* b -> bold -> negrito
* strong -> deixar a palavra ou frase mais forte 
* i -> italico 
* em -> deixa em italico porém para dar enfase e ajuda pessoas com problemas visuais, para leitor de tela
* a -> TAG DE LINK para colocar um link e recebe um href="diretorio", onde vc coloca um arquivo ou site -> usando target="_self,_blank", cada um faz algo 
* img -> TAG DE IMAGEM -> src="diretorio" -> alt="" texto alternativo(semantico, para leitor ler a imagem, descrevendo a imagem -> alt="logo da nike")
* s -> tag riscada -> para colocar o risco
* del -> risca a palavra
* u -> underline - sublinhado
* ins -> sublinhado -> inseção 
* small -> deixar a palavra menor que as outras
* sup -> para fazer qualquer coisa no exponencial(elevado)
* q -> citação de algo
* blockquote -> bloco de citação -> não pode ir dentro do paragrafo! -> Mas pode ter um paragrafo 
* code -> citando code 
* pre -> tag de texto preformatado, utilizado para colocar codigos em um site
* span -> conteiner generico inline(em linha para conteúdo fraseado) ->  pode ser utilizada dentro do paragrafo("tag p") -> como é inline não derruba os elementos próximos.
* div ->  container generio para conteudo de fluxo -> uitilizado para agrupar elementos.
* ul -> lista de itens sem orgem rígida
* li -> representa um item que faz parte de uma lista
* ol -> lista ordenada -> numeros inves de bolinhas

# Sites para pesquisar sobre qualquer coisa de html

* Apenas pesquise: "mdn strong" por exemplo no google vai achar o site: https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/strong -> site muit bom que explica cada tag 

* https://www.w3schools.com/tags/tag_a.asp

* Qualificar links externos para o Google: https://developers.google.com/search/docs/crawling-indexing/qualify-outbound-links?hl=pt-br

# Viewport 

* Os navegadores no celular utilizam uma janela virtual(viewport) para renderizar a página, geralmente é maior do que a tela do dispositivo. Então a resolução da viewport pode ser mais larga que a largura do dispositivo. Então a viewport é maior que a tela do dispositivo. Então a Apple produziu essa "metatag"-> viewport falando qual vai ser o tamanho do nosso viewport 

# ID

* Geralmente utilizado dentro da tag para colocar esse identificador. 
* Não é possível utilizar o mesmo id para elementos diferentes.

# Classes

* Também identificadores de elementos.
* Diferente do ID podem se repetir
* Pode também ter um elemento com mais de uma classe

# TAG STYLE

* Como chamar o elemento/tag h1 para o editor CSS:
    - Apenas colocar na tag style a tag/elemento que você quiser. obs: novo2.html/linha 10
    exemplo: h1{}
* Como chamar um identificador:
    - Apenas colocar "#nome_identificador{}" 
* Como chamar com classe?
    - ".nome_da_classe{}"
* OBS: O id tem hirarquia maior, ou seja, se você colocar uma classe depois de um id, o id vai ser preferência. Mas tem o !importante porém está forçando a colocar a classe.

# Semântica 

* Utilizar a tag correta no local correto para todo mundo que leia o seu site entenda.

# Display Block & Inline

No HTML, os elementos podem ser classificados como elementos de bloco (block elements) ou elementos em linha (inline elements), com base na forma como eles são renderizados na página.

Elementos de bloco:

*Os elementos de bloco começam em uma nova linha e ocupam toda a largura disponível. Eles criam um "bloco" no layout da página.

* Exemplos comuns de elementos de bloco incluem [<div>, <p>, <h1> a <h6>, <ul>, <li>, <table>, <form>], entre outros.
* Os elementos de bloco podem conter outros elementos de bloco e elementos em linha dentro deles.
* Eles geralmente são usados para estruturar o conteúdo da página, como seções, parágrafos, cabeçalhos, listas, etc.

Elementos em linha:

* Os elementos em linha não iniciam uma nova linha e ocupam apenas o espaço necessário para o conteúdo dentro deles. Eles fluem junto com outros elementos em linha.
* Exemplos comuns de elementos em linha incluem [<span>, <a>, <strong>, <em>, <img>, <input>, <button>], entre outros.
* Os elementos em linha geralmente são usados para aplicar estilos ou marcar partes do texto dentro de um bloco.

É importante notar que a distinção entre elementos de bloco e em linha é feita principalmente para descrever o comportamento padrão desses elementos. No entanto, é possível alterar esse comportamento por meio de estilos CSS. Por exemplo, é possível definir um elemento de bloco para ser exibido como em linha ou vice-versa, usando a propriedade display do CSS.

# Metadados do documento 

* Os metadados são onde se guardam várias informações sobre a página, incluindo informações sobre estilos, scripts e dados para auxiliar software (ferramentas de pesquisa (en-US), navegadores, etc) usar e renderizar a página. 

Link falando sobre: https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element#metadados_do_documento

# Semântica

* Você ta criando um elemento que tem lógica naquele determinado lugar.
Exemplo: criando um menu, utiliza tag nav com outros elementos