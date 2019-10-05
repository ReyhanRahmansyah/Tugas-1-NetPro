# Tugas-1-NetPro
Tugas NetPro 1 Reyhan Rahmansyah

Tugas 1

1. TCP Finite State Machine
	Diagram finite state machine dari TCP Connection pada nomer 1 maksudnya adalah diagram yang menjelaskan alur three way handshake pada koneksi TCP.

Dalam segi Client : Client mengirim SYN (SYN SENT), Client menerima SYN dan ACK, lalu mengirim ACK (Connection Established), Client mengirimkan FIN (FIN WAIT 1), Client menerima ACK (FIN WAIT 2), Client menerima FIN dan mengirim ACK (TIME WAIT), dan terjadi timeout, maka koneksi berakhir (Closed)

Dalam segi Server : Server membuat koneksi (Listen), Server menerima SYN, lalu mengirim SYN, ACK (SYN RCVD), Server menerima ACK (Connection Established), Server menerima FIN, lalu mengirim ACK (Close wait), Server mengirim FIN (Last ACK), dan server mengakhiri koneksi (Closed).

2. For

For berfungsi untuk mengulang pernyataan jika kondisi atau syarat tertentu terpenuhi. Hampir sama dengan while tetapi keunggulannya adalah kita dapat memberi nilai dan condition increase atau decrease.

Hasil running : Silahkan lihat di file "hasil running"












If-Else
If-else adalah suatu percabangan, dapat juga dikatakan pemilihan dalam program. Jika kondisi if false, makan akan dijalankan ke else if berikutnya, jika semua if kondisinya false, maka yang dijalankan adalah else. If akan dijalankan jika kondisinya true.

Hasil Running :Silahkan lihat di file "hasil running"








3. Array
Array adalah sekumpulan variabel yang memiliki tipe data yang sama dan dinyatakan dengan nama yang sama. Array dapat menyimpan data maupun referensi objek dalam jumlah banyak dan terindeks.

Hasil Running :Silahkan lihat di file "hasil running"









Function
Function merupakan sebuah struktur yang mengandung sekelokmpok pernyataan yang akan dilaksanakan jika function tersebut dipanggil untuk dieksekusi. Kecuali untuk function utama yaitu int main() yang akan dieksekusi secara otomatis.

Hasil Running :Silahkan lihat di file "hasil running"





4. Struct
Struct adalah kumpulan variabel yang dinyatakan dengan sebuah nama, dengan sifat setiap variabel dapat memiliki tipe yang berlainan.

Hasil Running : Silahkan lihat di file "hasil running"










Method
Method adalah function yang berada di suatu class. Seluruh fungsi dan sifat function bisa diterapkan ke dalam method, seperti argumen/parameter, mengembalikan nilai, dan lain-lain






5. Multiple Return Value

Dalam hasil running yang dilakukan pada nomer 5, dapat disimpulkan bahwa Multiple Return Value dalam bahasa go dapat mengembalikan lebih dari 1 nilai.

Hasil Running : Silahkan lihat di file "hasil running"






Command Line :Silahkan lihat di file "hasil running"







6. Simple Web Application

Hasil Running :Silahkan lihat di file "hasil running"

- Go dapat digunakan untuk membuat aplikasi web sederhana.
- HandleFunc berfungsi untuk menentukan route dan menentukan konten dalam web saat alamat diakses
- Listen And Serve dapat menentukan port dan menjalankan aplikasi pada port yang telah ditentukan.

7. Simple Web Application Using Config (Viper)

Cara mengerjakan nomer 7 :
- Jalankan perintah go get -u github.com/spf13/viper pada terminal
- Buat file config yang bernama config.json seperti di bawah ini





- Lalu buat code yang berisikan code ini dan jalankan. Buka browser dengan localhost:8000

- Setelah browser dengan localhost:8000 dibuka, maka akan muncul seperti di bawah ini :
