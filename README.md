# automato-sandubway
Trabalho Final da Disciplina de Linguagens Formais e Autômatos.
Realizado por Aline Osmar, Lucas de Lima E Pedro Fronchetti

*Ferramentas: Linguagem C.

*Objetivo: Dada uma string de entrada, o programa informa se a string é um sanduíche da lancheria Sandubway. Caso a string seja aceita por um autômato que reconhece a linguagem 
do Sandubway, ela é um sanduíche do Sandubway. Caso contrário, a string é rejeitada.

*Instruções de uso:
- Executar TF.exe
- Para que sua entrada seja aceita, informe uma palavra que tenha como pc prefixo e pag como sufixo. Os outros símbolos (não presentes em sufixo ou prefixo) devem seguir a ordem: g -> (s ou ss ou sss) -> (m ou mm) -> t -> b -> d, podendo qualquer um deles ser substituído por x. Caso a palavra seja aceita, o programa informará a sequência de passos que o autômato fez para reconhecer a palavra.
- Caso contrário, o programa avisará que sua palavra não pertence a linguagem do sandubway.

*Os símbolos codificam operações que um cliente pode executar em um Sandubway:
x: Não escolher ingrediente algum nessa etapa;
p: Escolher um tipo de pão;
c: Escolher um tipo de carne (carne vegana também disponível);
g: Escolher um tipo de queijo;
s: Escolher apenas um tipo de salada;
ss: Escolher apenas dois tipos de salada;
sss: Escolher três tipos de salada;
m: Escolher apenas um tipo de molho;
mm: Escolher dois tipos de molho;
t: Escolher um tipo de tempero;
b: Escolher uma bebida para acompanhar seu sanduíche;
d: Escolher uma sobremesa;
pag: Pagar o pedido.


*Exemplos de palavras aceitas e rejeitadas:
pcxsssmmxxxpag -> aceita
pcgsxtbdpag -> aceita
xxgssxxxxpag -> rejeita
