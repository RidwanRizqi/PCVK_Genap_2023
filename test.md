#### Pertanyaan


1. Jelaskan, mengapa pada modul praktikum ini eksekusi kode Python dilakukan menggunakan Google Colab?\
jawab: google collab digunakan karena menyediakan environment yang siap pakai tanpa perlu installasi, sehingga mudah digunakan dan pastinya gratis.

2. Jelaskan mengenai kegunaan setiap library pada praktikum langkah ke delapan?
Apakah semua library tersebut harus digunakan dalam praktikum sesi ini?\
jawab:
    * numpy Digunakan untuk operasi matematika dan manipulasi data numerik.
    * pandas digunakan untuk mengelola dan mengalisis data dalam bentuk tabel.
    * cv2_imshow digunakan untuk menampilkan hasil gambar pemrosesan
    * skimage.io digunakan untuk mengimpor dan proses gambar.
    * skimage.transform digunakan untuk transformasi gambar.
    * PIL digunakan untuk menipulasi dasar pada gambar
    * matplotlib.pylab digunakan untuk visualisasi grafik dan plot data\
  tidak semua library digunakan pada praktikum kali ini.



3. Pada uji coba langkah ke-9 terdapat potongan kode program sebagai berikut :
    ```python
    image = cv.resize(image, (0,0), fx=0.5, fy=0.5)
    ```
    apa kegunaan kode program tersebut? dan apa pengaruhnya jika tidak dilakukan?

4. Perhatikan potongan kode progam berikut :
    ```python
    for y in range (lebar):
        image_3[int((tinggi)/2),y] = [255,255,255]
    ```
    Apakah kegunaan kode [255,255,255] ?Jelaskan!

5. Jelaskan keterkaitan antara pixel dan juga resolusi gambar yang tinggi ataupun
rendah!