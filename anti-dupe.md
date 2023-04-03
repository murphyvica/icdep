# Anti-Dupe
### How can we ensure that each card is received once and only once?

To make sure that each card is only recieved once, we could create a unique identifier for each card. We can create a non-repeatable ID for each card upon it's creation, and make sure that no 2 identifiers can match. To do so, we would need a method to always assign unique ID's to a new card when it is created, and a log of previously recieved identifiers for each node. We then need a rule that checks if the ID of a card that is attempting to be delivered has already been logged for each specific node so that we know when to prevent delivery that would be redundant.

For creating a method of assigning unique ID's, we could use the method of hashing, as it would create a unique code each time that a card is created based on an algorithm.
