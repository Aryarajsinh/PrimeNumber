# PrimeNumber
package com.company;
import java.util.Scanner;
public class prime {
    public static void main(String[] args){
            System.out.print("Enter the number: ");
            Scanner input = new Scanner(System.in);
            int n = input.nextInt();
            int count=0,num=2;
            while(n>0){
                for(int i = 2; i < num; i++){
                    if(num % i == 0){
                        count ++;
                    }
                }
                if(count == 0){
                    System.out.println(num);
                    n--;
                }
                else count=0;
                num++;
            }
        }
    }

