# s-n-f-gecme
import java.util.Scanner;

public class Main {
    public static void main (String []args) {
        int mat,fizik,turkce,kimya,muzik;

        Scanner input=new Scanner(System.in);

        System.out.print("matematik notunuz: ");
        mat= input.nextInt();

        System.out.print("turkce notunuz: ");
        turkce= input.nextInt();

        System.out.print("fizik notunuz: ");
        fizik= input.nextInt();

        System.out.print("kimya notunuz: ");
        kimya= input.nextInt();

        System.out.print("muzık notunuz: ");
        muzik= input.nextInt();

        double avarage =(mat+fizik+kimya+turkce+muzik)/5;
        if ( avarage<=55) {
            System.out.println("sınıfta kaldınız");
        }else {
            System.out.println("tebrikler sınıfı geçtiniz");
            System.out.println("ortalamanız: "+avarage);
        }

        }
    }
