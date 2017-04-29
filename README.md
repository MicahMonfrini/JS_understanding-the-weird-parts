# JavaScript: Understand the Weird Parts

## JavaScript Vocabulary/Terms:

*Don't be afraid of big words. It's just vocabulary!*

+ **Syntax Parser**
  - *A program that reads your code and determines what it does and if its
  grammar is valid.*
  - Your code isn't magic. Someone else wrote a program to translate it for the
  computer. These programs are commonly known as **compilers** or **translators**.

+ **Lexical Environment**
  - *The physical location of something in your code.*
  - 'Lexical' means 'having to do with words or grammar'. A lexical environment
  exists in programming languages where the location of what you write is important.

+ **Execution Context**
  - *A wrapper to help manage the code that's running.*
  - There a lots of lexical environments. Which one should be running is managed
  by execution contexts. It can contain things beyond what has been written in
  your code.

+ **Name/Value Pair**
  - *A name which maps to a unique value.*
  - The name in question may be defined more than once, but can only have one value
  in any given **execution context**. That value may itself be additional name/value pairs.

+ **Word**
  - *Definition*
  - More Detail

+ **Word**
  - *Definition*
  - More Detail

+ **Word**
  - *Definition*
  - More Detail

+ **Word**
  - *Definition*
  - More Detail

## Conceptual Asides

### Syntax Parsers, Lexical Environments & Execution Contexts

**Syntax Parsers:**

Syntax parsers are programs written to translate your code for the computer. This
takes place in the intermediate step between the time your code is executed and the
actual end result.

**Lexical Environment:**

Where you write certain pieces of your code matters in languages consider lexical
environments important. In these languages, the lexical environment is crucial in
order for the compiler to properly translate your code.

This isn't the case for all programming languages.

**Execution Context:**

Since there are many different lexical environments, an execution context helps
manage which lexical environment is currently running.

### Name/Value Pairs & Objects

A name/value pair is a name that maps to a value. The name in question may be defined
more than once, but can only have one value in any given **execution context**.
That value may itself be additional name/value pairs.

Example:

  ```javascript
  var address = '100 Main St.'
  ```

In this example, the variable `address` is the **name**, and the string `'100 Main St.'`
is the value.
