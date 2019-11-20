# functions

#### Exercise 1:
Write a JavaScript function that returns a passed string with letters in alphabetical order.
Example string: 'Sara'
Expected Output: 'araS':

```

function alphabetOrder(str){
  let reversed = "";    
  for (var i = str.length - 1; i >= 0; i--){        
    reversed += str[i];
  }    
  return reversed;
}

alphabetOrder("hello");
```
---
#### Exercise 2:
Write a JavaScript function that reverse a number.
Sample Data and output:
Example x = 12345;
Expected Output: 54321

function reverseANumber(num) {
  return (
    parseFloat(
      num.toString().split('').reverse().join('')
    ) * Math.sign(num)
  )                 
}

reverseANumber(987654321);
```
---
#### Exercise 3 && 4:
Write a JavaScript function that accepts a number as a parameter and check the number is prime or not.
Note : A prime number (or a prime) is a natural number greater than 1 that has no positive divisors other than 1 and itself.

function testPrime(num){
  var num2 =parseFloat(
      num.toString().split('').reverse().join('')[0]
    ) * Math.sign(num);

  if(num2 % 2===0){
    return "is not prime";
  }
  else{
    return "is prime";
  }
}

testPrime(37);
```
#### Exercise 5:
Write a JavaScript program to pass a 'JavaScript function' as parameter.

```
function addStudent(num, refreshCallback)
{
    refreshCallback();  
}

function refreshStudentList() {
    console.log("Student list refreshed");
}

addStudent(1, refreshStudentList);

```
---
#### Exercise 6:
Write a function that takes the base and height of a triangle and return its area.
Examples
triArea(3, 2) ➞ 3

function triArea(base, height)
{
  return 0.5 * base * height;
}

triArea(3, 2);

---
#### Exercise 7:
Write a function that takes an integer minutes and converts it to seconds.

```
function convert(numMin){
    return numMin*60;
}

convert(2);
```
---

