# Lottery
This project allows people to enter a lottery system. Multiple people can enter and eventually a winner is chosen amongst them using pseudo randomness. 

Variables<br />
manager- The person who creates the lottery. <br />
players- array people who have entered into the lottery.<br />

Functions<br />
Lottery() - Constructor function which automically assigns manager to the person creating the lottery.<br />
enter() - allows people to enter into the lottery with a minimum contribution of .01 ether.<br />
random() - generates a random number with help of psuedorandom generator to get a random number.<br />
pickWinner() - uses the random number generated to pick the winner as the number generated is the index of the address that won the lottery.<br />

Certain function like pickWinner() can be only be called by the manager with the help of modifiers.<br />
