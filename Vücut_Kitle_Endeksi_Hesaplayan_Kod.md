import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
       double kilo , boy , formul ;

       Scanner sc = new Scanner(System.in);
        System.out.println("Lütfen boyunuzu giriniz: ");
        boy = sc.nextDouble();

        System.out.println("Lütfen kilonuzu giriniz: ");
        kilo = sc.nextDouble();

        //Vücut Kitle Endeksini Hesaplayalım
        formul = (kilo) / (boy * boy) ;

        System.out.println("Vücut Kitle Endeksiniz : " + formul );
    }
}
