# hypotenus
A code that calculates hypotenus
package patikaAcademy;

import java.util.Scanner;

public class hipotenüs {

	public static void main(String[] args) {
		Scanner input = new Scanner(System.in);
		
		System.out.println("Üçgenin bir kenarını giriniz:");
        double a = input.nextInt();
        		
        System.out.println("Üçgenin diğer kenarını giriniz:");
        double b = input.nextInt();
        
        
        // Math.sqrt () karesini almak için kullanılır. 
        double c; 
        c = Math.sqrt((a*a)+(b*b));
        
        System.out.println("Hipotenüs:" + c );
	}

}
