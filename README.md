# JobSheet 1 DASAR PEMROGRAMAN ESP32 UNTUK PEMROSESAN DATA INPUT/OUTPUT ANALOG DAN DIGITAL
# ESP32_InputOutput
 
ESP32 adalah nama dari mikrokontroler yang dirancang oleh perusahaan yang berbasis di Shanghai, China yakni Espressif Systems. ESP32 menawarkan solusi jaringan WiFi dan BLE. ESP32 menggunakan prosesor dual core yang berjalan di instruksi Xtensa LX16. Selain itu, ESP32 telah mendukung protokol komunikasi seperti I2C, UART dan SPI.

**ALAT DAN BAHAN** 
1) ESP32
2) Breadboard
3) Kabel jumper
4) Potensiometer 10k Ohm (1)
5) Sensor Capacitive Soil Moisture
6) LED (5) dan Push Button (3)
7) Multimeter
8) Resistor 330,1K, 10K Ohm (@ 3)


**HASIL KELUARAN**

**1) Instal lebih dulu Board ESP32 pada Arduino IDE** <br />
Klik menu Tools > Board: > Pilih Boards Manager lalu Pada kolom pencarian tulis ESP32 kemudian install dan tunggu sampai 
selesai.
![image](https://user-images.githubusercontent.com/41616849/210590603-9a7c81db-ac6e-4996-b249-10837fb9d26c.png)

   
**2) Mengakses GPIO ESP32**  <br />
<br />a) Program ini bisa mengendalikan satu LED dengan push button dimana LED bisa menyala apabila push button ditekan dan akan mati apabila dilepaskan.

https://user-images.githubusercontent.com/122078276/210948786-52b5cba7-572d-4efb-aeb6-177b32088713.mp4

b) Selanjtunya pada program GPIO yang kedua, ditambahkan 1 LED yang akan mati selama 5 setik dan menyala selama 5 detik. Apabila push button tetap ditekan tetapi waktu sudah habis, LED akan tetap mati.

https://user-images.githubusercontent.com/122078276/210949101-4dfc7864-c88e-44f0-87d4-980e8606089a.mp4



c) Pada percobaan GPIO yang ketiga menggunakan 3 LED yang dikendalikan oleh satu push button. Saat push button ditekan maka LED akan menyala secara berurutan (continue).



https://user-images.githubusercontent.com/122078276/210949177-1ef6574a-0fbf-4af5-9188-dd6f7f38de73.mp4


**2) Mengakses PWM ESP32**  <br />
<br />a) Percobaan ini menggunakan metode Pulse Width Modulation yaitu pendekatan pelebaran pulsa yang menghasilkan nilai tegangan analog dengan maksimal tegangan HIGH 3,3 V dan LOW 0 V. Pin pada PWM mengeluarkan sinyal digital yang dihasilkan dari dutty cycle (perbandingan HIGH dan LOW dalam 1 periode). LED akan menyala 5x lebih terang. Karena terdapat delay 0,015 maka LED akan redup dengan kecepatan 0,015 detik, lalu kemudian akan terang kembali.


https://user-images.githubusercontent.com/122078276/210949540-dc663221-323e-430a-bbe4-95353e4cfa8d.mp4



b) Percobaan yang kedua hampir sama dengan PWM yang pertama, hanya saja menggunakan 3 LED.

https://user-images.githubusercontent.com/122078276/210949628-55bb2e75-587c-4bab-b029-bb1043e32e55.mp4


**2) Mengakses ADC and DAC ESP32**  <br />
<br /> a) Percobaan ini menggunakan potensiometer yang menghasilkan output apabila potensiometer diputar. Semakin ke kanan maka nilainya akan semakin bertambah dan sebaliknya.


https://user-images.githubusercontent.com/122078276/210949797-1fa572a3-5480-400b-8714-8686cbf6d06b.mp4


b) Percobaan ini ditambahkan dengan LED dan GPIO. Ketika program ini dijalankan akan menghasilkan output apabila potensiometer diputar ke kanan maka lampu akan semakin terang nyala lampunya dan begitupun sebaliknya.



https://user-images.githubusercontent.com/122078276/210949889-c1b43c0d-ab8d-4f55-af86-b0f82bd720af.mp4




