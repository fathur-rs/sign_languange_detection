<img src="https://github.com/fathur-rs/sign_languange_detection/blob/main/preview.png" width="800"/><br>

## Intro
Bahasa Isyarat Amerika (ASL) adalah bahasa isyarat yang memiliki sifat linguistik yang sama dengan bahasa lisan, dengan tata bahasa yang berbeda dari bahasa Inggris. ASL diekspresikan dengan gerakan tangan dan wajah. Ini adalah bahasa utama yang banyak digunakan oleh orang Amerika Utara yang tuli dan sulit mendengar. 

## Data Used
Data yang digunakan adalah data primer yang menggunakan library open-cv untuk menangkap foto tangan berdasarkan bentuk yang melambangkan huruf-huruf bahasa isyarat amerika. library cvzone digunakan untuk melakukan mapping skeleton struktur jari-jari tangan agar memudahkan model untuk membedakan karakteristik antar huruf yang mana dapat meng-improve akurasi model. Label terdiri dari huruf A-Z yang direpresentasikan dengan notasi angka (A=1, B=2, ...) kecuali huruf J dan Z dikarenakan perlu adanya pergerakkan jari dalam mengisyaratkan huruf tersebut.
