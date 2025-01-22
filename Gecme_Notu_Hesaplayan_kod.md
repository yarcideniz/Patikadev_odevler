import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        int mat , fizik , turkce , kimya , muzik ;
        double not , ortalamaNot ;

        Scanner sc = new Scanner(System.in);
        System.out.println("Matematik notunuzu giriniz : ");
        mat = sc.nextInt();

        System.out.println("Fizik notunuzu giriniz : ");
        fizik = sc.nextInt();

        System.out.println("Turkce notunuzu giriniz : ");
        turkce = sc.nextInt();

        System.out.println("Kimya notunuzu giriniz : ");
        kimya = sc.nextInt();

        System.out.println("Muzik notunuzu giriniz : ");
        muzik = sc.nextInt();

        //Ortalama notu hesaplayalım

        ortalamaNot = (mat + fizik + turkce + kimya + muzik) / 5 ;
        System.out.println("Ortalama : " + ortalamaNot);

        if(ortalamaNot >= 55 ){
            System.out.println("Tebrikler! geçtiniz");
        }else {
            System.out.println("Maalesef Kaldınız.");
        }

    }
}
