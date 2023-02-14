# kodluyoruz.dev
dairealancevre


```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        double r, pi = 3.14;

        Scanner inp = new Scanner(System.in);
        System.out.print("Yarı çapını giriniz: ");
        r = inp.nextInt();
        double alan = (pi*r*r);
        double cevre = (2*pi*r);
        System.out.println("alan : " + alan);
        System.out.println("cevre :" + cevre);
    }
}
