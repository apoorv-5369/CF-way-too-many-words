import java.util.*;
import java.io.*;
public class main {
	
	public static void main (String[] args) {
        // Your code here
		Scanner scan1 = new Scanner(System.in);
		int testCases = scan1.nextInt();
		String[] randomWords = new String[testCases+1];
		for(int i=0; i<testCases+1; i++) {
			randomWords[i] = scan1.nextLine();
		}
		for(int i=0; i<testCases+1; i++) {
			if(randomWords[i].length()>10) {
				System.out.print(randomWords[i].charAt(0));
				System.out.print(randomWords[i].length()-2);
				System.out.print(randomWords[i].charAt(randomWords[i].length()-1));
			}else {
				System.out.println(randomWords[i]);
			}
			System.out.println();
		}
	scan1.close();
}
	
}
