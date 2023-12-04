# Calculo-de-Descontos
## Padrão Strategy - Java


Cálculo de Descontos
Considere que temos um sistema de vendas onde diferentes formas de desconto podem ser implementadas de acordo com as promoções vigentes, como em datas comemorativas. O sistema deve permitir o cálculo do desconto sobre a venda das seguintes maneiras:

percentual de desconto definido (que pode vir de um banco de dados);

percentual de desconto progressivo: valor da compra/25, não podendo ultrapassar 20% (este são apenas valores arbitrários de exemplo);

desconto de 15% na data de aniversário do cliente.

O usuário é quem escolhe o tipo de desconto a ser aplicado, não o programa. O programa deve apenas permitir que seja mudado o algoritmo de cálculo do desconto.

------------------------------------------------------------------------------------

# Responda
Qual padrão de projeto pode ser utilizado no desenvolvimento de uma solução?<br>
R: Padrão Strategy

Como poderíamos implementar estes tipos de desconto sem utilizar Padrões de Projetos?<br>
R: a implementação se tornaria confusa e ineficiente. Teríamos várias classes e vários métodos para lidar com cada tipo de desconto. O código se tornaria complexo e difícil de manter.<br>

Quais os problemas que tal implementação traria?<br>
R:A implementação sem Strategy causaria a duplicação de código e o aumento da complexidade do código.<br> 
Isso resultaria em um código difícil de manter e que pode apresentar problemas de bugs. <br>
Além disso, se algum dia precisássemos adicionar um novo tipo de desconto, teríamos que modificar todas as classes e métodos envolvidos.
