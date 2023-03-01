# Kdv

     import java.util.Scanner;
     
     public class kdv {
     
    public static void main(String[] args) {
    
        double tutar, kdvOran=0.18, kdvTutar, kdvliTutar;

        Scanner inp = new Scanner(System.in);
         System.out.print("Ucret Tutarı");
         tutar = inp.nextDouble();
         kdvOran = (tutar>0) && (tutar<=1000) ? 0.18 : 0.08;

          kdvTutar= tutar* kdvOran;
          kdvliTutar= tutar + kdvTutar;

        System.out.println(" KDV'siz tutar " + tutar);
         System.out.println(" KDV ORANI " + kdvOran);
        System.out.println(" KDV Tutarı " + kdvTutar);
        System.out.println(" KDV'li Tutar " + kdvliTutar);
        
        
           }
         }




