# Extension
### How can we add additional features to the protocol without breaking previous functionality?

### Send to any individual on the whole UW campus

To send to any individual on campus outside of our class room, we would need another way of addressing to specify the location more efficiently. Instead of using names for nodes, we should have a way of specifying their loction such as the building and room number in addition to the name. This is because we would need to know where to direct the card, and going by names may not mean much to us especially if we do not know where that node is located. Similar to subnet masking, we should have an address that points us to where the card should head to next for further redirecting.

### Specify whether contents are ASCII text, Unicode text, or binary values

To specify the content type, we can add another attribute to the cards that tells us this information. The type of contents can be specified somewhere on the card where the recipient knows where to look if they would like to know how the contents should be read. This can be specified as simply writing the type as a string such as "UTF-8", or could be encoded as an integer if preferred. This maybe done if it is more efficient to read integer rather than string. This extension should not interfere with other processes because it is simply the addition of an attribute to a card. 

### Keep a record of what nodes the card has passed through.

To keep a record of which nodes the card has been through, we could create a list for each card with unique identifiers of each node that the card has been through. To do so, we would need to create an empty list of strings or integers, and assign unique ID's to each of the nodes. As a card travels, the list on each card would append the ID of the node it has passed through. This should not break previous functionality, as a list is being used as an additional attribute to each one of the card objects. This list would act as a log for each card. 

If we would like to keep track of the path of travel for the card, we could have a list of repeatable node indentifiers (could be done through a Queue), so that we could see how the card traveled from node to node. On the other hand, if we would just like to know which nodes were passed through, we could have the list contain only 1 instance of each node identifier because the path does not matter nor does the order (could be done through ArrayList). 
