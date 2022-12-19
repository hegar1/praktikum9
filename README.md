# praktikum9

# NAMA : Mohamad Hegar Sukmana Wibowo

# NIM : 312210332

# KELAS : TI.22.A.3

Disini saya akan menjelaskan tentang latihan yg kemarin 

# Penjelasan Pertama

<img width="528" alt="208421053-c5a785de-63bd-44e3-8ceb-d4b298b346f0" src="https://user-images.githubusercontent.com/115518483/208439364-5d29c3b7-d89a-4d96-b763-61d0dd283162.png">

Berikut adalah fungsi yang mengubah mengubah suhu suhu dari derajat Kelvin ke derajat Fahrenheit. Karena nol derajat Kelvin sedingin yang didapat. Ketika kode di atas dijalankan, muncul Exception yang bernama Traceback...AssertionError artinya terjadi error pada pernyataan assert.

# Penjelasan Kedua

<img width="536" alt="208420939-e6524b52-b93c-4ebe-ad80-a2767dae238c" src="https://user-images.githubusercontent.com/115518483/208439507-933a3a5f-6d0e-495b-820f-46a4d8cf6260.png">

contoh ini membuka file, menulis konten di file, dan keluar tidak ada masalah, Ini menghasilkan hasil berikut

Written content in the file successfully

Dan kenapa hasilnya begitu? karena else akan dijalankan ketika try adalah True

# Penjelasan Ketiga

<img width="530" alt="208421362-7a3c5205-c93b-44ec-9c74-435a642fc912" src="https://user-images.githubusercontent.com/115518483/208439590-35745173-ae36-4fcb-907e-7fa601dc6122.png">

Mengapa muncul error?

Error: can't find file or read data

r adalah read - Membuka file untuk membaca, error jika file tidak ada. Disini ingin membaca file bukan menulis maka dibawahnya fh = open("testfile", "r") tambahkan print(fh.readline()) dan fh.write dihapus. Setelah dijalankan, try dan else ditampilkan

# Penjelasan Keempat

<img width="537" alt="208421584-cfc7049c-d719-4517-ba92-e98b93501c09" src="https://user-images.githubusercontent.com/115518483/208439706-6496ebe6-b52a-466b-8a10-e87cfb80ffb8.png">

Menghasilkan output:

Error: can\'t find file or read data

Ini bukan error, karena finally dijalankan ketika try dan except dijalankan. Dan berhasil dibuat filenya setelah dijalankan

# Penjelasan Kelima

<img width="474" alt="208421861-00db8fbd-5371-4041-9ba5-1ebc101fb158" src="https://user-images.githubusercontent.com/115518483/208439787-fda39beb-136b-4060-bce2-e4db0c95da3a.png">

ketika dijalankan, maka muncul error. Hapus #!/usr/bin/python dan di except ValueError, Argument: ganti koma dengan as seperti except ValueError as Argument:agar tidak error. Jika dijalankan akan muncul error lagi

The argument does not contain numbers
invalid literal for int() with base 10: 'xyz'

kenapa? karena parameter def temp_convert harus mengandung angka

# Penjelasan Keenam

<img width="470" alt="208422073-506acd12-3d12-4d15-8bd7-f5e30ede3d25" src="https://user-images.githubusercontent.com/115518483/208439883-234f06c6-094d-49f7-9a84-05b7765f5ece.png">

Jika dijalankan muncul SyntaxError artinya ada kesalahan sintaks. Pada raise "Invalid level!", level ganti tanda koma dengan tanda plus. Cetak def dengan angka yang lebih besar dari 1

