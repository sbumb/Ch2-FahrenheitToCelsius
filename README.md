# Ch2-FahrenheitToCelsius
Intro to Java Programming, Comprehensive Version, 10th Edition, Y. Daniel Liang

Question

        Input degrees in Fahrenheit, output degrees that the user put in as well as degrees 
        celsius using the formula:
        celsius = (5/9)*(fahrenheit - 32)
        
Code

    import java.util.Scanner;

    public class FahrenheitToCelcius {

      public static void main (String args[]){

        Scanner sc = new Scanner(System.in);

        System.out.println("Please enter degrees Fahrenheit: ");
        double fahrenheit = sc.nextDouble();

        double celsius = (5.0/9)*(fahrenheit - 32);

        System.out.printf(fahrenheit + " degrees F = " + celsius + " degrees C.");

      }
    }
