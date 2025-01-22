import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        int yil ;

        //Yıl girdisi isteyelim
        Scanner sc = new Scanner(System.in);
        System.out.println("Lütfen yıl giriniz : ");
        yil = sc.nextInt();

        if(yil % 4 == 0 && yil % 400 == 0 ){
            System.out.println("Bir artık yıldır.");
        }else {
            System.out.println("Artık yıl değildir.");
        }
    }
}
