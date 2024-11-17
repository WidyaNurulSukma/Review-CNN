# Review-CNN
Convolutional Neural Networks (CNN) adalah jenis jaringan saraf yang dirancang khusus untuk menangani data berbentuk grid, seperti gambar. CNN memiliki beberapa lapisan (layer) yang bekerja bersama untuk mengekstraksi fitur dan membuat prediksi yang akurat. Arsitektur CNN umumnya terdiri dari beberapa jenis lapisan.

### Convolutional Layer 
Pada lapisan ini, filter atau kernel digunakan untuk mengidentifikasi pola dalam gambar, seperti tepi, tekstur, atau bentuk. Setiap filter bergerak melintasi gambar (operasi konvolusi) untuk menghasilkan peta fitur (feature map).

### Pooling Layer
Lapisan pooling mengikuti lapisan konvolusional untuk mengurangi dimensi data. Ini berguna untuk mengurangi jumlah parameter dan komputasi yang diperlukan tanpa kehilangan informasi penting. Pooling yang umum digunakan adalah max pooling, yang mengambil nilai maksimum dalam sebuah jendela tertentu, atau average pooling, yang mengambil nilai rata-rata.

### Fully Connected Layer 
fully connected (FC), di mana setiap neuron terhubung ke semua neuron di lapisan sebelumnya. Lapisan ini digunakan untuk membuat keputusan akhir berdasarkan fitur yang telah diekstraksi.

## Penjelasan Code
### Code Link 2
Kode pada link 2  membangun dan melatih model Convolutional Neural Network (CNN) untuk klasifikasi gambar anjing dan kucing. Model ini terdiri dari lapisan konvolusi untuk ekstraksi fitur, dilanjutkan dengan lapisan pooling untuk mengurangi dimensi, dan lapisan dense untuk pengklasifikasian. Data gambar pelatihan diproses dengan augmentasi (seperti shear, zoom, dan flip) menggunakan ImageDataGenerator, sedangkan data pengujian hanya dilakukan rescaling. Model dilatih dengan 50 epoch menggunakan optimizer Adam dan fungsi loss binary crossentropy. Setelah pelatihan, model diuji dengan gambar dari set pengujian, dan hasil prediksi jumlah anjing dan kucing dicetak untuk evaluasi performa model.

### Code Link 3
Code pada link 3 ini membahas penerapan Convolutional Neural Network (CNN) untuk pengenalan gambar menggunakan dataset CIFAR-10 yang terdiri dari 60,000 gambar berwarna dalam 10 kelas, yaitu: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, dan truck. CNN dibangun dengan menggunakan beberapa layer seperti Convolutional Layer untuk ekstraksi fitur, Pooling Layer untuk downsampling, dan Fully Connected Layer untuk klasifikasi. Dataset CIFAR-10 diproses dengan normalisasi gambar dan konversi label ke format kategorikal untuk pelatihan model. Model CNN dilatih dengan optimizer Adam dan fungsi loss categorical crossentropy, lalu dievaluasi menggunakan data tes untuk mengukur akurasi. Setelah pelatihan, model dapat digunakan untuk memprediksi kelas gambar baru dengan melakukan inferensi pada gambar yang diunggah oleh pengguna.

# Link Materi dan Code
1. https://www.megabagus.id/deep-learning-convolutional-neural-networks/
2. https://www.megabagus.id/deep-learning-convolutional-neural-networks-aplikasi/
3. https://modul-praktikum-ai.vercel.app/Materi/4-convolutional-neural-network
