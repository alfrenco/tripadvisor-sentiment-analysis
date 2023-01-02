[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=8865015&assignment_repo_type=AssignmentRepo)


## Dataset

Dataset yang digunakan ini berisi sekitar 20 ribu review hotel dengan dari aplikasi Trip Advisor yang diperoleh dari Kaggle dengan [Link](https://www.kaggle.com/datasets/andrewmvd/trip-advisor-hotel-reviews)

---


## Objectives

Hotel merupakan salah satu hal penting dalam liburan. Cepatnya perkembangan zaman membuat lebih banyak cara dalam memilih hotel yang baik salah satunya adalah menggunakan reservasi online dengan aplikasi seperti Trip Advisor. Dataset yang digunakan ini berisi review hotel dengan jumlah sekitar 20 ribu dimana bisa digunakan untuk membantu menentukan mana hotel yang baik mana yang bukan. Dalam kasus ini akan dibuat model untuk membuat sentimen analisis terhadap review hotel di Trip Advisor.

---


## Kesimpulan

Model yang dibuat untuk mengatasi kasus ini memiliki beberapa layer utama yaitu input layer, TextVectorization layer, Embedding layer, Bidirectional LSTM layer, dense layer, dan output layer.

Model tersebut berhasil mendapatkan hasil sebagai berikut :

* Untuk label 0 atau label Bad, model berhasil mendapatkan hasil yang cukup baik yaitu mendapatkan precision sebesar 0.86 dan recall sebesar 0.71. Hasil tersebut cukup baik dimana diketahui bahwa jumlah data label 0 atau label Bad hanya ada sedikit dibandingkan dengan label 1.
* Untuk label 1 atau label Good, model berhasil mendapatkan hasil yang sangat baik. Hal tersebut bisa dilihat dari hasil precision sebesar 0.91 dan recall sebesar 0.96.
* Dari classification report untuk model di atas berhasil mendapatkan overall accuracy sebesar 0.90 dimana angka tersebut lumayan tinggi.



