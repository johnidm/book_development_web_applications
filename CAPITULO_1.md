#HTML5 

##Introdução ao HTML5

O HTML não é *case senitive*, ou seja, você pode escrever seus códigos em letras minusculas ou maiuscolas (eu recomendo fortemente o a escrita das tags em letras minuscolas), sua escrita é de fácil leitura e toda a sua estrurua é baseada em *tags*  que são elementos que informam ao navegador como ele renderizar determinda informação. Uma documento HTML é formado por um conjunto de tags que serão itnerpretadas pelo browser e exibida através de umja página HTML.

Uma *tag* é formada pelo seu nome, precedido do caractere "<" (menor que) sucedido pelo caractere ">" (maior que). A maiorias das *tag* possum um *tag* correspondente conecida como *tag* de fechamento que indica o final da *tag*, essa *tag* é compostas pela mesma estrutura da tag de abertura acresentando o caractere "/" após o caractere ">". Veja o exemplo.

Listagem 1
```html
<p>Bom dia!</p>
```
Veja nesse exemplo o uso da *tag* `p` e observe como ela possui uma tag de abertura, `<p>` e uma tag de fechamento `</p>`.

Existem algumas tag que não necessitam da tag de fechamento, seu uso é facultativo, nesse casos o uso do caractere  "/" pode vir logo após a tag de abertura. a tag `br` é um exemplo e pode ser escrita dessa forma `<br>` ou `<br />`. Esse tipo de tag é conhecido como **tag vazia** ou **elemento vazio**. Isso é uma caracteristica de documentos escritos em XHTML, eu recomentdo não utilizar o "/" em tag vazias.

Uma lista completa de todas as *tags* disponiveis no HTML5 por ser encontrada nesse link https://developer.mozilla.org/pt-BR/docs/Web/HTML/HTML5/HTML5_element_list

Atributos de um elemento HTML.

Esse é a estrutura basica de um código escrito em HTML

O deve sempre ser incluído no topo da página, essa declaração que vai informaro ao borwser que o documento deve ser interprtado como HTML 5. Logo após nos temos o elemento html que elvolve todos os elementos da página que serão exibidos no browser. O HTML possui dois atributos muito interessantes um dele é o lang que indica em qual lingua a página está desenvolvida e o elemento `dir` que indica a direção do texto. Veja os exemplos:

```html

```





