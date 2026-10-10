32bit Pipelined MIPS Processor

Architecture
- 32-bit RISC Load/Store architecture.
- 32 General Purpose Registers (R0 to R31). R0 is hardwired to 0.
- Dedicated 32-bit Program Counter (PC).
- No status flags (zero, carry, sign, etc).

Supported Instructions
- Memory: LW, SW
- Arithmetic/Logic (Register): ADD, SUB, AND, OR, MUL, SLT
- Arithmetic/Logic (Immediate): ADDI, SUBI, SLTI
- Control Flow: BEQZ, BNEQZ, J, HLT

5-Stage Pipeline
1. IF: Instruction Fetch
2. ID: Instruction Decode
3. EX: Execution
4. MEM: Memory Access
5. WB: Register Write-back
