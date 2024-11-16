# burc-bulan-program
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        int month, day;

        Scanner input = new Scanner(System.in);
        System.out.print("Doğduğunuz ay (1,12): ");
        month = input.nextInt();

        System.out.print("Doğduğunuz gün (1,31): ");
        day = input.nextInt();

        String burc = "";

        if (month == 1) {
            if (day >= 1 && day <= 31) {
                burc = (day < 22) ? "Oğlak" : "Kova";
            } else {
                System.out.println("Geçersiz bir gün girdiniz !");
                return;
            }
        } else if (month == 2) {
            if (day >= 1 && day <= 28) {
                burc = (day < 20) ? "Kova" : "Balık";
            } else {
                System.out.println("Geçersiz bir gün girdiniz !");
                return;
            }
        } else if (month == 3) {
            if (day >= 1 && day <= 31) {
                burc = (day < 21) ? "Balık" : "Koç";
            } else {
                System.out.println("Geçersiz bir gün girdiniz !");
                return;
            }
        } else if (month == 4) {
            if (day >= 1 && day <= 30) {
                burc = (day < 21) ? "Koç" : "Boğa";
            } else {
                System.out.println("Geçersiz bir gün girdiniz !");
                return;
            }
        } else if (month == 5) {
            if (day >= 1 && day <= 31) {
                burc = (day < 22) ? "Boğa" : "İkizler";
            } else {
                System.out.println("Geçersiz bir gün girdiniz !");
                return;
            }
        } else if (month == 6) {
            if (day >= 1 && day <= 30) {
                burc = (day < 23) ? "İkizler" : "Yengeç";
            } else {
                System.out.println("Geçersiz bir gün girdiniz !");
                return;
            }
        } else if (month == 7) {
            if (day >= 1 && day <= 31) {
                burc = (day < 23) ? "Yengeç" : "Aslan";
            } else {
                System.out.println("Geçersiz bir gün girdiniz !");
                return;
            }
        } else if (month == 8) {
            if (day >= 1 && day <= 31) {
                burc = (day < 23) ? "Aslan" : "Başak";
            } else {
                System.out.println("Geçersiz bir gün girdiniz !");
                return;
            }
        } else if (month == 9) {
            if (day >= 1 && day <= 30) {
                burc = (day < 23) ? "Başak" : "Terazi";
            } else {
                System.out.println("Geçersiz bir gün girdiniz !");
                return;
            }
        } else if (month == 10) {
            if (day >= 1 && day <= 31) {
                burc = (day < 23) ? "Terazi" : "Akrep";
            } else {
                System.out.println("Geçersiz bir gün girdiniz !");
                return;
            }
        } else if (month == 11) {
            if (day >= 1 && day <= 30) {
                burc = (day < 23) ? "Akrep" : "Yay";
            } else {
                System.out.println("Geçersiz bir gün girdiniz !");
                return;
            }
        } else if (month == 12) {
            if (day >= 1 && day <= 31) {
                burc = (day < 23) ? "Yay" : "Oğlak";
            } else {
                System.out.println("Geçersiz bir gün girdiniz !");
                return;
            }
        } else {
            System.out.println("Hatalı bir ay girdiniz !");
            return;
        }
        System.out.println("Burcunuz:" + burc);
    }
}
