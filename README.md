# THE-USE-OF-ARRAY-OF-OBJECT
JAVA PORGRAM TO DEMONSTRATE THE USE OF ARRAY OF OBJECTS
package check;
import java.util.Scanner;

class over{
	 int rollno;
	 String name;
	 
	 
	 void accept() {
		 Scanner sc =new Scanner(System.in);
		 System.out.println("what is your rollno");
		 rollno=sc.nextInt();
		 System.out.println("what is yourname");
		 name=sc.next();
	 }
	 void display() {
		 System.out.println(rollno+"\t"+name);
		 
	 }
	
	


}

 
public class Main {

	public static void main(String[] args) {
	over[] O=new over[10];
    System.out.println("numbeer of record");
    Scanner sc=new Scanner(System.in);
    int n=sc.nextInt();
    for(int i=0;i<n;i++) {
    	O[i]=new over();
    	O[i].accept();
    	
    }
	 System.out.println("what now ");
	 for(int i=0;i<n;i++) {
	  
	    	O[i].display();
	    	
	    }

}
}
