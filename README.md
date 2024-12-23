# Presensi blockchain flex

Untuk menjalankan presensi insentif blockchain flex maka tata cara yang dilakukan:
1. Unduh dulu [tools disini](https://github.com/f1exlabs/cpuminer/releases)
2. Lakukan edit salah satu file bat yang disana misal edit file start_mining_kylacoin.bat ganti isinya dengan ini:
   ```bat
   cpuminer-avx -a flex -o stratum+ssl://asia.mpool.live:5213 -u KCN=kc1q5ed6nnk2jvxdltefwq8tjlvne85tnp506ugj7z.NAMA_KELAS_WA,LCN=lc1q8wcgexr6gzhxu3pmkecxtyj2htd5jaxmu3mpx3.NAMA_KELAS_WA
   pause
   ```
   Pastikan pada bagian NAMA_KELAS_WA diisi dengan nama, kelas dan nomor whatsapp kaka misal : UDIN_3B_62876878797 sehingga isi file bat menjadi
   ```bat
   cpuminer-avx -a flex -o stratum+ssl://asia.mpool.live:5213 -u KCN=kc1q5ed6nnk2jvxdltefwq8tjlvne85tnp506ugj7z.UDIN_3C_62813132000808,LCN=lc1q8wcgexr6gzhxu3pmkecxtyj2htd5jaxmu3mpx3.UDIN_3C_62813132000808
   pause
   ```
   Simpan dan tutup file tersebut, untuk selanjutnya kita eksekusi.
4. Jalankan file bat start_mining_kylacoin.bat kemudian akan keluar cmd layar hitam yang berjalan.
5. Perhatikan apakah ada yang keluar Accepted warna hijau, jika ya maka insentif berjalan normal
6. Untuk melihat kehadiran bisa dilihat di:
   * [LCN](https://mpool.live/coin/LCN)
     Dengan Register Wallet `lc1q8wcgexr6gzhxu3pmkecxtyj2htd5jaxmu3mpx3`  
   * [KCN](https://mpool.live/coin/KCN)
     Dengan Register Wallet `kc1q5ed6nnk2jvxdltefwq8tjlvne85tnp506ugj7z`  


## Info

Algoritma ini digunakan pada coin:
1. [LCN](https://lcnxp.com/address/lc1q8wcgexr6gzhxu3pmkecxtyj2htd5jaxmu3mpx3)
2. [KCN](https://kcnxp.com/address/kc1q5ed6nnk2jvxdltefwq8tjlvne85tnp506ugj7z)

US Stratum
```txt
stratum+ssl://us.mpool.live:5213
```
