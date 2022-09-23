# L4_2
Grasshopper - Summation
import java.util.Scanner;

public class Sem4 {
    private static Scanner inn = new Scanner(System.in);

    public static int summation(int n) {
        int s = 0;
        for (int i = 0; i <= n; i++) {
            s += i;
        }

        return s;
    }

    public static <string> void main(String[] args) {
        System.out.println("введите натуральное чиcло");
        int n = inn.nextInt();
        System.out.println(summation(n));
    }
}
