Download Link: https://assignmentchef.com/product/solved-csis-312-assignment-6-factorial-calculator
<br>
5/5 - (7 votes)

Assignment 6-1It is interesting to watch recursion “in action.” Modify the factorial method in Fig. 18.3 to print its local variable and recursive-call parameter.



For each recursive call, display the outputs on a separate line and add a level of indentation. Do your utmost to make the outputs clear, interesting, and meaningful. Your goal here is to design and implement an output format that makes it easier to understand recursion.

0! = 11! = 12! = 23! = 64! = 245! = 1206! = 7207! = 50408! = 403209! = 36288010! = 362880011! = 3991680012! = 47900160013! = 622702080014! = 8717829120015! = 130767436800016! = 2092278988800017! = 35568742809600018! = 640237370572800019! = 12164510040883200020! = 2432902008176640000

Assignment 6-2Write a recursive method printArray() that displays all the elements in an array of integers, separated by spaces. The array must be 100 elements in size and filled using a for loop and a random number generator. The pseudo-code for this is as follows:

//Instantiate an integer array of size 100//fill the arrayFor (int i=0; i&lt;array.length; i++)Array[i] = random number between 1 and 100 inclusiveprintArray(integer array);For both assignments make sure that your screen shots show your program running and that your runtime display shows that your program does all that is required of it. You only get credit for what you demonstrate.

Submit this assignment by 11:59 p.m. (ET) on Monday of Module/Week 6.

// Fig. 18.3: FactorialCalculator.java// Recursive factorial method.

public class FactorialCalculator{// recursive method factorial (assumes its parameter is = 0public static long factorial(long number){if (number &lt;= 1) // test for base casereturn 1; // base cases: 0! = 1 and 1! = 1else // recursion stepreturn number * factorial(number – 1);}