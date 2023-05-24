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


# Viewport 

* Os navegadores no celular utilizam uma janela virtual(viewport) para renderizar a página, geralmente é maior do que a tela do dispositivo. Então a resolução da viewport pode ser mais larga que a largura do dispositivo. Então a viewport é maior que a tela do dispositivo. Então a Apple produziu essa "metatag"-> viewport falando qual vai ser o tamanho do nosso viewport 


