Lesson 2

String Properties
- How do we tell the difference between a method and a property?<br> 
    - the presence of (); length is a property that is also a function
- Does that distinction matter?
    - It doesn't matter.

Leading and Trailing Spaces
- What is meant by "multiple breakups"?
    - This was a comment meant for the notebook's editor regarding whether or not the blocks of code in the example should be separated or not.

Part 3

Playground
- Is there a way to evaluate more than expression at a time (e.g. when we use the && operator in JS)?
    - You can still evaluate more than one expression at a time with the && operation
- Is there is a way to use the .Contains method to search multiple lines at a time?
    - Yes, but you would still have to type .Contains and its parameter multiple times, they just wouldn'y be broken up by lines

Part 4 

Playground
- How are integers rounded?
    - I would have expected them to round down if the number immediately following the decimal point is less than 5 and round up if not. However, the above expression rounded down, and the below expression rounded up, so the opposite seems to be true.

Part 5

Doubles: Precision and Size
- What does "floating point" mean?
    - means it's a decimal # 
- What do they mean by doubles being able to "hold"?
    - does not round up or down, it "holds" the current value (ie the number stays the same)

Part 6

Working with Fixed Point Types
- What is meant by "fixed point types"?
    - means the result will be more precise

Playground 
- Why am I getting this error message when I try to use the integer or decimal type: "Cannot implicitly convert type 'double' to 'int'. An explicit conversion exists (are you missing a cast?)"?   
    - Math.PI holds a value that is a double type, so its result can't be assigned to a different number type; you'd have to convert it to that specific number type first for the expression to work
    
- What is a short number type?
    - uses 16 bits instead of 32 bits

Part 7 

- What is meant by "branches"?
    - another name for conditionals

Playground
- What is meant by "draw out the flow of an if statement"?
    - Best guess is that I'm meant to demonstrate the process of an if statement

1 bite = 8 bits