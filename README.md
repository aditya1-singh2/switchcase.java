# switchcase.java
by Aditya


import java.util.Scanner;
    public static void main(String[] args) {
        // TODO code application logic here
        int choice;
        System.out.println("pick one :1.hi\t2. hey\t3. hello\t");
        Scanner s = new Scanner(System.in);
        choice = s.nextint();
        switch(choice)
        {
            case 1 : System.out.println("you said hi");
                    break;
            case 2 : System.out.println("you said hey");
                    break;
            case 2 : System.out.println("you said hello");
                    break;
            default : System.out.println("invalid choice ");
        }
    }
