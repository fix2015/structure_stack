# Stack Data Structure in JavaScript 🚀  

A simple implementation of the **Stack** data structure in JavaScript. This repository demonstrates how to create a stack class with essential methods and explains its functionality with practical examples.  

---

## What is a Stack?  
A **Stack** is a data structure that follows the **LIFO** (Last In, First Out) principle. The last element added to the stack is the first one to be removed. Think of it as a stack of plates: you take the top plate first when serving.  

---

## Features  
- **Push**: Add an item to the stack.  
- **Pop**: Remove and return the top item.  
- **Peek**: View the top item without removing it.  
- **isEmpty**: Check if the stack is empty.  
- **Size**: Get the number of items in the stack.  

---

## Code Implementation  

Here’s the JavaScript implementation of the stack:  

```javascript
class Stack {
    constructor() {
        this.items = []; // Initialize an empty array
    }

    // Add an item to the stack
    push(element) {
        this.items.push(element);
    }

    // Remove and return the top item
    pop() {
        if (this.isEmpty()) {
            return "Stack is empty!";
        }
        return this.items.pop();
    }

    // Check if the stack is empty
    isEmpty() {
        return this.items.length === 0;
    }

    // Peek at the top item without removing it
    peek() {
        if (this.isEmpty()) {
            return "Stack is empty!";
        }
        return this.items[this.items.length - 1];
    }

    // Get the size of the stack
    size() {
        return this.items.length;
    }
}
```

---

## Example Usage  

```javascript
// Initialize the stack
const stack = new Stack();

// Add items to the stack
stack.push("Plate 1");
stack.push("Plate 2");
stack.push("Plate 3");

// Peek at the top item
console.log(stack.peek()); // Output: Plate 3

// Remove items from the stack
console.log(stack.pop()); // Output: Plate 3
console.log(stack.pop()); // Output: Plate 2

// Check if the stack is empty
console.log(stack.isEmpty()); // Output: false

// Get the size of the stack
console.log(stack.size()); // Output: 1
```

---

## Real-World Applications  
1. **Undo/Redo Operations**: In text editors and IDEs.  
2. **Backtracking**: In algorithms like depth-first search (DFS).  
3. **Expression Evaluation**: Managing operands and operators in mathematical expressions.  
4. **Function Call Stack**: Handling nested function calls in programming.  

---

## TikTok Tutorial 🎥  
Want to see a quick tutorial on how to build this? Check out this TikTok video:  
[https://www.tiktok.com/@jsmentoring/video/7461022091421273376](https://www.tiktok.com/@jsmentoring/video/7461022091421273376)  

---

## How to Run the Code  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/stack-data-structure.git
   cd stack-data-structure
   ```
2. Open the file `stack.js` in your favorite code editor.  
3. Run the file using Node.js:  
   ```bash
   node stack.js
   ```

---

## Contributing  
Contributions are welcome! If you have suggestions or want to add new features, feel free to create a pull request.  

---

## License  
This project is licensed under the MIT License.  

---

## Connect with Me:
- [LinkedIn - Vitalii Semianchuk](https://www.linkedin.com/in/vitalii-semianchuk-9812a786/)
- [Telegram - @jsmentorfree](https://t.me/jsmentorfree) - We do a lot of free teaching on this channel! Join us to learn and grow in web development.
- [Tiktok - @jsmentoring](https://www.tiktok.com/@jsmentoring) Everyday new videos
- [Youtube - @jsmentor-uk](https://www.youtube.com/@jsmentor-uk) Mentor live streams
- [Dev.to - fix2015](https://dev.to/fix2015) Javascript featured, live, experience
