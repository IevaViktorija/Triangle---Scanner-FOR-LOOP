# Triangle---Scanner-FOR-LOOP
enter any number and it will give a result - triangle shape with as many lines as the user entered

```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter the number of lines for the triangle: ");
        int lines = scanner.nextInt();

        for (int i = 1; i <= lines; i++) {
            for (int j = 1; j <= lines - i; j++) {
                System.out.print(" ");
            }
            for (int k = 1; k <= i; k++) {
                System.out.print("_ ");
            }
            System.out.println();
        }
    
      scanner.close();
    }
}

```
