# -Zadanie13
№13

Задание номер 1

public class Main
{
	public static void main(String[] args) {
	
	int[][] a=new int[10][10];
  for (int i=0;i < a.length;i++){
    for (int j=0;j < a[i].length;j++){
      a[i][j]=(int)(Math.random()*10);
      }
     }
for (int i=0;i < a.length;i++,System.out.println("Ответик")){
for (int j=0;j < a[i].length;j++){
System.out.print(a[i][j]+" ");

           }
		}
		}
		}
Задание номер 2

import java.util.Arrays;
class Main {
public static void main(String[] args) {
int num[][] = { {5, 4, 9}, {7, 5, 8},{0,3,1} }; int[] flat = new int[3 * 3]; int ctr = 0; for (int row = 0; row < 3; row++) { for (int col = 0; col < 3; col++) { flat[ctr++] = num[row][col]; } } Arrays.sort(flat); ctr = 0; for (int row = 0; row < 3; row++) { for (int col = 0; col < 3; col++) { num[row][col] = flat[ctr++]; } } for (int row = 0; row < 3; row++) { for (int col = 0; col < 3; col++) { System.out.print(num[row][col] + " "); } System.out.println(); } } }
