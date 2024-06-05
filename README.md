# convert-binary-to-decimal
package sampleprogram;
import java.util.Scanner;
public class ConvertBinaryToDecimal {
public static void main(String args[]){
Scanner BinaryInput = new Scanner( System.in );
System.out.print("Enter the Binary Number - ");
String BinaryNumber =BinaryInput.nextLine();
System.out.println("Decimal Number- "+Integer.parseInt(BinaryNumber,2));
}
}
