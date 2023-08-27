# Puzzle Solver Program: `puzzle.py`

**Description:**
`puzzle.py` is a Python program designed to solve logic puzzles known as "Knights and Knaves" puzzles. These puzzles involve characters who can either be knights, who always tell the truth, or knaves, who always lie. The program represents these puzzles using propositional logic and employs a model-checking algorithm to determine the true identities of the characters.

**Background:**
In 1978, logician Raymond Smullyan introduced "Knights and Knaves" puzzles in his book "What is the name of this book?". These puzzles challenge players to deduce the identities of characters based on statements they make, with the consideration that knights always tell the truth and knaves always lie.

**License:**
This program is provided under the MIT license. Feel free to use, modify, and distribute the code in accordance with the terms of the MIT license.

**Usage:**
1. Ensure you have Python installed on your system.
2. Open a terminal window and navigate to the directory containing `puzzle.py`.
3. Run the program by executing the command: `python puzzle.py`.

**Puzzles:**
The program comes with pre-defined "Knights and Knaves" puzzles, each represented using propositional logic.

- **Puzzle 0:**
  - A says "I am both a knight and a knave."

- **Puzzle 1:**
  - A says "We are both knaves."
  - B says nothing.

- **Puzzle 2:**
  - A says "We are the same kind."
  - B says "We are of different kinds."

- **Puzzle 3:**
  - A says either "I am a knight." or "I am a knave," but you don't know which.
  - B says "A said 'I am a knave'."
  - B says "C is a knave."
  - C says "A is a knight."

**Implementation:**
The program employs a set of logical symbols (`AKnight`, `AKnave`, `BKnight`, `BKnave`, `CKnight`, and `CKnave`) to represent the identities of characters. It uses propositional logic to represent the statements made by characters and employs a model-checking algorithm to determine the true identities of the characters.

**Execution:**
The program will display the solutions for each puzzle. If the knowledge base for a particular puzzle is not yet implemented, it will indicate so. Otherwise, it will determine and display the identities of the characters based on the model-checking results.

**Note:**
This program was developed as part of the CS50 AI Week 1 curriculum.

For any questions or assistance, please contact me.

---
*This program is provided as-is, and no warranties or guarantees are provided for its accuracy or suitability for any purpose.*
