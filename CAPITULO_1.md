#HTML

O HTML é uam liguagem de Hypertexto para acesso acesso a pagínas, o protocolo utilizado paara acessar esas informaçlão é HTTP ou HTPPS e elas estão doisponive atraves de nomes chamados de URI. O HTML é uuma sigla e possui o seguinte siognificado, isos que devemos utiliar o HTMLL para pugicar.

O desenvover d HTML é nada mais nada menos que Tim bernes Lee 
O HTMK e uma linguagem independente de platarofrmas, ou meios de acesso permitidno que ela seja extedidade a qualquer um que queira utilziar.
E uma plataforma universal


##Introdução ao HTML

O HTML não é *case senitive*, ou seja, você pode escrever seus códigos em letras minusculas ou maiuscolas (eu recomendo fortemente a escrita em letras minuscolas), sua escrita é de fácil leitura e toda a sua estrutura é baseada em *tags* que são elementos que informam ao navegador como ele renderizar determinda informação, as *tags* também são conecidas como elementos. Uma documento HTML é formado por um conjunto de *tags* que serão itnerpretadas pelo browser e exibida através de uma página HTML.

Uma *tag* é formada pelo seu nome, precedido do caractere "<" (menor que) sucedido pelo caractere ">" (maior que). A maiorias das *tag* possum um *tag* correspondente conecida como *tag* de fechamento que indica o final da *tag*, essa *tag* é compostas pela mesma estrutura da tag de abertura acresentando o caractere "/" após o caractere ">". Veja o exemplo.

Listagem 1
```html
<p>Bom dia!</p>
```
Veja nesse exemplo o uso da *tag* `p` e observe como ela possui uma tag de abertura, `<p>` e uma tag de fechamento `</p>`.

Existem algumas tag que não necessitam da tag de fechamento, seu uso é facultativo, nesse casos o uso do caractere  "/" pode vir logo após a tag de abertura. a tag `br` é um exemplo e pode ser escrita dessa forma `<br>` ou `<br />`. Esse tipo de tag é conhecido como **tag vazia** ou **elemento vazio**. Isso é uma caracteristica de documentos escritos em XHTML, eu recomentdo não utilizar o "/" em tag vazias.

Uma lista completa de todas as *tags* disponiveis no HTML5 por ser encontrada nesse link https://developer.mozilla.org/pt-BR/docs/Web/HTML/HTML5/HTML5_element_list

As *tags* Atributos de um elemento HTML.

##HTML5 



Esse é a estrutura basica de um código escrito em HTML5 e decrito da seguinte forma:


Salve esse arquivo com o nome de primeiro.html, pois vamos modifica-lo na sequencia.

O deve sempre ser incluído no topo da página, essa declaração que vai informaro ao borwser que o documento deve ser interprtado como HTML 5. Logo após nos temos o elemento html que elvolve todos os elementos da página que serão exibidos no browser. O HTML possui dois atributos muito interessantes um dele é o lang que indica em qual lingua a página está desenvolvida e o elemento `dir` que indica a direção do texto. Veja os exemplos:

```html
<html l>
```
A tag head possui informações de , veremos mais detalhes em outro capitulo.


Voce pode ter observado que o sinal especial çã da paravras não foi exeibido corretamente ao abrir o arqruivo primeiro.html, isso ocorreu pelo fato de não termos informaro ao browser que tipo de char sete ele deve usar para tratar de simbolos especiaias, é comum utilizar o char set UTF-8 para exibir pagainas escritar em prodtuges, dessa forma dentro da tag head vamos incluir a seguinte linha 

```html
utf-8
```

O resultado final de nosso c´pdigo é 

Abra novamente a pagina e veja com os caracteres são informado de forma correta.

Outro elemento basico de uma pagina html e o body, nele que estão todos os 


##Estrutad e uma pagina escrita em HTML5

Nos temos visto uma das mais interessantes melhorias no HTML5 o elementos que serao apresentados a seguir são elementos que ajudam a orginaizar a estrutura de nosso site, pense em um campo de futebol e em como temos as linhas que delemimanta cara area do campo, essas e a princial atribuicao dos elementos estruturaia sque vamos apresentar a seguir.


* Cabeçalho - <header></header>
* Menu de navegação  - <nav></nav> 
* Seçoes - <section></section>
* <article>
* <aside>
* <footer>
* 

É impostante detacar que esse elementos podem estar embutidos un nos outros, por exemplo um section pode ter um hearder, nav, article e assim por diante. Esse navas tags são muito importantes pois podem ser utilziadas para estilizar seu site com CSS especifico de cara area, 

Veja um exeml=plo de uso daassa tags. Crie o arquivo segundo.html com o conteúdo abaixo.

Salve o arquivo e abra ele em um browser. 

>Motores de renderização - são responsáveis pelo processamento da pagina



##Dicas para estudo 
Acesse o site da WHATWG - 

