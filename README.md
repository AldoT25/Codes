Codes
=====
public class Array4
{
  public static void main(String args[])
	{
		int quiz[] = {100, 90, 80, 70, 60};
		int temp[] = new int[7];
		
		System.arraycopy(quiz, 0, temp, 0, quiz.length);
		
		quiz = temp;
		temp = null;
		
		for (int i = 0; i < quiz.length; i++)
		{
			System.out.println("quiz[" + i + "] = " + quiz[i]);
		}
	}
}
=====