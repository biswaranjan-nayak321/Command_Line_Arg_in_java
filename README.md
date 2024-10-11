//Command_Line_Arg_in_java
Profit Loss Program
package CommandlineArgument;

public class ProfitLoss {
	public static void main(String[] args) {
		int cp=Integer.parseInt(args[0]);
		int sp=Integer.parseInt(args[1]);
		System.out.println("profit:"+(sp-cp));
		System.out.println("loss:"+(cp-sp));
		System.out.println("profit:"+(sp-cp));
		int a=(sp-cp)/cp;
		System.out.println("profit percentage:"+(a*100));
		int b=(cp-sp)/cp;
		System.out.println("loss percentage:"+(b*100));
	}
}

