---
layout: blankdemo
title: Agate
permalink: /hljs/agate/
---

<style>
@font-face {
  font-family: 'Roboto';
  font-style: normal;
  font-weight: 700;
  font-display: swap;
  src: url(https://fonts.gstatic.com/s/roboto/v27/KFOlCnqEu92Fr1MmWUlfBBc4.woff2) format('woff2');
  unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}
body {font-family:Roboto, sans-serif}
pre {user-select:all}

.hljs{display:block;overflow-x:auto;padding:0.5em;background:#333;color:white}
.hljs-name,.hljs-strong{font-weight:bold}
.hljs-code,.hljs-emphasis{font-style:italic}
.hljs-tag{color:#62c8f3}.hljs-variable,.hljs-template-variable,.hljs-selector-id,.hljs-selector-class{color:#ade5fc}
.hljs-string,.hljs-bullet{color:#a2fca2}
.hljs-type,.hljs-title,.hljs-section,.hljs-attribute,.hljs-quote,.hljs-built_in,.hljs-builtin-name{color:#ffa}
.hljs-number,.hljs-symbol,.hljs-bullet{color:#d36363}
.hljs-keyword,.hljs-selector-tag,.hljs-literal{color:#fcc28c}
.hljs-comment,.hljs-deletion,.hljs-code{color:#888}
.hljs-regexp,.hljs-link{color:#c6b4f0}
.hljs-meta{color:#fc9b9b}
.hljs-deletion{background-color:#fc9b9b;color:#333}
.hljs-addition{background-color:#a2fca2;color:#333}
.hljs a{color:inherit}.hljs a:focus,.hljs a:hover{color:inherit;text-decoration:underline}
</style>

<h2>Sample dan CSS yang digunakan</h2>

<h3>CSS (Copy CSS ini ke Template)</h3>

<pre><code class="hljs"><span class="hljs-selector-class">.hljs</span>{<span class="hljs-attribute">display</span>:block;<span class="hljs-attribute">overflow-x</span>:auto;<span class="hljs-attribute">padding</span>:<span class="hljs-number">0.5em</span>;<span class="hljs-attribute">background</span>:<span class="hljs-number">#333</span>;<span class="hljs-attribute">color</span>:white}
<span class="hljs-selector-class">.hljs-name</span>,<span class="hljs-selector-class">.hljs-strong</span>{<span class="hljs-attribute">font-weight</span>:bold}
<span class="hljs-selector-class">.hljs-code</span>,<span class="hljs-selector-class">.hljs-emphasis</span>{<span class="hljs-attribute">font-style</span>:italic}
<span class="hljs-selector-class">.hljs-tag</span>{<span class="hljs-attribute">color</span>:<span class="hljs-number">#62c8f3</span>}<span class="hljs-selector-class">.hljs-variable</span>,<span class="hljs-selector-class">.hljs-template-variable</span>,<span class="hljs-selector-class">.hljs-selector-id</span>,<span class="hljs-selector-class">.hljs-selector-class</span>{<span class="hljs-attribute">color</span>:<span class="hljs-number">#ade5fc</span>}
<span class="hljs-selector-class">.hljs-string</span>,<span class="hljs-selector-class">.hljs-bullet</span>{<span class="hljs-attribute">color</span>:<span class="hljs-number">#a2fca2</span>}
<span class="hljs-selector-class">.hljs-type</span>,<span class="hljs-selector-class">.hljs-title</span>,<span class="hljs-selector-class">.hljs-section</span>,<span class="hljs-selector-class">.hljs-attribute</span>,<span class="hljs-selector-class">.hljs-quote</span>,<span class="hljs-selector-class">.hljs-built_in</span>,<span class="hljs-selector-class">.hljs-builtin-name</span>{<span class="hljs-attribute">color</span>:<span class="hljs-number">#ffa</span>}
<span class="hljs-selector-class">.hljs-number</span>,<span class="hljs-selector-class">.hljs-symbol</span>,<span class="hljs-selector-class">.hljs-bullet</span>{<span class="hljs-attribute">color</span>:<span class="hljs-number">#d36363</span>}
<span class="hljs-selector-class">.hljs-keyword</span>,<span class="hljs-selector-class">.hljs-selector-tag</span>,<span class="hljs-selector-class">.hljs-literal</span>{<span class="hljs-attribute">color</span>:<span class="hljs-number">#fcc28c</span>}
<span class="hljs-selector-class">.hljs-comment</span>,<span class="hljs-selector-class">.hljs-deletion</span>,<span class="hljs-selector-class">.hljs-code</span>{<span class="hljs-attribute">color</span>:<span class="hljs-number">#888</span>}
<span class="hljs-selector-class">.hljs-regexp</span>,<span class="hljs-selector-class">.hljs-link</span>{<span class="hljs-attribute">color</span>:<span class="hljs-number">#c6b4f0</span>}
<span class="hljs-selector-class">.hljs-meta</span>{<span class="hljs-attribute">color</span>:<span class="hljs-number">#fc9b9b</span>}
<span class="hljs-selector-class">.hljs-deletion</span>{<span class="hljs-attribute">background-color</span>:<span class="hljs-number">#fc9b9b</span>;<span class="hljs-attribute">color</span>:<span class="hljs-number">#333</span>}
<span class="hljs-selector-class">.hljs-addition</span>{<span class="hljs-attribute">background-color</span>:<span class="hljs-number">#a2fca2</span>;<span class="hljs-attribute">color</span>:<span class="hljs-number">#333</span>}
<span class="hljs-selector-class">.hljs</span> <span class="hljs-selector-tag">a</span>{<span class="hljs-attribute">color</span>:inherit}<span class="hljs-selector-class">.hljs</span> <span class="hljs-selector-tag">a</span><span class="hljs-selector-pseudo">:focus</span>,<span class="hljs-selector-class">.hljs</span> <span class="hljs-selector-tag">a</span><span class="hljs-selector-pseudo">:hover</span>{<span class="hljs-attribute">color</span>:inherit;<span class="hljs-attribute">text-decoration</span>:underline}</code></pre>

<h3>Contoh HTML, XML</h3>

<pre><code class="hljs"><span class="hljs-meta">&lt;!DOCTYPE html&gt;</span>
<span class="hljs-tag">&lt;<span class="hljs-name">title</span>&gt;</span>Title<span class="hljs-tag">&lt;/<span class="hljs-name">title</span>&gt;</span>

<span class="hljs-tag">&lt;<span class="hljs-name">style</span>&gt;</span><span class="css"><span class="hljs-selector-tag">body</span> {<span class="hljs-attribute">width</span>: <span class="hljs-number">500px</span>;}</span><span class="hljs-tag">&lt;/<span class="hljs-name">style</span>&gt;</span>

<span class="hljs-tag">&lt;<span class="hljs-name">script</span> <span class="hljs-attr">type</span>=<span class="hljs-string">"application/javascript"</span>&gt;</span><span class="javascript">
  <span class="hljs-function"><span class="hljs-keyword">function</span> <span class="hljs-title">$init</span>(<span class="hljs-params"></span>) </span>{<span class="hljs-keyword">return</span> <span class="hljs-literal">true</span>;}
</span><span class="hljs-tag">&lt;/<span class="hljs-name">script</span>&gt;</span>

<span class="hljs-tag">&lt;<span class="hljs-name">body</span>&gt;</span>
  <span class="hljs-tag">&lt;<span class="hljs-name">p</span> <span class="hljs-attr">checked</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"title"</span> <span class="hljs-attr">id</span>=<span class="hljs-string">'title'</span>&gt;</span>Title<span class="hljs-tag">&lt;/<span class="hljs-name">p</span>&gt;</span>
  <span class="hljs-comment">&lt;!-- here goes the rest of the page --&gt;</span>
<span class="hljs-tag">&lt;/<span class="hljs-name">body</span>&gt;</span></code></pre>

<h3>Contoh JavaScript</h3>

<pre><code class="hljs"><span class="hljs-function"><span class="hljs-keyword">function</span> <span class="hljs-title">$initHighlight</span>(<span class="hljs-params">block, cls</span>) </span>{
  <span class="hljs-keyword">try</span> {
    <span class="hljs-keyword">if</span> (cls.search(<span class="hljs-regexp">/\bno\-highlight\b/</span>) != <span class="hljs-number">-1</span>)
      <span class="hljs-keyword">return</span> process(block, <span class="hljs-literal">true</span>, <span class="hljs-number">0x0F</span>) +
             <span class="hljs-string">` class="<span class="hljs-subst">${cls}</span>"`</span>;
  } <span class="hljs-keyword">catch</span> (e) {
    <span class="hljs-comment">/* handle exception */</span>
  }
  <span class="hljs-keyword">for</span> (<span class="hljs-keyword">var</span> i = <span class="hljs-number">0</span> / <span class="hljs-number">2</span>; i &lt; classes.length; i++) {
    <span class="hljs-keyword">if</span> (checkCondition(classes[i]) === <span class="hljs-literal">undefined</span>)
      <span class="hljs-built_in">console</span>.log(<span class="hljs-string">'undefined'</span>);
  }

  <span class="hljs-keyword">return</span> (
    <span class="xml"><span class="hljs-tag">&lt;<span class="hljs-name">div</span>&gt;</span>
      <span class="hljs-tag">&lt;<span class="hljs-name">web-component</span>&gt;</span>{block}<span class="hljs-tag">&lt;/<span class="hljs-name">web-component</span>&gt;</span>
    <span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span>
  )
}

export  $initHighlight;</span></code></pre>
