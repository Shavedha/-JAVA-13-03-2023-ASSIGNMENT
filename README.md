# JAVA-13-03-2023-ASSIGNMENT
### 1. Print the following pattern
```
*****
*****
*****
*****
*****
```
PROGRAM
```
public class Main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        for(int i=0;i<n;i++){
            for(int j=0;j<n;j++){
                System.out.print("*");
            }
            System.out.println();
        }
    }
}
```
OUTPUT

<img width="414" alt="Screenshot 2023-03-13 194453" src="https://user-images.githubusercontent.com/93427376/224884676-0c62ff9d-7736-4772-9ed0-e770fd2959b6.png">

### 2. Print the following pattern
```
*********
 *******
  *****
   ***
    *
```

PROGRAM
```
public class Main {
    public static void main(String[] args)
    {
        Scanner scan=new Scanner(System.in);
        int n=scan.nextInt();
        for(int i=n;i>=1;i--)
        {
            for(int j=n;j>=i;j--)
                System.out.print(" ");
            for(int k=1;k<=2*i-1;k++)
                System.out.print("*");

            System.out.println();
            }
      }
 }
 ```
 OUTPUT
 
 <img width="404" alt="Screenshot 2023-03-13 201214" src="https://user-images.githubusercontent.com/93427376/224885364-e9488b3c-18b1-44cd-86bf-145931799fb5.png">
 
 ### 3. Print the following pattern
```
*
**
***
****
*****
****
***
**
*
```
PROGRAM
```
public class Main{
    public static void main(String[] args){
       Scanner sc=new Scanner(System.in);
       int n=sc.nextInt();
       for(int i=0;i<=n;i++){
           for(int j=1;j<=i;j++){              //for(int j=i;j<=n;j++)
               System.out.print("*");
           }
           for(int k=i;k<=n;k++){
               System.out.print(" ");
           }
           
           System.out.println();
       }
       for(int i=n-1;i>=0;i--){
           for(int j=0;j<=i-1;j++){
               System.out.print("*");
           }
           System.out.println();
       }
    }
}
```
OUTPUT

<img width="292" alt="Screenshot 2023-03-13 204701" src="https://user-images.githubusercontent.com/93427376/224885715-5bf5866d-8da1-4dfe-ad98-0691d4beddf3.png">

