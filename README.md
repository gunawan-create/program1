# PROGRAM 1
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

![Image](https://github.com/user-attachments/assets/c58362a8-eb2b-4ee8-be85-d2a7be040d03)

### Step 2
Biaya dasar pengiriman diatur sebesar Rp 10.000.

![Image](https://github.com/user-attachments/assets/709396f5-8d9a-4e7f-8bdd-4cc5f0d3af63)

### Step 3
Jika berat paket melebihi 5 kg, maka biaya tambahan sebesar Rp 5.000 ditambahkan ke total biaya.

![Image](https://github.com/user-attachments/assets/ba35d0b1-d4e8-4095-ad22-c486b37a4dac)

### Step 4
Jika jarak pengiriman lebih dari 10 km, maka biaya tambahan sebesar Rp 8.000 ditambahkan ke total biaya.

![Image](https://github.com/user-attachments/assets/5675b548-bc16-4e5b-8a1f-c61066c3bcfb)

### Step 5
Jika pelanggan memilih layanan express, maka biaya tambahan sebesar Rp 20.000 ditambahkan ke total biaya.

![Image](https://github.com/user-attachments/assets/e5e5b8fe-5e18-4ab9-9f97-33ddaa6e04c5)
### Step 6
Jika pelanggan adalah member, maka total biaya akan dikalikan dengan 0.9 (10% diskon). Ini berarti biaya menjadi 90% dari total sebelumnya.

![Image](https://github.com/user-attachments/assets/c61d8ac6-ed32-40f0-841f-8a08b428eeea)

### Step 7
Fungsi mengembalikan nilai biaya sebagai integer. Ini memastikan bahwa hasil biaya pengiriman tidak memiliki pecahan.

![Image](https://github.com/user-attachments/assets/73b543cf-0d2c-4ac1-8094-38d9c3540f3c)

### Step 8
Di sini, fungsi dipanggil dengan berat paket 6 kg, jarak 15 km, dan pengiriman express untuk pelanggan yang juga merupakan member. Setelah menjalankan fungsi ini, hasil total biaya pengiriman yang dihitung akan dicetak ke konsol.

![Image](https://github.com/user-attachments/assets/b70fd2d6-b37f-417d-b790-a73245d0856e)

## Output

<img width="170" alt="Image" src="https://github.com/user-attachments/assets/39e55708-4b90-4f96-ae18-734385d78011" />

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







