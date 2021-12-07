# factorial-of-number
package com.company;

import jdk.swing.interop.SwingInterOpUtils;

import java.util.Scanner;

public class Main
{
    public static void main (String args[])
    {
        Scanner k =new Scanner(System.in);
        System.out.println("Enter any  number..");
        int num= k.nextInt();
        int f=1;
        for (int i = num; i > 1; i-- )
        {
            f*=i;
        }
        System.out.println("factorial =" + f);
    }
}
