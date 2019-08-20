# PoliteScript
### The most polite programming language. (Not that we think we are better than anyone else. Sorry if we offended you.)

The goal of the Polite Script project is to gain an understanding of creating a programming language from scratch. No care will be taken for speed of the language. No care will be taken for the developer experience. The only goal is to make a 
language that is excessivley verbose, but also, polite. For example, most developers are familiar with a simple for loop:

```
for(int i = 0; i < 10; i ++) {
  CODE BODY
}
```

In PoliteScript a for loop will look like this (subject to change as language evolves):
```
Please loop 10 times, using i, and start at 0
  CODE BODY
Thanks
```

Another example is simple variable assignment. Again in a typical programming language:

```
int a = 10;
```

In PoliteScript, this looks like:
```
Please set a equal to 10.
```

No parsers or lexers like Yacc or Flex will be employed because where would the fun be in that? (There is also a focus on 
truly understanding the whole process, knowledge, not performance is the goal here) 

### Development Language
Kotlin will be employed in the creation of the PoliteScript parser and lexer. Kotlin was selected due to its ease of
development. It was also selected due to a desire to learn the Kotlin programming language. 
