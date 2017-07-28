#### Seletor relacional :has
Esta pseudo classe até está data (27/julho/2017) ainda não possui nenhum suporte aos navegadores mais usados atualmente, mas não fique triste ainda irei descrever sua função. Como o própio nome diz essa pseudo classe relaciona os elementos ficando algo como o exemplo abaixo.<br>
<pre>
.main:has(h1, h2, h3) {
  color: green;
  font-family: arial;
}
</pre>
<br>
Claro você pode usar o relacional em outros elementos fora elementos de texto tais como imagens ficando algo do tipo:<br>  
<pre>
section:has(.imagem1, .imagem2, .imagem3){height:20vh; width: 30vw;}
</pre>
<br><hr>
