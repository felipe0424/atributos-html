<div align="center">
<a href="https://felipe0424.github.io/PortfolioDev/HTML/index.html"><img src="https://github.com/user-attachments/assets/b0cd55d7-f6f0-4cf9-a90d-db45c1832215" alt="html" width="70" align="center"></a>

# **Atributos HTML**
### `Principais Atributos HTML `
</div>

## :bookmark_tabs: Índice
* [1. O que são Atributos?](#1-o-que-são-atributos-html)
* [2. Atributos comuns](#2-atributos-comuns)
    * [2.1. ID](#21-id)
    * [2.2. class ](#22-class)
    * [2.3. style](#23-style)
    * [2.4. title](#24-title)
    * [2.5. href](#25-href)
    * [2.6. src](#26-src)
    * [2.7. alt](#27-alt)
    * [2.8. type](#28-type)
    * [2.9. value](#29-value)
* [3. Atributos Globais](#3-atributos-globais)
    * [3.1. data](#31-data-)
    * [3.2. contenteditable](#32-contenteditable)
    * [3.3. hidden](#33-hidden)
    * [3.4. tabindex](#34-tabindex)
    * [3.5. aria](#35-aria-)
* [4. Atributos Específicos](#4-atributos-específicos-de-elementos)
    * [4.1. colspan](#41-colspan-em--e-)
    * [4.2. rowspan](#42-rowspan-em--e-)
    * [4.3. disable](#43-disabled-em----etc)
    * [4.4. checked](#44-checked-em--do-tipo-checkbox-ou-radio)
    * [4.5. selected](#45-selected-em-)
* [5. Boas Práticas](#5-boas-práticas)

## :computer:	Ferramentas utilizadas no desenvolvimento
<div align="auto">
    <a href="https://felipe0424.github.io/PortfolioDev/HTML/index.html"><img src="https://github.com/user-attachments/assets/b0cd55d7-f6f0-4cf9-a90d-db45c1832215" alt="html" width="50"></a>
    <a href="https://felipe0424.github.io/PortfolioDev/HTML/index.html"><img src="https://github.com/user-attachments/assets/64486d67-8973-4b62-bdfc-212cf9f16709" alt="md" width="50"></a>
    <a href="https://felipe0424.github.io/PortfolioDev/HTML/index.html"><img src="https://github.com/user-attachments/assets/d3813ef4-1409-40c9-9bfb-6e988f79b2c8" alt="Git" width="50"></a>
    <a href="https://felipe0424.github.io/PortfolioDev/HTML/index.html"><img src="https://github.com/user-attachments/assets/b03adba8-e155-4555-8737-2afaf449620d" alt="Node" width="50"></a>
</div>

## :books:	Conteúdo

## 1. O que são Atributos HTML?
Os atributos HTML são usados para fornecer informações adicionais sobre elementos HTML. Eles são sempre especificados na tag inicial e geralmente vêm em pares de nome/valor, como `name="value"`.

## 2. Atributos Comuns

*   ### 2.1 `id`
Define um identificador único para um elemento HTML.
```html
<div id="mainContent"></div>
```

*   ### 2.2 `class`
Atribui uma ou mais classes a um elemento para estilização e manipulação com CSS e JavaScript.

```html
<p class="intro text-primary"></p>
```

*   ### 2.3 `style`
Adiciona estilo CSS diretamente a um elemento.

```html
<h1 style="color: blue; text-align: center;"></h1>
```

*   ### 2.4 `title`
Fornece informações adicionais sobre um elemento (geralmente exibidas como uma dica de ferramenta).

```html
<abbr title="Hypertext Markup Language">HTML</abbr>
```

*   ### 2.5 `href`
Especifica o URL de uma página para a qual o link deve ir.

```html
<a href="https://www.example.com">Visite nosso site</a>
```
*   ### 2.6 `src`
Especifica o URL de uma imagem ou recurso incorporado.

```html
<img src="image.jpg" alt="Descrição da imagem">
```
*   ### 2.7 `alt`
Fornece texto alternativo para uma imagem se a imagem não puder ser exibida.

```html

<img src="image.jpg" alt="Descrição da imagem">
```

*   ### 2.8 `type`
Define o tipo de elemento (geralmente usado em elementos `<input>` e `<button>`).

```html

<input type="text">
```

*   ### 2.9 `value`
Especifica o valor de um elemento (geralmente usado em elementos `<input>`, `<button>`, e `<option>`).

```html
<input type="text" value="Digite seu nome">
```

*   ### 2.10 `placeholder`
Fornece um texto de espaço reservado para um campo de entrada.

```html
<input type="text" placeholder="Digite seu nome">
```

## 3. Atributos Globais

*   ### 3.1 `data-*`
Usado para armazenar dados personalizados privados para a página ou aplicativo.

```html
<div data-user-id="12345"></div>
```

*   ### 3.2 `contenteditable`
Indica se o conteúdo de um elemento é editável ou não.

```html
<div contenteditable="true">Este texto pode ser editado pelo usuário.</div>
```

*   ### 3.3 `hidden`
Oculta um elemento.

```html
<div hidden>Este conteúdo está oculto.</div>
```

*   ### 3.4 `tabindex`
Especifica a ordem de tabulação de um elemento.

```html
<button tabindex="1">Primeiro Botão</button>
```
*   ### 3.5 `aria-*`
Atributos usados para melhorar a acessibilidade de elementos.

```html
<button aria-label="Fechar">X</button>
```

## 4. Atributos Específicos de Elementos

*   ### 4.1 `colspan (em <td> e <th>)`
Especifica o número de colunas que uma célula deve abranger.

```html
<td colspan="2">Célula que abrange duas colunas</td>
```

*   ### 4.2 `rowspan` (em `<td>` e `<th>`)
Especifica o número de linhas que uma célula deve abranger.

```html
<td rowspan="2">Célula que abrange duas linhas</td>
```

*   ### 4.3 `disabled` (em `<input>`, `<button>`, `<select>`, etc.)
Desabilita um elemento de formulário.

```html
<button disabled>Não pode ser clicado</button>
```

*   ### 4.4 `checked` (em <input> do tipo checkbox ou radio)
Indica que uma entrada de caixa de seleção ou rádio deve ser pré-selecionada.

```html
<input type="checkbox" checked>
```

*   ### 4.5 `selected` (em `<option>`)
Indica que uma opção deve ser pré-selecionada em uma lista suspensa.

```html
<option selected>Opção padrão</option>
```

## 5. Boas Práticas
Usar valores válidos e semânticos: Certifique-se de que os valores dos atributos sejam válidos e correspondam ao propósito pretendido.
Consistência e clareza: Use nomes de atributos que sejam claros e consistentes em todo o código.

Acessibilidade: Sempre considere a acessibilidade ao usar atributos, especialmente aqueles que afetam a navegação e a leitura de tela.
Este guia cobre os conceitos básicos e alguns atributos comuns, mas há muitos outros atributos específicos para diferentes elementos HTML.

## :telephone_receiver: Contato
Para saber mais sobre meus trabalhos, entre em contato comigo através do <a href="https://www.linkedin.com/in/jfeliperamos/">LinkedIn</a> ou visite meu <a href="https://felipe0424.github.io/PortfolioDev/HTML/index.html">GitHub.</a> 

<div align=center>
    <a href="https://www.linkedin.com/in/jfeliperamos/">
        <img src="https://github.com/user-attachments/assets/0350e54a-100e-4273-aa51-81aa9fce3d79" alt="LinkedIn" width="25">
    </a> 
    <a href="https://felipe0424.github.io/PortfolioDev/HTML/index.html">
        <img src="https://github.com/user-attachments/assets/3fda6271-fd40-4485-bb7c-60b927b9feae" alt="GitHub" width="25">
    </a>
</div>

> [!WARNING]
> Este código é disponibilizado exclusivamente para fins de estudo e aprendizado. A reprodução total ou parcial deste código, sem autorização prévia, é expressamente proibida. A utilização deste código em projetos comerciais, distribuição não autorizada ou qualquer outro uso que não seja educativo pode resultar em sanções legais. Ao utilizar este código, você concorda em respeitar os termos de uso e a propriedade intelectual do autor.