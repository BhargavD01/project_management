CoreShift — UML & System Design Pack

Slides:
1. Use Case Diagram — actors, core banking and migration/reconciliation use cases.
2. Class Diagram — Customer, Account, Transaction, ProductType, calculators and reconciliation engine.
3. Sequence Diagram — transaction request through modern services, legacy adapter/COBOL and database.
4. Activity Diagram — reverse engineering through parallel run, investigation and controlled cutover.
5. Target Architecture — strangler-fig architecture with modern services, legacy adapter, reconciliation and monitoring.
6. Deployment Diagram — modern and legacy environments operating in parallel.
7. Migration Sequence — staged strangler-fig migration from reverse engineering to full cutover.

Important:
- These are proposed design diagrams for the case study, not a claim that the legacy bank currently has this exact implementation.
- The migration uses a strangler-fig strategy rather than a big-bang replacement.
- Final reconciliation policy is zero unexplained monetary difference.
