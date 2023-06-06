## Jogo-javascript !!!

# Jogo Criado em Javascript ...
 
 
 * O jogo das 100 portas é um jogo de lógica e estratégia em que você tem 100 portas numeradas de 1 a 100, todas inicialmente fechadas. O objetivo é percorrer as portas e fazer algumas ações específicas com elas de acordo com certas regras.

Aqui está uma descrição básica de como o jogo funciona:

Todas as portas estão fechadas no início do jogo.
O jogador começa percorrendo todas as portas e abre todas elas.
Em seguida, o jogador faz um segundo percurso pelas portas, fechando todas as portas múltiplas de 2 (portas 2, 4, 6, ...).
Depois disso, o jogador faz um terceiro percurso pelas portas, alterando o estado das portas múltiplas de 3 (portas 3, 6, 9, ...). Se a porta estiver aberta, ela é fechada; se estiver fechada, é aberta.
O jogador continua fazendo percursos pelas portas, alternando o estado das portas múltiplas de 4, 5, 6 e assim por diante, até chegar ao centésimo percurso pelas portas, onde apenas a porta 100 é afetada.
No final do jogo, o jogador deve determinar quantas portas estão abertas. A resposta é o número de portas que permanecem abertas.

A estratégia para resolver o jogo é perceber que as portas serão alteradas em cada percurso apenas quando o número de divisores que elas têm for ímpar. Portas quadradas, como 4, 9, 16, ... terão um número ímpar de divisores, enquanto as portas não quadradas terão um número par de divisores. Isso significa que todas as portas quadradas serão deixadas abertas no final do jogo, enquanto as portas não quadradas serão fechadas.

Portanto, no jogo das 100 portas, as portas quadradas de 1 a 10 (1, 4, 9) permanecerão abertas, enquanto as portas não quadradas (2, 3, 5, 6, 7, 8, 10) serão fechadas.

Essa é a explicação básica de como o jogo funciona e como determinar quais portas ficarão abertas. É um jogo interessante para exercitar a lógica e o raciocínio matemático.
