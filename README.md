# Week 1 
## Week challenges (Tuesday)

### 1. Explanation About Interpreted And Compiled Programming Languages
Computers don't speak English or Spanish, they speak **Machine Code**. Machine code is a computer programming language comprising binary instructins which computers respond to directly, It's written in machine language. Therefore, a machine i.e., a computer, can execute it without any translation or conversion.

So then, How do computers read the code we write in a programming language? 
If we gave computers the text of the logic and instructions we want to execute with a set program, the computer wouldn't have a way to read it and execute it. 
#### Introducing Interpreted and Compiled Programming Languages 
A programming language allows us to translate the abstract `1 & 0's / Binary` into something humans can understand. 

#### Two types of languages 
1. High-Level
Ex: Java, Javascript, Python, C# and many more.

Upside: Easier for us to understand the syntax and write code.

Downside: It takes longer to translate into machine code.

2. Low-Level
Languages that are closer to **Machine Code** therefore easier for the computer to read. 

Benefits Include: They're fast, precise control on how they want the computer to function.

Ex: Machine code, Assembly Language 

We need to get our Source Code converted into Machine code somehow before it can run: 
There are two ways to turn Soruce code into machine code and it's up to the language you're using `Compiled` or `Interpreted` language. 

1. Compiled:
Source Code
Compiler Program : Translates Source Code into Machine Code and makes it an Executable file (Machine Code)
Separate Executable file on Machine Code 
Executable File 


2. Interpreted
Source Code
Interpreter Program (turns it into machiine code on the fly, line by line, on the spot)
Processes on the spot (Not saved as a another file)
Ex: Javascript interpreted into the web browser 



### Compiled                                                
| Pros     | Cons |                                    
| ----------- | ----------- |                               
| **ready** to to run      | **not** cross platform       |     
| often **faster**  | inflexible        | inflexible  |    
| source code is **private**          | extra Step    |          

## Interpreted 
| Pros     | Cons |                                    
| ----------- | ----------- |                               
| cross-Platform     | interpreter required      |     
| simpler to test | inflexible        | often **slower** |    
| easier to debug         | source code is **public**   |         


Compiled: C, C++, Objective-C
Interpreted: PHP, JavaScript
Hybrid: Java, C#, VB.Net, Python 


Intermidiate Approach:
Takes it as far as it can into Machine Code, often Assembly and let's the other party finish the rest.  
JIT: Just in time compilation. 


### 2. Is Java compiled or interpreted, or both?

Java is an Intermidiate Hybrid approach where it's neither compiled or interpreted all at one time, it's done half and half, we compile one part of the way to what's called an intermidiate language **which takes it as far as long to machine code as it can get** while still being portable across platforms, you then distribute the `Intermidiate Language` File sending it to the people who need to run it and each person who runs it takes it to the last step to take it to machine code. JIT Compilation / Bite Code. 


### 3. Pseudocode currency converter
1. START 
2. BTC <--- GET FROM ('https://www.coinbase.com/price/bitcoin')
3. USD <--- GET 
4. BTC2USD <--- BTC * USD
5. Print BTC2USD
6. END

Interpreted vs Compiled Programming Languages: What's the Difference? [^1].
What is Machine code Video [^2].  
Compiler and Interpreter: Compiled Language vs Interpreted Programming Languages[^3].
What is a programming language? [^4].

[^1]: https://www.freecodecamp.org/news/compiled-versus-interpreted-languages/
[^2]: https://www.youtube.com/watch?v=-XU3GbHBOKA&ab_channel=MarketingBusinessNetwork
[^3]: https://www.youtube.com/watch?v=I1f45REi3k4&ab_channel=CodingMentors
[^4]: https://www.youtube.com/watch?v=EGQh5SZctaE&ab_channel=Codecademy
--- 

## Week challenges (Wednesday)
`DOB`: 2002

| 2^10 | 2^11 |  2^10 |  
| -----------| ----------- |   ----------- |     
| 1 | 1 |  