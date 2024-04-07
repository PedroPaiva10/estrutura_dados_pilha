# estruura_dados_pilha
Este é um programa em C que implementa uma pilha utilizando um array estático. Ele permite ao usuário empilhar e desempilhar elementos, além de exibir os elementos da pilha. Aqui estão algumas observações sobre o programa:

- A estrutura de dados da pilha é definida como uma estrutura que contém um array de inteiros (representando os elementos da pilha) e um inteiro para rastrear o topo da pilha.
- Funções são fornecidas para inicializar a pilha, verificar se ela está vazia ou cheia, empilhar e desempilhar elementos, e para imprimir os elementos da pilha.
- O programa principal contém um loop que permite ao usuário empilhar, desempilhar ou sair do programa. Ele usa um switch-case para lidar com as diferentes opções do usuário.
- O usuário pode digitar 'E' para empilhar um elemento, 'D' para desempilhar um elemento, ou 'S' para sair do programa.
- O programa utiliza a função fflush(stdin) para limpar o buffer de entrada do teclado, o que pode não ser portável e não é recomendado. Uma alternativa mais portável seria utilizar uma função como getchar() para limpar o buffer de entrada.
- Comentários claros são fornecidos no código para facilitar a compreensão do seu funcionamento.
