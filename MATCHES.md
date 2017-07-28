#### MATCHES
  Está pseudo-classe leva uma lista de seletores como um argumento. Os estilos são aplicados ao elemento que é representado pelo argumento passado. Sua função é a inversa do seletor :not,seu suporte atualmente encontra-se 100% para o browser Safari. Mas pode em casos de alguns browsers como Chrome, Mozilla e Opera usar algumas soluções de compatibilidade para sua leitura, veja os exemplos de uso de matches abaixo.<br>
  E:matches(s1, s2, ...) {..}//Este código executa perfeitamente no Safari<br>
  E:-webkit-any(s1, s2, ...) {..} //Solução para rodar no Chrome e Opera<br> 
  E:-moz-any(s1, s2, ...) {..}//Solução pararodar no Firefox
