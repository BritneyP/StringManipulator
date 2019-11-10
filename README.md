# StringManipulator

import java.util.Scanner;

public class StringManipulator {
  public static void main(String[] args) {
    Scanner keyboard = new Scanner(System.in);
    String city;
    System.out.print("Enter your favorite city:");
    city = keyboard.nextLine();
    System.out.println(city.length());
    String upper = city.toUpperCase();
    System.out.println(upper);
    String lower = city.toLowerCase();
    System.out.println(lower);
    city.charAt(0);
    System.out.println(city.charAt(0)); 
    keyboard.close();
    
  }
}
