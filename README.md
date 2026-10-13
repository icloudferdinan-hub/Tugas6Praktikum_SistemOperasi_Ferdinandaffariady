# Tugas6Praktikum_SistemOperasi_Ferdinandaffariady

VI. Tugas

1. Eksekusi seluruh profile yang ada :

a. Edit file profile /etc/profile dan tampilkan pesan sebagai berikut : echo “Profile dari /etc/profile”

<img width="498" height="186" alt="image" src="https://github.com/user-attachments/assets/b7e29cef-f495-44ff-b6d4-fa0f3c221d02" />

b. Asumsi nama anda stD02001, maka edit semua profile yang ada yaitu :

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/b5a60787-5ec5-495a-820a-90764f353a39" />

Ganti nama /home/mahasiswa dengan nama anda sendiri. Pada setiap file tersebut, cantumkan instruksi echo, misalnya pada /home/ mahasiswa/.bash_profile : echo “Profile dari .bash_profile” Lakukan hal yang sama untuk file lainnya, sesuaikan tampilan dengan nama file yang bersangkutan.

c. Jalankan instruksi subtitute user, kemudian keluar dengan perintah exit sebagai berikut:
<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/ba99f13a-5ba4-4fdb-9fcd-533fc94499a0" />

2. Prompt String (PS)

a. Edit file .bash_profile, ganti prompt PS1 dengan ‘>’. Instruksi export diperlukan dengan parameter nama variable tersebut, agar perubahan variable PS1 dikenal oleh semua shell


<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/8b4515ff-adfb-48cc-8f2e-443acd9d4e1e" />

b. Eksperimen hasil PS1 :


<img width="487" height="141" alt="image" src="https://github.com/user-attachments/assets/e0b60963-ccc0-4fa8-a690-9aa1bbefaff6" />

3. Logout

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/43fde25e-8276-44b2-b97e-7f531ff80d5b" />

4. Bash script a. Buat 3 buah script p1.sh, p2.sh, p3.sh dengan isi masing-masing : p1.sh #! /bin/bash

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/0a2bea49-a8b5-4b91-8493-ec4136e0d3cd" />

p2.sh #! /bin/bash

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/b4ed3c0c-3f23-4d40-9240-6d0ccdbee619" />

p3.sh #! /bin/bash

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/e66d0385-22e8-48b8-ada4-463b821e4d0e" />

B. Jalankan script tersebut sebagai berikut 

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/a6c760f2-1b9f-432d-b681-cb430da9e45d" />

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/d4d54abb-e931-44a7-91e1-6ab6611e7e1b" />

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/876eedc6-c142-40e8-a0fe-fdf0f9537082" />

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/fedc4679-0ade-4759-b870-5f6f19f3e9b6" />

5. Jobs a. Buat shell-script yang melakukan loop dengan nama pwaktu.sh, setiap 10 detik, kemudian menyimpan tanggal dan jam pada file hasil.

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/6b041b16-e489-4cfd-8cbd-c7ae32ecbb99" />

b. Jalankan sebagai background; kemudian jalankan satu program (utilitas find) di background sebagai berikut :

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/f5c845ca-3313-444e-9830-663e736caaca" />

c. Jadikan program ke 1 sebagai foreground, tekan ^Z dan kembalikan program tersebut ke background

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/95a2d649-9e17-4d76-b40d-f4ec7abd0cf0" />

d. Stop program background dengan utilitas kill

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/8f9abb55-efb2-4fc4-a069-f937c30c39fa" />

6. History a. Ganti nilai HISTSIZE dari 1000 menjadi 20

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/7fbec74c-fa05-47a7-a126-b5d3e5e5c994" />

b. Gunakan fasilitas history dengan mengedit instruksi baris ke 5 dari instruksi yang terakhir dilakukan

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/a64389d4-b3d4-4093-95ca-c8f01035893f" />

c. Ulangi instruksi yang terakhir. Gunakan juga ^P dan ^N untuk bernavigasi pada history bufer

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/f0ea20f1-7673-4e19-ad3c-00b65ab7dcd0" />

d. Ulangi instruksi pada history bufer nomor 150

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/d4fde1a4-8c27-4c8b-8ab8-7cb5f929c6da" />

e. Ulangi instruksi dengan prefix “ls”

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/36783e36-839e-46ec-ae09-aec9ca723301" />













