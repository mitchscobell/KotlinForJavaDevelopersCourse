# Module 2

## From Java to Kotlin

- Java and Kotlin code can be used in the same project
- Gradually add Kotlin to your existing app
- Java Bytecode
- There's a Java to Kotlin converter
  - "Convert Java File to Kotlin file" intellisense in IntelliJ Studio
- No `new` keyword in Kotlin
- You can either convert the whole file or copy and paste it into a kotlin file and it will ask if you want to convert it.

### When operation

- Similar to a Case statement or If with else ifs.

## Introducing Kotlin to an existing project

- Try out in a real life problem
- Take some existing code that you are going to refactor anyway and use the kotlin converter.
- Alternately take a existing function or feature and just do one at a time in both Kotlin and Java
- Start maybe with Unit Tests, write them in Kotlin. Still real life tasks

### Read only variable

- `val`
- compiler error if you try and reassign you'll get an error
- It is mutable if it's an object, it's just a pointer
- Can't update a read only lists so it's fixed. Cant use `.add()`
- Try to use `val` for all new variables by default

### Read/Write variable

- `var`
- Can be reassigned

## Functions

- Return `Unit` is the same as return `void`. It's that by default if it doesn't return anything.
- you can use them in Java was a static function
- you can also call Java in Kotlin

## Named & Default Arguments

- named arguments allows you to add argments in whatever order just by providing the name.
- Example: `listOf('a', 'b', 'c').joinToString(separator = "", prefix = "(", postfix =")"))` prints `(abc)`
- Example: `listOf(1, 2, 3).joinToString(postfix = ".", separator = ""))` prints `1, 2, 3.`
- if you don't provide the named args and pass the wrong types it'll error. It wont implicitly convert.
-
