# lab-sesi-4
package com.company;

import java.util.Scanner;

public class Main
{
    public static void main(String[] args)
    {
	    Scanner put = new Scanner(System.in);

	    System.out.println("input kota pertama : ");
		String cty1 = put.nextLine();

	    System.out.println("input kota kedua : ");
	    String cty2 = put.nextLine();

	    System.out.println("urutan nama kota sesuai abjad : ");
	    if(cty1.compareTo(cty2) >0){
	        System.out.println(cty2 + "," + cty1);
        } else if(cty1.compareTo(cty2) <0){
	        System.out.println(cty1 + "," + cty2);
        }
    }
}
