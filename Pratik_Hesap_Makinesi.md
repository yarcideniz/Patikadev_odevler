import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        int numberOne , numberTwo , select;

        Scanner input = new Scanner(System.in);
        System.out.println("İlk sayıyı giriniz : ");
        numberOne = input.nextInt();

        System.out.println("İkinci sayıyı giriniz : ");
        numberTwo = input.nextInt();

        System.out.println("1-Toplama \n 2-Çıkarma \n 3-Çarpma \n 4-Bölme");

        System.out.println("Seçiminiz nedir : ");
        select = input.nextInt();

        System.out.println(select);

        switch (select) {
            case 1:
                System.out.println("Toplama : " + (numberOne + numberTwo));
                break;
            case 2:
                System.out.println("Çıkarma : " + (numberOne - numberTwo));
                break;
            case 3:
                System.out.println("Çarpma : " + (numberOne * numberTwo));
                break;
            case 4:
                System.out.println("Bölme : " + (numberOne / numberTwo));
                break;
                default:
                    System.out.println("Hatalı giriş yaptınız");


        }
        System.out.println("Sonuç");

    }
}
