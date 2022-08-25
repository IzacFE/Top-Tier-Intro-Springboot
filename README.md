# Top-Tier-Intro-Springboot

## Problem 2 - Endpoint Description
Untuk code response belum dibuat, dan mengandalkan code response bawaan

1. End point untuk Get all messages : localhost:8080/api/get/messages <br>
 Untuk method yang digunakan dalam endpoint ini adalah dengan menggunakan GET . Di dalamnya terjadi process Get Annotation yang mengambil segala message dari repository lalu dengan looping foreach menambahkan ke dalam sebuah ArrayList lalu hasilnya akan ditambahkan ke sebuah Hashmap dengan key data beserta informasi response message dan juga informasi total data
 
 ![image](https://user-images.githubusercontent.com/97284723/186650888-c97e4e77-c4f9-4e0f-b14e-3c58b80ef18f.png)

 
 2. End point untuk Create / Post message : localhost:8080/api/post/message/  <br>
 Untuk method yang digunakan dalam endpoint ini adalah dengan menggunakan POST . Di dalamnya terjadi process Post Annotation yang mengambil sebuah text dari request body dan diubah menjadi entity yang selanjutnya di set ke dalam set ke database, untuk response hit di simpan ke dalam sebuah hashmap dengan isi response message dan isi message body request
 
 ![image](https://user-images.githubusercontent.com/97284723/186650960-9337597f-47e2-4478-bb87-1c9cd636bc5d.png)

 
 3. End point untuk Delete message : localhost:8080/api/delete/message/{messageId} <br>
 Untuk method yang digunakan dalam endpoint ini adalah dengan menggunakan DELETE . Di dalamnya terjadi process Delete Annotation yang mengambil path variable / messageID untuk mencari message yang akan didelete dari message repository, untuk response hit di simpan ke dalam sebuah hashmap dengan isi response message
 
 ![image](https://user-images.githubusercontent.com/97284723/186651041-f43c4eb1-f81b-4957-932e-0ae9ec370c1c.png)

 
 4. (TAMBAHAN) End point untuk Edit / Put message : localhost:8080/api/put/message?messageId={messageID} <br>
 Untuk method yang digunakan dalam endpoint ini adalah dengan menggunakan Put . Di dalamanya terjadi process Delete Annotation yang mengambil param / messageID untuk mencari message yang akan diubah isi messagenya dari message repository, untuk response hit di simpan ke dalam sebuah hashmap dengan isi response message dan data yang berisikan message setelah diubah
 
 ![image](https://user-images.githubusercontent.com/97284723/186651105-3c679bf0-db8e-4007-bb59-2e253e9e3de0.png)

### SCREENSHOOT POSTGRE DATABASE DENGAN GUI

![image](https://user-images.githubusercontent.com/97284723/186651547-dfcb33d3-1884-46d0-a414-1df78c32d557.png)

![image](https://user-images.githubusercontent.com/97284723/186651720-6661d176-e401-41e0-bcf2-11509f80ac66.png)



 
