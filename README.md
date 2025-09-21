package restarting_program;

import java.util.Scanner;

/**
 *
 * @author HEMANT
 */
public class RESTARTING_PROGRAM {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        Scanner sc = new Scanner(System.in);
        String fruits;
        String Confirm;
        do
        {
            System.out.println("Enter a fruit : ");
            fruits = sc.nextLine();
          switch(fruits)
          {
              case "banana":
                  System.out.println("You selected banana !! ");
                  break;
                  
                  case "mango":
                  System.out.println("You selected mango !! ");
                  break;
                  
                  case "apple":
                  System.out.println("You selected apple !! ");
                  break;
                  
                  default:
                      System.out.println("Fruit not available : ");
                      break;
                    
                    
                      
                  
                      
          }
          System.out.println("Do you want to continue ? Yes or No");
          
          Confirm = sc.nextLine();
        } while(Confirm.equalsIgnoreCase("yes"));
        
        
    }
    
}
