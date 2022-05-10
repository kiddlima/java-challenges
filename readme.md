**Java challenges**

Challenge 1 - Caixa de supermercado:

Criar um programa que permita ao usuário operar um caixa de um supermercado:

**O usuário poderá:**

  - Registrar o código de um produto previamente cadastrado.
      Nesse operação, o usuário informa o nome, o valor, e a quantidade do produto que está sendo comprando.
  - Concluir venda
      Nessa operação, o usuário finaliza a compra de acordo com os produtos cadastrados e informa o subtotal da compra.
  - Emitir nota fiscal
      Nesse operação, o usuário informa se deseja emitir nota fiscal da última venda realizada.
  - Abonar estacionamento
      Nesse operação, o usuário abona ou não o estacionamento do cliente de acordo com o tempo de permanência, para isso, o usuário deverá informar a hora de entrada no supermercado.
      
**Regras de negócio:**

- Caso não seja informada qualquer informação do produto, o programa deverá apontar, através de uma mensagem de erro, o que o usuário não informou.
- Ao concluir a venda, o subtotal deve levar em consideração a quantidade informada de cada produto.
- Ao emitir a nota fiscal, o sistema deverá imprimir na tela o detalhe dos produtos conforme o exemplo abaixo:;
      2 - Cerveja Heineken - R$15,00
      1 - Alface - R$10,00
    
      
      
- Ao abonar o estacionamento, o sistema deverá informar até que horas o usuário tem para sair a partir da hora atual, conforme as informações abaixo:
      Mais que 15 reais -> 15 minutos para sair
      Mais que 50 reais -> 1 horas para sair
      Mais que 100 reais -> 3 horas para sair
