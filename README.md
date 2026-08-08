# 🔄 While Loop Counter | JavaScript Core Iteration Practice

## 📌 Description
This repository contains a foundational JavaScript practice file demonstrating basic iterative control flow. The script uses a standard `while` loop to count sequentially from 1 to 10, showing how a loop condition evaluates states and logs output dynamically to the terminal console until it meets its termination boundary.

---

## ⚡ Key Programming Concepts Applied
* 🔢 **Loop Counter Initialization:** Setting up a mutable iterator reference state variable (`let i = 1`).
* ⏳ **Boundary Condition Check:** Testing constraints on every iteration cycle (`i <= 10`) to prevent runaway infinite executions.
* 📈 **Post-Increment Operator:** Safely adding steps to the internal state pointer (`i++`) to move sequentially toward loop termination.
* 📟 **Stream Output Logging:** Directing numerical counts immediately onto the system runtime console interface.

---

## 💻 Source Code

Here is the exact source code written in this practice file:

```javascript
let i = 1;

while(i <= 10){
    console.log(i);
    i++;
}
```

---

## 📊 Iteration Flow Matrix

The execution block shifts states through these logical milestones step-by-step:

| Loop Cycle Count | Current Value of `i` | Condition Check (`i <= 10`) | Terminal Action Log | Next Updated State |
| :---: | :---: | :---: | :--- | :---: |
| 🏁 **Start** | `1` | `true` | Prints `1` | `2` |
| 🔄 **Cycle 2-9**| `2` to `9` | `true` | Prints `2` through `9` | `3` to `10` |
| 🎯 **Last Hit** | `10` | `true` | Prints `10` | `11` |
| ❌ **Exit** | `11` | `false` | Loop breaks instantly | End of Script |

---

## 🖥️ Expected Terminal Output

When executed in any valid runtime environment, the console renders a clean linear column sequence:

```text
1
2
3
4
5
6
7
8
9
10
```

---

## 🚀 Step-by-Step Execution Guide

### Method 1: Node.js Environment
1. Save this code block into a file named `counter.js`.
2. Open your terminal screen inside that exact folder path.
3. Run the following command lines:
   ```bash
   node counter.js
   ```

### Method 2: Web Browser Developer Console
1. Open any working browser webpage window.
2. Toggle your developer inspector layout tools by pressing `F12` (or Right-Click ➡️ **Inspect**).
3. Shift directly into the **Console** sub-tab layout.
4. Paste the raw script code completely inside the text line prompt and press **Enter**.

---
<p align="center">
  🚀 <i>Mastering linear sequential counters is the first major milestone to handling massive loop data matrices! Keep driving forward!</i>
</p>

## ✍️ Author
- GitHub: [SairaBano55](https://github.com/SairaBano55)
