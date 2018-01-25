# TirePressure2
import java.util.Scanner;
public class Program {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int FrontLeft;
		int FrontRight;
		int RearLeft;
		int RearRight;
		
		Scanner sc = new Scanner(System.in);
		
		System.out.println("What is your front right tire pressure?");
		
		FrontRight = sc.nextInt();
		
		System.out.println("What is your back right tire pressure?");
		
		RearRight = sc.nextInt();
		
		System.out.println("What is your front left tire pressure?");
		
		FrontLeft = sc.nextInt();
		
		System.out.println("What is your back left tire pressure?");
		
		RearLeft = sc.nextInt();
		
		if(FrontRight < 25) {
			System.out.println("TIRE LOW");
		}
		else if(RearRight < 25) {
			System.out.println("TIRE LOW");
		}
		else if(FrontLeft< 25) { 
			System.out.println("TIRE LOW");
		}
		else if(RearLeft < 25) {
			System.out.println("TIRE LOW");
		}
		
	}

}
