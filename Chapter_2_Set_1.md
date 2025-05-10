---

### **Batch 1: MCQs (1–10)**

---

**1. Which of the following are primary goals of instruction set design according to Burks, Goldstine, and von Neumann?**

I) Simplicity of hardware
II) Clarity of application to important problems
III) Maximizing software complexity
IV) Minimizing energy and cost
V) Supporting multiple programming languages

A. I, II & IV Only
B. I, II & III Only
C. I, IV & V Only
D. II, III & V Only

---

**2. Which of the following statements about MIPS instruction format and design are true?**

I) MIPS instructions always have exactly three operands.
II) The simplicity of hardware favors regularity in instruction formats.
III) MIPS allows variable-length instructions to increase flexibility.
IV) MIPS uses a fixed instruction size of 32 bits.
V) MIPS arithmetic instructions can operate directly on memory operands.

A. I, II & IV Only
B. I, III & V Only
C. II, III & IV Only
D. I, II, IV & V Only

---

**3. Which of the following describe characteristics of MIPS registers?**

I) They are directly built into the hardware.
II) There are typically 32 general-purpose registers in MIPS.
III) \$zero register always holds the value zero.
IV) MIPS registers store both instructions and data simultaneously.
V) MIPS register names always start with an asterisk (\*).

A. I, II & III Only
B. I, II & IV Only
C. II, III & V Only
D. I, III & V Only

---

**4. According to the text, what are advantages of keeping frequently used variables in registers?**

I) Registers have lower latency than memory.
II) Accessing registers requires more energy than accessing memory.
III) Registers have higher throughput than memory.
IV) Data in registers is less useful to instructions than data in memory.
V) Registers use less energy than memory for access.

A. I, III & V Only
B. I, II & IV Only
C. II, III & IV Only
D. I, IV & V Only

---

**5. Which of the following statements are correct about MIPS data transfer instructions?**

I) Load (lw) copies data from memory to register.
II) Store (sw) copies data from register to memory.
III) MIPS uses byte addressing for memory.
IV) MIPS allows unaligned memory access.
V) The sum of the constant and base register forms the memory address.

A. I, II & III Only
B. I, II, III & V Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

**6. Regarding signed and unsigned numbers in MIPS, which of the following statements are true?**

I) Unsigned numbers range from 0 to 4,294,967,295 (32-bit).
II) Signed numbers use two’s complement representation.
III) Sign extension replicates the sign bit to higher order bits.
IV) Two’s complement avoids both positive and negative zero.
V) MIPS supports one’s complement for signed numbers by default.

A. I, II & III Only
B. I, III & IV Only
C. II, III & V Only
D. I, II, III & IV Only

---

**7. In MIPS instruction encoding, which of these statements are accurate?**

I) The opcode field defines the operation.
II) The funct field determines specific operation variants for R-type instructions.
III) MIPS uses different instruction lengths for different instructions.
IV) I-type instructions contain a 16-bit constant field.
V) The shamt field specifies shift amount in all instructions.

A. I, II & IV Only
B. I, II, IV & V Only
C. II, III & IV Only
D. I, III & V Only

---

**8. Which of the following are examples of MIPS conditional branch instructions?**

I) beq (branch on equal)
II) bne (branch on not equal)
III) slt (set on less than)
IV) slti (set on less than immediate)
V) lui (load upper immediate)

A. I, II & IV Only
B. I, II & III Only
C. I, II, III & IV Only
D. II, III, IV & V Only

---

**9. Which of these are design principles highlighted in the MIPS architecture?**

I) Simplicity favors regularity.
II) Smaller is faster.
III) Good design demands good compromises.
IV) Maximize the number of instruction formats.
V) Increase instruction length for flexibility.

A. I, II & III Only
B. I, III & IV Only
C. II, III & V Only
D. I, II, IV & V Only

---

**10. In relation to the stored-program concept, which of the following statements are correct?**

I) Programs and data are both stored in memory.
II) Programs are executed directly from memory.
III) Instructions are represented as binary numbers.
IV) Programs can be loaded and executed without rewiring hardware.
V) Stored-program computers cannot use MIPS architecture.

A. I, II & III Only
B. I, II, III & IV Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

These 10 are ready.

Would you like me to proceed immediately with the **next batch of 10 (11–20)**?

Here’s **Batch 2: MCQs (11–20)** from the PDF content.

---

### **Batch 2: MCQs (11–20)**

---

**11. Which of the following correctly describe memory addressing in MIPS architecture?**

I) MIPS uses byte addressing.
II) Memory addresses for words differ by 4.
III) MIPS allows any byte alignment for words.
IV) The address of A\[8] is base + (8 \* 4).
V) Memory addressing requires combining offset and base register values.

A. I, II & IV Only
B. I, II, IV & V Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

**12. Which statements about MIPS registers and conventions are true?**

I) \$s0–\$s7 are used for saved variables.
II) \$t0–\$t9 are used for temporary values.
III) \$zero is hardwired to the value 0.
IV) \$ra holds the return address for procedures.
V) \$sp points to the stack base.

A. I, II & III Only
B. I, II, III & IV Only
C. I, III, IV & V Only
D. II, III, IV & V Only

---

**13. Regarding the use of immediate operands in MIPS, which are true?**

I) Immediate operands eliminate the need to load constants from memory.
II) Immediate fields in instructions are typically 16 bits.
III) MIPS has an instruction called `subi` for subtract immediate.
IV) The instruction `addi $s3, $s3, 4` adds 4 to \$s3.
V) Using immediate operands helps reduce instruction energy consumption.

A. I, II & IV Only
B. I, III & IV Only
C. I, II, IV & V Only
D. II, III, IV & V Only

---

**14. Which of the following MIPS instructions are considered logical operations?**

I) and
II) or
III) nor
IV) lui
V) xor

A. I, II & III Only
B. I, II, III & IV Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

**15. In MIPS two’s complement number system, which statements are valid?**

I) Negative numbers have 1 in the most significant bit.
II) Two’s complement avoids both positive and negative zero.
III) Negating a number involves bit inversion and adding 1.
IV) The range of 32-bit signed numbers is from −2,147,483,648 to +2,147,483,647.
V) Positive two’s complement numbers have infinite leading ones.

A. I, II & IV Only
B. I, II, III & IV Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

**16. Which of the following are characteristics of I-type instruction format in MIPS?**

I) Contains a 16-bit immediate field.
II) Uses an opcode to define the operation.
III) Uses rs and rt register fields.
IV) Is used for arithmetic instructions requiring a constant.
V) Is used exclusively for conditional branch instructions.

A. I, II & IV Only
B. I, II, III & IV Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

**17. According to the chapter, what advantages are associated with binary compatibility?**

I) Programs can run on multiple computers without modification.
II) Reduces the need for compilers.
III) Promotes software reuse across hardware generations.
IV) Avoids the need for instruction set compatibility.
V) Increases reliability of compiled software.

A. I, III & V Only
B. I, II & III Only
C. II, III & IV Only
D. I, III, IV & V Only

---

**18. Which of the following relate to the concept of sign extension?**

I) Converts smaller signed numbers to larger sizes.
II) Replicates the sign bit in higher order bits.
III) It is applied when loading smaller data types into registers.
IV) MIPS unsigned loads fill upper bits with ones.
V) Sign extension keeps the value unchanged after conversion.

A. I, II & III Only
B. I, II, III & V Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

**19. Which are examples of unconditional jump instructions in MIPS?**

I) j (jump)
II) jr (jump register)
III) jal (jump and link)
IV) beq (branch on equal)
V) slt (set on less than)

A. I, II & III Only
B. I, III & IV Only
C. II, III, IV & V Only
D. I, II, III & V Only

---

**20. Which of the following best describe the concept of the stored-program computer?**

I) Instructions and data coexist in memory.
II) Programs are executed directly from memory.
III) Memory can hold compiled code, source code, and data simultaneously.
IV) MIPS is incompatible with stored-program principles.
V) Stored-program systems simplify memory and software design.

A. I, II & III Only
B. I, II, III & V Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

That’s the second batch of 10.

Would you like me to proceed with the **final batch (21–30)** now?

Here’s **Batch 3: MCQs (21–30)** from the PDF content.

---

### **Batch 3: MCQs (21–30)**

---

**21. Which of the following accurately describe the stored-program concept?**

I) Programs are represented as numbers.
II) Programs can be modified by other programs.
III) Memory treats instructions and data the same.
IV) The MIPS architecture violates this concept.
V) The concept simplifies both hardware and software design.

A. I, II & III Only
B. I, III & V Only
C. II, III & IV Only
D. I, II, III & V Only

---

**22. Which of the following are characteristics of the R-type instruction format in MIPS?**

I) Contains fields: op, rs, rt, rd, shamt, funct.
II) Is used for register-to-register arithmetic.
III) The funct field defines the specific operation.
IV) Always includes a 16-bit constant field.
V) All instructions are 32 bits in size.

A. I, II & III Only
B. I, II, III & V Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

**23. Which of the following instructions are examples of data transfer operations in MIPS?**

I) lw (load word)
II) sw (store word)
III) lb (load byte)
IV) lui (load upper immediate)
V) add (addition)

A. I, II & III Only
B. I, II, III & IV Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

**24. According to the textbook, which statements reflect the hardware design principle “smaller is faster”?**

I) Reducing register file size can reduce signal travel time.
II) Using fewer registers decreases clock cycle time.
III) Increasing memory size reduces instruction set simplicity.
IV) MIPS limits general-purpose registers to 32.
V) Using many instruction formats improves speed.

A. I, II & IV Only
B. I, III & IV Only
C. II, III & V Only
D. I, II, III & V Only

---

**25. Which statements about endianess and memory storage are accurate for MIPS?**

I) MIPS uses big-endian addressing.
II) Endianess affects the order of bytes in multi-byte data.
III) Endianess matters when data is interpreted differently (word vs. byte).
IV) MIPS allows mixed-endian storage in memory.
V) Endianess has no effect on byte-wise data access.

A. I, II & III Only
B. I, III & IV Only
C. II, III & V Only
D. I, II, IV & V Only

---

**26. Which of the following are true about binary number representation and conversion?**

I) Binary numbers use base 2.
II) The least significant bit is bit 0.
III) Two’s complement simplifies hardware for negative numbers.
IV) Positive numbers have leading ones in two’s complement.
V) Computers use binary for both instructions and data.

A. I, II & III Only
B. I, II, III & V Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

**27. In relation to MIPS assembly language, which of these statements are true?**

I) Each instruction performs only one operation.
II) MIPS comments start with the # symbol.
III) MIPS uses both absolute and relative jump instructions.
IV) MIPS instructions must include at least four operands.
V) MIPS assembly is case-insensitive by design.

A. I, II & III Only
B. I, II, III & IV Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

**28. Which of these are true of logical shifts in MIPS?**

I) sll performs a shift left logical.
II) srl performs a shift right logical.
III) Logical shifts are used for multiplying or dividing by powers of two.
IV) MIPS includes arithmetic shift instructions by default.
V) Shift amounts are specified in the shamt field.

A. I, II & III Only
B. I, II, III & V Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

**29. What are valid uses of the MIPS `move` operation (implemented as add)?**

I) Copies a value from one register to another.
II) Involves an add instruction with \$zero as one operand.
III) Uses an instruction specifically called `move` in MIPS.
IV) Allows for register-to-register data transfer.
V) `addi` with an immediate value of 0 can also move a value.

A. I, II & IV Only
B. I, II, III & IV Only
C. II, III, IV & V Only
D. I, II, IV & V Only

---

**30. According to the principles of instruction set design, which are objectives of the MIPS architecture?**

I) Maximize performance.
II) Minimize cost.
III) Maximize instruction length variability.
IV) Minimize energy consumption.
V) Simplify hardware design.

A. I, II & IV Only
B. I, II, IV & V Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

That completes the full set of **30 MCQs**.

When you’re ready, say **“yes, now give me the answers for all 30”**, and I’ll provide them in a clean answer key format.

# ANSWERS

Here’s the **Answer Key for all 30 MCQs**:

---

### ✅ **Answers: Batch 1 (1–10)**

1. A
2. A
3. A
4. A
5. B
6. D
7. A
8. C
9. A
10. B

---

### ✅ **Answers: Batch 2 (11–20)**

1. B
2. B
3. C
4. A
5. B
6. B
7. A
8. B
9. A
10. B

---

### ✅ **Answers: Batch 3 (21–30)**

1. D
2. B
3. A
4. A
5. A
6. B
7. A
8. B
9. D
10. B

---
