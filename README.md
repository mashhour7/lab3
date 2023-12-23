# lab3
README.md# lab3.all.ex 1 and 2 and 3 and 4 and 5
/* name: Mashhour ali a
        /ID:44511289
        /group:144


        */




        
Exercise 1


    public static void main(String[] args) {
        System.out.print("Enter a number between 0 and 1000: ");
        Scanner input = new Scanner(System.in);
        int x = input.nextInt();
        int n1 = x % 10;
        int n2 = (x / 10) % 10;
        int n3 = (x / 100) % 10;
        int n4 = (x / 1000) % 10;
        System.out.println("Sum = " + (n1 + n2 + n3 + n4));
    }
}


exercise 2    |

import java.util.Scanner;

public class lab3 {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.print("Enter the first number: ");
        int x = input.nextInt();

        System.out.print("Enter the second number: ");
        int y = input.nextInt();

        System.out.print("Enter the third number: ");
        int z = input.nextInt();

        int s1 = x * x;
        int q1 = x * x * x;
        int s2 = y * y;
        int q2 = y * y * y;
        int s3 = z * z;
        int q3 = z * z * z;

        System.out.println("Number\tSquare\tCube");
        System.out.println("-----------------------");
        System.out.println(x + "\t|  " + s1 + "\t|  " + q1);
        System.out.println(y + "\t|  " + s2 + "\t|  " + q2);
        System.out.println(z + "\t|  " + s3 + "\t|  " + q3);
    }
}

exxrcise 3  |

 public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.println("[Golden Price Calculator]");
        System.out.println("      ");
        System.out.println("Enter the grams value: ");

        int x = input.nextInt();
        double g = x * 1.61803398875;

        System.out.println("The golden price is: " + g);
    }
}
exercise 4  |


    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.println("[BMI Calculator]");
        System.out.println("----------------");
        System.out.print("Enter your weight in pounds: ");
        double weight = input.nextDouble();

        System.out.print("Enter your height in inches: ");
        double height = input.nextDouble();

        double bmi = (weight * 703) / (height * height);

        System.out.println("Your body mass index (BMI): " + bmi);

        System.out.println("----------------");

        if (bmi < 18.5) {
            System.out.println("Underweight");
        } else if (bmi >= 18.5 && bmi <= 24.9) {

        } else if (bmi >= 25 && bmi <= 29.9) {
            System.out.println("Overweight");
        } else {
            System.out.println("Obese");
        }
    }
}

exercise 5  |


import java.util.Scanner;

public class lab3 {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        // User Input
        System.out.print("Enter total miles driven per day: ");
        double milesDriven = input.nextDouble();

        System.out.print("Enter cost per gallon of gasoline: ");
        double costPerGallon = input.nextDouble();

        System.out.print("Enter average miles per gallon: ");
        double milesPerGallon = input.nextDouble();

        System.out.print("Enter parking fees per day: ");
        double parkingFees = input.nextDouble();

        System.out.print("Enter tolls per day: ");
        double tolls = input.nextDouble();

        // Calculation
        double gallonsUsed = milesDriven / milesPerGallon;
        double totalCost = (gallonsUsed * costPerGallon) + parkingFees + tolls;

        // Display Result
        System.out.println("Total Cost per day: $" + totalCost);
    }
}
