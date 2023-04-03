<h1> Administration: How can we send commands to individual nodes in the network, rather than treat them as pass-through intermediaries? </h1>

<p>
  For a sender to send specific commands to individual network nodes (such as "SLEEP", "RESTART", "ARE-YOU-THERE", etc.), we can create a new type of index card that is intended specifically for commands rather than to send messages. These cards would be encased in envelopes of a certain color (such as pink). Furthermore, the envelopes would contain metadata specifying the identity of both the sender and the intended recipient node.
</p>

<p>
  If a node received an index card encased in a pink envelope, rather than just passing the card to the next node, the node would examine the envelope's metadata to discover the intended recipient. If the node is <b>not</b> the intended recipient, the node will pass the card and envelope to the next node in the network.
</p>

<p>
  However, if the node <b>is</b> the intended recipient, the node will open the envelope to read the command. After reading the command, the node will create and send a new index card message addressed to the sender with the appropriate response to the message. This card would be encased in an envelope of a different color (such as purple) so that the sender can identify which message is the node's response upon receiving it.
</p>
