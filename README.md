# FIBANOCCI-SERIES
// Online Java Compiler
// Use this editor to write, compile and run your Java code online
import java.util.*;
class HelloWorld {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        int m=0;
        int k=1;
        int p=0;
        System.out.print(m);
        System.out.print(" "+k);
        for(int i=1;i<n;i++){
            p=k;
            k=m+p;
            m=p;
            System.out.print(" "+k);
        }
    }
}
