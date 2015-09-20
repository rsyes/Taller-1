# Taller-1
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package taller1.pkg0;
import java.util.*;
/**
 *
 * @author usuario07
 */
public class tallerpunto2 {

    public static void main(String[] args){
        Scanner lector;
        String numero;
        int a=0;
        int i=0;
        
        lector=new Scanner (System.in);
        System.out.println("Escriba su numero");
        numero= lector.next();
        a=+numero.length();
        for(i=0;i<a;i++){
            System.out.print("" +numero.charAt(i));
            System.out.print("   ");
        }
    }
}
