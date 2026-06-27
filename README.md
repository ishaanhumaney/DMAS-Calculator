# DMAS-Calculator

This repository contains a simple, direct Python script designed to parse and calculate standard mathematical expressions based on DMAS operator precedence. Instead of relying on pre-built parsing libraries or complex abstract syntax trees, the logic evaluates string inputs linearly. It tokenizes user input and performs sequential multi-pass evaluations across the array, ensuring that division and multiplication operations are fully resolved before moving on to addition and subtraction. It provides a straightforward, no-nonsense approach to handling multi-number calculations directly in the console.

To get started with the calculator, you just need a standard Python 3 installation on your machine. You can run the script straight from your terminal by executing the main file, which immediately prompts you to type in your arithmetic expression. It is important to separate your numbers and operators with spaces so the tokenizer can split the input correctly. Once you press enter, the script handles the calculations under the hood in proper order and outputs the final result right back to the console window.

Let me know if you need to tweak the wording or add a section for installation commands.
