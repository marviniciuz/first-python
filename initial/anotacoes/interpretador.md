# Como funciona o interpretador python?

Antes de tudo temos que entender que o python e uma linguagem interpretada, diferente da linguagem c, ele não gera um arquivo .exe ou .o para isso ele utilizad um interpretador, da mesma forma que o C necessita de um compilador, guardada as devidas proporções, cada um precisa de um mecanismo para que o codigo possa rodar ou ser executado.

De forma geral, computadores só podem executar programas escritos em linguagem de máquina. Portanto, programas escritos em uma linguagem de alto nível (e mesmo aqueles escritos na linguagem assembly) precisam ser processados antes que possam ser executados

Um ```interpretador``` lê um programa de alto nível (chamado de código fonte) e executa ele, ou seja, realiza as ações do programa passo a passo.

![interpretador](../images/interpretador.png)


Na imagem acima vemos um exemplo da interpretação do codigo python,sendo passado de codigo.py para byte code e sendo impresso na tela.

### Byte Code

E um processo semelhante ao da compilação, onde neste caso o codigo python e passado para o byte code para o interpretador interpretar e informar alguma saida de dado, assim como na imagem acima.

Vale ressaltar que o bytecode não e codigo de maquina, depois do codigo python ser passado para bytecode ele ainda sera interpretado e enviado para um maquina virtual python para ser executado.

Ou seja o bytecode e uma representação de baixo nivel do codigo

