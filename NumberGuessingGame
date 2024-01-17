package javaApplication;

import java.util.Scanner;

public class number_guessing_game {
	public static void main(String[] args) {
	int guess_num=(int)(Math.random() * 100) + 1;
	int chance=5;
	Scanner s=new Scanner(System.in);
	int guess,i;
	System.out.println("Welcome to Number Guessing Game:");
	System.out.println("Guess a number batween 1 to 100:");
	for (i = 0; i < chance; i++) {
		 
        System.out.println(
            "Guess the number:");

        // Take input for guessing
        guess = s.nextInt();

        // If the number is guessed
        if (guess_num == guess) {
            System.out.println(
                "Congratulations!"
                + " You guessed the number.");
        }
        else if (guess_num > guess
                 && i != chance - 1) {
            System.out.println(
                "The number is "
                + "greater than " + guess);
        }
        else if (guess_num < guess
                 && i != chance - 1) {
            System.out.println(
                "The number is"
                + " less than " + guess);
        }
    }
	if (i == chance) {
        System.out.println(
            "You have completed with your"
            +(chance)+ " trials.");

        System.out.println(
            "The number was " + guess_num);
    }

    
}
	
}
