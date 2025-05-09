# Tutorial A
1. How much data your publisher program will send to the message broker in one
run?<br>
`"5", "Zer0"` = 14 <br>
`"90", "Salvador"`= 18<br>
`"8", "Maya"`= 13<br>
`"7", "Rhys"`= 13<br>
`"9", "Axton"`= 14<br>
Total =  72 bytes
2. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber
program, what does it mean?<br>
Sama untuk menghubungkan ke RabbitMQ dan dirun di local dan kedua program dapat bertukar pesan

3. Edit Blocker <br>
![alt text](image.png)

4. Sending and Processing Event
![alt text](image1.png) <br>
![alt text](image2.png)<br>
Setelah menjalankan beberapa cargo run pada console publisher, console subscriber langsung muncul 5 data message bertahap-tahap, sesuai dengan program.

5. Hasil Chart setelah beberapa cargo run
![alt text](image3.png)
Muncul spike pada chart kedua karena pengiriman request cargo run berkali-kali pada publisher yang menyebabkan spiking pada message rates yang diterima subscriber
