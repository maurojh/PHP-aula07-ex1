"# PHP-aula07-ex1" 
<?xml version="1.0" encoding="utf-8"?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" lang="en" xml:lang="en">
  <head>
    <link href="https://fonts.googleapis.com/css?family=Open+Sans&display=swap" rel="stylesheet">
<!-- 2019-09-30 seg 19:32 -->
<meta http-equiv="Content-Type" content="text/html;charset=utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>&lrm;</title>
<meta name="generator" content="Org mode" />
<style type="text/css">
  <!--/*--><![CDATA[/*><!--*/
  body { font-family: 'Open Sans', sans-serif; }
  .title  { text-align: center;
             margin-bottom: .2em; }
  .subtitle { text-align: center;
              font-size: medium;
              font-weight: bold;
              margin-top:0; }
  .todo   { font-family: monospace; color: red; }
  .done   { font-family: monospace; color: green; }
  .priority { font-family: monospace; color: orange; }
  .tag    { background-color: #eee; font-family: monospace;
            padding: 2px; font-size: 80%; font-weight: normal; }
  .timestamp { color: #bebebe; }
  .timestamp-kwd { color: #5f9ea0; }
  .org-right  { margin-left: auto; margin-right: 0px;  text-align: right; }
  .org-left   { margin-left: 0px;  margin-right: auto; text-align: left; }
  .org-center { margin-left: auto; margin-right: auto; text-align: center; }
  .underline { text-decoration: underline; }
  #postamble p, #preamble p { font-size: 90%; margin: .2em; }
  p.verse { margin-left: 3%; }
  pre {
    border: 1px solid #ccc;
    box-shadow: 3px 3px 3px #eee;
    padding: 8pt;
    font-family: monospace;
    overflow: auto;
    margin: 1.2em;
  }
  pre.src {
    position: relative;
    overflow: visible;
    padding-top: 1.2em;
  }
  pre.src:before {
    display: none;
    position: absolute;
    background-color: white;
    top: -10px;
    right: 10px;
    padding: 3px;
    border: 1px solid black;
  }
  pre.src:hover:before { display: inline;}
  /* Languages per Org manual */
  pre.src-asymptote:before { content: 'Asymptote'; }
  pre.src-awk:before { content: 'Awk'; }
  pre.src-C:before { content: 'C'; }
  /* pre.src-C++ doesn't work in CSS */
  pre.src-clojure:before { content: 'Clojure'; }
  pre.src-css:before { content: 'CSS'; }
  pre.src-D:before { content: 'D'; }
  pre.src-ditaa:before { content: 'ditaa'; }
  pre.src-dot:before { content: 'Graphviz'; }
  pre.src-calc:before { content: 'Emacs Calc'; }
  pre.src-emacs-lisp:before { content: 'Emacs Lisp'; }
  pre.src-fortran:before { content: 'Fortran'; }
  pre.src-gnuplot:before { content: 'gnuplot'; }
  pre.src-haskell:before { content: 'Haskell'; }
  pre.src-hledger:before { content: 'hledger'; }
  pre.src-java:before { content: 'Java'; }
  pre.src-js:before { content: 'Javascript'; }
  pre.src-latex:before { content: 'LaTeX'; }
  pre.src-ledger:before { content: 'Ledger'; }
  pre.src-lisp:before { content: 'Lisp'; }
  pre.src-lilypond:before { content: 'Lilypond'; }
  pre.src-lua:before { content: 'Lua'; }
  pre.src-matlab:before { content: 'MATLAB'; }
  pre.src-mscgen:before { content: 'Mscgen'; }
  pre.src-ocaml:before { content: 'Objective Caml'; }
  pre.src-octave:before { content: 'Octave'; }
  pre.src-org:before { content: 'Org mode'; }
  pre.src-oz:before { content: 'OZ'; }
  pre.src-plantuml:before { content: 'Plantuml'; }
  pre.src-processing:before { content: 'Processing.js'; }
  pre.src-python:before { content: 'Python'; }
  pre.src-R:before { content: 'R'; }
  pre.src-ruby:before { content: 'Ruby'; }
  pre.src-sass:before { content: 'Sass'; }
  pre.src-scheme:before { content: 'Scheme'; }
  pre.src-screen:before { content: 'Gnu Screen'; }
  pre.src-sed:before { content: 'Sed'; }
  pre.src-sh:before { content: 'shell'; }
  pre.src-sql:before { content: 'SQL'; }
  pre.src-sqlite:before { content: 'SQLite'; }
  /* additional languages in org.el's org-babel-load-languages alist */
  pre.src-forth:before { content: 'Forth'; }
  pre.src-io:before { content: 'IO'; }
  pre.src-J:before { content: 'J'; }
  pre.src-makefile:before { content: 'Makefile'; }
  pre.src-maxima:before { content: 'Maxima'; }
  pre.src-perl:before { content: 'Perl'; }
  pre.src-picolisp:before { content: 'Pico Lisp'; }
  pre.src-scala:before { content: 'Scala'; }
  pre.src-shell:before { content: 'Shell Script'; }
  pre.src-ebnf2ps:before { content: 'ebfn2ps'; }
  /* additional language identifiers per "defun org-babel-execute"
       in ob-*.el */
  pre.src-cpp:before  { content: 'C++'; }
  pre.src-abc:before  { content: 'ABC'; }
  pre.src-coq:before  { content: 'Coq'; }
  pre.src-groovy:before  { content: 'Groovy'; }
  /* additional language identifiers from org-babel-shell-names in
     ob-shell.el: ob-shell is the only babel language using a lambda to put
     the execution function name together. */
  pre.src-bash:before  { content: 'bash'; }
  pre.src-csh:before  { content: 'csh'; }
  pre.src-ash:before  { content: 'ash'; }
  pre.src-dash:before  { content: 'dash'; }
  pre.src-ksh:before  { content: 'ksh'; }
  pre.src-mksh:before  { content: 'mksh'; }
  pre.src-posh:before  { content: 'posh'; }
  /* Additional Emacs modes also supported by the LaTeX listings package */
  pre.src-ada:before { content: 'Ada'; }
  pre.src-asm:before { content: 'Assembler'; }
  pre.src-caml:before { content: 'Caml'; }
  pre.src-delphi:before { content: 'Delphi'; }
  pre.src-html:before { content: 'HTML'; }
  pre.src-idl:before { content: 'IDL'; }
  pre.src-mercury:before { content: 'Mercury'; }
  pre.src-metapost:before { content: 'MetaPost'; }
  pre.src-modula-2:before { content: 'Modula-2'; }
  pre.src-pascal:before { content: 'Pascal'; }
  pre.src-ps:before { content: 'PostScript'; }
  pre.src-prolog:before { content: 'Prolog'; }
  pre.src-simula:before { content: 'Simula'; }
  pre.src-tcl:before { content: 'tcl'; }
  pre.src-tex:before { content: 'TeX'; }
  pre.src-plain-tex:before { content: 'Plain TeX'; }
  pre.src-verilog:before { content: 'Verilog'; }
  pre.src-vhdl:before { content: 'VHDL'; }
  pre.src-xml:before { content: 'XML'; }
  pre.src-nxml:before { content: 'XML'; }
  /* add a generic configuration mode; LaTeX export needs an additional
     (add-to-list 'org-latex-listings-langs '(conf " ")) in .emacs */
  pre.src-conf:before { content: 'Configuration File'; }

  table { border-collapse:collapse; }
  caption.t-above { caption-side: top; }
  caption.t-bottom { caption-side: bottom; }
  td, th { vertical-align:top;  }
  th.org-right  { text-align: center;  }
  th.org-left   { text-align: center;   }
  th.org-center { text-align: center; }
  td.org-right  { text-align: right;  }
  td.org-left   { text-align: left;   }
  td.org-center { text-align: center; }
  dt { font-weight: bold; }
  .footpara { display: inline; }
  .footdef  { margin-bottom: 1em; }
  .figure { padding: 1em; }
  .figure p { text-align: center; }
  .inlinetask {
    padding: 10px;
    border: 2px solid gray;
    margin: 10px;
    background: #ffffcc;
  }
  #org-div-home-and-up
   { text-align: right; font-size: 70%; white-space: nowrap; }
  textarea { overflow-x: auto; }
  .linenr { font-size: smaller }
  .code-highlighted { background-color: #ffff00; }
  .org-info-js_info-navigation { border-style: none; }
  #org-info-js_console-label
    { font-size: 10px; font-weight: bold; white-space: nowrap; }
  .org-info-js_search-highlight
    { background-color: #ffff00; color: #000000; font-weight: bold; }
  .org-svg { width: 90%; }
  pre, code {font-family: 'Open Sans', sans-serif;}
  /*]]>*/-->
</style>
<script type="text/javascript">
/*
@licstart  The following is the entire license notice for the
JavaScript code in this tag.

Copyright (C) 2012-2019 Free Software Foundation, Inc.

The JavaScript code in this tag is free software: you can
redistribute it and/or modify it under the terms of the GNU
General Public License (GNU GPL) as published by the Free Software
Foundation, either version 3 of the License, or (at your option)
any later version.  The code is distributed WITHOUT ANY WARRANTY;
without even the implied warranty of MERCHANTABILITY or FITNESS
FOR A PARTICULAR PURPOSE.  See the GNU GPL for more details.

As additional permission under GNU GPL version 3 section 7, you
may distribute non-source (e.g., minimized or compacted) forms of
that code without the copy of the GNU GPL normally required by
section 4, provided you include this license notice and a URL
through which recipients can access the Corresponding Source.


@licend  The above is the entire license notice
for the JavaScript code in this tag.
*/
<!--/*--><![CDATA[/*><!--*/
 function CodeHighlightOn(elem, id)
 {
   var target = document.getElementById(id);
   if(null != target) {
     elem.cacheClassElem = elem.className;
     elem.cacheClassTarget = target.className;
     target.className = "code-highlighted";
     elem.className   = "code-highlighted";
   }
 }
 function CodeHighlightOff(elem, id)
 {
   var target = document.getElementById(id);
   if(elem.cacheClassElem)
     elem.className = elem.cacheClassElem;
   if(elem.cacheClassTarget)
     target.className = elem.cacheClassTarget;
 }
/*]]>*///-->
</script>
</head>
<body>
<div id="content">
<div id="table-of-contents">
<h2>Table of Contents</h2>
<div id="text-table-of-contents">
<ul>
<li><a href="#org2ebcabf">1. Classes</a>
<ul>
<li><a href="#org0bd4286">1.1. Definir uma classe</a></li>
<li><a href="#org33bca5e">1.2. Definindo objetos</a></li>
<li><a href="#org1ca68b0">1.3. Utilizando métodos</a></li>
<li><a href="#orgfec5234">1.4. Modificador de acesso</a></li>
<li><a href="#org445992b">1.5. Construtor</a></li>
</ul>
</li>
<li><a href="#orgfd115e0">2. Mysqli orientado a objetos</a>
<ul>
<li><a href="#orgbd4a5d1">2.1. Abrindo a conexão</a></li>
<li><a href="#org585b758">2.2. Fechar a conexão</a></li>
<li><a href="#orgd4ef660">2.3. Exercício 1</a></li>
<li><a href="#org446d13b">2.4. Criando banco de dados</a></li>
<li><a href="#orgb0062ca">2.5. Exercício 2</a></li>
<li><a href="#orgaa36d08">2.6. Criando tabelas</a></li>
<li><a href="#org4859951">2.7. Exercício 3</a></li>
<li><a href="#org5307ab0">2.8. Inserindo dados</a></li>
<li><a href="#org1142516">2.9. Exercício 4</a></li>
<li><a href="#org4e3fc75">2.10. Exercício 5</a></li>
<li><a href="#orgf6985a5">2.11. Exercício 6</a></li>
<li><a href="#org58cb6b3">2.12. Exercício 7</a></li>
<li><a href="#orgcb95734">2.13. Exercício 8</a></li>
<li><a href="#org4b3e119">2.14. Exercício 9</a></li>
</ul>
</li>
</ul>
</div>
</div>

<div id="outline-container-org2ebcabf" class="outline-2">
<h2 id="org2ebcabf"><span class="section-number-2">1</span> Classes</h2>
<div class="outline-text-2" id="text-1">
</div>
<div id="outline-container-org0bd4286" class="outline-3">
<h3 id="org0bd4286"><span class="section-number-3">1.1</span> Definir uma classe</h3>
<div class="outline-text-3" id="text-1-1">
<p>
A palavra chave <b>class</b> define uma classe em PHP:
</p>

<pre class="example">
class Carro {
  // propriedades do carro

  // métodos do carro
}
</pre>

<p>
Ajustamos as propriedades como variáveis dentro da classe:
</p>

<pre class="example">
class Carro {
  $portas = 2;
  $cor = "black";
  $rodas = 14;

  // métodos do carro
}
</pre>

<p>
Métodos são ajustados como funções dentro da classe.
</p>

<pre class="example">
class Carro {
  $portas = 2;
  $cor = "black";
  $rodas = 14;
  $velocidade = 0;

  function acelera() {
     $velocidade = $velocidade + 10;
  }

  function freia() {
     $velocidade = $velocidade - 10;
  }
}
</pre>
</div>
</div>

<div id="outline-container-org33bca5e" class="outline-3">
<h3 id="org33bca5e"><span class="section-number-3">1.2</span> Definindo objetos</h3>
<div class="outline-text-3" id="text-1-2">
<p>
Definidas as classes podemos criar objetos usando <b>new</b>:
</p>

<pre class="example">
class Carro {
  $portas = 2;
  $cor = "black";
  $rodas = 14;
  $velocidade = 0;

  function acelera() {
     $velocidade = $velocidade + 10;
  }

  function freia() {
     $velocidade = $velocidade - 10;
  }

  function get_velocidade() {
     return $velocidade;
  }
}

$fusca = new Carro();
$ferrari = new Carro();
</pre>
</div>
</div>

<div id="outline-container-org1ca68b0" class="outline-3">
<h3 id="org1ca68b0"><span class="section-number-3">1.3</span> Utilizando métodos</h3>
<div class="outline-text-3" id="text-1-3">
<p>
Criados os objetos podemos utilizar os métodos usando <b>-&gt;</b>:
</p>

<pre class="example">
$fusca = new Carro();
$ferrari = new Carro();

$fusca-&gt;acelera():
$fusca-&gt;acelera();

echo $fusca-&gt;get_velocidade();

$ferrari-&gt;acelera();

echo $ferrari-&gt;get_velocidade();
</pre>
</div>
</div>

<div id="outline-container-orgfec5234" class="outline-3">
<h3 id="orgfec5234"><span class="section-number-3">1.4</span> Modificador de acesso</h3>
<div class="outline-text-3" id="text-1-4">
<p>
Podemos modificar o tipo de acesso das propriedades da classe e dos métodos:
</p>

<ul class="org-ul">
<li>public - a propriedade ou método pode ser vista por qualquer um (padrão).</li>
<li>protected - somente a própria classe e derivadas podem acessar a propriedade ou método.</li>
<li>private - somente a própria classe pode acessar a propriedade ou método.</li>
</ul>

<pre class="example">
class Carro {
  private $portas = 2;
  private $cor = "black";
  private $rodas = 14;
  public $velocidade = 0;

  function acelera() {
     $velocidade = $velocidade + 10;
  }

  function freia() {
     $velocidade = $velocidade - 10;
  }

  function get_velocidade() {
     return $velocidade;
  }
}

$ferrari = new Carro();

echo $ferrari-&gt;velocidade;
</pre>
</div>
</div>

<div id="outline-container-org445992b" class="outline-3">
<h3 id="org445992b"><span class="section-number-3">1.5</span> Construtor</h3>
<div class="outline-text-3" id="text-1-5">
<p>
A função __construct permite inicializar uma propriedade de um objeto no momento da criação do objeto.
</p>

<p>
Se você criar uma função <b>__construct()</b> o PHP vai executá-la automaticamente quando você criar um objeto da classe.
</p>

<pre class="example">
class Carro {
  public $velocidade = 0;

  function acelera() {
     $velocidade = $velocidade + 10;
  }

  function freia() {
     $velocidade = $velocidade - 10;
  }

  function __construct() {
     $velocidade = 10;
  }
}

$ferrari = new Carro();

echo $ferrari-&gt;velocidade; // Começa com 10
</pre>
</div>
</div>
</div>


<div id="outline-container-orgfd115e0" class="outline-2">
<h2 id="orgfd115e0"><span class="section-number-2">2</span> Mysqli orientado a objetos</h2>
<div class="outline-text-2" id="text-2">
</div>
<div id="outline-container-orgbd4a5d1" class="outline-3">
<h3 id="orgbd4a5d1"><span class="section-number-3">2.1</span> Abrindo a conexão</h3>
<div class="outline-text-3" id="text-2-1">
<p>
Antes de acessar os dados em um banco de dados MySQL, você precisa se conectar ao servidor:
</p>

<pre class="example">
&lt;?php

$servidor = "localhost";
$usuario = "root";
$senha = "toor";

// Cria a conexão:
// Novo objeto!
$conexao = new mysqli($servidor, $usuario, $senha);

// Verifica a conexão
// Atributo do objeto $conexao
if( $conexao-&gt;connect_error ) {
   die("A conexão falhou: " . $conexao-&gt;connect_error());
}

echo "Conexão realizada com sucesso!";
?&gt;
</pre>
</div>
</div>


<div id="outline-container-org585b758" class="outline-3">
<h3 id="org585b758"><span class="section-number-3">2.2</span> Fechar a conexão</h3>
<div class="outline-text-3" id="text-2-2">
<p>
Quando o script termina, a conexão com o banco de dados é fechada automaticamente. Mas podemos fechá-la antes:
</p>

<pre class="example">
// método do objeto $conexao
$conexao-&gt;close();
</pre>
</div>
</div>

<div id="outline-container-orgd4ef660" class="outline-3">
<h3 id="orgd4ef660"><span class="section-number-3">2.3</span> Exercício 1</h3>
<div class="outline-text-3" id="text-2-3">
<p>
Crie uma página php chamada (teste.php) que verifica se a conexão com o servidor de banco de dados está sendo feita corretamente utilizando mysqli orientado a objetos.
</p>
</div>
</div>

<div id="outline-container-org446d13b" class="outline-3">
<h3 id="org446d13b"><span class="section-number-3">2.4</span> Criando banco de dados</h3>
<div class="outline-text-3" id="text-2-4">
<p>
Para criar o banco em PHP você efetua uma consulta (query) com o comando de criação:
</p>

<pre class="example">
$sql = "CREATE DATABASE prova";

// executando um método de $conexao
if ($conexao-&gt;query($sql) === TRUE) {
    echo "Banco de dados criado";
} else {
    // acessando a propriedade error de $conexao
    echo "Erro na criação do banco: " . $conexao-&gt;error; 
}
</pre>

<p>
A página completa deve:
</p>

<ul class="org-ul">
<li>criar a conexão com o servidor de banco de dados</li>
<li>efetuar a consulta</li>
<li>fechar a conexão</li>
</ul>

<pre class="example">
&lt;?php

$servidor = "localhost";
$usuario = "root";
$senha = "toor";

// Cria a conexão:
// Novo objeto!
$conexao = new mysqli($servidor, $usuario, $senha);

// Verifica a conexão
// Atributo do objeto $conexao
if( $conexao-&gt;connect_error ) {
   die("A conexão falhou: " . $conexao-&gt;connect_error());
}

echo "Conexão realizada com sucesso!";

$sql = "CREATE DATABASE prova";

// executando um método de $conexao
if ($conexao-&gt;query($sql) === TRUE) {
    echo "Banco de dados criado";
} else {
    // acessando a propriedade error de $conexao
    echo "Erro na criação do banco: " . $conexao-&gt;error; 
}

// método do objeto $conexao
$conexao-&gt;close();
?&gt;
</pre>
</div>
</div>

<div id="outline-container-orgb0062ca" class="outline-3">
<h3 id="orgb0062ca"><span class="section-number-3">2.5</span> Exercício 2</h3>
<div class="outline-text-3" id="text-2-5">
<p>
Escreva uma página em php (cria.php) que cria um banco de dados chamado: prova.
</p>
</div>
</div>

<div id="outline-container-orgaa36d08" class="outline-3">
<h3 id="orgaa36d08"><span class="section-number-3">2.6</span> Criando tabelas</h3>
<div class="outline-text-3" id="text-2-6">
<p>
O método mysqli para executar um comando SQL é:
</p>

<pre class="example">
$conexao-&gt;query($sql)
</pre>

<p>
A página completa orientada a objetos é:
</p>

<pre class="example">
&lt;?php
$servidor = "localhost";
$usuario = "root";
$senha = "toor";
$banco = "bdEscola"; // novo campo

// Cria a conexão:
// Novo objeto!
$conexao = new mysqli($servidor, $usuario, $senha, $banco);

// Verifica a conexão
// Atributo do objeto $conexao
if( $conexao-&gt;connect_error ) {
   die("A conexão falhou: " . $conexao-&gt;connect_error());
}

echo "Conexão realizada com sucesso!";

$sql = "CREATE TABLE alunos (
   id INT(6) UNSIGNED AUTO_INCREMENT PRIMARY KEY,
   nome VARCHAR(40) NOT NULL,
   nota VARCHAR(5)
)";

// executando um método de $conexao
if ($conexao-&gt;query($sql) === TRUE) {
    echo "Tabela criada com sucesso!&lt;br&gt;";
} else {
    // acessando a propriedade error de $conexao
    echo "Erro na criação da tabela: " . $conexao-&gt;error; 
}

// método do objeto $conexao
$conexao-&gt;close();
?&gt;
</pre>
</div>
</div>

<div id="outline-container-org4859951" class="outline-3">
<h3 id="org4859951"><span class="section-number-3">2.7</span> Exercício 3</h3>
<div class="outline-text-3" id="text-2-7">
<p>
Implementar usando mysqli:
</p>

<p>
Site com lista de compras:
</p>

<p>
Criar as Tabelas:
</p>

<ul class="org-ul">
<li>pessoas (nome, email, senha)</li>
<li>itens (lista, nome, estado[1-ativo,0-excluido])</li>
<li>listas (nome, dono, estado[1-ativa,0-excluida])</li>
<li>compartilhar (lista, pessoa)</li>
</ul>
</div>
</div>

<div id="outline-container-org5307ab0" class="outline-3">
<h3 id="org5307ab0"><span class="section-number-3">2.8</span> Inserindo dados</h3>
<div class="outline-text-3" id="text-2-8">
<p>
Depois de criar o banco e a tabela podemos adicionar dados.
</p>

<p>
As regras são:
</p>

<ul class="org-ul">
<li>A consulta SQL deve ser escrita entre aspas.</li>
<li>Os valores que são string dentro da consulta devem aparecer entre apóstrofos</li>
<li>Valores numéricos não devem ser colocados em apóstrofos</li>
<li>A palavra NULL não deve ser colocada entre apóstrofos</li>
</ul>

<p>
O comando abaixo é usado para inserir dados:
</p>

<pre class="example">
INSERT INTO nome_tabela (coluna1, coluna2, coluna3,...)
VALUES (valor1, valor2, valor3,...)
</pre>

<p>
Para inserir dados na tabela <b>alunos</b> temos o comando:
</p>

<pre class="example">
INSERT INTO alunos (nome, nota) VALUES ('Fulano', '5.5')
</pre>

<p>
Note que a nota aparece entre apóstrofos (') porque é armazenada em um campo com tipo VARCHAR.
</p>

<p>
Novamente a página de inserção de dados é bem parecida com a página de criação de tabela.
</p>

<pre class="example">
&lt;?php
$servidor = "localhost";
$usuario = "root";
$senha = "toor";
$banco = "bdEscola"; // novo campo

// Cria a conexão:
// Novo objeto!
$conexao = new mysqli($servidor, $usuario, $senha, $banco);

// Verifica a conexão
// Atributo do objeto $conexao
if( $conexao-&gt;connect_error ) {
   die("A conexão falhou: " . $conexao-&gt;connect_error());
}

echo "Conexão realizada com sucesso!";

$sql = "INSERT INTO alunos (nome, nota) 
VALUES ('Fulano', '5.5')";

// executando um método de $conexao
if ($conexao-&gt;query($sql) === TRUE) {
    echo "Tabela criada com sucesso!&lt;br&gt;";
} else {
    // acessando a propriedade error de $conexao
    echo "Erro na criação da tabela: " . $conexao-&gt;error; 
}

// método do objeto $conexao
$conexao-&gt;close();
?&gt;
</pre>
</div>
</div>

<div id="outline-container-org1142516" class="outline-3">
<h3 id="org1142516"><span class="section-number-3">2.9</span> Exercício 4</h3>
<div class="outline-text-3" id="text-2-9">
<p>
Crie uma página que cadastre o usuário.
</p>
</div>
</div>

<div id="outline-container-org4e3fc75" class="outline-3">
<h3 id="org4e3fc75"><span class="section-number-3">2.10</span> Exercício 5</h3>
<div class="outline-text-3" id="text-2-10">
<p>
Crie uma página de login para o usuário. Quando o usuário acerta o E-mail e senha você deve salvar o nome e o id dele na sessão.
</p>
</div>
</div>

<div id="outline-container-orgf6985a5" class="outline-3">
<h3 id="orgf6985a5"><span class="section-number-3">2.11</span> Exercício 6</h3>
<div class="outline-text-3" id="text-2-11">
<p>
Crie uma página que cria uma lista de compras. O dono é o usuário logado (id na sessão).
</p>
</div>
</div>

<div id="outline-container-org58cb6b3" class="outline-3">
<h3 id="org58cb6b3"><span class="section-number-3">2.12</span> Exercício 7</h3>
<div class="outline-text-3" id="text-2-12">
<p>
Crie uma página que insere itens em uma lista do usuário. Mostre as listas do usuário em um campo.
</p>
</div>
</div>

<div id="outline-container-orgcb95734" class="outline-3">
<h3 id="orgcb95734"><span class="section-number-3">2.13</span> Exercício 8</h3>
<div class="outline-text-3" id="text-2-13">
<p>
Crie uma página que mostra a lista do usuário.
</p>
</div>
</div>

<div id="outline-container-org4b3e119" class="outline-3">
<h3 id="org4b3e119"><span class="section-number-3">2.14</span> Exercício 9</h3>
<div class="outline-text-3" id="text-2-14">
<p>
Crie uma página que permite o compartilhamento da lista.
</p>
</div>
</div>
</div>
</div>
<div id="postamble" class="status">
<p class="date">Created: 2019-09-30 seg 19:32</p>
<p class="validation"><a href="http://validator.w3.org/check?uri=referer">Validate</a></p>
</div>
</body>
</html>
