import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Double fiyat , kdvOran = 0.18 , kdvFiyat , kdvliFiyat ;
        Scanner input = new Scanner(System.in);
        System.out.println("Ücret Tutarını Giriniz : ");
        fiyat = input.nextDouble() ;

        kdvFiyat = fiyat * kdvOran ;
        kdvliFiyat = fiyat + kdvFiyat ;

        System.out.println("KDV'siz Tutar : " + fiyat);
        System.out.println("KDV Oranı : " + kdvOran);
        System.out.println("KDV Tutarı : " + kdvFiyat);
        System.out.println("KDV'li Tutar : " + kdvliFiyat);


    }
}
