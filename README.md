# ch6

import java.util.Scanner;

public class StringSwap {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        System.out.print("Enter the first string: ");
        String str1 = scanner.nextLine();
        
        System.out.print("Enter the second string: ");
        String str2 = scanner.nextLine();
    
        String temp = str1;
        str1 = str2;
        str2 = temp;
        
        System.out.println( str1);
        System.out.println( str2);
    }
}
