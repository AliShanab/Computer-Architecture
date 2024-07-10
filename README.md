CPU Visual Simulator

URL: https://cpuvisualsimulator.github.io/

Summary of Content: 

If then else example, Imagine the instruction is: IF A > B THEN C = D ELSE C = E:

Step-by-Step Observation

Step 1: PC on Address Bus

What happens: The Program Counter (PC) sends the address of the next instruction to the memory.

Example: The address where IF A > B THEN C = D ELSE C = E is stored.
![Screenshot 2024-07-10 143242](https://github.com/AliShanab/Learning-Documentation/assets/169182461/8eff24b4-4afd-4d77-8cba-171c7a9fd1c2)

Step 2: Fetch Signal

What happens: The control unit signals to fetch the instruction from memory.

Example: Memory gets the IF A > B THEN C = D ELSE C = E instruction.
![Screenshot 2024-07-10 143330](https://github.com/AliShanab/Learning-Documentation/assets/169182461/e6af2737-1b38-474e-b1f8-b8a9d3c06efb)

Step 3: Load Instruction

What happens: The fetched instruction is placed into the Instruction Register (IR).

Example: The IR now holds IF A > B THEN C = D ELSE C = E.
![Screenshot 2024-07-10 143448](https://github.com/AliShanab/Learning-Documentation/assets/169182461/55e0b82a-fe53-42cc-aff4-9ae2cace4678)

Step 4: Decode Instruction

What happens: The control unit decodes the instruction to understand what needs to be done.

Example: The control unit identifies the comparison (A > B) and the actions (C = D and C = E).
![Screenshot 2024-07-10 143552](https://github.com/AliShanab/Learning-Documentation/assets/169182461/b3714b10-fec6-4b6d-8619-fce475f93465)

Step 5: Set Multiplexer

What happens: The control unit sets the multiplexer to choose the correct operand mode (direct or immediate).

Example: It decides how to access A, B, D, and E.
![Screenshot 2024-07-10 143613](https://github.com/AliShanab/Learning-Documentation/assets/169182461/19240ba9-b703-4838-9d3e-d1c5924d4d65)

Step 6: Set ALU Operation

What happens: The control unit tells the ALU what operation to perform (like compare or assign).

Example: It sets up the ALU to compare A and B.
![Screenshot 2024-07-10 143632](https://github.com/AliShanab/Learning-Documentation/assets/169182461/bc4c42a7-e5cd-4ca9-9f5a-36bb7e490441)

Step 7: Operand Address on Address Bus

What happens: The address of the operand (like A or B) is placed on the address bus.

Example: The address for A is put on the address bus.
![Screenshot 2024-07-10 143720](https://github.com/AliShanab/Learning-Documentation/assets/169182461/cafa94d8-2bd6-4c64-ad01-ec813ae2078d)

Step 8: Memory Read Signal

What happens: The control unit signals to read the operand from memory.

Example: It reads the value of A from memory.
![Screenshot 2024-07-10 143744](https://github.com/AliShanab/Learning-Documentation/assets/169182461/a57b438e-d870-4864-b470-645c95e567bc)

Step 9: Load Operand

What happens: The operand is loaded from RAM into the CPU.

Example: A is loaded into the CPU.
![Screenshot 2024-07-10 143807](https://github.com/AliShanab/Learning-Documentation/assets/169182461/5beceb82-fbf9-4618-9b59-4185b868ee61)

Step 10: Execute Operation

What happens: The ALU performs the operation (like comparing A to B).

Example: The ALU checks if A > B.
![Screenshot 2024-07-10 143917](https://github.com/AliShanab/Learning-Documentation/assets/169182461/9c03a59c-7402-4ff3-b8c3-1538c7d2186a)

Step 11: Increment PC

What happens: The Program Counter (PC) is incremented to point to the next instruction.

Example: The PC moves to the address of the next instruction after the IF statement.
![Screenshot 2024-07-10 143833](https://github.com/AliShanab/Learning-Documentation/assets/169182461/8a4443c4-10a5-4789-8e08-fc8604ebbf0a)
