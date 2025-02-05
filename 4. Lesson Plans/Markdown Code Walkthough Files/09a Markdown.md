# Autonomy Algorithm - Robotics Course

## 1. Planning the Algorithm
When programming, we can use comments just to lay out what we want our code to look like.
```
//some motor variables
//some ultrasonic variables

void setup(){
    //set pin modes
    //start serial monitor
}

void loop(){
    //measure distance

    //if distance is small
        //stop
        //turn around

    //if distance is big
        //drive forwards
}

//some motor functions
```

Then we can start to flesh some things out. We already have all the motor and ultrasonic variables, the pin modes and the distance measuring, so let's flesh out the `if` statements.  

## 2. If Statements  
An if statement allows us to check to see if some logical test is `True` and run specific code depending on the answer.  
  
Here is an example:

```
if (distance < 10){
    //stop
    //pause
    //turn
}
```

The logical test here is to see if the value of `distance` (which is calculated in the ultrasonic code) is less than `10`cm.  
  
We then have an open curly brace `{` which indicates that all the code within the two curly braces `{}` should be executed if the logical test is `True` (i.e. if `distance` is `< 10 cm`)  

## 3. Else Statement  
What if the `if` statement is `false`? We can use the `else` statement for this:
```
if (distance < 10){
    //stop
    //pause
    //turn
}

else{
    //go forwards
}
```
Here we are saying that if `distance` is not `< 10 cm`, we will execute the code in the `else` curly braces `{}`.  
## 4. Your Turn  
Now you go fill in these blanks with your code and make your robot autonomous!!