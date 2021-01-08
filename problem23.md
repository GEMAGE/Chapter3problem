# Chapter3problem
import java.util.Scanner;

public class JudgePointInCoordinates {
	
	public static void main(String[] args) {
		System.out.println("input (x,y):");
		Scanner input=new Scanner(System.in);
		double x=input.nextDouble();
		double y=input.nextDouble();
		
		if((x>=-5&&x<=5)&&(y>=-2.5&&y<=2.5)) {
			System.out.print("Point ("+x+" "+y+") is in the coordinates");
		}
		else {
			System.out.print("Point ("+x+" "+y+") is not in the coordinates");
		}
		
	}
	
}
