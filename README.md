# A Chicken Ship Adventure!
### IT Studio 1 - Educational Game
#### Vyomaa, Arha & Vince

Successfully navigate the waters of this Java coding multi-choice challenge and safely reach the beans!  
... chickens may be involved.

The site features:  
1. Welcome/Landing Page that introduces the concept & how-to-guide for the user
2. A series of four challenges the user must pass in order to successfully complete the voyage
3. Correct & incorrect pages depending on how the user responds to the challenges
4. A successful game complete screen

This is the link for the game: 
https://vyomaa03.github.io/IT-Studio/

 Just going to add my answers here so i can work with them - vyomaa
 
 Answer 1:
 System.out.printf("Volume: %.1f cubic inches\n", cVol);
 System.out.printf("Surface area: %.1f square inches\n", cArea);

 Answer for Challenge 2:
import java.util.Scanner; 

public class MinCostChange {
   public static void main(String[] args) {
      Scanner scnr = new Scanner(System.in);
      
      int cents = scnr.nextInt();

      int dollars = (cents / 100) % 100;
      int quarters = (cents % 100) / 25;
     
      if (cents == 0) {
         System.out.println("No change");
      }
     
      if (dollars < 2 && dollars == 1) {
         System.out.println(dollars + " Dollar");
      }
      
      else if (dollars >= 2) {
          System.out.println(dollars + " Dollars");
      }
      else {
          System.out.println("Not enough dollars!!");
      }
     
      if (quarters < 2 && quarters == 1) {
          System.out.println(quarters + " Quarter");
      }
      
      else if (quarters >= 2) {
          System.out.println(quarters + " Quarters");
      }
      else {
          System.out.println("You got enough cash!");
      }
   }
}
Answer for Challenge 3:
*******x

Answer for Challenge 4:
Challenge4 - C
4A - A
4C - C
4D - B