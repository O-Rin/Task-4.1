# git_tutorial
# Task-4.1

public class task4 {
	public static void main(String[] args) {


	        System.out.println("What your name?");

	       String name = new java.util.Scanner(System.in).nextLine();

	        System.out.println("Hello " + name + "!");

	        System.out.println("Rolling the dice...");

	        int val1 = new java.util.Random().nextInt(6)+1;
	        System.out.println("Die 1   " +val1);

	        int val2 = new java.util.Random().nextInt(6)+1;
	        System.out.println("Die 2   " +val2);

	        int sum;

	        sum = val1 + val2;

	        if(sum < 7) {
	            System.out.println(name +"lose");
	        }

	        if(sum >= 7) {
	            System.out.println(name +"Won!");
	        }

    }
}
