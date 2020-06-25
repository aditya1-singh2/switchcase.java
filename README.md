# switchcase.java
by Aditya


/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package switchcase;

/**
 *
 * @author adity
 */
import java.util.Scanner;
public class Switchcase {

    /**
     * @param args the command line arguments
     */
    
            
    public static void main(String[] args) {
        // TODO code application logic here
        int choice;
        System.out.println("pick one :1.hi\t2. hey\t3. hello\t");
        Scanner s = new Scanner(System.in);
        choice = s.nextInt();
        switch(choice)
        {
            case 1 : System.out.println("you said hi");
                    break;
            case 2 : System.out.println("you said hey");
                    break;
            case 3 : System.out.println("you said hello");
                    break;
            default : System.out.println("invalid choice ");
        }
    }
    
}
