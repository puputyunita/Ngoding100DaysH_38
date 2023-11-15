# Ngoding100DaysH_38
package Ngoding100daysH_38;
import java.util.Scanner;
public class Main {
    
    public static void main(String[] args) {
        Scanner input = new Scanner (System.in);
        System.out.println("hasil");
        
        int jumlah = input.nextInt();
        int total = 100;
        for (int i = 0; i<jumlah; i++ ){
            int kelompok = input.nextInt();
            jumlah += kelompok;
            
            System.out.println(jumlah );
        
        
    }
    
}
}
