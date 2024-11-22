Pada assignment ini, dilakukan web scraping pada 2 website berbeda untuk mengambil data berikut:

1. Website Harga Emas (https://harga-emas.org/)
   Tujuan: mengambil data harga emas dari halaman tersebut
2. Website Produk Fashion (Cotton Ink) (https://cottonink.co.id/collections/women)
   Tujuan: Mengambil data produk fashion wanita, seperti nama produk, harga, dan URL produk

Proses scraping dilakukan menggunakan modul requests untuk mengunduh konten halaman web dan BeautifulSoup untuk parsing HTML agar dapat mengekstrak data yang diperlukan. Data yang berhasil diambil kemudian disusun dalam format yang lebih terstruktur menggunakan pandas untuk analisis lebih lanjut.