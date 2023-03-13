# NotOrtalamasiHesaplamaProgrami
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args){
        int mat, fizik, turkce, tarih, muzik, kimya;
        Scanner inp = new Scanner(System.in);
        System.out.print("Matematik notunuz: ");
        mat=inp.nextInt();

        System.out.print("Fizik notunuz: ");
        fizik=inp.nextInt();

        System.out.print("Türkçe notunuz: ");
        turkce= inp.nextInt();

        System.out.print("Tarih notunuz: ");
        tarih=inp.nextInt();

        System.out.print("Müzik notunuz: ");
        muzik=inp.nextInt();

        System.out.print("Kimya notunuz: ");
        kimya=inp.nextInt();

        int toplam = (mat+fizik+turkce+tarih+kimya+muzik);
        double ortalama = toplam/6;

        boolean sonuc = ortalama>60;
        String str = (sonuc)? "Sınıfı Geçti": "Sınıfta Kaldı";

        System.out.println("Ortalamanız: "+ ortalama);
        System.out.println(str);
    }

}
```
