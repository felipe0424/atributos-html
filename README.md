# **FORMS HTML**

## Índice
* [1. Form](#1-definir-o-documento-html)
* [2. Cabeçalho e Parágrafos](#2-cabeçalhos-e-parágrafos)
* [3. Definir Parágrafo](#3-definir-um-parágrafo)
* [4. Botões *Buttons*](#4-botão)
* [5. Formatação de Texto](#5-formatação-de-texto)
* [6. Listas](#6-listas)
* [7. Links e Imagens](#7-links-e-imagens)
* [8. Tabelas](#8-tabelas)
* [9. Formulários](#9-formulários)
* [10. Seções e Agrupamentos](#10-seções-e-agrupamentos)
* [11. Outras Tags](#11-outros)

## Ferramentas utilizadas no desenvolvimento
<div align="auto">
    <a href="https://felipe0424.github.io/PortfolioDev/HTML/index.html"><img src="https://github.com/user-attachments/assets/3804386a-094d-42de-8a5d-f4dfb033ffba" alt="js" width="50"></a>
    <a href="https://felipe0424.github.io/PortfolioDev/HTML/index.html"><img src="https://github.com/user-attachments/assets/99565e92-5ce7-4298-ac67-95801f113f9f" alt="ts" width="50"></a>
    <a href="https://felipe0424.github.io/PortfolioDev/HTML/index.html"><img src="https://github.com/user-attachments/assets/64486d67-8973-4b62-bdfc-212cf9f16709" alt="md" width="50"></a>
    <a href="https://felipe0424.github.io/PortfolioDev/HTML/index.html"><img src="https://github.com/user-attachments/assets/d3813ef4-1409-40c9-9bfb-6e988f79b2c8" alt="Git" width="50"></a>
    <a href="https://felipe0424.github.io/PortfolioDev/HTML/index.html"><img src="https://github.com/user-attachments/assets/b03adba8-e155-4555-8737-2afaf449620d" alt="Node" width="50"></a>
</div>

### 1. Form
Para iniciar o novo documento digite `<form action="">` html* ou *!* e depois tecle *Enter* que iniciará.
 
```r
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Título da Página</title>
</head>
<body>
    [Conteúdo da página]
</body>
</html>
```

### 2. Cabeçalhos e Parágrafos
Definem cabeçalhos, sendo *h1* o mais importante e *h6* o menos importante.

```r
<h1>Cabeçalho 1</h1>
<h2>Cabeçalho 2</h2>
<h3>Cabeçalho 3</h3>
<h4>Cabeçalho 4</h4>
<h5>Cabeçalho 5</h5>
<h6>Cabeçalho 6</h6>
```

### 3. Definir um parágrafo
```r
<p>Este é um parágrafo de texto.</p>
```

### 4. Botão
```r
<button type="button">
    Clique Aqui
</button>
```

### 5. Formatação de Texto
* Negrito
```r
<b>
    Texto em negrito
</b>
```
* Itálico
```r
<i>
    Texto em itálico
</i>
```
* Destaque Negrito
```r
<p>
    Texto em <strong>destaque</strong>
</p>
```
* Span
```r
<p>
    Texto <span>importante</span>
</p>
```
* Small
```r
<p>
    Texto <small>importante</small>
</p>
```

### 6. Listas
* Lista não ordenada

```r
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>
```
* Lista ordenada
```r
<ol>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>
```

### 7. Links e Imagens
* Hiperlink
```r
<a href="https://www.exemplo.com" target="_blank" title="Visite o Exemplo">Clique Aqui</a>
```
* Imagem
```r
<img src="caminho/para/imagem.jpg" alt="Descrição da imagem" width="300" height="200">
```
* Imagem + Link
```r
<a 
href="https://www.exemplo.com">
    <img src="caminho/para/imagem.jpg" alt="Descrição da imagem" width="300" height="200">
</a>
```

### 8. Tabelas
* Definir uma tabela
```r
<table>
    <thead>
        <tr>
            <th>Coluna 1</th>
            <th>Coluna 2</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Dado 1</td>
            <td>Dado 2</td>
        </tr>
        <tr>
            <td>Dado 3</td>
            <td>Dado 4</td>
        </tr>
    </tbody>
</table>
```

### 9. Formulários
* Definir um formulário
```r
<form action="/enviar" method="post">
    <label for="nome">Nome:</label>
    <input type="text" id="nome" name="nome">
    
    <label for="mensagem">Mensagem:</label>
    <textarea id="mensagem" name="mensagem"></textarea>
    
    <label for="opcoes">Escolha uma opção:</label>
    <select id="opcoes" name="opcoes">
        <option value="opcao1">Opção 1</option>
        <option value="opcao2">Opção 2</option>
    </select>
    
    <button type="submit">Enviar</button>
</form>
```

### 10. Seções e Agrupamentos
* Div (Divisão ou seção)
```r
<div class="container">
    <h2>Conteúdo da Div</h2>
    <p>Este é um exemplo de uso da tag &lt;div&gt; para agrupar conteúdo.</p>
</div>
```
* Header (Cabeçalho)
```r
<header>
    <h1>Título da Página</h1>
    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Sobre</a></li>
            <li><a href="#">Contato</a></li>
        </ul>
    </nav>
</header>
```
* Footer (Rodapé)
```r
<footer>
    <p>
    &copy; 2024 Nome da Empresa. Todos os direitos reservados.
    </p>
</footer>
```
* Section (Seção)
```r
<section>
    <h2>Introdução</h2>
    <p>Este é um exemplo de uso da tag &lt;section&gt; para agrupar conteúdo relacionado.</p>
</section>
```
* Nav (Menu de navegação)
```r
<nav>
    <h2>Introdução</h2>
    <p>Este é um exemplo de uso da tag &lt;section&gt; para agrupar conteúdo relacionado.</p>
</nav>
```
* Aticle (Artigo)
```r
<article>
    <h2>Introdução</h2>
    <p>Este é um exemplo de uso da tag &lt;section&gt; para agrupar conteúdo relacionado.</p>
</article>
```
* Aside ()
```r
<aside>
    <h2>Introdução</h2>
    <p>Este é um exemplo de uso da tag &lt;section&gt; para agrupar conteúdo relacionado.</p>
</aside>
```
### 11. Outros
* Script
```r
<script>
    console.log('Olá, mundo!');
</script>
```
* Link para CSS
```r
<link rel="stylesheet" href="estilos.css">
```
* Metadados
```r
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Título do site">
```
* Estilos embutidos
```r
<style>
    body {
        font-family: Arial, sans-serif;
    }
</style>
```
## Contato
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