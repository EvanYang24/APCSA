## Lesson on "if" Statements
# if statements are used to run a method based on if something specifically described happens.
import java.util.Scanner;
Scanner scanner = new Scanner(System.in);

double x;
double y;

System.out.print("Enter the first number: ");

x = scanner.nextDouble();

System.out.println(x);

System.out.print("Enter the second number: ");

y = scanner.nextDouble();

System.out.println(y);

if (x > y) {
  System.out.println(x + " is greater than " + y);
}
# if-else -- if the specific condition is true then proceed below and run the method BUT if the condition is false then proceed with the different set of instructions defined
import java.util.Scanner;
Scanner scanner = new Scanner(System.in);

double x;
double y;

System.out.print("Enter the first number: ");

x = scanner.nextDouble();

System.out.println(x);

System.out.print("Enter the second number: ");

y = scanner.nextDouble();

System.out.println(y);

if (x > y) {
  System.out.println(x + " is greater than " + y);
} else {
    System.out.println(y + " is greater than " + x);
}
# if-elseif-else -- if the specific condition is true then proceed below and run the method BUT if the condition is not met try the next condition and if the condition is met run this code segment now if both of the conditions are false then proceed with the different set of instructions defined
import java.util.Scanner;
Scanner scanner = new Scanner(System.in);

double x;
double y;

System.out.print("Enter the first number: ");

x = scanner.nextDouble();

System.out.println(x);

System.out.print("Enter the second number: ");

y = scanner.nextDouble();

System.out.println(y);

if (x > y) {
  System.out.println(x + " is greater than " + y);
} else if (x == y) {
  System.out.println(x + " is equal to " + y);
}
else {
    System.out.println(y + " is greater than " + x);
}
# Create and if-elseif-elseif-elsif-else statement, 5 or more conditions.
import java.util.Scanner;
Scanner scanner = new Scanner(System.in);

double x;
double y;

System.out.print("Enter the first number: ");

x = scanner.nextDouble();

System.out.println(x);

System.out.print("Enter the operator (+,-,*,/): ");

char operator = scanner.next().charAt(0);

System.out.println(operator);

System.out.print("Enter the second number: ");

y = scanner.nextDouble();

System.out.println(y);

if (operator == '+') {
  System.out.println(x + y);
} else if (operator == '-') {
  System.out.println(x - y);
} else if (operator == '*') {
  System.out.println(x * y);
} else if (operator == '/') {
  System.out.println(x / y);
} else {
  System.out.println("Invalid operator");
}
# Covert the 5 or more decisions to a switch-case-case-case-case-otherwise.
double num1, num2;

// Take input from the user
Scanner scanner = new Scanner(System.in);

System.out.print("Enter the first number: ");

// take the inputs
num1 = scanner.nextDouble();

System.out.println(num1);

System.out.print("Enter the operator (+,-,*,/): ");

char operator = scanner.next().charAt(0);

System.out.println(operator);

System.out.print("Enter second number: ");

num2 = scanner.nextDouble();

System.out.println(num2);

double output = 0;

switch (operator) {

// case to add two numbers
case '+':

    output = num1 + num2;

    break;

// case to subtract two numbers
case '-':

    output = num1 - num2;

    break;

// case to multiply two numbers
case '*':

    output = num1 * num2;

    break;

// case to divide two numbers
case '/':

    output = num1 / num2;

    break;

default:

    System.out.println("Invalid input");

    break;
}

System.out.println("The final result: ");

// print the final result
System.out.println(num1 + " " + operator + " " + num2 + " = " + output);
## De Morgan's Law
# In the 1800s, Augustus De Morgan created the DeMorgan laws. They demonstrate how to handle a complicated conditional negation, which is a conditional statement that has several conditions connected by and (&&), or (||), or (||), such as (x 3) && (y > 2).

# The same as "not a" or "not (a and b)" (not b). This is written as! in Java. (a && b) == ! a || ! b

# The equivalent of not (a or b) is not (a) and (not b). This is written as! in Java. (a || b) == ! a && ! b

# The negation modifies each conditional:

# < becomes >=
# becomes <=

# == becomes !=
# <= becomes >
# = becomes <

# != becomes ==
public class DeMorgansAndTest
{
   public static void main(String[] args)
   {
     int x = 6;
     int y = 3;
     System.out.println(!(x > 6 && y < 3));
     // prints true if x is not > 6 OR y is not < 3
     // prints false otherwise
     // this output should be true as x IS > 6 BUT y IS NOT < 3
   }
}

DeMorgansAndTest.main(null)
public class DeMorgansOrTest
{
   public static void main(String[] args)
   {
     int x = 0;
     int y = 5;
     System.out.println(!(x < 3 || y > 2));
     // prints true if x is not < 3 AND y is not > 2
     // prints false otherwise
     // this output should be false as x IS > 3 AND y IS > 2
   }
}
DeMorgansOrTest.main(null)
