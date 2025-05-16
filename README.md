1. How much data your publisher program will send to the message broker in one
run?  
    publisher akan mengirim 5 data ke message broker dalam satu waktu  

2. The url of: `amqp://guest:guest@localhost:5672` is the same as in the subscriber
program, what does it mean?
    url yang sama menandakan bahwa publisher akan terhubung ke server yang sama dengan subscriber untuk mengirim pesan yang akan diterima subscriber

Running RabbitMQ  
![](./img/Screenshot%202025-05-16%20184410.png)  



![](./img/console.png)   
Ketika publisher dijalankan, publisher akan mengirimkan pesan melalui broker. Lalu, pesan tersebut akan diterima subscriber.  



1[](./img/spike.png)  
Spike menunjukkan message yang diproses oleh broker. Setiap kali publisher dijalankan, akan ada spike yang menunjukkan publisher sukses mengirimkan pesan.  