Quantum teleportation doesn’t move a particle from one place to another it transfers a qubit’s state, not the qubit itself. The main principles are in entanglement, superposition, and measurement, working together in just the right sequence.

You start with a message qubit (this is the state we want to teleport), and an entangled pair shared between the sender and the receiver. The sender holds one half of the entangled pair, the receiver holds the other. This entangled pair is like the bridge that allows teleportation to happen.

Once entanglement is set up, the sender interacts the message qubit with their half of the entangled pair applying specific gates that mix the information of the message into the entangled system. Then, they measure their two qubits, and the original message state collapses. But the info isn’t lost, it's now encoded in the entanglement and those two classical bits from the measurement.

At this point, the sender sends those two classical bits to the receiver. The receiver can then use them to reconstruct the original message qubit by applying the correct X and/or Z gates depending on what the sender measured. After the corrections, the receiver’s qubit becomes an exact replica of what the message qubit was before measurement.

What’s wild is that the actual quantum state was never copied or directly sent rather it was recreated purely through entanglement + measurement + communication.

To me, this feels less like teleportation and more like state transfer by quantum mov't, where every move has to land precisely or the message disappears.
