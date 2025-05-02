# BrainFK online compiler

Write, Run & Share BrainFK code online using OneCompiler’s BrainFK online compiler for free. It’s a lightweight and interactive platform to experiment with the BrainFK programming language, known for its minimalistic and esoteric nature.

# About BrainFK

BrainFK is an esoteric programming language created by Urban Müller in 1993. It is designed to be minimal, with only eight commands and an instruction pointer. Despite its simplicity, it is Turing complete and capable of performing any computation.

# Sample Code

The following BrainFK program prints "Hello, World!":

```brainfuck
++++++++++[>+++++++>++++++++++>+++>+<<<<-]>++.>+.+++++++..+++.>++.<<+++++++++++++++.>.+++.------.--------.>+.>.
```

# Taking inputs (stdin)

OneCompiler’s BrainFK editor supports standard input via the I/O tab. Here's a simple example that echoes the first character typed by the user:

```brainfuck
,.
```

# BrainFK Commands

| Command | Description                                  |
| ------- | -------------------------------------------- |
| `>`     | Move pointer to the right                    |
| `<`     | Move pointer to the left                     |
| `+`     | Increment the byte at the pointer            |
| `-`     | Decrement the byte at the pointer            |
| `.`     | Output the byte at the pointer               |
| `,`     | Input a byte and store it at the pointer     |
| `[`     | Jump past matching `]` if byte is zero       |
| `]`     | Jump back to matching `[` if byte is nonzero |

# Example: Add two numbers (assumes two inputs)

```brainfuck
,>++++++[<-------->-],<[->+<]>.
```

---

This guide provides a quick reference to BrainFK syntax and usage. Start exploring the world of esoteric programming using OneCompiler’s BrainFK online compiler today!
