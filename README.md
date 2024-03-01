import java.util.Scanner;

public class TimeConverter {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Masukan detik : ");
        int totalDetik = scanner.nextInt();

        int Detik = totalDetik % 60;
        int totalMenit = totalDetik / 60;
        int Menit = totalMenit % 60;
        int totalJam = totalMenit / 60;
        int Jam = totalJam % 24;

        System.out.println("Hasil : " + Jam + ":" + Menit + ":" + Detik);
    }
}
