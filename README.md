# Addition-In-Brainfudge
Addition program written in esoteric language, brainf***

## What language is this?
Formally known as "Brainfuck", the language used to write this program is known as more as a novelty language for programmers looking for a challenge. For sake of avoidance of vulgarity, I will call refer to the language as BF. Though it is turing complete, the language is not at all for practical use.

## How does the language work?
The language only consists of +, -, <, >, [, ] commands to work with which lends itself to the unpractical trait the language possesses. Combine this with an instruction pointer for memory manipulation, this language is very well turing complete.

## What's inside?
I included a scratch sheet of my thought process as I was learning the language as well as implementation notes for my program. This is called development.txt. Obviously, I also included the program itself called addition.bf which holds the raw implementation of the language. 

## Finally, what does the program do?
This program takes three inputs: two numbers and a plus operator in-between them. The program will add these numbers and output the correct sum. If anything other than a plus is given as input, the program will output an "ERROR" string.

## Try it yourself!
There are many interpretors out there for BF however due to a large portability issue of the program due to limited community size, these interpretors include various flavors and dialects of BF. Thus, there is no standard for the language but the code should work with the few browser interpretors out there. A goto for me is https://copy.sh/brainfuck/
