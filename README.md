Caesar Cipher Program

This program can encrypt or decrypt text using the Caesar cipher.
Each letter is shifted by 3 positions.

How to use
1. Run the program.
2. Type 'e' to encrypt or 'd' to decrypt.
3. Enter a word in uppercase (no spaces).

For example:
Enter mode (e=encrypt, d=decrypt): e
Enter text (uppercase, no spaces): HELLO
Result: KHOOR

Enter mode (e=encrypt, d=decrypt): d
Enter text (uppercase, no spaces): KHOOR
Result: HELLO

Finito!!!



Flowchart
<img width="179" height="277" alt="image" src="https://github.com/user-attachments/assets/70f8d1cc-6831-4899-b5bd-114c4a0098e2" />



Explanation (Modularization)
- CLI (Command Line Interface): The program asks the user for input using `scanf`.
- Caesar Cipher Logic: The main loop goes through each letter and shifts it.
- No separate header files are used because this version is very simple.
