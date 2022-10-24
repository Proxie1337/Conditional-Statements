import java.util.Scanner;//import java class Scanner from library

public class Con6 {
	
	//Declare the Scanner object
	static Scanner input = new Scanner(System.in);
	
	public static void main (String [] args) {
		menu();//Execute the menu method
	}
	
	public static void menu() {
		//Print out to user asking for input
		System.out.println("Please choose an option");
		System.out.println("1) Say Hello\t2) Say Goodbye");
		
		//Take in their decision
		int decision = input.nextInt();
		
		//Call methods based on user decision using switch statement
		switch(decision) {
			case 1:
				sayHello();
				break;
			case 2:
				sayGoodbye();
				break;
			default:
				System.out.println("\nYou chose an invalid option. Please try again\n");
				menu();
		}
		//Call the method again to loop it over and over.
		menu();	
	}
	
	//Method for saying hello
	public static void sayHello() {
		System.out.println("Hello!\n");
	}
	
	//Method for saying goodbye
	public static void sayGoodbye() {
		System.out.println("Goodbye!\n");
	}
}
