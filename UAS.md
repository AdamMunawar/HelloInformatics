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
Link Youtube ()
## Mencoba Instalasi Database (PostgreSQL / MySQL / dsb.) [v] ⭐⭐⭐

Referensi installer [PostgreSQL](https://www.postgresql.org/download/windows/)
Referensi tambahan [1](https://db-engines.com/en/ranking)
![Screenshot (214)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/612383e0-ad22-4746-adea-634f150407c8)
![Screenshot (215)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/7c5faad0-a2cd-4834-9d17-be805bfbf8fc)
![Screenshot (216)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/4a845ea3-2f4d-4792-a946-6cf33165f4e5)
![Screenshot (218)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/67cbadee-b69f-43d3-813a-0810d559d908)

## Mencoba Eksplorasi dan Query Database Menggunakan Database Explorer (Dbeaver / dsb.) [v] ⭐⭐⭐
![Screenshot (221)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/52637a58-edd8-4cd4-a86c-aa972a9f8bf5)
![Screenshot (223)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/67416a6f-89bd-4cfa-b59f-9a306c3c59d3)

Referensi installer [Dbeaver](https://dbeaver.io/download/)
Referensi [1](https://www.w3schools.com/postgresql/postgresql_create_table.php)

## Mendemonstrasikan dan Menjelaskan Penggunaan Web Browser untuk Mengakses Halaman Website HTML [v] ⭐⭐⭐⭐
-Akses Website pemerintah Kab. Bandung Barat menggunakan Web Browser google chrome 
![Screenshot (256)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/d24ae89f-75f9-4f18-905a-178e2f313622)

- Dokumen HyperText Markup Language (HTML) ada untuk memudahkan pertukaran informasi berbasis Hypertext.
- Web Browser seperti Firefox, Chrome, Opera, ada untuk membuka dan mempresentasikan dokumen HTML
- Dokumen HTML ini bisa bersumber dari web server yang kita ingin datanya (Tokopedia, Wikipedia, Detik.com, dsb.) atau bisa juga dukumen HTML yang kita buat sendiri

## Mendemonstrasikan dan Menjelaskan Komponen Dari Contoh Uniform Resource Locator (URL) [v] ⭐⭐
URL, atau Uniform Resource Locator, adalah alamat yang digunakan untuk menunjukkan lokasi sumber daya di internet. URL terdiri dari beberapa komponen yang memberikan informasi tentang cara mengakses sumber daya tersebut.<br>
Contohnya, https://www.example.com:8080/path/to/resource?query_param=value#fragment. Dalam URL ini:
Protokol (https://) menunjukkan aturan komunikasi yang digunakan, seperti HTTPS.<br>
Nama host (www.example.com) menentukan alamat situs atau server.
Port (:8080) adalah saluran khusus untuk mentransmisikan data (opsional).
Path (/path/to/resource) menunjukkan lokasi spesifik di server.
Query parameter (?query_param=value) memberikan informasi tambahan kepada server.
Fragment (#fragment) menandakan bagian tertentu dari sumber daya yang ditampilkan.<br>
Jadi, URL ini adalah cara kita menyampaikan instruksi ke server untuk mendapatkan atau menampilkan sumber daya yang diinginkan.
Referensi: [1](https://www.startertutorials.com/ajwt/uniform-resource-locator.html)

## Mencoba Pelacakan Informasi Server dari Alamat Domain [v] ⭐
![Screenshot (241)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/ea39fbcf-8b92-466d-996d-4e1ca28c1361)
![Screenshot (242)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/f612ad50-7d7a-4ce1-affe-adc3b565a4d2)
![Screenshot (243)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/8b86a2fb-0b95-485b-a579-7cb02c9f8e39)

Referensi terkait: [1](https://en.wikipedia.org/wiki/Country_code_top-level_domain) [2](https://en.wikipedia.org/wiki/List_of_Internet_top-level_domains)

## Mencoba Pembuatan Halaman Web Menggunakan HTML, CSS, dan JavaScript [v] ⭐⭐⭐
![Screenshot (243)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/32956075-6797-4ae9-99e3-0027f3ab3390)
![Screenshot (244)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/7c071ae8-703f-472f-95f7-1c0c6be1459c)

Referensi tutorial 
- Isi konten halaman web : [HTML](https://www.w3schools.com/html/)
- Styling halaman web : [CSS](https://www.w3schools.com/css/)
- Interaktivitas halaman web : [JavaScript](https://www.w3schools.com/js/)

## Mencoba Penerapan Teknik Search Engine Optimization (SEO) Pada HTML [v] ⭐⭐⭐
![Screenshot (247)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/421becfe-e0ef-45aa-bc3f-503ce9e81706)
![Screenshot (244)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/af3bef81-8730-4aa9-ba8d-c5b8c7402499)

Referensi []

## Mencoba Pembuatan File JSON [v] ⭐⭐⭐
```
{
    "nama": "Adam Sirojuddin",
    "umur": 18,
    "Email": "muhammadadam.005@gmail.com",
    "hobi": ["berenang", "membaca", "menulis"],
    "status": "Single"
  }
  ```
![Screenshot (260)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/d6d76ad7-233e-454e-8324-466241436e90)

## Mencoba Penggunaan Web Hosting Dengan Untuk Halaman HTML [v] ⭐⭐⭐


## Mencoba Penggunaan Web Hosting Dengan Untuk Web Service [v] ⭐⭐⭐
![Screenshot (265)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/b9954227-da7c-4c9f-94ea-1020418d3d36)

## Mencoba HTTP Request dan Web API dengan Hoppscotch / Postman [v] ⭐⭐
![Screenshot (264)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/d3cf6e63-a33d-4b7c-ae4d-90a0362ccbac)

## Mendemonstrasikan Penggunaan Developer Tools Pada Web Browser (Firefox / Chrome) [v] ⭐⭐⭐⭐⭐
![Screenshot (231)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/5fcefaa5-cb5c-42b7-bd11-d9180b85824b)

## Mengeksplorasi dan Menjelaskan Layanan Cloud Service yang Diminati (GCP / AWS / Azure) [v] ⭐⭐
Saat ini banyak perusahaan berbasis digital seperti Gojek, Tokopedia, Instagram, Telkom memanfaatkan Cloud Service karena memudahkan untuk mulai pembangunan dan analisis menggunakan infrastruktur digital yang dapat berkembang secara dinamis dengan tarif yang sangat teliti.

Referensi cloud service: [Amazon Web Service](https://aws.amazon.com/) [Microsoft Azure](https://azure.microsoft.com) [Google Cloud Platform](https://cloud.google.com) 

## Mencoba Penggunaan Content Management System (Wordpress) [v] ⭐⭐⭐
![Screenshot (248)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/9b757a77-0fa1-48dd-8a2f-787053b87b11)

## Mendemonstrasikan Akses Konten Multimedia (Image, Audio, Video) ⭐⭐⭐

## Mencoba Edit Konten Multimedia (Image, Audio, Video) [v] ⭐⭐

## Mencoba Pembuatan Game dan Simulasi Menggunakan Logo [v] ⭐⭐

## Mencoba Pemrosesan Konten Multimedia (Image, Audio) Menggunakan Google Colab [v] ⭐⭐⭐

## Mencoba Web Tool AI Discriminative (Image Classification) [v] ⭐⭐⭐⭐

## Mencoba Web Tool AI Generative (Text to Image, Text to Text) [v] ⭐⭐⭐⭐

## Mencoba Model Machine Learning Menggunakan Google Colab, TTS, Speechrecognition, dan HuggingFace [v] ⭐⭐⭐

## Mencoba Data Visualization Dengan Tools [v] ⭐⭐
![Screenshot (232)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/0916a8cb-8c93-46cc-a478-1c718f1bc6ee)
![Screenshot (233)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/8f51c35c-224f-4b2f-beab-5f7e12cd63e1)

## Mencoba Data Visualization Dengan Code [v] ⭐⭐

## Mendaftar dan Mencoba Eksplorasi HuggingFace [v] ⭐⭐⭐
![Screenshot (234)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/ebd2e5c8-1536-4b5d-a7d9-10785fd5fe9b)


## Mendaftar dan Mencoba Eksplorasi Kaggle [v] ⭐⭐⭐⭐
![Screenshot (235)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/e31f2932-df80-441b-998e-26338bb75645)
![Screenshot (236)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/8dcb4252-17ca-411e-847e-8d2688dbb074)

## Mencoba Protokol Komunikasi IoT (MQTT) [v] ⭐
![Gambar WhatsApp 2023-12-30 pukul 14 58 27_251d1cf1](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/aa4da4a7-cc94-40c6-8ef6-b93178c92c58)

## Mencoba Memproses File CSV Menggunakan Google Colab [v] ⭐⭐

## Mencoba Memproses File Big Data ORC Menggunakan Google Colab [v] ⭐⭐

## Menjelaskan Jurnal, Conference, Artikel, Grade Jurnal [v] ⭐⭐⭐⭐⭐

## Eksplorasi Artikel Jurnal / Conference di Repository Terekognisi Internasional (IEEE / Arxiv / Science Direct / ACM /DBLP) [v] ⭐⭐⭐⭐

## Menonton Video Presentasi Tugas Akhir Informatika ⭐⭐⭐⭐⭐

## Mengeksplorasi Seluruh Profesi Terkait Informatika dan Profesi yang Diminati ⭐⭐⭐⭐
![Screenshot (255)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/60b980b7-56aa-4c5a-830b-54f1449bbb8e)
![Screenshot (254)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/ddd42725-4ec0-4941-9dc0-7574b3013d4f)
![Screenshot (270)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/0a222de2-2c6a-41ea-9e13-3a66c9f36f8b)

## Eksplorasi Tools Untuk Belajar Bahasa Inggris (Duolingo) ⭐⭐⭐
![Screenshot (267)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/a38bd9d9-fd0f-4f74-bcb6-11353264d4ff)
![Screenshot (266)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/ddace013-070c-4a5c-9750-b9464747d604)
![Screenshot (268)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/503aba79-a3bf-4143-a55a-629f60f32a61)

## Eksplorasi Tools Untuk Belajar Berbicara Bahasa Inggris (HelloTalk) ⭐⭐⭐ 

## Eksplorasi Lowongan Pekerjaan IT ⭐⭐⭐
![Screenshot (254)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/07944af2-26ce-4ea9-8904-eb99a7daf092)
![Screenshot (255)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/4c851efb-ad8b-421c-9f88-4d758c1bd2ae)

## Eksplorasi Lowongan Freelancer IT (Upwork / Toptal / Freelancer.com) ⭐⭐⭐
![Screenshot (253)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/6479279c-a261-480e-b594-09a4be8c3ac7)
![Screenshot (252)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/3227537b-6798-42c0-8e58-d9e9c94a0e9d)

## Eksplorasi dan Pilih Topik yang Diminati di Roadmap.sh ⭐⭐⭐
![Screenshot (237)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/fd899460-2750-4849-9cd4-1fcfce4fa859)

## Eksplorasi Top Github Project yang Diminati ⭐⭐ 
Machine Learning (https://github.com/PhilipPurwoko/Panduan-Belajar-Machine-Learning)
## Membangun Profil Linkedin dan Mengikuti Akun-Akun Inspirasif Bertema Informatika ⭐⭐⭐
Adapun Link Akun LinkedIn saya (https://www.linkedin.com/in/muhammad-adam-sirojuddin-munawar-624171273/) <br>
- Tampilan Profil saya
![Screenshot (238)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/ce4d238b-d35f-4e33-bfce-46e1f9426da9) <br>
- Tampilan Akun yang diikuti di LinkedIn <br> 

## Membangun Profil Github Page ⭐⭐⭐⭐⭐

## Mengikuti Workshop / Event / Course Terkait IT ⭐⭐⭐⭐
- Course ini saya dapatkan dari konten instagram
  (https://www.instagram.com/reel/C1T8h4HLuE0/?igsh=dHNobHZmenpzMHNy) <br>
![Screenshot (240)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/ce0f871f-db24-4bf9-9f2c-9fe75e23c077)
![Screenshot (239)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/717333ee-81fa-4cf6-b298-6fcdd338b826)
- Course RevoU
![Screenshot (250)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/6273a8db-0ef8-41de-8006-1e9043a313dc)
![Screenshot (249)](https://github.com/AdamMunawar/HelloInformatics/assets/143864605/f01a45eb-7746-4b76-8b7e-259b7498de4e)

## Membaca dan Mengambil Inspirasi Dari Buku Bertema Informatika ⭐⭐⭐⭐⭐





