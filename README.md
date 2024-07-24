﻿# Apache-Flink

# How to Run jar files

pertama jalankan maven untuk membuat file jar

```
mvn clean package

```

setelah jadi jar jalankan file jar :

```
flink run -c org.example.WordCount /root/ApacheFlink-1.0-SNAPSHOT.jar --input input.txt --output /root/output1.txt

```

lalu cek di dashboard flink di port 8081

![image](https://github.com/user-attachments/assets/31e47aee-5f24-4d46-937f-d3799c02b363)
