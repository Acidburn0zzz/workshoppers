# Constructs: The Bedrock of Any Software.

There is no software that does not contain a construct, this help shapes the programme or software. It tells the complier or the interpreter of any programme when to perform a certain task, how it performs the task and also how it ends the task. 

## Type of construct
- Conditional Construct.
- Looping Construct.

### Condition construct
- if, else if and else
- switch - case

### Looping construct
- for 
- forEach
- for (in)
- for (as)
- while
- do - while 

The *if* construct is the most used construct and probably the easiest to play around with, making it the most straight forward construct. 

As it's name 
 ```
if
    its a boy 
    then print boy
 else
    print girl.
```

```
if(1 == 1){
    console.log(true)
}else{
    console.log(false)
};
```

The switch - case is quite easy and helps make programmes meet conditions a lot easier other than having excess if and else if clauses all over a programme.

```
switch(variable){
    case 1:
        runs if the variable is equal to 1;
        when variable = 1
            do case 1;
    break;
    case 2:
    runs if the variable is equal to 1;
        when variable = 2
            do case 2;
    break;
    default:
        runs if the variable condition is never met;
        : if the variable is not 1 or 2 
            do default
    break;
}
```

Looping Construct: Are construct that performs a certain action in an iteration state while a condition remains true, until the condition returns false.

### for Loop
```
for(initialization, testing, incrementing||decrementing){
    certainActionToPerform();
}
```

The for-loop function holds 3 parameter, the first which is the **init** : declares the condition that wants to be tested, **test** : checks the initialized condition, **iterate**: either increase the number of times the operation should be performed or reduces the number of time should be performed while the condition in the **test** remains true.

### forEach Loop
```
Array.forEach(element(index){
   certainActionToPerform();
});
```

The forEach is best for test out arrays and sorting out the elements in the Array object. It has callback function that returns the elements of the array. 

### While 
```
while(condition){
    certainActionToPerform();
} or do{
    certainActionToPerform();
}while(condition);
```

While the condition remains true perform a certain command or action... This the most dangerous loop, if the condition never meets false it remains infinite, it either crashes the application when the loops exhaust all the thread in the programme or your laptop if the consume the thread on your RAM.

*elaborate explanation, when you start working with arrays*

*NB:- construct are also functions, predefined and unique functions.*

