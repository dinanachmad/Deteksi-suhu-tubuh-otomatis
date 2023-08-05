# Deteksi-suhu-tubuh-otomatis
Sistem deteksi suhu tubuh otomatis adalah sistem yang dapat mendeteksi wajah dan mengukur suhu tubuh manusia. Deteksi wajah menggunakan model machine learning yang dibuat dengan metode transfer learning. Sistem terdiri dari kamera termal, kamera optik, SBC (Single Board Computer), dan display. Kamera termal menggunakan AMG8833, kamera optik menggunakan Raspberry Pi camera v2, SBC menggunakan Raspberry Pi model B, dan display menggunakan LCD atau monitor. Selain menggunakan LCD atau monitor, display dapat dihubungkan dengan laptop atau komputer dengan cara melacak alamat IP Raspberry Pi.

### Gambar sistem

<img src = "https://github.com/dinanachmad/Deteksi-suhu-tubuh-otomatis/assets/101391849/7db5d7a1-fd18-4c1d-93a3-44350d5f4e1a" width="50%" height="50%">

### Flowchart sistem
Cara kerja dari sistem ini adalah pertama, sistem membaca model machine learning yang telah dibuat. Selanjutnya, video real time ditampilkan pada LCD, monitor, atau komputer. Setelah video real time ditampilkan, sistem mulai mendeteksi wajah. Setelah ada wajah yang terdeteksi, proses selanjutnya adalah suhu tubuh diukur oleh sistem menggunakan thermal camera.

<img src = "https://github.com/dinanachmad/Deteksi-suhu-tubuh-otomatis/assets/101391849/6cff5ae6-e561-431b-80ee-d5e8520308ac" width="50%" height="50%">

### Hasil deteksi wajah dan pengukuran suhu
![Untitled-1](https://user-images.githubusercontent.com/101391849/220138173-618f651c-2076-4340-a4cf-01ec7c98a6b0.png)


