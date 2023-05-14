/*  You have given an integer n , you have to print first n numbers of the fibonacci series till n.

"Sample Input"                  "Sample Output"
10                              0 1 1 2 3 5 8 13 21 34       
*/

 

import java.util.*;
import java.io.*;

public class Main {
    public static void main(String[] args) {
 Scanner asd = new Scanner (System.in);
   int n = asd.nextInt();
       int a = 1, b = 0;
            
            for (int i = 1; i<=n; i++){
                    int c = a+b;
                    a = b;
                    b = c;
                    System.out.print(a+" ");
            }
    }
}
