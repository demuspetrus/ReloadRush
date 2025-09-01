# ChatGPT Chat OS 0.6

ChatGPT Chat OS 0.6 is a minimal operating layer built from **Memory Banks**.  
It lets you keep structured state inside a chat by combining two simple rules:  
- Start from a **snapshot**  
- Apply updates with **small, explicit commands**  

This avoids forgetting and makes it possible to manage projects, notes, or even games in a consistent way.

---

## Components

- **OS Kernel** (`chatgpt_os_kernel.txt`)  
  Manages banks: create, list, switch, checkpoint, revert.  

- **Empty Bank Starter** (`empty_bank_starter.txt`)  
  A minimal template you can adapt to anything.  

- **(Optional Banks)**  
  You can add domain-specific banks (General, Factory, Chess, Sudoku, etc.).  

---

## Quick Start

1. Open a new ChatGPT session.  
2. Upload `chatgpt_os_kernel.txt`.  
3. Say: `Use ChatGPT OS`.  
4. Create a bank:  
