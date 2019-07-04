# QQQQQ
import java.lang.invoke.SwitchPoint;
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {


        Scanner scanner = new Scanner(System.in);
        System.out.println("Введите ваше имя");
        String inputName = scanner.nextLine();
        System.out.println("Привет, " + inputName);

        System.out.println("Введите первое число 'А': ");
        int a = scanner.nextInt();

        System.out.println("Введите второе число 'B': ");
        int b = scanner.nextInt();

        System.out.println("-, +, /, *");
        String action = scanner.next();

        if (action.equals("+")) {
            System.out.println("Сумма чисел = " + (a + b));
        } else if (action.equals("-")) {
            System.out.println(("Разность чисел = ") + (a - b));
            String action1 = scanner.next();
        } else if (action.equals("/")) {
            System.out.println(("Результат деления: ") + (a / b));
            String action1 = scanner.next();
        } else if (action.equals("*")) {
            System.out.println(("Результат умножения: ") + (a * b));


        }
    }
}
