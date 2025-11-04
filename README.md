# Latihan-UKL-Sedang-1

Bagian 1 :

        public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.println("PROGRAM MENGHITUNG FAKTORIAL");
        System.out.print("Masukkan bilangan bulat positif: ");
        int n = input.nextInt();

kode ini digunakan untuk memulai program perhitungan faktorial — yaitu menghitung hasil perkalian semua bilangan dari 1 hingga n.

Bagian 2 : 

        if (n < 0) {
        System.out.println("Bilangan harus positif!");
        } else {
        long hasil = faktorial(n);
        System.out.println("Faktorial dari " + n + " adalah: " + hasil);
        }
        }

Kode ini digunakan untuk memeriksa apakah input pengguna valid (positif) dan kemudian menghitung serta menampilkan hasil faktorial dari bilangan tersebut.

Bagian 3 : 

        public static long faktorial(int n) {
        long hasil = 1;
        for (int i = 1; i <= n; i++) {
            hasil *= i;
        }
        return hasil;
        }

digunakan untuk menghitung nilai faktorial dari bilangan bulat positif n.
Faktorial (n!) adalah hasil perkalian semua bilangan dari 1 sampai n.

<img width="744" height="216" alt="Screenshot 2025-11-04 233256" src="https://github.com/user-attachments/assets/eb78dd8e-0e4e-4812-be15-506e09a4fae3" />
