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
 ![lui_a0](https://github.com/user-attachments/assets/4bb8fc38-a449-4334-8044-90a047fbeca3)
 

---

### 2. `addi sp, sp, -32`
- **Operation:** Add immediate (-32) to stack pointer (`sp = sp - 32`).
- **Opcode:** `0010011`
- **Binary Encoding:** `11111111111100010000000010010011`
- **Hexadecimal:** `0xFE010113`

![addi_sp](https://github.com/user-attachments/assets/a76ba6b1-fc5e-4531-a45d-7365e09b8780)

---

### 3. `auipc a5, 0xffff0`
- **Operation:** Add upper immediate to PC (`a5 = PC + 0xffff000`).
- **Opcode:** `0010111`
- **Binary Encoding:** `11111111111111110000011110010111`
- **Hexadecimal:** `0xffff0797`

![auipc_a5](https://github.com/user-attachments/assets/18130065-d54d-4a5b-b88e-0c38bd23d986)


---

### 4. `jal ra, 0x10184`
- **Operation:** Jump and link (`ra = PC + 4; PC = 0x10184`).
- **Opcode:** `1101111`
- **Hexadecimal:** `0x0c0000ef`

![jal_ra](https://github.com/user-attachments/assets/83aac50a-acd7-4e1d-bcef-0a150efeefec)


---

### 5. `sb a5, 1944(gp)`
- **Operation:** Store byte from `a5` to memory at `gp + 1944`.
- **Opcode:** `0100011`
- **Hexadecimal:** `0x781fc23`
  
![sb_a5](https://github.com/user-attachments/assets/635cfec0-9de7-496f-b686-84cb153bc8c0)


---

### 6. `bnez a5, 1015c`
- **Operation:** Branch if `a5` is not zero to `1015c`.
- **Opcode:** `1100011`
- **Hexadecimal:** `0x04079463`
  
![bnez_a5](https://github.com/user-attachments/assets/a88ea41b-a81e-4685-8306-b01f41eb257c)


---

### 7. `jalr zero, 0(register_fini)`
- **Operation:** Jump and link register (return to zero).
- **Hexadecimal:** `0x00100073`
  
![jalr_zero](https://github.com/user-attachments/assets/becc702e-b5eb-4afa-9364-55d7c11496dd)


---

### 8. `lw a0, 0(sp)`
- **Operation:** Load word from memory at `sp + 0` into `a0`.
- **Opcode:** `0000011`
- **Hexadecimal:** `0x00052083`

![lw_a0](https://github.com/user-attachments/assets/c1dddfb1-85f0-4407-80b9-818f8685b37a)


---

### 9. `li a1, 1`
- **Operation:** Load immediate `1` into `a1`.
- **Hexadecimal:** `0x0100793`

![li_a1](https://github.com/user-attachments/assets/9d07ddae-6967-4951-81ef-6fdebadaae1d)


---

### 10. `sub a2, a2, a0`
- **Operation:** Subtract (`a2 = a2 - a0`).
- **Opcode:** `0110011`
- **Hexadecimal:** `0x40a60633`
  
![sub_a2](https://github.com/user-attachments/assets/11a51aca-e854-4617-976f-de637f5c960e)


---

### 11. `jal ra, 0x10264`
- **Operation:** Jump and link (`ra = PC + 4; PC = 0x10264`).
- **Hexadecimal:** `0x0cc000ef`

![jal_ra](https://github.com/user-attachments/assets/47e071ad-ed23-4d69-9a97-d158d8bbd5fd)


---

### 12. `addi a0, a0, 332`
- **Operation:** Add immediate (`a0 = a0 + 332`).
- **Hexadecimal:** `0x14c50513`

![addi_a0](https://github.com/user-attachments/assets/99adf464-1b2a-47ea-80d4-97a2e3442e68)


---

### 13. `j 0x101c0`
- **Operation:** Unconditional jump to `0x101c0`.
- **Opcode:** `1101111`
- **Hexadecimal:** `0x0c80006f`

![j_101c0](https://github.com/user-attachments/assets/9f8f3837-9fc9-4890-8b77-99125a1cf248)


---

### 14. `jalr ra, 8(sp)`
- **Operation:** Jump to address in `sp + 8`, store return address in `ra`.
- **Hexadecimal:** `0x00813083`
  
![jal_ra](https://github.com/user-attachments/assets/2139e451-30e5-4410-876d-704504c7e591)


---

### 15. `ret`
- **Operation:** Return from function (`jalr x0, 0(ra)`).
- **Hexadecimal:** `0x00008067`
  
![ret](https://github.com/user-attachments/assets/02178bec-6b91-44d0-93b8-9d3f90ce5599)


---
  
</details>


<details>
<summary>Task 5: Trying out the new VSD squadron Mini board with simple circuit</summary>

**GitHub Repository:** [Task 5](https://github.com/Bhoomika-Sahyadri-ECE/samsung-riscv/tree/main/task%205)                                                    
**Description:**  
This project demonstrates **GPIO-based LED control using push buttons** on the **VSDSquadron Mini**, a **RISC-V-based SoC development kit**. The system responds to user input by lighting up LEDs independently based on the button pressed.

- **Button 1 Pressed** → **LED 1 turns ON**  
- **Button 2 Pressed** → **LED 2 turns ON**  
- **Button 3 Pressed** → **LED 3 turns ON**  


## **Components Required**
- **VSDSquadron Mini** (1x)  
- **LEDs** (3x)  
- **Push Buttons** (3x)  
- **Jumper Wires** (As needed)  
- **Breadboard** (1x)  


## **Pin Connections**

### **LEDs**
| LED  | VSDSquadron Mini Pin |
|------|----------------------|
| LED 1 | PC0 |
| LED 2 | PC1 |
| LED 3 | PC2 |

### **Push Buttons (Active HIGH Configuration)**
| Button  | VSDSquadron Mini Pin |
|---------|----------------------|
| Button 1 | PD1 |
| Button 2 | PD2 |
| Button 3 | PD3 |


## **Wiring Details**

### **LED Connections**
- Connect the **anode (+)** of **LED 1** to **PC0**.  
- Connect the **anode (+)** of **LED 2** to **PC1**.  
- Connect the **anode (+)** of **LED 3** to **PC2**.  
- Connect the **cathode (-)** of all LEDs to **GND**.  

### **Push Button Connections**
- Connect one terminal of **Button 1** to **PD1**.  
- Connect one terminal of **Button 2** to **PD2**.  
- Connect one terminal of **Button 3** to **PD3**.  
- Connect the **other terminal** of all buttons to **GND**.  


## **Logic Implementation**
| Button Pressed | LEDs Activated |
|---------------|---------------|
| **Button 1 (PD1)** | **LED 1 (PC0) turns ON** |
| **Button 2 (PD2)** | **LED 2 (PC1) turns ON** |
| **Button 3 (PD3)** | **LED 3 (PC2) turns ON** |



## **Circuit Diagram**
![Glowing LED circuit](https://github.com/Bhoomika-Sahyadri-ECE/samsung-riscv/blob/main/task%205/ciruit%20diagram.png)



## **Working**
- The code is written for the **VSD Squadron Mini Board**.  
- Three LEDs are connected to **PC0, PC1, and PC2**, while three push buttons are connected to **PD1, PD2, and PD3**.  
- In the `setup()` function:
  - LED pins are configured as **output**.
  - Button pins are configured as **input with internal pull-up resistors enabled**.  
- In the `loop()` function:
  - The state of each button is read using `digitalRead()`. Since **pull-up resistors** are used, the buttons read **LOW when pressed**.  
  - **Button 1 pressed** → Only **LED 1** turns ON, others remain OFF.  
  - **Button 2 pressed** → Only **LED 2** turns ON, others remain OFF.  
  - **Button 3 pressed** → Only **LED 3** turns ON, others remain OFF.  
  - **No button pressed** → All LEDs remain OFF.  


## **Code Implementation**
```cpp
#include <Arduino.h>

// Define LED pins
#define LED1 PC0
#define LED2 PC1
#define LED3 PC2

// Define Button pins
#define BUTTON1 PD1
#define BUTTON2 PD2
#define BUTTON3 PD3

void setup() {
    // Configure LED pins as OUTPUT
    pinMode(LED1, OUTPUT);
    pinMode(LED2, OUTPUT);
    pinMode(LED3, OUTPUT);

    // Configure Button pins as INPUT with PULL-UP
    pinMode(BUTTON1, INPUT_PULLUP);
    pinMode(BUTTON2, INPUT_PULLUP);
    pinMode(BUTTON3, INPUT_PULLUP);
}

void loop() {
    // Read button states
    bool button1State = digitalRead(BUTTON1) == LOW;
    bool button2State = digitalRead(BUTTON2) == LOW;
    bool button3State = digitalRead(BUTTON3) == LOW;

    // Control LEDs independently based on button presses
    digitalWrite(LED1, button1State ? HIGH : LOW);
    digitalWrite(LED2, button2State ? HIGH : LOW);
    digitalWrite(LED3, button3State ? HIGH : LOW);
}
```


## **Response Captured**
| **Button Pressed** | **LED Status** |
|--------------------|---------------|
| **Button 1** Pressed | ![One LED Glowing](https://github.com/Bhoomika-Sahyadri-ECE/samsung-riscv/blob/main/task%205/button%201.jpg) |
| **Button 2** Pressed | ![Two LEDs Glowing](https://github.com/Bhoomika-Sahyadri-ECE/samsung-riscv/blob/main/task%205/button%202.jpg) |
| **Button 3** Pressed | ![Three LEDs Glowing](https://github.com/Bhoomika-Sahyadri-ECE/samsung-riscv/blob/main/task%205/button%203.jpg) |


## **Key Takeaways**
**Independent LED Control:** Each button **independently** turns ON a specific LED.  
**GPIO Handling:** Demonstrates **basic GPIO input (buttons)** and **output (LEDs)**.  
**PlatformIO & RISC-V Development:** Utilizes **PlatformIO for VSDSquadron Mini programming**.  

### **Conclusion**
This project successfully demonstrates the use of GPIO-based LED control with push buttons on the VSDSquadron Mini board. By implementing an independent control logic for each LED, we showcase how simple button inputs can be used to drive different outputs effectively. This hands-on experiment reinforces fundamental embedded system concepts like digital input/output operations, pull-up resistors, and microcontroller-based control logic.


</details>


<details>
<summary>Task 6: Testing and Implementing new Logic</summary>

**GitHub Repository:** [Task 6](https://github.com/Bhoomika-Sahyadri-ECE/samsung-riscv/tree/main/task%206)

**Description:**  
This project demonstrates **GPIO-based LED control using push buttons** on the **VSDSquadron Mini**, a **RISC-V-based SoC development kit**. The system responds to user input by lighting up LEDs in a predefined pattern:  

- **Button 1 Pressed** → **LED 1 turns ON**  
- **Button 2 Pressed** → **LED 1 & LED 2 turn ON**  
- **Button 3 Pressed** → **LED 1, LED 2 & LED 3 turn ON**  

This project illustrates fundamental **embedded system concepts**, including **GPIO input/output operations**. The implementation is done in **C using the PlatformIO IDE**, providing a hands-on approach to hardware interaction.  

### Components Required  
- **VSDSquadron Mini** (1x)  
- **LEDs** (3x)  
- **Push Buttons** (3x)  
- **Jumper Wires** (As needed)  
- **Breadboard** (1x)  

### Pin Connections  

#### **LEDs**  
| LED  | VSDSquadron Mini Pin |
|------|----------------------|
| LED 1 | PC0 |
| LED 2 | PC1 |
| LED 3 | PC2 |

#### **Push Buttons (Active HIGH Configuration)**  
| Button  | VSDSquadron Mini Pin |
|---------|----------------------|
| Button 1 | PD1 |
| Button 2 | PD2 |
| Button 3 | PD3 |

### Wiring Details  

#### **LED Connections**  
- Connect the **anode (+)** of **LED 1** to **PC0**.  
- Connect the **anode (+)** of **LED 2** to **PC1** via a.  
- Connect the **anode (+)** of **LED 3** to **PC2** via a **.  
- Connect the **cathode (-)** of all LEDs to **GND**.  

#### **Push Button Connections**  
- Connect one terminal of **Button 1** to **PD1**.  
- Connect one terminal of **Button 2** to **PD2**.  
- Connect one terminal of **Button 3** to **PD3**.  
- Connect the **other terminal** of all buttons to **GND**.  

### Logic Implementation  

| Button Pressed | LEDs Activated |
|---------------|---------------|
| **Button 1 (PD1)** | **LED 1 (PC0) turns ON** |
| **Button 2 (PD2)** | **LED 1 (PC0) & LED 2 (PC1) turn ON** |
| **Button 3 (PD3)** | **LED 1 (PC0), LED 2 (PC1) & LED 3 (PC2) turn ON** |


### Circuit Diagram
![Glowing LEd circuit](https://github.com/Bhoomika-Sahyadri-ECE/samsung-riscv/blob/main/task%206/ciruit%20diagram.png)


### Working
- The code is written for an Arduino-based system using VSD squadron Mini
- Three LEDs are connected to pins PC1, PC2, and PC3, and three push buttons are connected to pins PD1, PD2, and PD3.  
- In the `setup()` function, the LED pins are configured as output, and the button pins are configured as input with internal pull-up resistors enabled.  
- In the `loop()` function, the state of each button is read using `digitalRead()`, and since pull-up resistors are used, the buttons read LOW when pressed.  
- If Button 1 is pressed, only LED1 turns on, while LED2 and LED3 remain off.  
- If Button 2 is pressed, LED1 and LED2 turn on, while LED3 remains off.  
- If Button 3 is pressed, all three LEDs turn on.  
- If no button is pressed, all LEDs remain off.  
- The logic ensures that pressing a button overrides the previous LED state based on priority, meaning the highest button number pressed determines the LED pattern.

### Code
```cpp
#include <Arduino.h>

// Define LED pins
#define LED1 PC1
#define LED2 PC2
#define LED3 PC3

// Define Button pins
#define BUTTON1 PD1
#define BUTTON2 PD2
#define BUTTON3 PD3

void setup() {
    // Configure LED pins as OUTPUT
    pinMode(LED1, OUTPUT);
    pinMode(LED2, OUTPUT);
    pinMode(LED3, OUTPUT);

    // Configure Button pins as INPUT with PULL-UP
    pinMode(BUTTON1, INPUT_PULLUP);
    pinMode(BUTTON2, INPUT_PULLUP);
    pinMode(BUTTON3, INPUT_PULLUP);
}

void loop() {
    // Read button states
    bool button1State = digitalRead(BUTTON1) == LOW;
    bool button2State = digitalRead(BUTTON2) == LOW;
    bool button3State = digitalRead(BUTTON3) == LOW;

    // Control LEDs based on button presses
    if (button1State) {
        digitalWrite(LED1, HIGH);
        digitalWrite(LED2, LOW);
        digitalWrite(LED3, LOW);
    } 
    else if (button2State) {
        digitalWrite(LED1, HIGH);
        digitalWrite(LED2, HIGH);
        digitalWrite(LED3, LOW);
    } 
    else if (button3State) {
        digitalWrite(LED1, HIGH);
        digitalWrite(LED2, HIGH);
        digitalWrite(LED3, HIGH);
    } 
    else {
        // Turn off all LEDs when no button is pressed
        digitalWrite(LED1, LOW);
        digitalWrite(LED2, LOW);
        digitalWrite(LED3, LOW);
    }
}
```
### Response Captured

![Button 1 pressed](https://github.com/Bhoomika-Sahyadri-ECE/samsung-riscv/blob/main/task%206/one%20led%20glowing.png)
![Button 2 pressed](https://github.com/Bhoomika-Sahyadri-ECE/samsung-riscv/blob/main/task%206/two%20leds%20glowing.png)
![Button 3 pressed](https://github.com/Bhoomika-Sahyadri-ECE/samsung-riscv/blob/main/task%206/three%20leds%20glowing.png)


### Conclusion  
This project demonstrates how to control LEDs using push buttons on an VSD squadron Mini board.The logic implemented allows different LED patterns based on button presses, making it a simple yet effective example of digital input and output control. This can be further expanded for more complex interactive applications. 🚀

</details>
