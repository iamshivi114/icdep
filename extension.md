# Extension

These are some additional features added to the protocol without breaking previous functionality.

### Sending to Any Individual on UW Campus

In order to allow transfer of index cards to any individual on UW campus, we can allow the individual nodes to move.
By doing so, the nodes can then form a network from the origin of the message to it's intended destination.
This would be a dynamic network whose formation is determined by the source and the destination of the message.
In this network all the nodes stand equidistant to each other, and the message is passed on from one node to another.
This a network that can move the index card either forward or backwards, no node in the chain can be skipped.
The first node takes the index card from the origin and walks to the next node, and the process continues in a similar way until the index card reaches its destination.

### Specifying Whether Contents are ASCII Text, Unicode Text, or Binary Values

In order to specify whether the contents of the index card are ascii, unicode, or binary, I propose we make use of one of the corners of the index card. 
Since the top and the bottom corners on the right are taken by the anti-duplication code and card number respectively, we can use the top left corner of the index card to mention the nature of its contents.
We can use "A" to indicate ascii, "U" to indicate unicode, and "B" to indicate binary.

### Keep a Record of What Nodes the Card has Passed Through

For this we would use the back of the index card.
I propose that every node is given a number which acts as a unique identifier for each one of them. We would begin from the number 1 and go all the way to the number of nodes.
Since the back already has a covered anti-duplication code, we will use the rest of the space to document what all nodes the index card has been to.
At the back, each node would mention their number followed by a comma "," once they receieve the index card. Therefore, as the index card travels from one node to the other, the identities of all the nodes it has travelled to would be mentioned at the back of it in an ordered comma-seperated list.