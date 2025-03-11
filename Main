import java.util.Scanner;
public class pegamain {
    public static void main (String[] args) {
        Scanner input = new Scanner(System.in);

        pegawaix pegawai1 = new pegawaix();
        
        System.out.println("Masukkan data pegawai:");
        System.out.print("Nama: ");
        String nama = input.nextLine();
        System.out.print("Jabatan: ");
        String jabatan = input.nextLine();
        System.out.print("Gaji Pokok: ");
        double gajiPokok = input.nextDouble();
        System.out.print("Tunjangan: ");
        double tunjangan = input.nextDouble();
        System.out.print("Potongan: ");
        double potongan = input.nextDouble();
        System.out.print("Bonus: ");
        double bonus = input.nextDouble();
        
        pegawaix pegawai2 = new pegawaix(nama, jabatan, gajiPokok, tunjangan, potongan, bonus);

        pegawai2.displayInfo();

        System.out.print("\nMasukkan tambahan bonus: ");
        double tambahanBonus = input.nextDouble();
        pegawai2.tambahBonus(tambahanBonus);

        System.out.println("\nSetelah penambahan bonus:");
        pegawai2.displayInfo();

        input.close();
    }
}
