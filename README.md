# Scribble Language Interpreter

## Overview
This project is a simple **Scribble language interpreter**. It allows you to write and run scripts using a custom scripting language called **Scribble**.

## Features
- Interpret commands like `add_object`, `set_property`, and `say`.
- Draw basic shapes on a canvas (like circles, squares, and more).
- Customizable properties for each shape (like color, size, position).
- Easy-to-use scripting format.

## How to Use
1. **Download/Clone the project**:
   - Clone the repository to your local machine or download it as a ZIP file.

2. **Write a Scribble script**:
   - Create a new file with a `.scribble` extension (e.g., `my_game.scribble`).
   - Example:
     ```txt
     <start>
     {add_object} ;circle [pos=100,100] [size=50]
     {set_property} Tag=circle ;color=red
     {say} "Welcome to Scribble Game!"
     <end>
     ```

3. **Run the interpreter**:
   - Open the `index.html` file (if you want to run in a browser) or use your custom script with a Python interpreter (if you built one for the backend).
   
   - If you're using HTML, you can use it in the browser like this:
     ```html
     <script src="scribble_interpreter.js"></script>
     ```

4. **Customization**:
   - Change the text, shapes, colors, and other properties in the `.scribble` files to create different scenes, shapes, and animations.
   
## Example Script
```txt
<start>
{add_object} ;circle [pos=100,100] [size=50]
{set_property} Tag=circle ;color=red
{say} "Hello, Scribble World!"
<end>
