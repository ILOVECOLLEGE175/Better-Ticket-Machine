Project: better-ticket-machine
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling
   Pearson Education

It is discussed in chapter 2.

Purpose of project: To illustrate conditional statements.
How to start this project: Create one or more TicketMachine objects.

#47. I'm predicting that it will request for a higher number to put in the machine. I was right the number needs to be greater then 0
#48. If you do >= 0 then if u insert 0 it will accept the amount since it's between the accepted range. And it accepts 0 as an insertMoney.
#49. Once you add 0 as a value it works. Weird...
#52. A ticket doesn't get printed nor is there a error message.
#53. No since once I ticket is printed and if there is a sufficient amount in the balance it will set the balance back to 0 after the ticket is printed such as said on the printTicket method.
#55. saving = price * discount
#56. mean = total / count
#59. Since the new method won't refund the balance that you have, and later it will make ur balance go back to 0 while returning the amountToRefund.
#60. Since you cannot return balance, before doing anything. returning something should as well be at the end.
