//!1.Write a for loop that prints the numbers from 1 to 5 (inclusive).

ans - for(i = 1; i <= 5; i++){
    console.log(i);
}

//!2.What will be the output of this code?
//!let i = 3;
//!while (i > 0) {
//!  console.log(i);
///!  i--;
//!}

ans - 3 
      2
      1

//!3.Fill in the blanks to complete this do...while loop so it prints 0 1 2:

//!let n = 0;
//!do {
//!  console.log(n);
//!  n++;
//!} while (__________);

ans - while(n<=2)

//!4.True or False:
//!A while loop will always execute its body at least once.
//!Explain your answer.

ans - false, a while loop won't execute its atleast once because it is  pre test loop, it checks the conditon first whether it is true or not and if the condition is true then only it executes the code.

//!5.Rewrite this for loop as a while loop:

//!for (let i = 10; i > 5; i--) {
//!  console.log(i);
//!}

ans - let i = 10;
      while(i>5){
        console.log(i);
        i--;
      }

//!6.What is the output of the following code? Explain why.

//!let x = 5;
//!do {
//!  console.log(x);
//!  x++;
//!} while (x < 5);

ans - The output will be 5 . As we are using do...while loop ,this loop ensures that the code will run once no matter what the condition is. So, the do block is executed first, printing 5. Then the condition is checked , as x++ denotes 6 (that is not less than 5 and hence a false condition) the loop exits .

//!7.Write a for loop that prints all even numbers from 2 to 10 (inclusive).

ans - for(let i = 2; i <= 10; i++ ){
    if(i % 2 == 0){
        console.log(i);
    }
}

//!8.Write a while loop that sums all numbers from 1 to 100 and prints the result.

ans - let i = 1;
      let sum = 0;
      while(i <= 100){
        sum +=  i;
        i++;
      }
      console.log(sum);

//!9.What is the difference between a while loop and a do...while loop? Give an example where this difference is visible.

ans - while loop:
      -> it is a pre-test loop.
      -> it does not execute the loop if the condition is false.
      -> e.g: let i = 5;
              while(i<5){
                console.log(i);
                i++;
              }
        In this case, the loop won't run.
      do...while loop:
      -> it is a post-test loop.
      -> it runs the code atleast once even if the condition is false.
      -> e.g: let i = 5;
              do{
                console.log(i);
                i++;
              }
              while(i<5);
        In this case the loop runs once and prints 5.

//!10.Write a for loop that prints the numbers from 10 down to 1, but stops early if the number is divisible by 4 (use break).

ans - for(let i = 10; i >= 1; i--){
        if(i % 4 == 0){
            console.log(i);
            break;
        }
}