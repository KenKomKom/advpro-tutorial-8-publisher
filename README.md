# advpro-tutorial-8-publisher


7.Try to answer the following questions, and write the answer in the and new file readme.md in 
you repository.

a. How many data your publisher program will send to the message broker in one 
run?

5 kali. Karena pad publisher. Dilakukan publish_event sebanyak 5 kali.

b. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?

Kedua url sama karena mengirimkan reuqeust terhadap server rabbitMQ dimana akan perbedaan dengan subscriber adalah hasil request ini akan membuat publisher untuk mengirimkan message ke queue. Sedangkan untuk yang subscriber dibuat sebuah listener yang mengambil data dari message queue.

![alt text](image.png)


![alt text](image-1.png)
Image diatas menunjukkan kalau setelah publisher di run. Publisher akan mengirimkan data-data yang telah di hard code didalam kode nya ke message queue. Subscriber yang sedang ter connect ke message queue akan mendapatkan data-data tersebut dari message queue dan mengeluarkannya di console seperti sesuai kode yang telah dibuat. 