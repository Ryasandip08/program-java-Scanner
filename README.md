import java.util.Scanner;

public class YesNoSelection {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("25, 35, 40, 55, 65, 80");
        System.out.println("pilih nomer");

        System.out.print("please enter your selection (pilih): ");
        String userInput = scanner.nextLine().toLowerCase();


        if (userInput.equals("ganjil")) {
            System.out.println("You selected 'ganjil'.");
        } else if (userInput.equals("ganjil")) {
            System.out.println("You selected 'ganjil'.");
        } else {
            System.out.println("ini bilangan ganjil");
            if (userInput.equals("yes")) {
            System.out.println("You selected 'genap'.");
        } else if (userInput.equals("no")) {
            System.out.println("You selected 'ganjil'.");
        } else {
            System.out.println("ini bukan bilangan genap");

        }
    }
    scanner.close();
}
}
