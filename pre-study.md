## The state machine model of computer system.
ISA(X86 Arm or RISC-V) describes program's abilities of an **abstract** computer by defining state transition rules.  
We use state machine model to help us better understand the complex computer system. It's effective.  
The design of a CPU Chip can be accounted as a precess of unifying program, abstract computer and physics CPU's state machine behaviour.  
|                 | Program                  | Abstract Machine         | CPU                          |
|-----------------|--------------------------|--------------------------|------------------------------|
| **State**       | `{<V, PC>}`             | `{<R, M>}`              | `{Timing Logic Circuit}`    |
| **State Transition Rule** | Semantics of C statements | Semantics of instructions | Microprogrammed logic circuit |
| **FM**          | C Standard Manual       | Instruction Manual       | Architecture Design Document |
