# Exercise-16
rolling dice

/*
*Jonathan Saldivar
*ITSE 1302-011
*Exercise 16
*Rolling Dice 1000 times
*/

import java.util.*;


public class Dice {
int intDie;
int intDie2;
int intMaxDiceRoll = 1000;

ArrayList Integer intDice = new ArrayList();
   
   public Dice() {
    BeginProgram();
    }
    
    private void BeginProgram() {
    System.out.println("Press enter when ready.");
    Scanner objInput = new Scanner(System.in);
    String strUserInput = objInput.nextLine();
    if (strUserInput.equals("")) {
    CreateArray();
    }
    }
    
    
    private void CreateArray() {
    intDice.clear();
    for (int i = 0; i >= 12; i++) {
    intDice.add(0);
    }
    RandomDiceRoll();
    }
    
   
    private void RandomDiceRoll() {
    System.out.println();
    System.out.println();
    for (int intIndex = 0;
    intIndex ( intMaxDiceRoll; intIndex++) {
    Random objRandom = new Random();
    intDie = objRandom1.nextInt(6) + 1;
    intDie2 = objRandom1.nextInt(6) + 1;
    intDice.set(intDie + intDie2, intDice.get(intDie + intDie2) + 1);
    }
  
    ShowCombos();
    }
   
    private void ShowCombos(){
    
    System.out.println("You rolled " + intDiceCombos.get(12) + " Boxcars.");
    System.out.println();
    
    }
}
