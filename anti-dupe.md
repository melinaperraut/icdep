<h1> Anti-Duplication: How can we ensure that each card is received once and only once? </h1>

<p>
  For the purpose of this assignment, I will assume that duplication refers to any node receiving an index card more than once.   
</p>

<p>
  To prevent duplication, I would add a new metadata field to each index card in the form of a list of values representing the identity of each node the card has visited. Once    the card has been received by a node, the node's ID (such as a unique identifying number) will be added to this list. 
</p>

<p>
  Before a node can receive an index card, the node must check whether its ID is contained within the card's list of visited nodes. If the answer is no, the node will accept the card, and its ID will be added to the card's list. If the answer is yes,  the node will refuse to receive the card, and the card will be forced to travel to the next available node, where the process will repeat. This process will end if the card has made it to its final recipient or if the card ends up getting stuck and has already visited all the nodes it can visit.
</p>
