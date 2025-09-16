# Case1-Praktikum-JARKOM

# GNS3 Latihan Praktikum 

## Task 1
- Buat sambungan jaringan antara netics-pc-1 dan netics-pc-2

  ![imagealt](https://github.com/xaldinzz/image/blob/main/Screenshot%202025-09-16%20131754.png?raw=true)
  
- Set IP address di masing-masing interface di masing-masing pc

  ![imagealt](https://github.com/xaldinzz/image/blob/main/Screenshot%202025-09-16%20203717.png?raw=true)
  ![imagealt](https://github.com/xaldinzz/image/blob/main/Screenshot%202025-09-16%20203722.png?raw=true)

- Cek ip address masing-masing di netics-pc-1 dan netics-pc-2 dengan Gunakan tool ping untuk melakukan connectivity test

  ![imagealt](https://github.com/xaldinzz/image/blob/main/Screenshot%202025-09-16%20204143.png)
  ![imagealt](https://github.com/xaldinzz/image/blob/main/Screenshot%202025-09-16%20204156.png)

-  Dari netics-pc-1 ke ip address netics-pc-2 dan sebaliknya
  
  ![imagealt](https://github.com/xaldinzz/image/blob/main/Screenshot%202025-09-16%20204350.png)
  
- Penjelasan: Untuk Task ini kami disuruh untuk melakukan link kepada komputer netics1 dan netics2 setelah itu kami melakukan set IP Address kepada masing masing komputer seperti yang ada di gambar diatas. setelah itu aku melakukan ping untuk kedua komputer tersebut. setelah itu aku akan menjelaskan task 2

  ## Task 2
  
- Lakukan uji performance test dengan iperf3
  
- Di netics-pc-1 jalankan iperf server dengan iperf -s
![imagealt](https://github.com/xaldinzz/image/blob/main/Screenshot%202025-09-16%20205436.png)

- Di netics-pc-2 jalankan iperf client dengan
![imagealt](https://github.com/xaldinzz/image/blob/main/Screenshot%202025-09-16%20205328.png?raw=true)
Penjelasan: Untuk task ini aku melakukan iperf tool untuk melaporkan apa yang dia dapatkan ketika mereka melakukan interaksi, bisa di liat di gambar bahwa iperf3 melaporkan Kapasitas yang bisa dicapai oleh interface eth0 untuk transfer data hanya 1.22 Gbps (sender) dan 207 Mbps (receiver).

## Task 3
- Tambahkan satu netics-pc (netics-pc-3), dengan 2 interfaces yang terhubung diantara netics-pc-1 dan netics-pc-2
  ![imagealt](https://github.com/xaldinzz/image/blob/main/Screenshot%202025-09-16%20132847.png?raw=true)
- Simulasikan packet loss hingga 10 persen (simulasi 10 dari 100 packets hilang dalam perjalanan)
  Sebelum dilakukan packet loss 10 persen:
  ![imagealt](https://github.com/xaldinzz/image/blob/main/Screenshot%202025-09-16%20134526.png?raw=true)
  Setelah kode ini dilakukan:
  ![imagealt](https://github.com/xaldinzz/image/blob/main/Screenshot%202025-09-16%20134734.png?raw=true)
  Maka dia akan menampilkan packet loss yang mendekati 10 persen:
  ![imagealt](https://github.com/xaldinzz/image/blob/main/Screenshot%202025-09-16%20134734.png?raw=true)
- Jalankan iperf3 -s di netics-pc-1, Jalankan iperf3 client dengan speed 100Mbps di netics-pc-2, traffic akan melewati netics-pc-3 dengan throughput/bitrate 100Mbps (ket: netics-pc-2 → netics-pc-3 → netics-pc-1
   Sebelum itu dia mempunyai kode seperti itu tetapi saat saya melakukannya saya memiliki masalah karena kodenya tidak bisa di jalankan maka dari itu saya akan mengecilkan jarak jangkauannya seperti gambar di bawah:
  ![imagealt](https://github.com/xaldinzz/image/blob/main/Screenshot%202025-09-16%20140531.png?raw=true)
  maka Iperf3 nya akan memunculkan seperti ini:
  ![imagealt](https://github.com/xaldinzz/image/blob/main/Screenshot%202025-09-16%20140519.png?raw=true)
Penjelasan soal tersebut adalah Di task ini kami disuruh untuk menyimulasikan packet loss hingga 10 persen dan setelah itu kita akan menjalankan iperf3 dengan speed seperti di soal yang saya modifikasi sedikit.

## Task 4





  
  
