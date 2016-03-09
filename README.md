# Random-Codes-for-Java-programming-First-Semester
import java.util.Scanner;
public class MoreStuffV2 {

	public static void main(String[] args) {
		Scanner input= new Scanner(System.in);

		int i,j,k,l,stars;

		do{
			System.out.print("Enter digit or -1 to exit program: ");
			stars= input.nextInt();
			System.out.println("");


			if(stars%2!=0 && stars<=19){
				for(i=0;i<stars;i++)
				{
					for(j=0;j<=i;j++)
					{

						System.out.print("*");

						if(j<i){
							System.out.print("*");
						}	
					}
					System.out.print("\n");

					if(i+j==stars){
						for(k=stars-2;k>0;k-=2){
							for(l=0;l<k;l++){
								if(l<k){
									System.out.print("*");
								}
								else{
									System.out.print("*");
								}
							}
							System.out.print("\n");
						}
						System.out.println("");
						break;

					}	
				}
			}
			else
				System.out.println("please enter an odd number or a value less than or equal to 19\n");
		}while(stars!=-1);
	}

}

