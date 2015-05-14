# myrepository
import java.util.Scanner;
public class rekursi {
public static void main (String[]args){

Scanner input = new Scanner(System.in);
int angka,a,b;
System.out.println("masukkan angka : ");
angka= input.nextInt();

System.out.println("hasil faktorial adalah:" + faktorial(angka));

public static double faktorial (int angka){
if(angka==1){
return 1;
}
else
return angka * faktorial(angka-1);
}
}
