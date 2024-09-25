<h1 align='center' style='font-family : "times new roman"'>Laporan Pemrosesan Citra Digital</h1>
<h2 align='center' style='font-family : "times new roman"'>Halftoning: Patterning dan Dithering</h2>
<p align="center">
  <img src="image-1.png" alt="deskripsi gambar">
</p>

<p align='center' style='font-family : "times new roman"'><b>oleh :</b></p>

<b><p align='center' style='font-family : "times new roman"'>Muhammad Mauladi : 2310131110005</p>

<p align='center'style='font-family : "times new roman"'>Pemrosesan Citra Digital : ABKC6306</p></b>
<br>

<div align='center' style='font-family : "times new roman"'>
<b>dosen :<br></b>
<b>Dr. Harja Santanapurba, M.Kom <br>
Novan Alkaf B. S., S.Kom., M.T
</b>
<br>
<br>
<h3>PROGRAM STUDI PENDIDIKAN KOMPUTER<br>
FAKULTAS KEGURUAN DAN ILMU PENDIDIKAN<br>
UNIVERSITAS LAMBUNG MANGKURAT<br>
2024
</h3>
<br>
<br>
<br>
</div>
<div style='font-family : "times new roman";font-size : 20px'>
<h5 align='center'>DAFTAR ISI</h5><br><br><br><br><br><br><br><br>
<h5 align='center'>PENDAHULUAN</h5>
<p style='text-align: justify'>Dalam dunia grafika komputer dan pencetakan, halftoning merupakan teknik penting yang digunakan untuk menciptakan ilusi dari berbagai nuansa warna dan gradasi melalui penggunaan titik-titik kecil. Teknik ini sangat krusial dalam representasi visual, terutama ketika bekerja dengan perangkat yang hanya mampu menampilkan sejumlah terbatas warna, seperti printer inkjet atau monitor dengan resolusi rendah. Terdapat dua metode utama dalam halftoning, yaitu patterning dan dithering, masing-masing dengan karakteristik dan aplikasi yang berbeda.</p><br><p style='text-align:justify'>Patterning melibatkan penggunaan pola tetap untuk menciptakan efek visual yang diinginkan, sedangkan dithering menggunakan distribusi titik yang bervariasi untuk menciptakan transisi yang lebih halus antara warna. Kedua metode ini tidak hanya penting dalam pencetakan, tetapi juga dalam pengolahan citra digital, desain grafis, dan berbagai aplikasi multimedia.</p>
<br><br><br><br><br><br><br><br>
<h5 align='center'>PEMBAHASAN</h5>
<br>
<b><P >A. Halftoning</p></b>
<p style='margin-left:19px;text-align: justify'>Halftoning adalah teknik yang digunakan untuk mencetak gambar dengan cara meniru nuansa warna melalui penggunaan pola titik. Di mana keterbatasan dalam reproduksi warna memerlukan teknik untuk menciptakan ilusi warna dan gradasi. Dua metode umum dalam halftoning adalah patterning dan dithering. Dibawah ini adalah penjelasan mendalam tentang kedua metode tersebut :<br> </p>
<b><p style='margin-left:19px'>1. Patterning</p></b>
<p style='margin-left:43px;text-align:justify'>Patterning adalah metode halftoning yang menggunakan pola tetap untuk menciptakan efek gradasi. Pola ini biasanya berupa titik-titik dengan ukuran atau jarak yang bervariasi tergantung pada intensitas warna yang ingin direproduksi. <br> </p>
<p style='margin-left:43px;text-align:justify'>Metode dan Langkah-langkahnya : <br> </p>
<ol style='margin-left:24px;text-align:justify'>
<li><b>Pembagian Intensitas:</b><br>Gambar dibagi menjadi area-area kecil (pixel) dan setiap area dianalisis untuk menentukan intensitas warna.</li><br>
<li><b>Penerapan Pola:</b><br> Pola titik tetap diterapkan ke setiap area berdasarkan intensitas. Misalnya, area dengan intensitas tinggi mungkin memiliki titik yang lebih besar dan lebih rapat, sedangkan area dengan intensitas rendah memiliki titik yang lebih kecil dan jarang.</li><br>
<li><b>Pencetakan</b><br>Pola akan dicetak untuk membentuk gambar akhir.</li>
</ol>
<p style='margin-left:65px;text-align:justify'>Contoh : <br> pada patterning ada 10 tingkat keabuaan yang dimulai dari index 0 - 9 yang mana tingkat 0 dari poin 0-25, tingkat 1 dari 26-51, tingkat 2 dari 52-77, tingkat 3 dari 78-103, tingkat 4 dari 109-129, tingkat 5 dari 130-155, tingkat 6 dari 156-181, tingkat 7 dari 182-207, tingkat 8 dari 208-233, tingkat 9 dari 234-255, semakin levelnya mendekati 0 maka akan semakin gelap (hitam) gambar tersebut dan sebalik nya semakin tinggi level nya (9) maka akan menjadi putih.</p>
<br>
<p style='margin-left:65px;text-align:justify'>dibawah ini adalah kode untuk Patterning :<br>
<img src='Screenshot 2024-09-25 101034.png'>
</p>

</div>
