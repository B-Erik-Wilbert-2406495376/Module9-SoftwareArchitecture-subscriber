7. 
a. What is amqp?
AMQP (Advanced Message Queuing Protocol) adalah protokol komunikasi yang digunakan untuk pertukaran pesan antar aplikasi melalui message broker seperti RabbitMQ. Dengan AMQP, aplikasi dapat saling berkomunikasi secara asynchronous menggunakan queue sehingga sistem menjadi lebih terstruktur, scalable, dan tidak saling bergantung secara langsung.

b. What does it mean? guest:guest@localhost:5672 , what is the first guest, and what is the second guest, and what is localhost:5672 is for?
Pada connection string `amqp://guest:guest@localhost:5672`, kata `guest` pertama merupakan username untuk login ke RabbitMQ, sedangkan `guest` kedua adalah password-nya. `localhost` menunjukkan bahwa server RabbitMQ berjalan di komputer yang sama dengan aplikasi, dan `5672` adalah port default yang digunakan RabbitMQ untuk komunikasi menggunakan protokol AMQP.