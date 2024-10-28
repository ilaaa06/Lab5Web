# Lab5Web   
## Nur Laila   
## NIM 312310149 (TI 23 A1)  

## 1. Membuat Dokumen HTML dengan nama file
```sh
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Mengenal JavaScript</title>
</head>
<body>
    <h1>Pengenalan JavaScript</h1>
    <h3>Contoh document.write dan console.log</h3>
    <script>
        document.write("Hello World");
        console.log("Hello World");
    </script>
</body>
</html>
```
![Screenshot 2024-10-28 132941](https://github.com/user-attachments/assets/295601ee-de2d-4b23-901a-d08c9f193ce7)   

Kode JavaScript tersebut menggunakan document.write untuk menampilkan `"Hello World"` pada halaman web dan `console.log` untuk mencetaknya di konsol browser. `document.write` menampilkan teks langsung di halaman, sementara `console.log` berguna untuk debugging tanpa mengubah tampilan halaman.   

## 2. Pemakaian Alert sebagai property window.  
```sh
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>alert box</title>
</head>
<body>
    <script language = "Javascript">
        window.alert("ini merupakan pesan untuk anda");
    </script>
</body>
</html>
```
![Screenshot 2024-10-28 133628](https://github.com/user-attachments/assets/04d833e4-5a6d-4243-8a91-f324fff8024b)   
Kode JavaScript ini menggunakan `window.alert` untuk menampilkan kotak pesan (alert box) dengan teks "ini merupakan pesan untuk anda" segera setelah halaman dimuat. Kotak ini memerlukan interaksi pengguna untuk ditutup sebelum melanjutkan ke halaman.    

## 3. Pemakaian method dalam objek
```sh
    <title>Skrip javascript</title>
</head>
<body>
    percobaan memakai javascript:<br>
    <script language = "Javascript">
        document.write("selamat mencoba javascript<br>");
        document.write("semoga sukses!");
    </script>
</body>
</html>
```
![image](https://github.com/user-attachments/assets/c5569869-b690-4574-bbef-70830f724770)  
Kode JavaScript ini menampilkan teks "selamat mencoba javascript" diikuti dengan pindah baris (`<br>`), lalu menampilkan "semoga sukses!" pada halaman web. `document.write` digunakan untuk menulis teks langsung ke halaman saat kode dieksekusi.    

## 4. Pemakaian Prompt 
```sh
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pemasukkan Data</title>
</head>
<body>
    <script language = "Javascript">
        var nama = prompt("siapa nama anda?","masukkan nama anda");
        document.write("hai, "+ nama);
    </script>
</body>
</html>
```
![image](https://github.com/user-attachments/assets/08abd20a-1397-42fa-91ac-a7975b3198c7)   
setelah perintah berikut tampilannya akan seperti gambar diatas, dan ketik nama dengan "lala" maka akan muncul seperti ini:
![image](https://github.com/user-attachments/assets/9f42252b-7ec1-4e70-a212-915be3a72e58)   

## 5. Pembuatan fungsi dan cara pemanggilannya  
```sh
<html>
<body>
    <title>Contoh program javascript</title>
    <script language = "Javascript">
        function pesan(){
            alert("memanggil javascript lewat body onload")
        }
    </script>
</body>
<body onload=pesan()>
</body>
</html>
```
![image](https://github.com/user-attachments/assets/18f3514e-1904-4137-947c-badc53412b15)   
Kode ini menampilkan alert box dengan pesan "memanggil javascript lewat body onload" saat halaman dimuat. Atribut `onload=pesan()` di `<body>` memanggil fungsi `pesan()` secara otomatis saat halaman selesai dimuat, memunculkan pesan sebagai pop-up.   

## 6. Dasar Pemrograman Di Javascript
#### Operasi dasar aritmatika
```sh
<html>
<head>
    <title>contoh program javascript</title>
    <script language="javascript">
        function test (val1, val2)
        {
            document.write("<br>"+"perkalian : val1*val2"+"<br>")
            document.write(val1*val2)
            document.write("<br>"+"pembagian : val1/val2 "+"<br>")
            document.write(val1/val2)
            document.write("<br>"+"penjumlahan : val1+val2 "+"<br>")
            document.write(val1+val2)
            document.write("<br>"+"pengurangan : val1-val2 "+"<br>")
            document.write(val1-val2)
            document.write("<br>"+"mmodulus : val1%val2 "+"<br>")
            ocument.write(val1%val2)
        }
    </script>
</head>
<body>
    <input type="button" name="button1" value="arithmetic" onclick=test(9,4)>
</body>
</html>
```
![image](https://github.com/user-attachments/assets/616e5c3d-138c-400a-bfc0-913925f990c1)   
![image](https://github.com/user-attachments/assets/c5d86116-369b-4527-8b5d-37c1a3c346da)   
Kode ini mendefinisikan fungsi `test(val1, val2)` yang melakukan operasi aritmatika (perkalian, pembagian, penjumlahan, pengurangan, dan modulus) antara dua angka yang diberikan. Saat tombol "arithmetic" diklik, fungsi dipanggil dengan argumen 9 dan 4. Hasil dari setiap operasi ditampilkan di halaman menggunakan `document.write`, menghasilkan tampilan:
- Perkalian: 36
- Pembagian: 2.25
- Penjumlahan: 13
- Pengurangan: 5
- Modulus: 1

## 7. Seleksi kondisi (if..else) 
```sh
<html>
<head>
    <title>contoh if-else</title>
    <script language="javascript">
        var nilai = prompt("nilai (0-100): ", 0);
        var hasil = " ";
        if (nilai >= 60)
        hasil = "lulus";
        else
        hasil = "tidak lulus";
        document.write("hasil: " + hasil);
    </script>
</head>
<body>
</html>
```
![image](https://github.com/user-attachments/assets/052b4858-dc00-4e76-bf68-542a3c4952c4)   
mengetik nilai dengan 75, maka hasilnya adalah
![image](https://github.com/user-attachments/assets/a47e51fb-b88d-4074-902c-b26bdfe5404d)   

## 8. Penggunaan operator switch untuk seleksi kondisi  
```sh
<html>
<head>
    <title>contoh if-else</title>
    <script language="javascript">
            function test() {
                let val = window.prompt("Input nilai (1-5):")
                switch (val) {
                    case "1":
                        document.write("Bilangan satu")
                        break
                    case "2":
                        document.write("Bilangan dua")
                        break
                    case "3":
                        document.write("Bilangan tiga")
                        break
                    case "4":
                        document.write("Bilangan empat")
                        break
                    case "5":
                        document.write("Bilangan lima")
                        break
                    default:
                        document.write("Bilangan lainnya")
           }
    }
    </script>
</head>
<body>
    <input type="button" name="button1" value="switch" onclick=test()>
</body>
</html>
```
![image](https://github.com/user-attachments/assets/81b42794-4cb7-45fc-91f4-6c65263fd90e)  
setelah mengetik angka 5 pada output dari perintah tersebut maka hasilnya adalah "bilangan lima".  
![image](https://github.com/user-attachments/assets/44e95bdb-e8fa-4afc-9296-3799c6344016)

## 9. Form Input
#### Form Input
```sh
<html>
<head>
    <title>contoh if-else</title>
    <script language="javascript">
    function test() {
        ver val1=document.kirim.T1.value
        if (val1%2==0)
            document.kirim.T2.value="bilangan genap"
        else
            document.kirim.T2.value="bilangan ganjil"
    }
    </script>
</head>
<body>
    <form method="POST" name="kirim">
        <p>BIL <input type="text" name="T2" size="20">
        MERUPAKAN BIL <input type="text" name="T2" size="20"></p>
        <p><input type="button" value="TEBAK" name="B1" onclick=test()></p>
    </form>
</body>
</html>
```
![image](https://github.com/user-attachments/assets/746218c1-7026-47b0-9232-330c59ec3f5a)   
Kode ini memeriksa apakah nilai pada kotak input pertama (`T1`) adalah bilangan genap atau ganjil. Ketika tombol "TEBAK" diklik, hasilnya ditampilkan di kotak input kedua (`T2`) sebagai "bilangan genap" atau "bilangan ganjil".   

## 10. from button
```sh
<html>
<head>
    <title>objek document</title>
</head>
<body>
    <script language="javascript">
        function ubahWarnaLB(warna) {
            document.bgColor = warna;
        }
        function ubahWarnaLD(warna) {
            document.fgColor = warna;
        }
        </script>
        <h1>tes</h1>
        <form>
            <input type="button" value="Latar Belakang Hijau" onclick="ubahWarnaLB('GREEN')">
            <input type="button" value="Latar Belakang Putih" onclick="ubahWarnaLB('WHITE')">
            <input type="button" value="Teks Kuning" onclick="ubahWarnaLD('YELLOW')">
            <input type="button" value="Teks Biru" onclick="ubahWarnaLD('BLUE')">
        </form>
        <script language = "javascript">
            document.write("Dimodifikasi terakhir pada " +
            document.lastModified);
        </script>
</body>
</html>
```
![image](https://github.com/user-attachments/assets/8ba2ba12-254e-4d8c-83bb-4dcf31df8448)   
![image](https://github.com/user-attachments/assets/23652daf-214b-4226-bfeb-d1c489de987c)   
![image](https://github.com/user-attachments/assets/a8af0d2f-46f9-42b4-bdcc-1ce968cad758)   
![image](https://github.com/user-attachments/assets/9942ee2a-8cd5-41d3-bcd0-410606938a13)   
Kode ini menyediakan tombol untuk mengubah warna latar belakang dan warna teks halaman. Fungsi `ubahWarnaLB` mengubah warna latar belakang (`bgColor`), sementara `ubahWarnaLD` mengubah warna teks (`fgColor`). Tombol-tombol yang ada memungkinkan pengguna memilih warna latar belakang hijau atau putih dan warna teks kuning atau biru. Di bagian bawah, `document.write` menampilkan informasi terakhir kali halaman dimodifikasi dengan `document.lastModified`.      

## 11. HTML DOM
#### Pilihan menggunakan checkBox dengan perhitungan otomatis
```sh
<!--
File: daftar_menu.html
-->
<html>
<head>
    <title>Daftar Menu</title>
    <script>
        function hitung(ele) {
            var total = document.getElementById('total').value;
            total = (total ? parseInt(total) : 0);
            var harga = 0;

            if (ele.checked) {
                harga = ele.value;
                total += parseInt(harga);
            } else {
                harga = ele.value;
                if (total > 0)
                    total -= parseInt(harga);
            }

            document.getElementById('total').value = total;
        }
    </script>
</head>
<body>
    <h1>Daftar Menu Makanan</h1>
    <label><input type="checkbox" value="5000" id="menu1" onclick="hitung(this);"> Ayam Goreng Rp. 5.000</label><br />
    <label><input type="checkbox" value="500" id="menu2" onclick="hitung(this);"> Tempe Goreng Rp. 500</label><br />
    <label><input type="checkbox" value="2500" id="menu3" onclick="hitung(this);"> Telur Dadar Rp. 2.500</label><hr />
    <strong>Total Bayar: Rp. <input id="total" type="text" /></strong>
</body>
</html>
```
![image](https://github.com/user-attachments/assets/1962e747-6152-4f9a-9c2d-8ededa1fe2ab)   
Kode ini menampilkan daftar menu makanan dengan checkbox untuk memilih item dan menampilkan total harga. Fungsi `hitung` akan menambah atau mengurangi harga dari item yang dipilih atau dibatalkan, lalu memperbarui nilai total di kotak input `total`. Setiap checkbox memiliki nilai harga sesuai dengan itemnya, dan ketika dipilih, total harga langsung diperbarui di halaman.   

# Pertanyaan dan Tugas
## 1. Buat script untuk melakukan validasi pada isian form.
```sh
<!DOCTYPE html>
<html>
<head>
    <title>Form dengan Validasi</title>
    <script>
        function validasiForm() {
            // Mengambil nilai dari masing-masing field
            var nama = document.forms["myForm"]["nama"].value;
            var email = document.forms["myForm"]["email"].value;
            var usia = document.forms["myForm"]["usia"].value;

            // Memeriksa apakah nama sudah diisi
            if (nama == "") {
                alert("Nama harus diisi");
                return false;
            }

            // Memeriksa apakah email sudah diisi dan dalam format yang benar
            if (email == "") {
                alert("Email harus diisi");
                return false;
            } else {
                var emailFormat = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
                if (!email.match(emailFormat)) {
                    alert("Format email tidak valid");
                    return false;
                }
            }

            // Memeriksa apakah usia sudah diisi dan merupakan angka
            if (usia == "") {
                alert("Usia harus diisi");
                return false;
            } else if (isNaN(usia)) {
                alert("Usia harus berupa angka");
                return false;
            }

            // Jika semua validasi terpenuhi, form akan dikirim
            return true;
        }
    </script>
</head>
<body>
    <h2>Formulir Pendaftaran</h2>
    <form name="myForm" onsubmit="return validasiForm()">
        Nama: <input type="text" name="nama"><br><br>
        Email: <input type="text" name="email"><br><br>
        Usia: <input type="text" name="usia"><br><br>
        <input type="submit" value="Submit">
    </form>
</body>
</html>
```
![image](https://github.com/user-attachments/assets/29130478-7328-4be9-8a15-90a736f42d23)   
Fungsi validasiForm: Fungsi ini dipanggil saat form dikirim.   
Validasi Nama: Memastikan bahwa field "nama" tidak kosong.   
Validasi Email: Memastikan bahwa email tidak kosong dan formatnya valid menggunakan regex.   
Validasi Usia: Memastikan bahwa usia tidak kosong dan berupa angka.   
Jika ada isian yang tidak valid, JavaScript akan menampilkan pesan peringatan (alert) dan mencegah pengiriman form.   













