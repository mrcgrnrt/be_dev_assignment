Requirements for the message collector

* REQ-1 - every message must be recorded exactly once
* REQ-2 - received messages must be checked for plausibilty (criteria: temperature measurement must be between -50 and +110 ˚C)
* REQ-3 - the system must react on rising and falling amount of usage
  * add new compute resources when the load rises
  * release resources when to load falls
* REQ-4 - the implementation must follow the 12-factor-app principles
* REQ-5 - all data must be transported and stored in a secure way

