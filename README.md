# CSS DASAR

Langkah - Langkah
1. Buat Dokumen HTML terlebih dahulu
   buat dokumen HTML yang kita inginkan
   ![image](https://github.com/user-attachments/assets/d9ced04a-5936-48a1-b76c-0824fc6530ab)
   hasil:
   ![image](https://github.com/user-attachments/assets/f1867c06-7c93-443a-9271-2d016f2c1f4e)
   
3. Deklarasikan CSS internal
   mendeklarasikan CSS internal kita bisa menambahkan pada bagian head agar CSS di render lebih dahulu saat kita membuka web
   ![Screenshot (357)](https://github.com/user-attachments/assets/04faa84e-4c59-419d-abd6-d300421ea644)
   ![image](https://github.com/user-attachments/assets/4c370955-b786-446a-b0dd-d18c50697d0c)

5. Menambahkan inline CSS
   kita bisa menambahkan inline style dengan cara menambahkan "styles" dalam tag 'p'
   ![image](https://github.com/user-attachments/assets/d33d49ce-b54d-4c4f-9f95-534fd122922c)

6. Menambahkan CSS eksternal
   kita harus menambahkan perintah 'link' pada bagian Head agar file HTML kita terkoneksi dengan CSS eksternal kita
   ![image](https://github.com/user-attachments/assets/71cc450c-7616-46e8-8c03-910df17a89af)

7.  Menambahkan CSS selector
   kita bisa menambahkan style pada file HTML kita untuk beberapa bagian saja. kita bisa menggunakan '#' untuk ID dan '.' untuk class
   ![image](https://github.com/user-attachments/assets/fd03d2dd-9404-4881-af38-41b099ddd9d8)

Saya akan menjelaskan :

   1. Perbedaan antara h1 {...} dan #intro h1 {...} adalah selector elemen yang akan mempengaruhi SEMUA elemen h1 di halaman web #intro h1 {...} adalah selector yang lebih spesifik, hanya mempengaruhi elemen h1 yang berada di dalam elemen dengan id "intro"
      
   2.	Prioritas antara Internal CSS, External CSS, dan Inline CSS
      prioritas CSS dari tertinggi ke terendah adalah Inline CSS - Internal CSS - External CSS
     	   Dalam contoh di atas, teks akan berwarna MERAH karena inline CSS memiliki prioritas tertinggi, meskipun ada deklarasi warna berbeda di internal dan external CSS.
     	
   3.	Prioritas antara ID dan Class Selector
      
         ID selector (#paragraf-1) memiliki prioritas lebih tinggi dibandingkan Class selector (.text-paragraf)
         Dalam contoh di atas, teks akan berwarna MERAH dan ukuran font 14px, mengikuti style dari ID selector
         Ini karena ID bersifat unik dan lebih spesifik dibandingkan Class
     	
Secara umum, urutan prioritas CSS (specificity) dari tinggi ke rendah adalah:
   1.	Inline styles
   2.	ID selectors
   3.	Class selectors, attributes selectors, dan pseudo-classes
   4.	Element selectors dan pseudo-elements



   
