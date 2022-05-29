# Praktikum 2 Probstat

- Nama : Muhammad Afif Dwi Ardhiansyah
- NRP : 5025201212
- Kelas : Probstat - B

## Screenshot dan Penjelasan Singkat

### Nomor 1
a) Cari standar deviasi dan data selisih pasangan <br><br>
![image](https://user-images.githubusercontent.com/87472849/170867553-b2cd1c27-7360-4cd2-87d3-b321e8bce067.png)<br><br>
Hasil:<br><br>
![image](https://user-images.githubusercontent.com/87472849/170867577-d005ceef-4259-42ec-be4d-0aa01a2ac24a.png)<br><br>
standev adalah standar deviasi yaitu 6.3596 dan data selisih adalah diff {22, 20, 3, 13, 20, 18, 16, 23}<br><br>

b) Cari nilai t (p-value)<br><br>
![image](https://user-images.githubusercontent.com/87472849/170868112-26dbef46-974b-40a3-830e-b978bb4ba6ce.png)<br><br><br><br>
![image](https://user-images.githubusercontent.com/87472849/170868125-a8830abb-ba76-4683-8779-3ef889dbce43.png)<br><br>

t hitung adalah 7.6525 dan p-value adalah 0.00006003<br><br>

c) <br><br>
Karena p-value di bawah nilai signifikan (0.005), maka h0:"“tidak ada pengaruh yang signifikan secara statistika dalam hal kadar saturasi oksigen , sebelum dan sesudah melakukan aktivitas", sehingga kesimpulannya adalah tidak ada pengaruh yang signifikan secara statistika dalam hal kadar saturasi oksigen<br><br>

### Nomor 2

Diketahui jumlah sampel adalah 100, rata-rata adalah 23500, dan standar deviasi 3900<br>
Klaim : mobil dekemudikan rata-rata lebih dari 20.000 kilometer per tahun<br><br>

a) Apakah anda setuju dengan klaim tersebut?<br><br>
Berdasarkan uji z sebagai berikut:<br><br>
![image](https://user-images.githubusercontent.com/87472849/170869142-f362ac87-50e3-4552-80e5-1f84d86d36ea.png)<br><br>
Didapatkan:<br><br>
![image](https://user-images.githubusercontent.com/87472849/170869181-6a566f8e-202c-4014-a076-99c7a598852e.png)<br><br>
Dari hasil tersebut, p-value kurang dari 0.005. Sehingga h0(rata-rata kurang dari sama dengan 20000 km) ditolak<br><br>

b) Jelaskan maksud dari output yang dihasilkan!<br><br>
Maksud dari output di atas adalah z hitung adalah 60.256. Dari nilai z tersebut didapat p value < 2.2*10^-16. Dengan persentase confidence 95% adalah 22858.51<br><br>

c) Kesimpulan berdasarkan P-Value yang dihasilkan<br><br>
Karena p-value kurang dari nilai signifikan (0.005), maka h0:(rata-rata mobil yang dikemudikan kurang dari 20000 kilometer per tahun) ditolak. Sehingga klaim rata-rata mobil yang dikemudikan kurang dari 20000 kilometer per tahun adalah benar

## Nomor 3

a) H0 dan H1 untuk masalah tersebut:<br><br>
H0: Saham di kota Bandung dan Bali sama<br>
H1: Saham di kota Bandung dan Bali berbeda<br><br>

b) Sampel Statistik:<br><br>
![image](https://user-images.githubusercontent.com/87472849/170877450-ce884d65-cdc2-42c0-92b9-840197caadf2.png)<br><br>
Dari hasil tersebut, didapatkan t hitung adalah 1.9267, p-value adalah 0.03024, dan df adalah 44<br><br>

c) Uji Statistik (df =2):<br><br>
![image](https://user-images.githubusercontent.com/87472849/170878450-92467738-fc95-4b5a-846f-2caa7d946ab4.png)<br><br>


d) Nilai Kritikal:<br><br>
![image](https://user-images.githubusercontent.com/87472849/170878510-d6453092-76e8-460c-8070-c57d98e020fd.png)<br><br>

e) Keputusan:<br><br>
Karena p-value kurang dari nilai signifikan, maka h0:(Saham di kota Bandung dan Bali sama) ditolak<br><br>

f) Kesimpulan:<br><br>
Kesimpulannya adalah saham di kota Bandung dan Bali tidak sama / berbeda<br><br>

### Nomor 4

a) <br><br>
Masing-masing jenis spesies menjadi 3 subjek (grup1, grup2, grup3): <br><br>
![image](https://user-images.githubusercontent.com/87472849/170872938-197f3774-aedf-44ca-8405-3e06825a6856.png)<br><br>
Plot kuantil normal grup 1:<br><br>
![image](https://user-images.githubusercontent.com/87472849/170871563-317a3a6f-8fa5-4717-84f0-de90886bdc63.png)<br><br>
Plot kuantil normal grup 2:<br><br>
![image](https://user-images.githubusercontent.com/87472849/170871593-ccb60044-f25e-4e43-9160-57fa5baeb153.png)<br><br>
Plot kuantil normal grup 3:<br><br>
![image](https://user-images.githubusercontent.com/87472849/170871610-ca0f5650-837c-4511-841b-2ef15d1836f2.png)<br><br>

Berdasarkan ketiga gambar di atas, tidak ditemukan adanya outlier utama dalam homogenitas varians.<br><br>

b) <br><br>
nilai p yang didapatkan:<br><br>
![image](https://user-images.githubusercontent.com/87472849/170870883-e6e0f287-5ffd-42bd-9ce0-fb0a284bcdcb.png)<br><br>
Karena p lebih dari nilai signifikan, maka h0 diterima.<br><br>

c) <br><br>
model linier dengan Panjang versus Grup:<br><br>
![image](https://user-images.githubusercontent.com/87472849/170871872-defafb8c-91ac-44d4-b101-d91a3907ee7f.png)<br><br>

d) <br><br>
Nilai p adalah 0.0013, Karena p-value kurang dari 0.005, maka h0 ditolak<br><br>

e)<br><br>

Post-hoc test Tukey HSD:<br><br>
![image](https://user-images.githubusercontent.com/87472849/170872692-04035a02-72ab-4f59-bbbe-120a7a907542.png)<br><br>
Berdasarkan hasil di atas grup3-grup1 satu0satunya yang p-value lebih dari 0.05, sehingga h0 diterima. Sedangkan p-value grup2-grup1 dan grup3-grup2 kurang dari 0.05 sehingga h0 ditolak<br><br>

e)<br><br>
Visualisasi dengan ggplot2:<br><br>
![image](https://user-images.githubusercontent.com/87472849/170872767-d4ed47a3-ce89-40ce-9360-3436f0d2e7aa.png)<br><br>

### Nomor 5

a)<br><br>
Plot sederhana:<br><br>
![image](https://user-images.githubusercontent.com/87472849/170873261-9ebff734-9d6e-4485-b79a-f868255dd021.png)<br><br>

b) <br><br>
Uji ANOVA dua arah:<br><br>
![image](https://user-images.githubusercontent.com/87472849/170873580-cb71bfc0-5df2-4687-a5d6-57f0ffb1b4f4.png)<br><br>

c) Tabel dengan mean dan standar deviasi keluaran cahaya untuk setiap perlakuan:<br><br>
![image](https://user-images.githubusercontent.com/87472849/170873659-1bd94b67-04d0-4a32-b5b0-7bdca598e6eb.png)<br><br>

d) Uji Tukey:<br><br>
![image](https://user-images.githubusercontent.com/87472849/170873757-a291f960-1daf-4b2d-842e-aa7bde540aaa.png)
<br>
![image](https://user-images.githubusercontent.com/87472849/170873780-16a66e78-f88e-4c62-aa16-8dbd43bc037c.png)
<br><br>

e) Compact letter display untuk menunjukkan perbedaan signifikan antara uji Anova dan uji Tukey: <br><br>
![image](https://user-images.githubusercontent.com/87472849/170873883-cc233b4e-711a-48f8-9ab4-336d4723be43.png)<br><br>







