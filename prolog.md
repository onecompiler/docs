# Prolog online compiler

Write, Run & Share Prolog code online using OneCompiler’s Prolog online compiler for free. It’s a simple and intuitive platform to experiment with logic programming in Prolog. OneCompiler supports standard Prolog syntax, great for learning, prototyping, and practicing logic-based problems.

# About Prolog

Prolog (Programming in Logic) is a logic programming language associated with artificial intelligence and computational linguistics. It works through facts, rules, and queries, using a form of symbolic reasoning known as backward chaining. Prolog is declarative, meaning you describe *what* you want instead of *how* to compute it.

# Sample Code

The following is a simple Prolog program that prints a greeting:

```prolog
:- initialization(main).

main :-
    write('Hello, World!').
```

# Syntax Basics

## Facts

Facts represent basic assertions about the world.

```prolog
likes(alice, pizza).
likes(bob, pasta).
```

## Rules

Rules define logical relationships using facts.

```prolog
friends(X, Y) :- likes(X, Z), likes(Y, Z).
```

## Queries

Queries are used to find information based on facts and rules.

```prolog
?- likes(alice, What).
```

## Operators

| Operator | Description     |
| -------- | --------------- |
| `:-`     | Rule definition |
| `,`      | Logical AND     |
| `;`      | Logical OR      |
| `=`      | Unification     |

## Lists

```prolog
member(X, [X|_]).
member(X, [_|T]) :- member(X, T).
```

## Recursion

Prolog heavily relies on recursion.

```prolog
factorial(0, 1).
factorial(N, F) :-
  N > 0,
  N1 is N - 1,
  factorial(N1, F1),
  F is N * F1.
```

---

This guide provides a quick reference to Prolog programming syntax and features. Start writing Prolog code using OneCompiler’s Prolog online compiler today!
