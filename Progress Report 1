package responsi;

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */

/**
 *
 * @author ASUS
 */
import java.util.Scanner;

public class ProgramKasirRestoran {
    public static void main(String[] args){
        Scanner scan = new Scanner(System.in);
       
        System.out.println("MENU MAKAN : ");
        
        System.out.println("--------------------------------------------------------");
        System.out.println("No.      MENU            Harga");
        System.out.println("1.   Ayam Goreng       Rp.8000,-");
        System.out.println("2.   Tumis Kangkung    Rp.6000,-");
        System.out.println("3.   Tempe Goreng      Rp.2000,-");
        System.out.println("4.   Nasi Goreng       Rp.10.000,-");
        System.out.println("5.   kwetiaw           Rp.21.000,-");
        System.out.println(" ");
        
        int harga = 0;
        int h1 = 8000, h2 = 6000, h3 = 2000, h4 = 10000, h5 = 21000;
        String menu;
        for (String i = "Y"; i.equals("Y")||i.equals("Y");){
            
            System.out.println("----------------------------------------------------");
            
            System.out.print("Masukkan Nomor Pesanan : ");
            int inNomor = scan.nextInt();
            
            System.out.println("----------------------------------------------------");
            
            if (inNomor == 1){
                menu = "Ayam Goreng";
                System.out.println("Pilihan anda nomor "+inNomor + menu);
                harga = harga + h1;
            }
            else if (inNomor == 2)
            {
                menu = " Tumis Kangkung";
                System.out.println("Pilihan anda nomor "+inNomor + menu);
                harga = harga + h2;
            }
            else if (inNomor == 3)
            {
                menu = "Tempe Goreng";
                System.out.println("Pilihan anda nomor "+inNomor + menu);
                harga = harga +h3;
            }
            else if (inNomor == 4)
            {
                menu = "Nasi Goreng";
                System.out.println("Pilihan anda nomor "+inNomor + menu);
                harga = harga + h4;
            }
            else if (inNomor == 5)
            {
                menu = "kwetiaw";
                System.out.println("Pilihan anda nomor "+inNomor + menu);
                harga = harga + h5;
            }
            else
            {
                System.out.println("Nomor yang anda pilih tidak ada di menu.");
            }
            System.out.println("Apakah anda mau melanjukan? Y/T");
            i = scan.next();
        }
        System.out.println("---------------------------------------------------------");
        System.out.println("Total pembayaran sebesar "+harga+".");
        
        }
        
    }

