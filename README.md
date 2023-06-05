# Exp5-java
## Aim:
To code a program that produces the table below.
```
Name             Year of joining              Address
Robert                1994               64C- WallsStreat
Sam                   2000               8D- WallsStreat
John                  1999               26B- WallsStreat
```

## Algorithm:
### Step1:
Import the required packages.

### Step2:
Create a method for each employee and print the inputs accordingly.

### Step3:
then display the results.
##Code:
```
import java.util.Scanner;
public class Exp6 {
         static int power(int base, int exponent)
        {
            int power = 1;
             for (int i = 1; i <= exponent; i++)
                 power = power * base;
             return power;
        }
        public static void main(String args[])
        {
            int base, exponent;
            Scanner sc=new Scanner(System.in);
            System.out.print("Enter the base: ");
            base=sc.nextInt();
            System.out.print("Enter the exponent: ");
            exponent=sc.nextInt();

            int pow=power(base, exponent);
             System.out.println(base +" to the power " +exponent + " is: "+pow);
        }
    }

```
## Output:![image](https://github.com/Archana2003-Jkumar/Exp5-java/assets/93427594/bf56284c-a05d-4731-8be9-a9e716cf7910)
## Result:
Hence the program has been successfully executed.
