import java.util.Scanner;

public class pismena {
    public static void main(String[]args){
        Scanner sc = new Scanner(System.in);
        System.out.print("zadej vetu: ");
        String str = sc.nextLine();
        char[] ch = str.toCharArray();
        int count = 0;
            for (int i = 0; i < str.length(); i++) {
                if (Character.isLetter(ch[i]))
                    count++;
                }
            System.out.println("Pismena: "+count);
            }
        }

