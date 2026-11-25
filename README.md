This repository describes a personal method and format for reading code. When reading code with this approach and comparing it against the source code, comprehension becomes much faster. Its main features are:
1. Express everything in Chinese except for fixed terminology. For example, import random → 导入random; for key in conversation: → 对conversation中的key进行循环.
2. Write a pair of parentheses next to each original variable, indicating what that variable means.For example, chunk (被turns划分出的文本块，用于xxx), turns (把所有turn合成一个大内容，用于xxx).
3. Translate any English sentences that carry real meaning (prompts or comments) into Chinese.
4. For parts involving overall architecture or principles, set aside a dedicated comment block explaining what the function is and how it is used, and include an example within the comment area to show the details concretely.
5. For some key functions, reflect on the designer's ingenuity. Do not analyze every function this way—only do so for places that are genuinely elegant or unusual and that constitute the main thread of logic for the file or even the whole folder/project.
