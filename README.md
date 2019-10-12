#TUTORIAL MEMBUAT FILE README.md

1.	Download Git Bash https://git-scm.com/downloads Download sesuai OS masing-masing

![image](https://user-images.githubusercontent.com/56198396/66697616-86925d00-ed01-11e9-8451-9a25196825c2.png)


2.	Setelah download dan di install, langkah selanjutnya buka aplikasi Git Bash yang tadi sudah di download

![image](https://user-images.githubusercontent.com/56198396/66697640-ca856200-ed01-11e9-9cdb-8ba958a40ae1.png)


3.	Lalu Git Bash akan terbuka, dan ketik perintah git –version

![image](https://user-images.githubusercontent.com/56198396/66697653-e852c700-ed01-11e9-8906-611c75a5e040.png)


4.	Langkah selanjutnya ketik perintah user.name dan user.email

![image](https://user-images.githubusercontent.com/56198396/66697693-3f589c00-ed02-11e9-98f0-087a2ee3cf35.png)


5.    Lalu untuk membuat folder yg bernama latihan1 ketik perintah mkdir latihan1

![image](https://user-images.githubusercontent.com/56198396/66697766-eb01ec00-ed02-11e9-938f-1d94cb82b68e.png)


6.	Lalu akan muncul folder bernama latihan1

![image](https://user-images.githubusercontent.com/56198396/66697795-17b60380-ed03-11e9-8d52-aac1b857c71a.png)


7. 	Setelah itu kembali ke aplikasi Git Bash lalu ketik cd latihan1 untuk masuk ke direktori tersebut

![image](https://user-images.githubusercontent.com/56198396/66697812-2e5c5a80-ed03-11e9-91f8-27e4794126f2.png)


8.	Selanjutnya untuk membuat file README.md lalu di isikian dengan text latihan 1 dengan menjalankan perintah $  echo “#latihan 1” >> README.md

![image](https://user-images.githubusercontent.com/56198396/66697824-4f24b000-ed03-11e9-8265-2dd3c390ce07.png)


9.	Jika berhasil maka akan muncul file README.md di dalam folder latihan1 yang pertama kali di buat di awal

![image](https://user-images.githubusercontent.com/56198396/66697880-b3e00a80-ed03-11e9-884c-713fdbf43854.png)


10.	Jalankan perintah git init, untuk membuat repository local

![image](https://user-images.githubusercontent.com/56198396/66697931-03bed180-ed04-11e9-8db0-c6e7ae16cfc9.png)


11.	Jika berhasil maka akan muncul direktori hidden .git

![image](https://user-images.githubusercontent.com/56198396/66697953-2fda5280-ed04-11e9-9531-2ffcf070889d.png)


12.	Lalu untuk langkah selanjutnya ketik perintah git add README.md

![image](https://user-images.githubusercontent.com/56198396/66697972-5e582d80-ed04-11e9-929a-66e9600168c0.png)


13.	Selanjutnya ketik perintah git commit –m “first commit”

![image](https://user-images.githubusercontent.com/56198396/66697986-7465ee00-ed04-11e9-89b0-f91dea8621b8.png)


                            #SAMPAI DI SINI SELESAI UNTUK REPOSITORY LOKAL
                            
                            #TUTORIAL MEMBUAT REPOSITORY SERVER


1.	Buatlah repisiory di Github.com dengan nama latihan 1, lalu klik create repository

![image](https://user-images.githubusercontent.com/56198396/66698056-fce48e80-ed04-11e9-959c-aaaee593f657.png)


2.	setelah itu kembali ke Git Bash dengan mengetik perintah git remote add origin [url]

![image](https://user-images.githubusercontent.com/56198396/66698069-0f5ec800-ed05-11e9-90a7-9c9cc3e8e585.png)


3.	lalu untuk menaruh file README.md yang tadi sudah di buat, dengan cara mengetik perintah git push -u origin master

![image](https://user-images.githubusercontent.com/56198396/66698080-23a2c500-ed05-11e9-94c1-1256053871c1.png)


4. 	jika berhasil akan seperti gambar di bawah, dan file README.md sudah berada di reposiory latihan 1 di Github.com yang tadi di buat

![image](https://user-images.githubusercontent.com/56198396/66698099-459c4780-ed05-11e9-8f78-866506be7b8d.png)

