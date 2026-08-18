# legendrian-

In legacy 4IR engines, every time you add an agent or a data point, the computer has to run O(N^2) distance checks (N \times (N-1) operations) to prevent collisions. At 10,000 nodes, that’s 100,000,000 calculations per frame. The thread locks up, thermal throttling kicks in, and performance plummets.
With our 5D Legendrian Contact Engine, agents don't check for collisions against each other. Instead, they are constrained to move along the invariant curves of a continuous vector field:

