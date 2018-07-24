# Java-Assignment-Return-Values
Java Assignment on returning values from methods

### Which Number is Largest? 
# Given a main function:
```java
int number1 = 0;
int number2 = 0;

System.out.println(“The largest number is: “ + largestNumber(number1, number2))
```
Create a ```largestNumber``` method that will return the largest number of the 2 passed in

### Matching Password Checker
# Given a main function: 
```java
 Scanner scanInput = new Scanner(System.in);
 String password1, password2= "";

 System.out.print("Enter your new password: ");
 password1 = scanInput.nextLine();

 System.out.print("Enter new password again: ");
 scanInput = new Scanner(System.in);
 password2 = scanInput.nextLine();

  System.out.println("Does passwords match? " + checkPassword(password1, password2));
```
Create a ```checkPassword``` method that will return a boolean value 'true' if the passwordsmatch, otherwise return a boolean value of 'false' 
