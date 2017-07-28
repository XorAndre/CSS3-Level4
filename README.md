# CSS4<br>
#### NOVIDADES QUE O CSS4 TROUXE PARA O MARAVILHOSO MUNDO DA WEB<br>
![CSS 4 LOGO](https://www.script-tutorials.com/wp-content/uploads/2013/12/fimg.png)

#### SELETOR DE NEGAÇÃO :not()
  Essa pseudo-classe apareceu pela primeira vez no CSS3, quando só permitia o uso máximo de um seletor simples como argumento. Nos seletores de nível 4, pode levar uma lista de seletores como argumento. Os estilos são aplicados aos elementos que não são representados pelos argumentos passados veja nos exemplos abixo.<br>
  E:not(s1, s2, ...){código...}<br>
Exemplo de uso junto com outro pseudos <br>

p:not(:first-child, .special){color: red;}<br>

 Atualmente o suporte 100% para esse tipo de pseudo em Browsers é somente para Safari<br>
<hr>
#### MATCHES
  Está pseudo-classe leva uma lista de seletores como um argumento. Os estilos são aplicados ao elemento que é representado pelo argumento passado. Sua função é a inversa do seletor :not,seu suporte atualmente encontra-se 100% para o browser Safari. Mas pode em casos de alguns browsers como Chrome, Mozilla e Opera usar algumas soluções de compatibilidade para sua leitura, veja os exemplos de uso de matches abaixo.<br>
  E:matches(s1, s2, ...) {..}//Este código executa perfeitamente no Safari<br>
  E:-webkit-any(s1, s2, ...) {..} //Solução para rodar no Chrome e Opera<br> 
  E:-moz-any(s1, s2, ...) {..}//Solução pararodar no Firefox<br><hr>

#### Seletor relacional :has
Esta pseudo classe até está data (27/julho/2017) ainda não possui nenhum suporte aos navegadores mais usados atualmente, mas não fique triste ainda irei descrever sua função. Como o própio nome diz essa pseudo classe relaciona os elementos ficando algo como o exemplo abaixo.<br>
.main:has(h1, h2, h3) {
  color: green;
  font-family: arial;
}<br>
Claro você pode usar o uso relacional em outros elementos fora elementos de texto tais como imagens ficando algo do tipo:<br>  
section:has(.imagem1, .imagem2, .imagem3){height:20vh; width: 30vw;}
<br><hr>
  
