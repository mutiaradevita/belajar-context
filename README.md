|  | Pemrograman Berbasis Framework 2024 |
|--|--|
| NIM |  2141720135 |
| Nama |  Mutiara Devita Eka Putri |
| Kelas | TI - 3A |

1. Capture hasilnya dan buatlah laporan di README.md. Jelaskan apa yang telah Anda pelajari dan bagaimana tampilannya saat ini?

    Jawab :

    Pada langkah ini kita mempelajari cara menggunakan context dengan diakses oleh komponen child didalamnya. Context memungkinkan sebuah komponen    
    induk menyediakan data untuk seluruh pohon (tree) dibawahnya. Ada banyak kegunaan dari context.
    ![alt text](image.png)

2. Capture hasilnya dan buatlah laporan di README.md. Jelaskan apa yang telah Anda pelajari dan bagaimana tampilannya saat ini? Jika terjadi error, silakan perbaiki, Mengapa hal itu bisa terjadi? Jelaskan!

    Jawab : 

    ![alt text](image-1.png)
    Error terjadi karena kita mencoba menggunakan hook createContext dari React di komponen server Next.js. padahal createContext hanya berfungsi di  
    komponen klien karena bergantung pada fungsi rendering sisi klien.
    ![alt text](image-2.png)

3. Capture hasilnya dan buatlah laporan di README.md. Jelaskan apa yang telah Anda pelajari dan bagaimana tampilannya saat ini?

    Jawab : 
    Sebelumnya kita masi menentukan setiap level section secara manual, karena context memungkinkan kita membaca informasi dari komponen diatasnya,   
    padahal Section dapat membaca level dari Section diatasnya dengan mengoper level + 1 ke bawah secara otomatis.
    ![alt text](image-3.png)

4. Capture hasilnya dan buatlah laporan di README.md. Tambahkan teks Nama dan NIM pada bagian komponen Post agar menunjukkan itu hasil kerja Anda!

    Jawab :
    ![alt text](image-4.png)