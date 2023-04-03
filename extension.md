# Extension
### How can we add additional features to the protocol without breaking previous functionality?
### Keep a record of what nodes the card has passed through.

To keep a record of which nodes the card has been through, we could create a list for each card with unique identifiers of each node that the card has been through. To do so, we would need to create an empty list of strings or integers, and assign unique ID's to each of the nodes. As a card travels, the list on each card would append the ID of the node it has passed through. This should not break previous functionality, as a list is being used as an additional attribute to each one of the card objects. This list would act as a log for each card. 

If we would like to keep track of the path of travel for the card, we could have a list of repeatable node indentifiers (could be done through a Queue), so that we could see how the card traveled from node to node. On the other hand, if we would just like to know which nodes were passed through, we could have the list contain only 1 instance of each node identifier because the path does not matter nor does the order (could be done through ArrayList). 
