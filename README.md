# Week 1 
## Week 1 challenges (Tuesday)

### 1. Explanation About Interpreted And Compiled Programming Languages
Computers don't speak English or Spanish, they speak **Machine Code**. Machine code is a computer programming language comprising binary instructions which computers respond to directly, It's written in machine language. Therefore, a machine i.e., a computer, can execute it without any translation or conversion.

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

Interpreted vs Compiled Programming Languages: What's the Difference? ^1
What is Machine code Video ^2.  
Compiler and Interpreter: Compiled Language vs Interpreted Programming Languages ^3.
What is a programming language? ^4.

1. https://www.freecodecamp.org/news/compiled-versus-interpreted-languages/
2. https://www.youtube.com/watch?v=-XU3GbHBOKA&ab_channel=MarketingBusinessNetwork
3. https://www.youtube.com/watch?v=I1f45REi3k4&ab_channel=CodingMentors
4. https://www.youtube.com/watch?v=EGQh5SZctaE&ab_channel=Codecademy
--- 

## Week 1 challenges (Wednesday)
`DOB`: 2002

* 2^0 = 1 
* 2^1 = 2
* 2^2 = 4
* 2^3 = 8
* 2^4 = 16
* 2^5 = 32
* 2^6 = 64
* 2^7 = 128
* 2^8 = 256
* 2^9 = 512
* 2^10 = 1024
* 2^11 = 2048

|  2^10 |  2^9 |  2^8|  2^7 |  2^6 |  2^5 |  2^4 |  2^3 |  2^2  |  2^1 |  2^0 |    
| -    |   -   |   -  |   -  |  -   |   -  |   -  |   -  |   -  |   -  |   -  |  
| 1    |   1   | 1    | 1    |  1  | 0   |   1  |   0  |   0    |  1  |   0  |  

Anwser= `11111010010`

### Misp Exercises:  


## Week 1 challenges (Thursday)
Feedback on the Videos and Re-search


#### Summary
<a href="https://www.youtube.com/watch?v=Sh6lK57Cuk4&ab_channel=Fireship">The Weird History of Java</a>   

It was really interesting video to watch, gave me a perspective on how javascript has evolved over the las two decades and a half since it's release in Dec '95 Brendon Ike's, being banned by MS in the Internet Explorer, Ecma Standarizing JS, touch on the Tech Bubble of march 2000s, Jquery, sep 8 Chrome V8engine, May 2009 Node Js "Launch Web applications at scale", ES 3.1 == ES5, ES5 introduced (JSON SUPPORT, Functional array and object methods, stric mode, accessors many other), Single Page application frameworks Oct 2010: Backbone & Angular, similar problem different approaches. backbone was light weight Dom updates with imperative programming style, Angular Js more inclusive and use declarative programming, 2015 React Js included angular js with declarative UI but improve them with uni-directional data flow immutability and use of the virtual DOM. The creator of the video is Bullish on javascript, and has learned to always bet on javascript. 

# Week 2
## Week 2 challenges (Monday)
1. Create a Code Wars Account
https://www.codewars.com/users/sbravo15

## Week 2 challenges (Tuesday)
Code Wars Challenges

<a href="https://www.codewars.com/kata/50654ddff44f800200000004/train/javascript">1. Multiply exercise</a>   `DONE`
```
function multiply(a, b){
  return a * b
}
```

<a href="https://www.codewars.com/kata/55ad04714f0b468e8200001c/train/javascript">3. ASCII Total exercise</a>   `DONE`

```
function uniTotal (string) {
  let total = 0; //Variable Total
  for (let i = 0, length = string.length; i<length; i++){
    total += string[i].charCodeAt(); //Suma Charcode al total (Loopea el string y va sumando)
  }
  return total; //Retorna la variable total (Sum of the Chars)
}
```

<a href="https://www.codewars.com/kata/551f37452ff852b7bd000139/train/javascript">4. Char From ASCII Value exercise</a>   `DONE`
```
function getChar(c){
  let char = String.fromCharCode(c);
  return char
}
```

<a href="https://www.codewars.com/kata/551f37452ff852b7bd000139/train/javascript">5. Binary Addition exercise</a>   `DONE`

```
function addBinary(a,b) {
  let sum = a+b;
  let res = sum.toString(2); //to string(2) turns it into a binary number
  return res
}
```

<a href="https://www.codewars.com/kata/5ad0d8356165e63c140014d4/train/javascript">6. Student's Final Grade exercise</a>   `DONE`


```
function finalGrade (exam, projects) {
  // final grade
  if (exam > 90 || projects > 10){
    let grade = 100
    return grade
  } else if (exam > 75 && projects>=5){
    let grade = 90
    return grade
  } else if (exam>50 && projects>=2){
    let grade = 75
    return grade
  } else{
    return 0
  }
}
```


## Week 2 challenges (Wednesday)
Code Wars Challenges


<a href="https://www.codewars.com/kata/57e92e91b63b6cbac20001e5/train/javascript">1. Holiday VIII - Duty Free exercise</a>   `DONE`
```
function dutyFree(normPrice, discount, hol) {
  /* 
    what would be the price of a bottle with the discount?
    normalPrice  --- 100%
    dicountPrice --- discount%
  */
  let dicountPrice = (normPrice * discount) / 100;
  // How many bottles at the discount price will cover the hol cost? 
  let bottlesWithDicountPriceToCoverHoliday = hol / dicountPrice;
  // Please return an integer. Round down. 
  let roundedResult = Math.floor(bottlesWithDicountPriceToCoverHoliday);
  return roundedResult;
}
```

<a href="https://www.codewars.com/kata/5b853229cfde412a470000d0/train/javascript">2. Twice As Old exercise</a>   `DONE` `WH`
```
function twiceAsOld(dadYearsOld, sonYearsOld) {
  return Math.abs(((sonYearsOld*2)-(dadYearsOld)))
}
```

<a href="https://www.codewars.com/kata/5f77d62851f6bc0033616bd8/train/javascript">3. Valid Spacing exercise</a>   `DONE` `WH`
```
function validSpacing(s) {
  
// Verifica espacios vacios al Principio y al final del string  

if (s.charAt(0) === ' ' || s.charAt(s.length - 1) === ' ') { 
     return false;
  }
 
 //Loopea el string : Si el char es espacio vacio y le suma un espacio y el otro es vacio == False 
 
  for (let i = 0; i < s.length; i++) {
    if(s.charAt(i) === ' '){ // es el caracter que estamos viendo igual a un espacio?
      if(i != 0 && s.charAt(i-1) === ' ') {
        return false;
      }
      if (i != (s.length - 1) && s.charAt(i+1) === ' ') {
        return false;
      }
    }
    // ....
  }
  
  return true; // fuera la verificacion
}
 
```

<a href="https://www.codewars.com/kata/57eae65a4321032ce000002d/train/javascript">4. Fake Binary exercise</a>   `DONE` `WH`
```
function fakeBin(x){
  let resultDigits = "";
  for (let i=0; i< x.length; i++){
    if(parseInt(x[i]) < 5){
       resultDigits = resultDigits +"0";
       }else {
         resultDigits = resultDigits + "1"; 
       }
  }
  return resultDigits; 
}  
```






## Week 2 challenges (Thursday)
Code Wars Challenges


<a href="https://www.codewars.com/kata/57faece99610ced690000165/train/javascript">1. Remove All Exclamation Marks From The End Of Sentence exercise</a>   `n/a`


<a href="https://www.codewars.com/kata/5547929140907378f9000039/train/javascript">2. Vowel Remover exercise</a>   `DONE`
```
function remove (string) {  
  //Implementation (regex)
 return string.replace(/!+$/, "");
 
```


<a href="https://www.codewars.com/kata/5672a98bdbdd995fad00000f/train/javascript">3. Rock Paper Scissors! exercise</a>   `DONE`
```
const rps = (p1, p2) => { 
  //rock & rock // p & p // s & s 
  // rock < paper // paper < scissor //scissor < rock // 
  
if (p1 === "rock" && p2 === "scissors"){
  return "Player 1 won!";
}else if(p2 ==="rock" && p1 === "scissors"){
  return "Player 2 won!";
}else if(p1 === "paper" && p2 === "scissors"){
    return "Player 2 won!";
}else if(p2 === "paper" && p1 === "scissors"){
    return "Player 1 won!";
}else if( p1 === "rock" && p2 === "paper"){
    return "Player 2 won!";
}else if( p1 === "paper" && p2 === "rock"){
    return "Player 1 won!";
}else{
  return "Draw!"; 
}
};
```
<a href="https://www.codewars.com/kata/55bf01e5a717a0d57e0000ec/train/javascript">4. Persistent Bugger exercise</a>   `n/a`



# Week 3
## Week 3 challenges (Monday)
Code Wars Challenges

<a href="/corecodeio/devguide-from-scratch-2022-02/blob/main/src/technologies/2022/week03/exercises/e00/desc">1. Who Likes It?</a>   `n/a`


<a href="/corecodeio/devguide-from-scratch-2022-02/blob/main/src/technologies/2022/week03/exercises/e01/desc">2. Bit Counting</a>    `n/a`   


<a href="/corecodeio/devguide-from-scratch-2022-02/blob/main/src/technologies/2022/week03/exercises/e02/desc">3. Your Order, Please</a>    `n/a`   


## Week 3 challenges (Tuesday)
Code Wars Challenges

<a href="/corecodeio/devguide-from-scratch-2022-02/blob/main/src/technologies/2022/week03/exercises/e03/desc">1. Simple Pig Latin</a>.   `n/a`


<a href="/corecodeio/devguide-from-scratch-2022-02/blob/main/src/technologies/2022/week03/exercises/e04/desc">2. Counting Duplicates</a>    `n/a`


<a href="/corecodeio/devguide-from-scratch-2022-02/blob/main/src/technologies/2022/week03/exercises/e05/desc">3. Decode The Morse Code</a>    `n/a`


## Week 3 challenges (Wednesday)
Code Wars Challenges

<a href="/corecodeio/devguide-from-scratch-2022-02/blob/main/src/technologies/2022/week03/exercises/e06/desc">1. Valid Parentheses</a>    `n/a`

<a href="/corecodeio/devguide-from-scratch-2022-02/blob/main/src/technologies/2022/week03/exercises/e07/desc">2. Convert String To Camel Case</a>    `n/a`

<a href="/corecodeio/devguide-from-scratch-2022-02/blob/main/src/technologies/2022/week03/exercises/e08/desc">3. Unique In Order</a>    `n/a`


## Week 3 challenges (Thursday)
Code Wars Challenges

<a href="/corecodeio/devguide-from-scratch-2022-02/blob/main/src/technologies/2022/week03/exercises/e09/desc">1. Fold An Array</a>    `n/a`


<a href="/corecodeio/devguide-from-scratch-2022-02/blob/main/src/technologies/2022/week03/exercises/e10/desc">2. Encrypt This!</a>    `n/a`



3. ✨Complete your 1st Core Challenge. This is one of the requirements for the certification, where you'll boost your dev professional-brand. `n/a`


