# ExampleSplashScreen
Ini adalah contoh aplikasi sederhana, dimana disini kita akan membuat Splash Screen yang ditambah dengan animasi sederhana dengan
menggunakan file xml yang disimpan pada folder anim, sehingga akan menjadi lebih menarik.
</br></br></br>
Oke, sebelum masuk pembahasan, disini saya ingin memberikan sebuah contoh untuk teman-teman saya yang membutuhkan pencerahan dalam memulai
Android Programming, terutama teman-teman sekelas saya di IA12.
</br>Pada dasarnya, materi yang saya gunakan berasal dari : 
</br>https://www.udacity.com/course/android-development-for-beginners--ud837
</br></br></br>
Pada aplikasi ini kita hanya menggunakan 2 layout, layout pertama sebagai SplashScreen dan layout kedua sebagai layout yang akan muncul
setelah SplashScreen selesai. Jadi, disini kita hanya mengimplementasikan intent. Intent sendiri digunakan pada Android untuk melakukan
interaksi antar activity, sehingga intent terbagi menjadi dua yaitu implicit intent dan explicit intent, kali ini kita hanya akan menggunakan
implicit intent. Bentuk umum intent seperti berikut ini :
</br></br>Intent intent = new Intent(KelasSekarang.this,KelasTujuan.class);  
startActivity(intent);
</br></br></br>
Hasil Output untuk tampilan SplashScreen akan seperti berikut ini :
</br>![alt tag](http://i.imgur.com/dsjJAUz.png)
