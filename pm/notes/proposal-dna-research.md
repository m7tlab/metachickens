### **Proposal: Differential Analysis**

This proposal outlines a system where players acquire DNA modifiers by abstractly "subtracting" the components of one genetic sample from another. This treats DNA as a complex set of traits and focuses on isolating a single desired one through comparison.

* **The Differential Analyzer:** A new block that serves as the core of this process. It has two input slots: one for a complex DNA sample and one for a reference sample.
* **The Process:**
    1.  **Complex Sample:** A DNA bottle extracted from a mob (e.g., a **Rabbit DNA bottle**). This contains all the mob's traits (health, speed, jump, etc.).
    2.  **Reference Sample:** A DNA bottle extracted from an item that represents a single, pure trait, like a **Potion of Leaping**.
    3.  **Analysis:** The player places both into the Differential Analyzer. The machine processes them, abstractly "subtracting" the reference DNA from the complex DNA. The result is the isolated "difference"—the specific trait you're looking for.
* **The Outcome:** The Analyzer yields a single, usable **DNA Modifier** (e.g., a `DNA Modifier (Jump)`). The original DNA bottle is consumed in the process. This modifier can then be used in the **Genetic Sequencer** to apply the trait to any other mob's DNA.
