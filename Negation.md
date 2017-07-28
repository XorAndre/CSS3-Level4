#### SELETOR DE NEGAÇÃO :not()
 Essa pseudo-classe apareceu pela primeira vez no CSS3, quando só permitia o uso máximo de um seletor simples como argumento. Nos seletores de nível 4, pode levar uma lista de seletores como argumento. Os estilos são aplicados aos elementos que não são representados pelos argumentos passados veja nos exemplos abixo.<br>
  <pre>E:not(s1, s2, ...){código...}</pre><br>
Exemplo de uso junto com outro pseudos <br>
<pre>
p:not(:first-child, .special){color: red;}
</pre>
<br>
 Atualmente o suporte 100% para esse tipo de pseudo em Browsers é somente para Safari<br>
