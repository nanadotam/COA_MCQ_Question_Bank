The content of **chap2-set2.pdf** is mainly focused on:

* **Arrays vs. Pointers in MIPS**
* **ARMv7 (32-bit) Instructions**
* **ARM vs. MIPS Comparison**
* **x86 Instruction Set Architecture**
* **Instruction Encoding and Addressing Modes**
* **Instruction Set Design Principles**
* **Instruction Types and Optimization Techniques**
* **Common Pitfalls and Fallacies in Programming**

I will proceed with **Batch 1 (10 MCQs)** from this new document, in the same style and difficulty level as before.

---

### **Batch 1: MCQs (1–10)**

---

**1. Which of the following statements about array and pointer implementations in MIPS are true?**

I) Arrays require recalculating addresses each iteration.
II) Pointers avoid repeated address calculations within loops.
III) Pointer increments are typically by 4 bytes for integers.
IV) Arrays and pointers produce identical assembly code.
V) Modern optimizing compilers eliminate all differences.

A. I, II & III Only
B. I, III & IV Only
C. II, III & V Only
D. I, II, III & V Only

---

**2. Which of the following describe optimizations used in converting array code to pointer code in MIPS?**

I) Strength reduction replaces multiplication with shifts.
II) Induction variable elimination removes redundant calculations.
III) Pointer loops minimize instruction count per iteration.
IV) All address calculations stay inside the loop for efficiency.
V) ANSI C requires size to be checked before loops.

A. I, II & III Only
B. I, III & IV Only
C. II, III & IV Only
D. I, II, III & V Only

---

**3. According to the textbook, which are valid ARM instruction set features?**

I) ARM uses a 32-bit instruction size.
II) ARM lacks a dedicated register for constant zero.
III) ARM supports only three data addressing modes.
IV) ARM supports conditional execution of all instructions.
V) ARM does not support memory-mapped I/O.

A. I, II & IV Only
B. I, II & III Only
C. II, III & IV Only
D. I, III, IV & V Only

---

**4. Which statements are true about addressing modes of ARM versus MIPS?**

I) MIPS has 3 simple addressing modes.
II) ARM has 9 addressing modes including complex calculations.
III) ARM supports PC-relative data addressing.
IV) MIPS allows register + register addressing by default.
V) ARM supports register + scaled register addressing.

A. I, II & III Only
B. I, II, III & V Only
C. II, III & IV Only
D. I, II, IV & V Only

---

**5. In comparing instruction set philosophies, which are correct?**

I) MIPS and ARM share RISC design principles.
II) MIPS includes a divide instruction in its core set.
III) ARM allows shifting operands before operations.
IV) ARM instructions may include condition codes.
V) MIPS uses a variable instruction size for flexibility.

A. I, III & IV Only
B. I, II & IV Only
C. I, III, IV & V Only
D. I, II, III & IV Only

---

**6. Which statements best describe key x86 instruction set characteristics?**

I) x86 allows memory-memory operations.
II) x86 instructions vary from 1 to 15 bytes.
III) x86 supports both 16-bit and 32-bit operands.
IV) x86 enforces register-only source and destination operands.
V) x86 uses postbyte encodings for addressing modes.

A. I, II & III Only
B. I, II, III & V Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

**7. Regarding x86 addressing modes, which of the following are accurate?**

I) Base plus scaled index addressing is available.
II) Displacements can be 8, 16, or 32 bits.
III) ESP cannot be used as an index register.
IV) ARM supports base plus scaled index mode.
V) MIPS requires two instructions to emulate complex x86 modes.

A. I, II & III Only
B. I, II, III & V Only
C. II, III & IV Only
D. I, III, IV & V Only

---

**8. Which of the following correctly describe x86 instruction encoding?**

I) x86 uses prefixes to modify instruction behavior.
II) Displacement and immediate fields vary in length.
III) All x86 instructions include scaled index specifiers.
IV) Condition codes are set as side effects of operations.
V) Typical x86 instructions can contain two postbytes.

A. I, II & IV Only
B. I, II, III & IV Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

**9. Which of the following are valid design principles discussed in the chapter?**

I) Simplicity favors regularity.
II) Smaller is faster.
III) Good design demands good compromises.
IV) Maximum instruction length increases performance.
V) Minimize instruction formats to simplify hardware.

A. I, II & III Only
B. I, II, III & V Only
C. II, III & IV Only
D. I, III, IV & V Only

---

**10. According to the book, which of these pitfalls and fallacies are identified?**

I) More powerful instructions always mean higher performance.
II) Writing in assembly guarantees highest performance.
III) Compilers now outperform humans in register allocation.
IV) Sequential word addresses differ by only one in byte addressing.
V) Using pointers to automatic variables can cause instability.

A. I, II & III Only
B. I, III & IV Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

If you confirm, I will immediately proceed to **Batch 2 (questions 11–20)**.
Just say **"yes, continue with Batch 2"**.


Here’s **Batch 2: MCQs (11–20)** from **chap2-set2.pdf**.

---

### **Batch 2: MCQs (11–20)**

---

**11. Which of these statements about MIPS vs. ARM architectures are true?**

I) MIPS has more registers than ARMv7.
II) ARM has more data addressing modes than MIPS.
III) Both MIPS and ARM have 32-bit instruction sizes.
IV) ARM reserves a register to always contain zero.
V) Both architectures use memory-mapped I/O.

A. I, II & III Only
B. I, II, III & V Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

**12. Which of these are differences between MIPS and x86 architectures?**

I) MIPS uses register-register operations exclusively.
II) x86 allows a source operand to also be the destination.
III) MIPS has fixed 32-bit instruction size.
IV) x86 allows memory operands for most instructions.
V) MIPS allows memory-memory operations.

A. I, II & III Only
B. I, II, III & IV Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

**13. According to the document, which of these are benefits of compiler optimization?**

I) Reduces code execution time.
II) Can replace multiplications with shifts.
III) Minimizes energy consumption by reducing instruction count.
IV) Avoids redundant recalculation in loops.
V) Eliminates the need for all manual code tuning.

A. I, II & III Only
B. I, II, III & IV Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

**14. Which statements are true about ARM conditional execution?**

I) ARM instructions may execute based on condition codes.
II) ARM condition codes include negative, zero, carry, overflow.
III) MIPS implements conditions using dedicated branch instructions.
IV) ARM conditional execution reduces code size.
V) Every ARM instruction must be conditionally executed.

A. I, II & III Only
B. I, II, III & IV Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

**15. In the context of ARM instruction formats, which are accurate?**

I) ARM instructions have a 4-bit condition field.
II) ARM register fields are smaller than MIPS due to fewer registers.
III) ARM supports immediate values via special rotations.
IV) ARM and MIPS have identical instruction format layouts.
V) ARM allows operand shifting within arithmetic instructions.

A. I, II & III Only
B. I, II, III & V Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

**16. Which statements about x86 instruction encoding are correct?**

I) x86 instructions vary from 1 to 15 bytes.
II) x86 uses a “mod, reg, r/m” postbyte scheme.
III) x86 includes scaled index addressing.
IV) x86 requires two registers for all instructions.
V) x86 allows memory operands for arithmetic operations.

A. I, II & III Only
B. I, II, III & V Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

**17. Which of these x86 instructions and functions are correctly matched?**

I) jmp: unconditional jump
II) call: subroutine call with return address push
III) add: adds immediate to register
IV) test: performs logical AND and sets condition codes
V) movsl: moves string data and increments pointers

A. I, II & III Only
B. I, II, III & IV Only
C. I, II, III, IV & V
D. II, III, IV & V Only

---

**18. Which statements are true about x86 addressing modes?**

I) x86 supports register indirect addressing.
II) x86 supports base + scaled index addressing.
III) Displacement can be up to 32 bits.
IV) ESP can be used as an index register.
V) x86 addressing modes are simpler than MIPS.

A. I, II & III Only
B. I, II, III & IV Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

**19. Which of these x86 architectural changes over time are correctly stated?**

I) 80386 extended address size to 32 bits.
II) AMD64 introduced 64-bit addressing.
III) SSE added SIMD multimedia instructions.
IV) SSE2 added double-precision floating-point SIMD.
V) SSE5 removed all SSE instructions for backward compatibility.

A. I, II & III Only
B. I, II, III & IV Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

**20. According to the text, which pitfalls are highlighted regarding programming practices?**

I) Sequential word addresses differ by one in byte addressing.
II) Using a pointer to an automatic variable after function return causes instability.
III) High-level language code is easier to maintain than assembly.
IV) Writing in assembly guarantees future compatibility.
V) More complex instructions always improve performance.

A. I, II & III Only
B. I, III, IV & V Only
C. II, III, IV & V Only
D. I, II, III & V Only

---

Batch 2 is done.
If you’re ready for **Batch 3 (questions 21–30)** just say **“yes, continue with Batch 3”**.


Here’s **Batch 3: MCQs (21–30)** from **chap2-set2.pdf**.

---

### **Batch 3: MCQs (21–30)**

---

**21. According to the document, which are true of x86 data movement instructions?**

I) mov moves data between register and memory.
II) push saves a register value onto the stack.
III) pop restores a value from the stack.
IV) les loads both ES segment and a GPR.
V) movsl compares string operands for equality.

A. I, II & III Only
B. I, II, III & IV Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

**22. Which of these are examples of x86 control flow instructions?**

I) jnz: jump if not zero
II) je: jump if equal
III) jmp: unconditional jump
IV) call: subroutine call
V) cmp: compare operands

A. I, II & III Only
B. I, II, III & IV Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

**23. Which statements are true about instruction set evolution as described?**

I) x86 extended from 16-bit to 32-bit in 80386.
II) AMD64 added 64-bit addressing.
III) SSE introduced multimedia SIMD instructions.
IV) ARMv8 completely removed v7’s conditional execution field.
V) MIPS has retained variable instruction lengths for flexibility.

A. I, II & III Only
B. I, II, III & IV Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

**24. Which of these fallacies and pitfalls are identified in the reading?**

I) Compilers cannot optimize register allocation as well as humans.
II) Pointer arithmetic must consider word size in byte addressing machines.
III) Assembly language guarantees the fastest execution.
IV) Using complex instructions always results in faster execution.
V) Using pointers to automatic variables outside their scope leads to instability.

A. I, II & III Only
B. II, III & IV Only
C. II, IV & V Only
D. II, III & V Only

---

**25. Regarding design principles mentioned for instruction sets, which are correct?**

I) Simplicity favors regularity.
II) Smaller is faster.
III) Instruction set design always prioritizes maximum functionality.
IV) Good design demands good compromises.
V) Common cases should be optimized for speed.

A. I, II & III Only
B. I, II, III & IV Only
C. I, II, IV & V Only
D. II, III, IV & V Only

---

**26. Which of these describe characteristics of x86 arithmetic and logic instructions?**

I) Two-operand instructions with register or memory operand.
II) Source and destination can be the same register.
III) Support for both 8-bit and 32-bit operands.
IV) Instruction size can be modified with prefixes.
V) MIPS allows memory operands like x86.

A. I, II & III Only
B. I, II, III & IV Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

**27. In comparing x86 and MIPS, which statements are accurate?**

I) x86 allows memory operands for arithmetic instructions.
II) MIPS uses fixed 32-bit instruction formats.
III) x86 has fewer general-purpose registers than MIPS.
IV) MIPS supports variable-length instruction formats.
V) x86 supports scaled index addressing.

A. I, II & III Only
B. I, II, III & V Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

**28. Which of these are typical x86 instruction features discussed?**

I) test: performs logical AND to set condition codes.
II) add: adds immediate values to registers.
III) je: jumps if equal based on condition codes.
IV) movsl: copies string values between memory locations.
V) x86 uses fixed 32-bit instruction size.

A. I, II & III Only
B. I, II, III & IV Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

**29. Which of the following features were highlighted about ARMv8 in comparison to ARMv7?**

I) ARMv8 uses 32 general-purpose registers.
II) ARMv8 removed conditional execution field.
III) ARMv8 includes a divide instruction.
IV) ARMv8 kept the PC as a general-purpose register.
V) ARMv8 added more complex load/store instructions.

A. I, II & III Only
B. I, II, III & V Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

**30. According to the book’s discussion on abstraction, which are true about MIPS assembly?**

I) Assembly language hides complex binary instruction formats.
II) Assemblers translate symbolic instructions into machine code.
III) Assemblers support pseudo-instructions not in hardware.
IV) MIPS arithmetic instructions directly match assignment operations in high-level languages.
V) MIPS supports direct memory-memory arithmetic operations.

A. I, II & III Only
B. I, II, III & IV Only
C. II, III, IV & V Only
D. I, III, IV & V Only

---

This completes all **30 MCQs for chap2-set2.pdf**.

If you’re ready, just say **“yes, now give me the answers for all 30”**.
I’ll prepare the full answer key right away.



Here’s the **Answer Key for all 30 MCQs (chap2-set2.pdf)**:

---

### ✅ **Answers: Batch 1 (1–10)**

1. D
2. D
3. A
4. B
5. D
6. B
7. B
8. A
9. B
10. D

---

### ✅ **Answers: Batch 2 (11–20)**

11. B
12. B
13. B
14. B
15. B
16. B
17. C
18. A
19. B
20. A

---

### ✅ **Answers: Batch 3 (21–30)**

21. B
22. B
23. B
24. D
25. C
26. B
27. B
28. B
29. A
30. B

---

If you want, I can also **compile all 30 questions + answers into a clean, printable document (Word or PDF)** for easy study or printing.
Just say **"yes, please prepare it"** if you want that too.
