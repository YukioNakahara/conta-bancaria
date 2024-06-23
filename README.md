Um projeto simples para gerenciar contas bancárias de maneira eficiente e intuitiva, o código foi feito baseado no desafio da Alura no curso de Java: criando a sua primeira aplicação.

Cabeçalho Inicial:

No início da aplicação, exibimos um cabeçalho com os dados do cliente

Menu de Operações
Um menu interativo que permite ao usuário realizar diversas operações. As opções do menu foram cuidadosamente escolhidas para cobrir as necessidades básicas de qualquer cliente bancário. As operações disponíveis são:

1 - Entrada de Valor (Deposita/Recebe Transferência/Recebe Pix): Esta opção permite ao usuário adicionar fundos à sua conta. O método escolhido para esta operação é deposita, onde o cliente pode inserir o valor desejado para depósito.

2 -Saída de Valor (Saca/Transfere/Envia Pix): Esta operação possibilita a retirada de valores da conta. Utilizo o método saca, garantindo que a operação só seja concluída caso o cliente tenha saldo suficiente para a retirada.

3 - Consulta de Saldo: Com esta opção, o usuário pode verificar o saldo atual da sua conta a qualquer momento, oferecendo transparência e controle sobre suas finanças.

4 - Finalização da Aplicação: Permite ao usuário sair do sistema de forma segura e controlada.

O menu é projetado para aparecer continuamente até que o usuário escolha a opção de finalizar a aplicação. Isto garante que todas as operações necessárias possam ser realizadas sem a necessidade de reiniciar o programa.

