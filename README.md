# Complier-time-polymorphism-
package main;
public class Main {
 public int addition(int x, int y) {
    return x + y;
  }
  // method to add three integers
  public int addition(int x, int y, int z) {
    return x + y + z;
  }
  // method to add two doubles
  public double addition(double x, double y) {
    return x + y;
  }
  public static void main(String[] args) {
    // Creating an object of the Main method
    Main number = new Main():
    // calling the overloaded methods
    int res1 = number.addition(444, 555);
    System.out.println("Addition of two integers: " + res1);
    int res2 = number.addition(333, 444, 555);
    System.out.println("Addition of three integers: " + res2);
    double res3 = number.addition(10.15, 20.22);
    System.out.println("Addition of two doubles: " + res3);
  }
}

output:
Addition of two integers: 999
Addition of three integers: 1332
Addition of two doubles: 30.369999999999997
BUILD SUCCESSFUL (total time: 0 seconds)

Addition of two integers: 933
Addition of three integers: 1983
Addition of two doubles: 21.5
BUILD SUCCESSFUL (total time: 0 seconds)


