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

## 5. Atributos Opcionais 

*   ### 5.1 `colspan (em <td> e <th>)`
Especifica o número de colunas que uma célula deve abranger.

```html
<td colspan="2">Célula que abrange duas colunas</td>
```
---

### Atributos Comuns em Diversas Tags HTML

1. **`class`**
   - Define uma ou mais classes CSS para o elemento.
   - Usado para aplicar estilos ou selecionar o elemento via JavaScript.

   ```html
   <div class="container main-content"></div>
   ```

2. **`id`**
   - Define um identificador único para o elemento.
   - Usado para estilos CSS e seleção JavaScript.

   ```html
   <div id="header"></div>
   ```

3. **`style`**
   - Aplica estilos CSS diretamente ao elemento.
   - Normalmente utilizado para estilos rápidos ou temporários.

   ```html
   <p style="color: red;">Texto em vermelho</p>
   ```

4. **`title`**
   - Fornece uma dica (tooltip) que aparece quando o usuário passa o mouse sobre o elemento.

   ```html
   <button title="Clique aqui para enviar">Enviar</button>
   ```

5. **`data-*`**
   - Atributos personalizados usados para armazenar dados extras no elemento.
   - Acessíveis via JavaScript.

   ```html
   <div data-user-id="12345"></div>
   ```

### Atributos Específicos para Tags Comuns

#### `<a>` (Link)

1. **`href`**
   - Define a URL de destino do link.

   ```html
   <a href="https://www.example.com">Visite o exemplo</a>
   ```

2. **`target`**
   - Define onde abrir o link.
   - `_self`: Abre na mesma janela (padrão).
   - `_blank`: Abre em uma nova aba ou janela.
   - `_parent`: Abre na janela pai.
   - `_top`: Abre no topo do frame.

   ```html
   <a href="https://www.example.com" target="_blank">Abrir em nova aba</a>
   ```

3. **`rel`**
   - Define a relação entre o documento atual e o link de destino.
   - `nofollow`: Informa aos motores de busca para não seguir o link.
   - `noopener`: Melhora a segurança ao abrir links em nova aba.

   ```html
   <a href="https://www.example.com" rel="noopener noreferrer">Link seguro</a>
   ```

#### `<img>` (Imagem)

1. **`src`**
   - Define o caminho da imagem.

   ```html
   <img src="imagem.jpg" alt="Descrição da imagem">
   ```

2. **`alt`**
   - Fornece texto alternativo para a imagem.

   ```html
   <img src="imagem.jpg" alt="Descrição da imagem">
   ```

3. **`width` e `height`**
   - Define a largura e a altura da imagem.

   ```html
   <img src="imagem.jpg" alt="Descrição da imagem" width="300" height="200">
   ```

4. **`loading`**
   - Especifica como a imagem deve ser carregada.
   - `lazy`: Carrega a imagem apenas quando está prestes a entrar na tela.

   ```html
   <img src="imagem.jpg" alt="Descrição da imagem" loading="lazy">
   ```

#### `<input>` (Campo de Entrada)

1. **`type`**
   - Define o tipo de campo de entrada.
   - Exemplos: `text`, `password`, `email`, `number`, `checkbox`, `radio`, etc.

   ```html
   <input type="text" placeholder="Digite seu nome">
   ```

2. **`placeholder`**
   - Texto exibido quando o campo está vazio.

   ```html
   <input type="text" placeholder="Digite seu nome">
   ```

3. **`value`**
   - Define o valor inicial do campo de entrada.

   ```html
   <input type="text" value="Texto inicial">
   ```

4. **`name`**
   - Nome do campo de entrada usado para identificação no envio de formulários.

   ```html
   <input type="text" name="username">
   ```

5. **`required`**
   - Indica que o campo é obrigatório para o envio do formulário.

   ```html
   <input type="text" required>
   ```

#### `<button>` (Botão)

1. **`type`**
   - Define o tipo do botão.
   - `button`: Botão comum.
   - `submit`: Envia o formulário.
   - `reset`: Reseta o formulário.

   ```html
   <button type="submit">Enviar</button>
   ```

2. **`disabled`**
   - Desativa o botão, impedindo que seja clicado.

   ```html
   <button disabled>Desativado</button>
   ```

### Exemplo Completo com Diversos Atributos

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exemplo de Atributos Opcionais</title>
  <style>
    .highlight {
      color: red;
    }
  </style>
</head>
<body>
  <div id="main" class="container">
    <h1 title="Cabeçalho Principal">Bem-vindo</h1>
    <p style="font-size: 18px;" data-info="extra info">Este é um parágrafo com estilo inline e um atributo de dados.</p>
    <a href="https://www.example.com" target="_blank" rel="noopener noreferrer" class="highlight">Visite o exemplo</a>
    <img src="imagem.jpg" alt="Descrição da imagem" width="300" height="200" loading="lazy">
    <form>
      <input type="text" name="username" placeholder="Digite seu nome" required>
      <button type="submit">Enviar</button>
    </form>
  </div>
</body>
</html>
```

Esses atributos opcionais fornecem uma ampla gama de funcionalidades para enriquecer e controlar o comportamento e a aparência dos elementos HTML em suas páginas web.


---
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