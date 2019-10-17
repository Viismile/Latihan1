# Latihan 1

## Mengenal Version Control System (VCS)
VCS adalah sebuah sistem yang mencatat semua perubahan yang terjadi pada file atau sekumpulan file seiring dengan terjadinya pergantian atau perubahan yang telah dilakukan, jadi kita dapat melihat versi spesifiknya kapan saja.

### Langkah-langkah menggunakan git.
1. Membuka git
2. Mengatur email dan username dengan perintah "git config --global user.mail <email> dan git config --global user.name <nama>
3. Membuat atau memilih folder untuk dijadikan sebagai repository lokal, kemudian membuat repository dengan perintah 'git init'
4. Membuat file dengan perintah, contoh 'echo "# Latihan1" > Readme.md'
5. Mengedit isi file tersebut dengan perintah 'nano <nama_file>'
6. Gunakan perintah "git add" setelah melakukan perubahan
7. Jika telah yakin dengan perubahannya, berikan catatan dengan menggunakan perintah 'git commit -m "catatan"'
8. Membuat sambungan antara repository lokal dengan server dengan perintah 'git remote add origin <link server>'
9. Mengirim perubahan ke server dengan perintah 'git push -u origin master'




# Latihan 2

## Mengenal apa itu Operator
- Operator adalah simbol khusus pada Phyton yang melakukan perhitungan aritmatika atau logika.
- Nilai yang dihasilkan oleh operator disebut Operand.

### Lab 2
Pada lab 2 kita mencoba untuk mengoperasikan operator, contoh:
1. a=input("Masukkan nilai a: ")
2. b=input("Masukkan nilai b: ")
    Langkah 1 dan 2 nanti akan meminta kita untuk memasukkan nilai kepada variable a dan b.
3. print("Variable a= ", a)
4. print("Variable b= ", b)
    Langkah 3 dan 4 akan menuliskan ulang nilai yang telah kita masukkan tadi.
5. print("Hasil penggabungan {1}&{0}=%d".format(a,b) %(a+b))
    Langkah 5 akan menggabungkan variable a dan b, tetapi pada tahap ini akan terjadi error karena tipe data pada variable adalah string sedangkan yang diminta adalah nomor atau integer, maka kita harus mengubah '%d' menjadi '%s' agar sistem membacanya sebagai string bukan integer.
    Lalu karena {1} adalah variable b dan {0} adalah variable a (b, a), maka diubah menjadi {0}&{1} agar tidak terbalik dan sesuai dengan format yang akan digabungkan.

6. a=int(a)
7. b=int(b)
    Langkah 6 dan 7 akan mengkonversikan tipe data variable a dan b, dari yang tadinya str menjadi int.
8. print("Hasil penjumlahan {1}+{0}=%d".format(a,b) %(a+b))
    Langkah 8 akan menjumlahkan nilai variable a dan b, dan sebaiknya {1}+{0} diubah menjadi {0}+{1}
9. print("Hasil pembagian {1}/{0}=%d".format(a,b) %(a/b))
    Langkah 9 akan melakukan pembagian nilai variable a dengan b, ubah {1}/{0} menjadi {0}/{1} agar nilai yang dibagi sesuai dengan hasilnya.
    Gunakan '%f' atau '%s' apabila hasilnya adalah angka desimal