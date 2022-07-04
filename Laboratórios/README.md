# Laboratorio_01
Laboratório 1 para a disciplina de sistemas microcontrolados.

Os comandos MOV são utilizados para guardar valores nos registradores internos do processador. Depois do comando MOV está o registrador de destino seguido do registrador de origem que possui a variável a ser guardada no novo registrador ou uma constante. Números negativos são codificados em complemento de 2 e é possível ver o estado individual das flags no registrador ASPR ao adicionar-se S ao comando MOV. Na janela Dissassembly é possível ver como o PC tem seu endereço alterado conforme cada operação é realizada.

Instruções de 16 bits: MOVS.

Instruções de 32 bits: MOV.W, MVNS.W, MVN.W, MOVS.W. 

Os mnemônicos utilizados no programa não são exatamente iguais ao mnemônicos usados no dissassembly.

Os comandos LSL, LSR, ASR, ROR e RRX realizam deslocamentos e são feitos com o uso do barrel shifter
no caminho dos dados. As funções desses comandos são:

- LSL: desloca todos os bits para a esquerda n vezes, os bits menos significativos são substituídos por 0.
- LSR: desloca todos os bits para a direita n vezes, os bits mais significativos são substituídos por 0.
- ASR: desloca todos os bits para a direita n vezes, os bits mais significativos são substituídos pelo MSB.
- ROR: rotaciona os bits para a direita n vezes, o MSB torna-se o LSB e os demais bits são deslocados para a direita.
- RRX: rotaciona todos os bits para a direita 1 vez.

Os comandos MVN apenas funcionaram com os comandos de deslocamento usando-se constantes para deslocar o conteúdo dos registradores, e não usando-se outros registradores.

