## Comparison and logical operators
- === strict equal to
- !== strict not equal to

- < = less than or equal

## for and while loops
- for loop is used when you know the number of iterations the loop needs to make.

for(var i=0; i<=10; i++){
	var answer = 5 * i;
  console.log(answer);
}

- while loop can be used when you need your loop to run an unknown number of times until a specific condition is met

var userInput = 20;
var x = 0;
while(x <= userInput){
	var answer = x * 5;
  console.log(answer);
  x++;
}
