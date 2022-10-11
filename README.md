# Basic-Java-programs
Basic Java programs
import java.util.*;

import javax.swing.plaf.synth.SynthStyle;
//rectangle pattern
/*public class patterns{
    public static void main(String args[]){
        Scanner sc = new Scanner(System.in);
        System.out.println("no. of rows");
        int m = sc.nextInt();
        System.out.println("no. of columns");
        int n = sc.nextInt();
        //rows
        for(int i=1; i<=m; i++ ){
            //columns   
            for(int j=1; j<=n; j++){
                System.out.print("*");
            }
            System.out.println();

        } 
    }
}*/

//hollow rectangle
/*public class patterns{
    public static void main(String args[]){
    Scanner sc = new Scanner(System.in);
    System.out.println("write no of rows you want");
    int m = sc.nextInt();
    System.out.println("write no. of columns you want ");
    int n = sc.nextInt();
    for(int i=1; i<=m; i++){
        for(int j=1; j<=n; j++){
            if(i==1 || j==1 || i==m || j==n ){
                System.out.print("*");
            }else{
                System.out.print(" ");
            }
        } System.out.println();
    }
    }
} */

//half pyramid
/*public class patterns{
    public static void main(String agrs[]){
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        for(int i=1; i<=n; i++){
            for(int j=1; j<=i; j++){
                System.out.print("*");
            }
            System.out.println();
        }
    }
}

*/


//print
//****
//***
//** 
//*

/*public class patterns{
    public static void main(String args[]){
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        for(int i=n; i>=1; i--){
            for(int j=1; j<=i; j++ ){
                System.out.print("*");
            } System.out.println();
        }
    }
}
*/

//    *
//   **
//  ***
// ****
//***** 

/*public class patterns{
    public static void main(String [] args){
    Scanner sc = new Scanner(System.in);
    int n = sc.nextInt();
    //outer loop
    for(int i=1; i<=n ; i++){
       //inner loop-> space
        for(int j=1; j<=n-1; j++){
            System.out.print(" ");
        }
        for(int j=i; j<=n; j++){
            System.out.print("*");
        }
        System.out.println();
    } 
    }
}*/

//half pyramid with numbers
/*public class patterns{
    public static void main(String args[]){
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
    //outer loop
    for(int r=1; r<=n; r++){
        //inner loop
        for(int c=1; c<=r; c++){
            System.out.print(c+" ");
        }
        System.out.println();
    }
    }
}*/

/* 
//inverse half pyramid with no 
public class patterns{
    public static void main(String args[]){
        Scanner sc= new Scanner(System.in);
        System.out.println("write a no.");
        int n = sc.nextInt();
        for(int i=1; i<=n; i++){
            for(int j=1; j<=n-i+1; j++){
                System.out.print(j+" ");
            } 
            System.out.println();
        }
          
    }
}
*/

//floyd's triangle
/* 
public class patterns{
    public static void main(String args[]){
        Scanner sc= new Scanner(System.in);
        System.out.println("write a no.");
        int n = sc.nextInt(); 
        int m =1;
        for(int i=1; i<=n; i++){
            for(int j=1; j<=i; j++){
                System.out.print(m+ " ");
                m++;
            }
            System.out.println();
        }

    }
}
*/

//0-1 triangle
/*
public class patterns{
    public static void main(String args[]){
        Scanner sc= new Scanner(System.in);
        System.out.println("write a no.");
        int n = sc.nextInt(); 
        for(int i=1; i<=n; i++){
            for(int j=1; j<=i; j++){
                int sum=i+j;
                if(sum%2==0){
                    System.out.print("1 ");
                }else{
                    System.out.print("0 ");
                }
            } System.out.println();
        }
    }
}
*/

//butterfly pattern
/* 
public class patterns{
    public static void main(String args[]){
        Scanner sc = new Scanner(System.in);
        System.out.println("write a no. for n");
        int n = sc.nextInt();
        //upper half
        for(int i=1; i<=n; i++){
            //1st part
            for(int j=1; j<=i; j++){
                System.out.print("*");
            }
            //spaces
            int spaces = 2 * (n-i);
            for(int j=1; j<=spaces; j++){
                System.out.print(" ");
            }
           //2nd part
           for(int j=1; j<=i; j++){
            System.out.print("*");
           }
           System.out.println();

        }

         //lower half
         for(int i=n; i>=1; i--){
            //1st part
            for(int j=1; j<=i; j++){
                System.out.print("*");
            }
            //spaces
            int spaces = 2 * (n-i);
            for(int j=1; j<=spaces; j++){
                System.out.print(" ");
            }
           //2nd part
           for(int j=1; j<=i; j++){
            System.out.print("*");
           }
           System.out.println();
        }
        }

    }
*/

/* 
//solid rhombus
public class patterns{
    public static void main(String args[]){
        Scanner sc = new Scanner(System.in);
        System.out.println("no. of rows you want");
        int n =sc.nextInt();
        //rows
        for(int i=1; i<=n; i++){
            //spaces
            for(int j=1; j<=n-i; j++){
                System.out.print(" ");
            }
            //stars
            for(int j=1; j<=n; j++){
                System.out.print("* ");
            }
            System.out.println();
        }
    }
}
*/

/* 
//number pyramid
public class patterns{
    public static void main(String args[]){
        Scanner scanner= new Scanner(System.in);
        System.out.println("write no. of row you want:");
        int n = scanner.nextInt();
        for(int i =1; i<=n; i++){
            //spaces
            int spaces= n-i;
            for(int j=1; j<=spaces; j++){
                System.out.print(" ");
            }
            //numbers
            for(int j=1; j<=i; j++){
                System.out.print(i + " ");
            }
            System.out.println();
        }

    }
}
*/

//palindromic pyramid pattern(jise aage or piche se dekhne m same lge ex bob,121,343 etc)
/* 
public class patterns{
    public static void main(String args[]){
        Scanner scanner= new Scanner(System.in);
        System.out.println("write no. of row you want:");
        int n = scanner.nextInt();
        for(int i=1; i<=n; i++){
            //spaces
            for(int j=1; j<=n-i; j++){
                System.out.print(" ");
            }
            //first half
            for(int j=i; j>=1; j-- ){
                System.out.print(j);
            }
            for(int j=2; j<=i; j++){
                System.out.print(j);
            }
            System.out.println();
        }
    }
    }
*/

//diamond pattern
/*public class patterns{
    public static void main(String args[]){
        Scanner scanner= new Scanner(System.in);
        System.out.println("write no. of row you want:");
        int n = scanner.nextInt();
        for(int i=1; i<=n; i++){
            //spaces
            for(int j=1; j<=n-i; j++){
                System.out.print(" ");
            }
            //upper half
            for(int j=1; j<=2*i-1; j++){
                System.out.print("*");
            }
            System.out.println();
            
        }  
        
        for(int i=n; i>=1; i--){
            //spaces
            for(int j=1; j<=n-i; j++){
                System.out.print(" ");
            }
            //upper half
            for(int j=1; j<=2*i-1; j++){
                System.out.print("*");
            }
            System.out.println();
            
        }  
    }
}
*/
