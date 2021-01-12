package com.company;  
import java.util.Scanner;  
public class Main{  
    public static void main(String[] args) {  
        Scanner sc=new Scanner(System.in);  
        System.out.println("input integer:");  
        int n=sc.nextInt();  
        System.out.print(n+"  ");  
        for(int k=2;k<=n;k++){  
            while(n%k==0&&n!=k){  
                n=n/k;  
                    System.out.print(k+" ");  
  
                }  
            if(n==k){  
                System.out.print(k);  
                    break;  
                }  
            }  
        }  
    }  
