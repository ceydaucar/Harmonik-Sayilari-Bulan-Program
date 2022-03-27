# Harmonik-Sayilari-Bulan-Program
Patika.dev > Java101 > Döngüler > Pratik7 - Harmonik Sayıları Bulan Program

Java ile girilen sayının harmonik serisini bulan program yazacağız.

Harmonik Seri Formülü :

![harmonic_series](https://user-images.githubusercontent.com/69717631/160280917-ce5db5b0-0132-42f3-99ef-02b6e81272b5.gif)


      import java.util.*;

      public class harmonik_sayilari_bulan_program {

        public static void main(String[] args) {

          Scanner sc =  new Scanner(System.in);

          System.out.print("Enter the number n: ");
          int n = sc.nextInt();

          double total = 0;

          for(double i=1; i<=n; i++) {
            total += (1/i);
          }

          System.out.println("Harmonic series: " + total);
        }
      }
