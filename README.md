# program1
DAFTAR ISI
==========
- [LAPORAN PROGRAM MENGHITUNG PENGIRIMAN BIAYA PAKET](#laporan-Latihan-String) 
    - [PSEUDECODE PROGRAM MENGHITUNG PENGIRIMAN BIAYA PAKET](#pseudecode-program-data-string)
    - [KESIMPULAN](#kesimpulan)

## PSEUDECODE MENGHITUNG PENGIRIMAN BIAYA PAKET
Berikut adalah penjelasan terperinci tentang fungsi hitung_biaya_pengiriman beserta kegunaan setiap bagian dari kodenya:

### Step 1
dalam program hitung_biaya_pengiriman didefinisikan dengan empat parameter:
    - berat: Berat paket dalam kilogram.
    - jarak: Jarak pengiriman dalam kilometer.
    - express: Boolean (default False), jika bernilai True, menunjukkan bahwa pengiriman adalah layanan express.
    - member: Boolean (default False), jika bernilai True, menunjukkan bahwa pelanggan adalah member.

![gambar1](screenshot/ss1.png)

### Step 2
Biaya dasar pengiriman diatur sebesar Rp 10.000.

![gambar2](screenshot/ss2.png)

### Step 3
Jika berat paket melebihi 5 kg, maka biaya tambahan sebesar Rp 5.000 ditambahkan ke total biaya.

![gambar3](screenshot/ss3.png)

### Step 4
Jika jarak pengiriman lebih dari 10 km, maka biaya tambahan sebesar Rp 8.000 ditambahkan ke total biaya.

![gambar4](screenshot/ss4.png)

### Step 5
Jika pelanggan memilih layanan express, maka biaya tambahan sebesar Rp 20.000 ditambahkan ke total biaya.

![gambar5](screenshot/ss5.png)

### Step 6
Jika pelanggan adalah member, maka total biaya akan dikalikan dengan 0.9 (10% diskon). Ini berarti biaya menjadi 90% dari total sebelumnya.

![gambar6](screenshot/ss6.png)

### Step 7
Fungsi mengembalikan nilai biaya sebagai integer. Ini memastikan bahwa hasil biaya pengiriman tidak memiliki pecahan.

![gambar7](screenshot/ss7.png)

### Step 8
Di sini, fungsi dipanggil dengan berat paket 6 kg, jarak 15 km, dan pengiriman express untuk pelanggan yang juga merupakan member. Setelah menjalankan fungsi ini, hasil total biaya pengiriman yang dihitung akan dicetak ke konsol.

![gambar8](screenshot/ss8.png)

## Output

![gambar9](screenshot/ss9.png)

Hasil Output yang kita dapatkan Bahwa nilai:
    - Berat = 6 kg (lebih dari 5 kg, kena tambahan Rp 5.000).
    - Jarak = 15 km (lebih dari 10 km, kena tambahan Rp 8.000).
    - Express = True (kena tambahan Rp 20.000).
    - Member = True (diskon 10%).

Langkah perhitungan biaya:
    - Biaya dasar = Rp 10.000
    - Tambahan berat > 5 kg = Rp 5.000 → Total = Rp 15.000
    - Tambahan jarak > 10 km = Rp 8.000 → Total = Rp 23.000
    - Tambahan layanan express = Rp 20.000 → Total = Rp 43.000
    - Diskon 10% untuk member → 10% dari 43.000 = 4.300
    - Total setelah diskon: 43.000 - 4.300 = Rp 38.700

## kesimpulan
Fungsi ini secara komprehensif menghitung biaya pengiriman dengan mempertimbangkan berat paket, jarak, jenis layanan pengiriman, dan status keanggotaan pelanggan, sesuai dengan aturan yang telah Anda berikan. Dengan menggunakan parameter yang fleksibel, Anda dapat memanggil fungsi ini untuk berbagai kasus pengiriman yang berbeda.







