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
10. Selesai
