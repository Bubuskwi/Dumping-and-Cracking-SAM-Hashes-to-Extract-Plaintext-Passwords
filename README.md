# Dumping-and-Cracking-SAM-Hashes-to-Extract-Plaintext-Passwords
Dumping-and-Cracking-SAM-Hashes-to-Extract-Plaintext-Passwords

Buka Command prompt sebagai admin kemudian ketik wmic useraccount get name,sid dan tekan enter, setelah mengenter perintah tersebut akan menampilkan tampilan seperti dibawah

![Cuplikan layar 2024-10-13 130659](https://github.com/user-attachments/assets/d00edc94-b415-4b95-9b7b-e88cc57b0824)

kemudian download dan ekstrak file dari pwdump7 dan pindahkan lokasi folder dari command prompt ke lokasi file dari pwdump7 yang disimpan sebelumnya.
![Cuplikan layar 2024-10-13 130715](https://github.com/user-attachments/assets/9fe8d27d-cb44-4fe7-b888-317f97486c44)

kemudian jalankan pwdump7.exe melalui command prompt seperti dibawah
![Cuplikan layar 2024-10-13 130730](https://github.com/user-attachments/assets/c0046450-f285-40aa-8ff0-9e769daff7a6)
setelah perintah pwdump7.exe dijalankan maka akan menampilkan nama akun, RID, dan hash terkait.

kemudian simpan output dari pwdump7 yang telah dijalankan sebelumnya di direktori c:\ dengan format nama hashes.txt
![Cuplikan layar 2024-10-13 130839](https://github.com/user-attachments/assets/99bdc699-1610-47e9-a3aa-fbedef368329)

buka folder hashes.txt tersebut dan didalam file tersebut terdapat nama akun pengguna yang hilang seperti gambar dibawah
![Cuplikan layar 2024-10-13 131406](https://github.com/user-attachments/assets/9ba88037-92b2-4b30-a82a-bf49e047ca5e)

kemudian isi nama akun pengguna yang hilang tersebut dengan nama akun pengguna yang didapatkan dari perintah wmic useraccount sebelumnya.
![Cuplikan layar 2024-10-13 131406](https://github.com/user-attachments/assets/368ab99a-5de1-4c58-8e3a-3b590ac87ca6)

kemudian download dan buka ophcrack
![Cuplikan layar 2024-10-13 131406](https://github.com/user-attachments/assets/a2f54744-b31d-4c0a-9198-410cb265b5c3)

kemudian buka load dan pilih PWDUMP file dan pilih file hashes.txt. Setelahnya akan menampilkan nama akun pengguna dan hashes dari hashes.txt
![Cuplikan layar 2024-10-13 131646](https://github.com/user-attachments/assets/7c6d418d-d1f8-478e-8885-2f1859f2b073)

Install Vista free dibrowser kemudian pada ophcrack dan pilih tables dan pilih folder vista free yang telah didownload sebelumnya
![Cuplikan layar 2024-10-13 132708](https://github.com/user-attachments/assets/378d52ac-7478-4df0-8295-4f13293edcbe)
setelahnya pilih crack dan tunggu hingga prosesnya selesai
![Cuplikan layar 2024-10-13 135224](https://github.com/user-attachments/assets/5abb0c92-f692-4bfe-b953-b37827d358be)

setelah selesai maka ophcrack akan menampilkan password yang tersedia
![Cuplikan layar 2024-10-13 135224](https://github.com/user-attachments/assets/a5a27971-bae5-4b5a-bc95-a2021b7c2db0)
saya tidak memakai password diwindows saya tetapi menggunakan pin maka outputnya not found
![Cuplikan layar 2024-10-13 135604](https://github.com/user-attachments/assets/850b7a31-ede0-4509-ae41-68e9acead128)

