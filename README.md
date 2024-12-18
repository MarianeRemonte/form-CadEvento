# Projeto - Cadastro de evento

projeto criado como parte avaliativa da disciplina de Fundamentos de Desenvolvimento Web ministrada pelo professor Leonardo Rocha


## Índicie

* [Descrição](#descrição)
* [Tecnologias](#tecnologias)
* [Referências](#referências)
* [Autor](#autora)

### descrição

O projeto consiste na construção de uma tela de cadastro de evento, possibilitando o usuário a realizar um cadastro em um site destinado para organização de eventos não existente, inserindo e-mail, nome completo, telefone e outras informações referentes ao tipo de cerimônea a ser realizada. O projeto foi realizado em sala, utilizando diversos elementos do HTML5 e propriedades do CSS3.


### Resultado do projeto

#### Formulário

Foram usados os seguintes elementos:

* Div - Cria container com elementos dentro de si.
* Class - Atribui nome para o elemento HTML, possibilitando sua estilização no CSS.
* Form - define o formulário e os atributos que definem a maneira como esse formulário se comporta
* H3 - Usado para inserir título no formulário.
* Label - Dá nome para a área de escrita, seja e-mail ou senha.
* Input -  Permite que o usuário escreva na página.
* Select -  Cria um pequeno container com capacidade de armazenar opções de escolha
* Option -  Cria uma opção para o select
* Button -  Cria um botão clicável.
* Textarea - Gera uma área para que o usuário escreva um texto maior que o pemitido no Input, como parágrafos.

Veja agora imagens dos elementos citados anteriormente:

![Imagem ilustrativa dos elementos sendo utilizados no código](img/html.PNG)


Além dos elementos do HTML5, também foram usados as propriedades do CSS3. Segue aqui as utilizadas no projeto:

##### Cor

* Background-color - Altera a cor do fundo do projeto.

```
background-color:rgb(147, 83, 177);
```

* Box-shadow - Adicona sombra ao fundo de um container presente na composição.
```
 box-shadow: 0 0 20px rgb(31, 4, 31);
```


* Color - Foi usado par mudar a cor do testo do título.

```
background-color: rgb(228, 188, 233);
```

##### Texto

* Text-align - Alinha texto de acordo com a função colocada junto.

![Imagem iustrando uso do elemento citado](img/T-al.PNG)

* Font-family - Muda a fonte do texto.

![Imagem iustrando uso do elemento citado](img/T-f.PNG)


##### Outros

Todos os itens abaixo foram usados na aba do container.

* Display - Define comportamento dos elementos. Usado no Body e Container.
* Justify-content - usada para alinhar os elementos ao longo do eixo principal em horizontal.
* Align-items - Alinha os itens verticalmente
* Width - Largura aplicada na ciaxa do projeto.
* Height - Altura aplicada na caixa do projeto,

```
display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 100%;
```

Todos os elementos abaixo pertencem a aba do form:


* Padding - Afasta a borda (Padding-top apenas a define como afastar apenas a borda de cima.)
* Border-radius - Arredonda a borda da caixa de login do projeto.

```
    padding: 30px;
    padding: 30px;
    padding-top: 0;
    padding-left: 70px;
    padding-right: 70px;
```

A seguir, ilustra a imagem do resultado final do projeto:

![Resultado final do projeto - Imagem 1](img/final.PNG)


### Estilização

O projeto foi estilizado, utilizando CSS3. Foi criado um arquivo main.css. Nesse arquivo constam configurações de estlo apresentadas a seguir:

* Estilo de cores - A cor de fundo no projeto foi definida como segue:

```
.Form{
    background-color: rgb(228, 188, 233);
```

```
body{
    background-color:rgb(147, 83, 177);
```

O elemento background-color foi utilizado con diferentes finalidades e cada parte do projeto, uma para definir o fundo total e outra como definição do fundo da caixa de cadastro.


## Tecnologias

* HTML5
* CSS3
* README
* Git
* Github

## Referências

[Alura](https://www.alura.com.br/artigos/escrever-bom-readme) - Como escrever um README incrível no seu Github <br>
[w3school](https://www.w3schools.com/cssref/css3_pr_justify-content.php) - Explica como usar propriedade Justify-content e align-itens. Também possui explicações sobre outras propriedades CSS e HTML. <br>
[developer.mozilla CSS3](https://developer.mozilla.org/pt-BR/docs/Web/CSS/box-shadow) - Explica as demais propriedades CSS <br>
[developer.mozilla HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Attributes) - Explica as demais propriedades HTML <br>


# Autora

O projeto foi desenvolvido por:

* Mariane Lima Remonte Viana.

