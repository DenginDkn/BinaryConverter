import java.util.Scanner;

// Binary Converter JAVA Language
// I hope it will useful for you :)

class Converter{
    public static String toBinary(int x){
        String binary="";
        while(x > 0) {
            binary = (x%2)+binary;
            x /= 2;
        }
        return binary;
    }

}


public class Main {
    public static void main(String[ ] args) {
        Scanner sc = new Scanner(System.in);
        int x = sc.nextInt();
        System.out.print(Converter.toBinary(x));
    }
}
