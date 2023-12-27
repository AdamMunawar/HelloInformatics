# Hello Informatics ! 
## Muhammad Adam Sirojuddin Munawar (1237050133)

## Menjelaskan dan Menginternalisasi Computational Thinking ⭐⭐⭐⭐⭐⭐⭐
1. Penjelasan Mengenai Berpikir komputasi (https://mudabergelora.wordpress.com/2023/12/20/computational-thinking-gerbang-pemahaman-dan-internalisasinya-dalam-dunia-digital/) <br>

1.1 Berikut tampilan blog yang sudah disusun <br>
![Screenshot (204)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/0d293c2d-d5e2-496f-ac4f-f4718f8b21c6)

1.2 Simpulan mengenai Computational Thinking beserta Internalisasinya <br>
    Computational Thinking (dalam bahasa indonesia Berpikir Komputasi) dapat disimpulkan yakni cara berpikir layaknya komputer, dengan pemecahanan masalah secara terstruktur dan dipecah ke ranah yang lebih dalam lagi.<br>
Tentunya, sistematika berpikir dan pemecahan masalah tersebut didasari akan logika yang kuat dalam penyelesaian masalah. <br>
Contoh sederhana dalam penerapan berpikir komputasi, yakni ketika akan memasak nasi. Tentunya bagi sebagian kalangan untuk memasak nasi merupakan hal yang mudah, namun di sisi lain, kita dapat menerapkan pola pemikiran computational thinking dengan penjabaran akar masalah utama. Di sini, yang menjadi permasalahan ialah saya ingin memasak nasi, lalu saya mesti melakukan apa supaya pada akhirnya saya bisa memakan hasil masakan nasi tersebut. <br>
Selanjutnya, kita dapat memperinci masalah yang sudah dijabarkan dengan memastikan terlebih dahulu apakah beras tersedia apakah tidak, jika tersedia maka kita bisa melanjutkan untuk memasak nasi, adapun jika tidak tersedia, maka dapat membeli beras terlebih dahulu, berlanjut poin demi poin permasalahan dan pencarian solusi hingga masalah "memasak nasi" telah terselesaikan.<br> 

## Menjelaskan Jenis-Jenis Mesin Komputasi ⭐⭐⭐
1. Penjelasan rinci mengenai Jenis Mesin Komputasi (https://mudabergelora.wordpress.com/2023/12/20/mengenal-lebih-dekat-jenis-jenis-mesin-komputasi/) <br>.
1.1 Berikut tampilan blog yang sudah disusun <br>
![Screenshot (205)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/4733f18b-b399-42f1-bc9a-55f3b3d12005) <br>
1.2 Simpulan mengenai Jenis-jenis Mesin Komputasi <br>
Adapun jenis jenis mesin komputasi yang umum diketahui yakni : <br>
a. Personal Computer (PC). Semacam Komputer dekstop dan laptop <br>
b. Minicomputer <br>
c. Supercomputer <br>
d. Server <br>
e. Embedded System, seperti peralatan rumah tangga, Mobil pintar, CCTV, dan segala peralatan yang terintegrasi dengan perangkat lain <br>

## Mengktifkan dan Mencoba Google Colab [v] ⭐⭐⭐⭐⭐
Google Colab, saya mendaftar dengan akun email pribadi : muhammadadam.005@gmail.com <br>
- Penggunaan Google Colab, dengan bahasa Phyton dengan tujuan pemahaman cara kerja Kecerdasan Buatan dalam membuat Text-to-Speech <br>
![Screenshot (190)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/7d6a9b73-766b-4590-8684-5d7b6f3ea085)

## Mencoba Console Sistem Operasi
Console Sistem operasi adalah antarmuka teks berupa perintah yang menghasilkan respon berupa teks kembali, yang mana pengguna dapat menjelajahi sistem yang berada dalam operasi, menjalankan program yang disimpan dalam sistem operasi dan berbagai kegunaan lainnya. <br> Adapun ssalah satu contoh dari console sistem operasi antara lain Command Prompt (CMD) yang biasa di windows, Terminal Linux, dan MacOs Command Shell seperti contoh di bawah yang akan saya tampilkan setelahnya. <br>
Link Penjelasan Selengkapnya ()<br>
### Windows CMD [v] ⭐⭐⭐⭐
![Screenshot (191)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/9f9acc11-9097-4f90-b624-ea08b7c2b12f)


Referensi [1](https://www.stationx.net/windows-command-line-cheat-sheet/)

### Linux Terminal Menggunakan Google Colab [v] ⭐⭐⭐⭐
![Screenshot (192)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/d313932b-0825-4bc5-a248-13e20ef240d2)

## Membuat Algoritma Dalam Bentuk Flow Chart [v] ⭐⭐⭐⭐⭐
Berdasarkan referensi yang diambil dari (https://dev.to/angelotheman/flowchart-wizardry-master-the-art-of-visualizing-algorithms-4e4j), saya menggunakan tool draw.io untuk membuat algoritma "memasak nasi" dengan flow chart, adapun hasilnya dilampirkan <br>
##![Algoritma Memasak Nasi drawio](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/74871259-db37-4db7-a6c6-3aebbdb2b27d)

## Mencoba Scratch Bahasa Indonesia [v] ⭐⭐⭐⭐⭐⭐⭐
Link Blog () <br>
Link Hasil Percobaan (https://scratch.mit.edu/projects/944177475/)
Link Video Youtube ()
![Screenshot (193)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/e320e4cf-2ae2-448f-9782-87fbfd72e9f0)

## Mencoba Algoritma Bubble Sort Menggunakan Java [v] ⭐⭐⭐
```
public class BubbleSort {
    public static void main(String[] args) {
        String[] nama = {"Budi", "Andi", "Citra", "Dewi", "Eko"};

        System.out.println("Nama sebelum diurutkan:");
        printNames(nama);

        bubbleSort(nama);

        System.out.println("\nNama setelah diurutkan:");
        printNames(nama);
    }

    static void bubbleSort(String[] nama) {
        int n = nama.length;

        for (int i = 0; i < n - 1; i++) {
            for (int j = 0; j < n - i - 1; j++) {
                if (nama[j].compareTo(nama[j + 1]) > 0) {
                    String temp = nama[j];
                    nama[j] = nama[j + 1];
                    nama[j + 1] = temp;
                }
            }
        }
    }

    static void printNames(String[] nama) {
        for (String namas : nama) {
            System.out.print(namas + " ");
        }
    }
}
```
Adapun Implementasinya : <br>
![Screenshot (208)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/641c585b-cdf9-4b6c-9512-9e9173842c0a) <br> Penjelasan : <br>
Bubble Sort digunakan untuk mengurutkan daftar angka atau kata dengan cara yang sederhana. Dalam analogi ini, kita membayangkan kartu-kartu yang memiliki angka atau kata di atasnya. Langkah pertama melibatkan perbandingan antara dua kartu pertama. Jika kartu pertama memiliki nilai yang lebih besar, posisinya akan ditukar dengan kartu kedua. Selanjutnya, perpindahan dilakukan ke kartu berikutnya dan proses ini diulangi hingga mencapai kartu terakhir.

Setelah satu putaran selesai, dimulai kembali dari awal, kecuali yang terakhir. Proses ini diulangi beberapa kali hingga tidak ada lagi pertukaran yang terjadi. Dalam perjalanan waktu, kartu dengan nilai tertinggi akan bergeser ke posisi terakhir. Meskipun cara ini sederhana, Bubble Sort dianggap tidak efisien untuk jumlah data yang besar. Ini adalah cara untuk memahami bagaimana pengurutan dilakukan dengan membandingkan dan menukar elemen-elemen bertetangga. <br>

## Mencoba dan Mendemonstrasikan Penggunakan IDE ⭐⭐
IDE dengan Visual Studio Code (VsCode)
![Screenshot (210)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/98ca4168-e661-4f19-ae69-4b865be04d91)

![Screenshot (209)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/8baac846-38a2-42c2-a1cb-2b706dc0aede)

## Mendaftar, Mengeksplorasi, dan Mendemonstrasikan Penggunaan HackerRank [v] ⭐⭐⭐⭐⭐
Akun HackerRank Saya (https://www.hackerrank.com/profile/muhammadadam_005) <br>
- Tampilan Layar Proifle Hackerrank <br>
![Screenshot (212)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/e0bbf87e-1f76-4c2a-9b1c-d9aeb5cc6bda)

![Screenshot (211)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/41980148-b811-4877-84b4-f35917e45818)

## Mendemonstrasikan Pembuatan Aplikasi / Game Pada Platform : Mobile / Desktop / Web Browser ⭐⭐⭐⭐⭐

## Mencoba Instalasi Database (PostgreSQL / MySQL / dsb.) [v] ⭐⭐⭐

Referensi installer [PostgreSQL](https://www.postgresql.org/download/windows/)
Referensi tambahan [1](https://db-engines.com/en/ranking)

## Mencoba Eksplorasi dan Query Database Menggunakan Database Explorer (Dbeaver / dsb.) [v] ⭐⭐⭐

Referensi installer [Dbeaver](https://dbeaver.io/download/)
Referensi [1](https://www.w3schools.com/postgresql/postgresql_create_table.php)

## Mendemonstrasikan dan Menjelaskan Penggunaan Web Browser untuk Mengakses Halaman Website HTML [v] ⭐⭐⭐⭐
- Dokumen HyperText Markup Language (HTML) ada untuk memudahkan pertukaran informasi berbasis Hypertext.
- Web Browser seperti Firefox, Chrome, Opera, ada untuk membuka dan mempresentasikan dokumen HTML
- Dokumen HTML ini bisa bersumber dari web server yang kita ingin datanya (Tokopedia, Wikipedia, Detik.com, dsb.) atau bisa juga dukumen HTML yang kita buat sendiri

## Mendemonstrasikan dan Menjelaskan Komponen Dari Contoh Uniform Resource Locator (URL) [v] ⭐⭐

Referensi: [1](https://www.startertutorials.com/ajwt/uniform-resource-locator.html)

## Mencoba Pelacakan Informasi Server dari Alamat Domain [v] ⭐

Referensi terkait: [1](https://en.wikipedia.org/wiki/Country_code_top-level_domain) [2](https://en.wikipedia.org/wiki/List_of_Internet_top-level_domains)

## Mencoba Pembuatan Halaman Web Menggunakan HTML, CSS, dan JavaScript [v] ⭐⭐⭐

Referensi tutorial 
- Isi konten halaman web : [HTML](https://www.w3schools.com/html/)
- Styling halaman web : [CSS](https://www.w3schools.com/css/)
- Interaktivitas halaman web : [JavaScript](https://www.w3schools.com/js/)

## Mencoba Penerapan Teknik Search Engine Optimization (SEO) Pada HTML [v] ⭐⭐⭐

Referensi []

## Mencoba Pembuatan File JSON [v] ⭐⭐⭐

## Mencoba Penggunaan Web Hosting Dengan Untuk Halaman HTML [v] ⭐⭐⭐


## Mencoba Penggunaan Web Hosting Dengan Untuk Web Service [v] ⭐⭐⭐

## Mencoba HTTP Request dan Web API dengan Hoppscotch / Postman [v] ⭐⭐

## Mendemonstrasikan Penggunaan Developer Tools Pada Web Browser (Firefox / Chrome) [v] ⭐⭐⭐⭐⭐

## Mengeksplorasi dan Menjelaskan Layanan Cloud Service yang Diminati (GCP / AWS / Azure) [v] ⭐⭐
Saat ini banyak perusahaan berbasis digital seperti Gojek, Tokopedia, Instagram, Telkom memanfaatkan Cloud Service karena memudahkan untuk mulai pembangunan dan analisis menggunakan infrastruktur digital yang dapat berkembang secara dinamis dengan tarif yang sangat teliti.

Referensi cloud service: [Amazon Web Service](https://aws.amazon.com/) [Microsoft Azure](https://azure.microsoft.com) [Google Cloud Platform](https://cloud.google.com) 

## Mencoba Penggunaan Content Management System (Wordpress) [v] ⭐⭐⭐

## Mendemonstrasikan Akses Konten Multimedia (Image, Audio, Video) ⭐⭐⭐

## Mencoba Edit Konten Multimedia (Image, Audio, Video) [v] ⭐⭐

## Mencoba Pembuatan Game dan Simulasi Menggunakan Logo [v] ⭐⭐

## Mencoba Pemrosesan Konten Multimedia (Image, Audio) Menggunakan Google Colab [v] ⭐⭐⭐

## Mencoba Web Tool AI Discriminative (Image Classification) [v] ⭐⭐⭐⭐

## Mencoba Web Tool AI Generative (Text to Image, Text to Text) [v] ⭐⭐⭐⭐

## Mencoba Model Machine Learning Menggunakan Google Colab, TTS, Speechrecognition, dan HuggingFace [v] ⭐⭐⭐

## Mencoba Data Visualization Dengan Tools [v] ⭐⭐

## Mencoba Data Visualization Dengan Code [v] ⭐⭐

## Mendaftar dan Mencoba Eksplorasi HuggingFace [v] ⭐⭐⭐

## Mendaftar dan Mencoba Eksplorasi Kaggle [v] ⭐⭐⭐⭐

## Mencoba Protokol Komunikasi IoT (MQTT) [v] ⭐

## Mencoba Memproses File CSV Menggunakan Google Colab [v] ⭐⭐

## Mencoba Memproses File Big Data ORC Menggunakan Google Colab [v] ⭐⭐

## Menjelaskan Jurnal, Conference, Artikel, Grade Jurnal [v] ⭐⭐⭐⭐⭐

## Eksplorasi Artikel Jurnal / Conference di Repository Terekognisi Internasional (IEEE / Arxiv / Science Direct / ACM /DBLP) [v] ⭐⭐⭐⭐

## Menonton Video Presentasi Tugas Akhir Informatika ⭐⭐⭐⭐⭐

## Mengeksplorasi Seluruh Profesi Terkait Informatika dan Profesi yang Diminati ⭐⭐⭐⭐

## Eksplorasi Tools Untuk Belajar Bahasa Inggris (Duolingo) ⭐⭐⭐

## Eksplorasi Tools Untuk Belajar Berbicara Bahasa Inggris (HelloTalk) ⭐⭐⭐ 

## Eksplorasi Lowongan Pekerjaan IT ⭐⭐⭐

## Eksplorasi Lowongan Freelancer IT (Upwork / Toptal / Freelancer.com) ⭐⭐⭐

## Eksplorasi dan Pilih Topik yang Diminati di Roadmap.sh ⭐⭐⭐

## Eksplorasi Top Github Project yang Diminati ⭐⭐ 

## Membangun Profil Linkedin dan Mengikuti Akun-Akun Inspirasif Bertema Informatika ⭐⭐⭐

## Membangun Profil Github Page ⭐⭐⭐⭐⭐

## Mengikuti Workshop / Event / Course Terkait IT ⭐⭐⭐⭐

## Membaca dan Mengambil Inspirasi Dari Buku Bertema Informatika ⭐⭐⭐⭐⭐





