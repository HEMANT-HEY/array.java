# array.java
java.util.*;
class arr {
    public static void main(String[] args) {
        int[] arr= new int[5];
        Scanner sc =new Scanner (System.in);
        System.out.println("enter the num :");
       int n=sc.nextInt();
    System.out.println("input ");
      //  int arr[]=sc.nextInt();
       
       for(int i=0; i<n; i++){
        arr[i]= sc.nextInt();  
       }
       System.out.println("out");
       for(int i=0; i<n; i++){
           System.out.println(arr[i]);
       }
    }
}
