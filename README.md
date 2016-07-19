# OddNumberBetweenRange
import java.util.Scanner;

public class OddNumberBetweenIntegers {

	public static void main(String[] args) {
		Scanner get = new Scanner(System.in);
		System.out.println("Enter range");
		int from = get.nextInt();
		int to = get.nextInt();
		System.out.println("odd numbers  are :");
		for (int i = from; i <= to; i++) {
			if (i % 2 == 1) {
				System.out.print(i + " ");
			}
		}
	}
}
