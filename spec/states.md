# States

## INIT
Initial state when node is created, not yet part of network.

## WAITING_FOR_CONNECTION
Waiting for `SuccessorID` after issuing `Join()` request to known node in network, but not yet part of network.

## PROSPECTIVE_MEMBER
After calling `NotifySuccessor()`, waiting for this node's `Successor` and `Predecessor` to acknowledge.

## MEMBER

TODO: We need to insert states for all the API calls, for the data migration based on policy

STABILIZING
NETWORK_UPDATE
DATA_MIGRATION
DISCONNECTED
ERROR
