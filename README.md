# praktikum5


## kode ##
### programer.java ###
```
   public class Programmer {
    String nama;
    int gaji;
    int bonus;

    // Constructor tanpa parameter
    public Programmer() {
        this.nama = "Fahmi Arifin";
        this.gaji = 5000000;
        this.bonus = 1000000;
    }

    // Constructor dengan 1 parameter
    public Programmer(String nama) {
        this.nama = nama;
        this.gaji = 5000000;
        this.bonus = 1000000;
    }

    // Constructor dengan 2 parameter
    public Programmer(String nama, int gaji) {
        this.nama = nama;
        this.gaji = gaji;
        this.bonus = 1000000;
    }

    // Constructor dengan 3 parameter (Overload)
    public Programmer(String nama, int gaji, int bonus) {
        this.nama = nama;
        this.gaji = gaji;
        this.bonus = bonus;
    }

    // Method untuk menampilkan informasi
    public void displayInfo() {
        System.out.println("Nama: " + nama);
        System.out.println("Gaji: " + gaji);
        System.out.println("Bonus: " + bonus);
    }
}
```
### main.java ###
```
public class main {
    public static void main(String[] args) {
        // Menggunakan constructor tanpa parameter
        Programmer prog1 = new Programmer();
        prog1.displayInfo();

        // Menggunakan constructor dengan 1 parameter
        Programmer prog2 = new Programmer("Andi Herlambang");
        prog2.displayInfo();

        // Menggunakan constructor dengan 2 parameter
        Programmer prog3 = new Programmer("Riko", 6000000);
        prog3.displayInfo();

        // Menggunakan constructor dengan 3 parameter
        Programmer prog4 = new Programmer("Dina", 5000000, 3000000);
        prog4.displayInfo();
    }
}
```
## Hasil eksekusi ##
```
Nama: Fahmi Arifin
Gaji: 5000000
Bonus: 1000000
Nama: Andi Herlambang
Gaji: 5000000
Bonus: 1000000
Nama: Riko
Gaji: 6000000
Bonus: 1000000
Nama: Dina
Gaji: 5000000
Bonus: 3000000
```
## ScreenShot ##
![Cuplikan layar 2024-11-06 174551](https://github.com/user-attachments/assets/f407f8b1-13d9-4e5d-9a90-924d3cd941bc)


![Cuplikan layar 2024-11-06 174339](https://github.com/user-attachments/assets/0c1d5e12-7de4-48b8-92ce-7ce771f6236e)

