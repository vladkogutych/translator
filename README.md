# translator
The result of this course work is a translator that allows you to translate the input language, which is specified in accordance with the option, into assembly code. The translator performs the following stages of translation: lexical analysis, syntactic analysis and code generation.
Lexical analysis: the input sequence of characters is divided into tokens, which are recorded in the corresponding token table. Each token is assigned a number (numbers are easier to compare than characters). Additional information is also recorded in the token table: the string in which the token is placed; the value if the token type is a number; and so on.
Parsing: uses an ascending parsing method without return. It is intended to build a parse tree by moving sequentially from the leaves upwards to the root of the parse tree.
Code generation: the token table is read again and the corresponding assembly code is generated for each block of tokens. The resulting code is written to the output file and is ready for execution.
The code obtained as a result of translation can be compiled using appropriate programs (LINK, ML, etc.).
