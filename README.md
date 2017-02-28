# Bottles-on-the-wall
A program to count down the bottles
public class Bottles{

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int i = 99;
		int p = 100;
		while(i >= 0){
			System.out.println( p + " bottles of milk on the wall take one down and pass it around, how many bottles of milk on the wall? " + i);
			i = i - 1;
			p = p - 1;
		}
	}

}
