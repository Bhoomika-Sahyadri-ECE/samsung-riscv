# RISC-V Internship Program Powered by SAMSUNG and VSD🎯
### Co- Founder of VSD : Mr. Kunal Ghosh

## Description💪
This RISC-V Internship uses the VSDSquadron Mini, based on the RISC-V architecture, to teach students about VLSI SoC design and RISC-V using open-source tools. The program is led by Mr. Kunal Ghosh, Co-Founder of VSD.


## About Me ✒

**👩‍🎓Name:** Bhoomika H Salian  
**📌College:** Sahyadri College of Engineering and Management  
**🔑Email ID:** [bhoomikahsalian@gmail.com](mailto:bhoomikahsalian@gmail.com)  
**🏷️GitHub Profile:** [Bhoomika-Sahyadri-ECE](https://github.com/Bhoomika-Sahyadri-ECE)  
**🔗LinkedIn Profile:** [Bhoomika H Salian](https://www.linkedin.com/in/bhoomika-h-salian-7470a3253/)


## Task Overview📅
<details>
<summary>Task 1: Introduction to RISC-V Architecture and Toolchain Setup</summary>

**GitHub Repository:** [Task 1](https://github.com/Bhoomika-Sahyadri-ECE/samsung-riscv/tree/main/task%201)  
**Description:**

- Set up the development environment for RISC-V on the VSDSquadron Mini.
- Install necessary open-source tools and verify the RISC-V toolchain.
- Familiarize with the basic RISC-V architecture, including registers and instruction sets.
- Document the setup process and any issues encountered during the setup.

</details>

<details>
<summary>Task 2: Implementing Basic RISC-V Programs</summary>

**GitHub Repository:** [Task 2](https://github.com/Bhoomika-Sahyadri-ECE/samsung-riscv/tree/main/task%202)  
**Description:**

- Write and execute basic RISC-V assembly programs.
- Explore the functionalities of the RISC-V instruction set by implementing simple arithmetic and logical operations.
- Debug and test the programs using the RISC-V simulator.
- Record the results and learning outcomes from each program.

</details>

<details>
<summary> Task 3: Assembly Instructions</summary>

  **GitHub Repository:** [Task 3](https://github.com/Bhoomika-Sahyadri-ECE/samsung-riscv/tree/main/task%203)
**Description:**

### 1. `lui a0, 0x2b`
- **Operation:** Load the upper 20 bits of an immediate (0x2b) into register `a0`.
- **Opcode:** `0110111`
- **Binary Encoding:** `000000000000001011010100110111`
- **Hexadecimal:** `0x002b537`

![LUI Instruction]("D:\samsung\task 3\lui_a0.png")

---

### 2. `addi sp, sp, -32`
- **Operation:** Add immediate (-32) to stack pointer (`sp = sp - 32`).
- **Opcode:** `0010011`
- **Binary Encoding:** `11111111111100010000000010010011`
- **Hexadecimal:** `0xFE010113`

![ADDI Instruction](images/addi_sp.png)

---

### 3. `auipc a5, 0xffff0`
- **Operation:** Add upper immediate to PC (`a5 = PC + 0xffff000`).
- **Opcode:** `0010111`
- **Binary Encoding:** `11111111111111110000011110010111`
- **Hexadecimal:** `0xffff0797`

![AUIPC Instruction](images/auipc_a5.png)

---

### 4. `jal ra, 0x10184`
- **Operation:** Jump and link (`ra = PC + 4; PC = 0x10184`).
- **Opcode:** `1101111`
- **Hexadecimal:** `0x0c0000ef`

![JAL Instruction](images/jal_ra.png)

---

### 5. `sb a5, 1944(gp)`
- **Operation:** Store byte from `a5` to memory at `gp + 1944`.
- **Opcode:** `0100011`
- **Hexadecimal:** `0x781fc23`

![SB Instruction](images/sb_a5.png)

---

### 6. `bnez a5, 1015c`
- **Operation:** Branch if `a5` is not zero to `1015c`.
- **Opcode:** `1100011`
- **Hexadecimal:** `0x04079463`

![BNEZ Instruction](images/bnez_a5.png)

---

### 7. `jalr zero, 0(register_fini)`
- **Operation:** Jump and link register (return to zero).
- **Hexadecimal:** `0x00100073`

![JALR Instruction](images/jalr_zero.png)

---

### 8. `lw a0, 0(sp)`
- **Operation:** Load word from memory at `sp + 0` into `a0`.
- **Opcode:** `0000011`
- **Hexadecimal:** `0x00052083`

![LW Instruction](images/lw_a0.png)

---

### 9. `li a1, 1`
- **Operation:** Load immediate `1` into `a1`.
- **Hexadecimal:** `0x0100793`

![LI Instruction](images/li_a1.png)

---

### 10. `sub a2, a2, a0`
- **Operation:** Subtract (`a2 = a2 - a0`).
- **Opcode:** `0110011`
- **Hexadecimal:** `0x40a60633`

![SUB Instruction](images/sub_a2.png)

---

### 11. `jal ra, 0x10264`
- **Operation:** Jump and link (`ra = PC + 4; PC = 0x10264`).
- **Hexadecimal:** `0x0cc000ef`

![JAL Instruction](images/jal_ra_10264.png)

---

### 12. `addi a0, a0, 332`
- **Operation:** Add immediate (`a0 = a0 + 332`).
- **Hexadecimal:** `0x14c50513`

![ADDI Instruction](images/addi_a0.png)

---

### 13. `j 0x101c0`
- **Operation:** Unconditional jump to `0x101c0`.
- **Opcode:** `1101111`
- **Hexadecimal:** `0x0c80006f`

![JUMP Instruction](images/j_101c0.png)

---

### 14. `jalr ra, 8(sp)`
- **Operation:** Jump to address in `sp + 8`, store return address in `ra`.
- **Hexadecimal:** `0x00813083`

![JALR Instruction](images/jalr_ra.png)

---

### 15. `ret`
- **Operation:** Return from function (`jalr x0, 0(ra)`).
- **Hexadecimal:** `0x00008067`

![RET Instruction](images/ret.png)

---
