# Administration
### How can we send commands ("SLEEP", "RESTART", "ARE-YOU-THERE", etc) to individual nodes in the network, rather than treat them as pass-through intermediaries?

To send them to a specific node in a network, we should have the address of the node that is the destination. We need to have this to know where the command is being delivered to, and we should have a confirmation that the command was delivered so that unnecessary repeats are not sent. To do so, we would also need the orgin address since we would like to recieve a response confirming that the command was successful. After the message was successfully delivered, the same card or a new ("confirmation") card can be sent back to the origin to let them know of the status. There should be a way of showing confirmation on the card, such as the card having a signature or check mark.

If we would like to use a new "confirmation" card as a way of letting the origin know of delivery status, we would need to have unique identifiers on each card since a place of origin could have sent out multiple commands. 
