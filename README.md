# framework_multi_case
The framework is used to parser multiple case functions according to user input. It divides the case function and framework into two parts, and enble them to evolve respectively. Any one of them is modified in future, the other one works well without modification.

There are three parts with the framework, FSM for user input, case function and framework parser.

1. FSM for user input:
   Used to process the input of user, and switch FSM state according to input from user. It produces the case index according to user input, and provide it
   to framework parser.

2. Framework parser:
   Used to parse case function according to case index from user, and call entrance of case function saved in case list array. Entrance of all the case
   functions are saved in case list array. It divides the framework parser and case functions, and enables them evolve respectively. In another words, one of
   them is modified, the other one works well without any modification. Even if new cases needed to add according to customer, current exisiting cases and 
   framework works without modification. Besides, case functions and framework parser can be implemented parallelly with different engineer.

3. Case functions:
   Used to implement the detail operation and drive destination module to work. it also give indication (LED Blink) to indicate the status of operation.
