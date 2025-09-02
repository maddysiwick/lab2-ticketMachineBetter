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

part3:

48. It would now accept 0
50. isVisible and yes because there was two possible states
51. the better ticket machine desnt assume that the balance entered by the user is equal to the price of the ticket and so allows for chance, 
not resetting the balance to zero or adding the entire balance to the total
52. it works but if the user didn't insert enough money they are not given an indication of what went wrong
53. no, because it already checked that there was at least enough money in the balance for the ticket
55. int saving = price * discount;
56. int mean = total / count;
57. if(price<=budget){
    System.out.println("Just right!");
}
else {
    System.out.println("Too expensive :(");
}
if(price<=budget){
    System.out.println("Just right!");
}
else {
    System.out.println("Too expensive :(, must be at most " + budget + " cents.");
}
second message is more clear
59. it resets balance to zero before returning it. you can demonstrate this by running it with different initial values of balance
60. the return statement ends the block, code after it will not run
61. because price is being declared in the body of the constructor, it is not considered the same price variable as the field and so the
field does not get updated (i think)
62.