Download Link: https://assignmentchef.com/product/solved-c-programming-language-project-8
<br>
<strong><u>The Monopoly Game with Linked List</u> </strong>

In this project, you are going to enhance the Monopoly game that you implemented in the previous      project. The following features will be added:

<ul>

 <li>Playing Against Computer</li>

 <li>Board Implementation</li>

 <li>Fortune Cards</li>

</ul>




<strong>Gameplay Rules for Computer:</strong> <strong> </strong>

(Unless it is told, actions are the same as user actions defined in the previous project      .)

<ul>

 <li>When played  against  the  computer,  it  rolls  a  dice  just  like  a  Dice rolling result for the computer must be printed as “Computer rolled the dice: N”.</li>

</ul>




<ul>

 <li>If computer arrives at an unowned property, it decides what to do          based on the followings:

  <ul>

   <li>If the price of the property is below the average cost of all</li>

  </ul></li>

</ul>

properties, then computer must buy the property.

<ul>

 <li>Otherwise, the computer rolls the dice again. If the outcome is between 1 and 3, then the computer must buy the property. If the</li>

</ul>

roll is between 4 and 6, the computer skips its turn.

<ul>

 <li>If the computer lands on a property it owns, it may construct up to 3 houses on that property. The number of houses it can built depends on</li>

</ul>

the number of properties it owns:

<ul>

 <li>If the computer owns 1/3 of all the properties, it rolls a dice.</li>

</ul>

If the result is between 1 and 3, then the computer constructs a

house. Otherwise, it skips the current turn. o If computer does not have 1/3 of all his properties, it skips its          turn.

<ul>

 <li>When computer does not have enough money to pay its rent/tax, then the bank asks it to sell some of its properties. The computer must sell</li>

</ul>

starting with the highest priced property till it pays off its dept.

<ul>

 <li>Player_type for computer is “cap”. Update your implementation accordingly.</li>

</ul>




<strong>Board Implementation:</strong> <strong> </strong>

<ul>

 <li>You must convert your array-based board implementation to a linked</li>

 <li>There are 4 more blocks added to the board. The total number of blocks on the board now is 24.</li>

</ul>













Page <strong>1</strong> of <strong>2 </strong>




<strong>Fortune Cards: </strong>




<ul>

 <li>Whenever a player lands on a fortune card block, player draws a card from fortune card deck (you randomly pick a fortune card). It carries</li>

</ul>

out the action the card says.

<ul>

 <li>Location of fortune card blocks on board are defined in the     xlsx file.</li>

 <li>Block type is “fortune”. You must update your block_type enumeration    implementation accordingly.</li>

 <li>Define a struct with name “fortune_card”. Rest of the implementation          is up to you.</li>

 <li>Fortune cards are defined below.</li>

</ul>




<table width="636">

 <tbody>

  <tr>

   <td width="75"><strong>Card No </strong> </td>

   <td width="163"><strong>Fortune Card Name </strong> </td>

   <td width="399"><strong>Explanation </strong> </td>

  </tr>

  <tr>

   <td width="75">1  </td>

   <td width="163">Free House </td>

   <td width="399">Build a house on one of your properties for free. </td>

  </tr>

  <tr>

   <td width="75">2  </td>

   <td width="163">Time Travel </td>

   <td width="399">Roll a dice. If result is [1-3], move forward by 2 blocks. Else, move backward by 2 blocks. </td>

  </tr>

  <tr>

   <td width="75">3 </td>

   <td width="163">Garnishment<span style="text-decoration: line-through;"> </span></td>

   <td width="399">Pay 5.000 to the bank.<span style="text-decoration: line-through;">                                                            </span></td>

  </tr>

  <tr>

   <td width="75"> 4</td>

   <td width="163"> Generosity</td>

   <td width="399"> Give 10.000 <sub> </sub>to the opponent.</td>

  </tr>

  <tr>

   <td width="75">5 </td>

   <td width="163">Treasure Hunter </td>

   <td width="399">Take 20.000 from the bank. </td>

  </tr>

 </tbody>

</table>










Page <strong>2</strong> of <strong>2 </strong>