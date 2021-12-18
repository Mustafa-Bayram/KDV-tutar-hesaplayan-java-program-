import java.util.Scanner;

public class Main {

    public static void main(String[] args) {

double tutar,kdvOrani;
        Scanner input = new Scanner(System.in);
        System.out.print("Ücret tutarını giriniz : " );
        tutar = input.nextDouble();

        boolean kdv = tutar > 1000;
        kdvOrani = kdv ? 0.08 : 0.18;

        double kdvTutari = tutar * kdvOrani;
        double kdvliTutari = tutar * kdvOrani;


        System.out.println("KDV'li tutarı : " + kdvTutari );
        System.out.println("KDV'siz Tutarı :" + (tutar));
        System.out.println("KDV Tutarı : " + kdvTutari);



    }
}
