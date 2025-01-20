import java.util.Scanner ;

public class Main {
    public static void main(String[] args) {
        int a , b , c ;

        Scanner sc = new Scanner(System.in);
        System.out.println("1.Sayıyı giriniz : ");
        a = sc.nextInt();

        System.out.println("2.Sayıyı giriniz : ");
        b = sc.nextInt();

        System.out.println("3.Sayısı giriniz : ");
        c = sc.nextInt();

        //Koşullu ifadeleri yazıyoruz

        if((a < b) && (a < c)) {
            if(b < c){
                System.out.println("a < b < c");
            }
            if(c < b){
                System.out.println("a < c < b");
            }
        }
        if((b < a) && (b < c)) {
            if(a < c){
                System.out.println("b < a < c");
            }
            if (c < a){
                System.out.println("b < c < a");
            }

        }
        if((c < a) && (c < b)) {
            if(a < b){
                System.out.println("c < a < b");
            }else
                System.out.println("c < b < a");
        }


    }
}
