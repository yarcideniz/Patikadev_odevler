import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Double fiyat, kdvOran, kdvFiyat, kdvliFiyat;
        Scanner input = new Scanner(System.in);

        System.out.println("Ücret Tutarını Giriniz: ");
        fiyat = input.nextDouble();

        // KDV oranını belirleyelim
        kdvOran = (fiyat < 1000) ? 0.18 : 0.08; // KDV oranı, fiyat 1000'den küçükse %18, küçük değilse %8

        // KDV hesaplamaları
        kdvFiyat = fiyat * kdvOran;
        kdvliFiyat = fiyat + kdvFiyat;

        // Sonuçları yazdırma
        System.out.println("KDV'siz Tutar: " + fiyat);
        System.out.println("KDV Oranı: " + kdvOran);
        System.out.println("KDV Tutarı: " + kdvFiyat);
        System.out.println("KDV'li Tutar: " + kdvliFiyat);
  }
}
