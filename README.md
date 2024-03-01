import java.util.Scanner;

public class Main {
  public static void main(String[] args) {
    Scanner scanner = new Scanner(System.in);

    System.out.print("imput nim anda: ");
    String nim = scanner.nextLine();

    System.out.print("Mohon masukan nama anda: ");
    String nama = scanner.nextLine();

    System.out.print("Mohon masukan jurusan anda: ");
    String jurusan = scanner.nextLine();

    System.out.print("Mohon masukan fakultas anda: ");
    String fakultas = scanner.nextLine();

    System.out.println("\nNim: " + nim);
    System.out.println("Nama: " + nama);
    System.out.println("Jurusan: " + jurusan);
    System.out.println("Fakultas: " + fakultas);
  } 
}
