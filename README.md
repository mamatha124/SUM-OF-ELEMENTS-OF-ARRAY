# SUM-OF-ELEMENTS-OF-ARRAY 
import java.util.*;
class HelloWorld {
    public static void main(String[] args) {
        int a[];
        int sum=0;
        a=new int[100];
        Scanner sc= new Scanner(System.in);
        int n=sc.nextInt();
        for(int i=0;i<n;i++){
            int k=sc.nextInt();
            a[i]=k;
            sum=sum+k;
        }
        System.out.println("Sum of Elements of  array:"+sum);
    
    }
}
