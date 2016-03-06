# Random-Codes-for-Java-programming-First-Semester

import java.util.Scanner;
public class Lab6 {

	public static void main(String[] args) {
		Scanner input = new Scanner (System.in);
		int length=0;
		int width=0;

		System.out.print("Enter the length: ");
		do{ //Keeps looping till correct length is entered / width will always be zero
			length = input.nextInt();
			if(length<=0 || length>20 ){
				System.out.print("Invalid - enter length between 1 and 20: ");
			}
			else{
				System.out.print("Enter the width: ");
				do{ // keeps looping till width is less than or equal 20
					width = input.nextInt();
					
					if(width<=0 || width>20){
						System.out.print("Invalid - enter width between 1 and 20: ");
					}
					else{
						System.out.print("\n\n");
						for(int i = 0 ; i < length ; i++){ //# of rows
							for(int j=0; j < width ;j++){ //# of columns
								System.out.print("*");
							}
							System.out.print("\n");
						}
					}
				}while(width>=20);
			}
		}while(width==0);
	}
}
