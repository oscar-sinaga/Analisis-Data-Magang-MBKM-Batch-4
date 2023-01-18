	![](logo_kampus_merdeka.jpg)
  ![](logo_kemdikbud.jpg)

# Analisis-Data-Magang-MBKM-Batch-4
Dalam analisis data MBKM ini, saya akan mengolah data dan menganalisis data lowongan magang MBKM dari website Kampus Merdeka. Tahapan dari pengambilan dan pengolahan datanya sebagai berikut:

1. Collecting/Scraping data : Sebelum melakukan pengolahan, datanya harus ada dulu. Untuk mendapatkan data lowongan magang MBKM tersebut, saya mengkoneksikan Python di local saya dengan API magang MBKM dari website Kampus Merdeka : https://api.kampusmerdeka.kemdikbud.go.id/magang/browse/position. Selain itu, saya juga mendownload data geospatial untuk tiap :

  Provinsi dari link : https://geodata.ucdavis.edu/gadm/gadm4.1/json/gadm41_IDN_1.json.zip dan 
  
  Kab/Kot dari link : https://geodata.ucdavis.edu/gadm/gadm4.1/json/gadm41_IDN_2.json.zip

2. Cleaning and Transforming : Setelah data dikumpulkan, kemudian saya mentransformasi dan membersihkan data dengan bahasa pemrograman Python agar nantinya dapat diolah dengan mudah di Tableau serta data kab/kota dan provinsi nya dapat dijoin dengan data geospatial.  Kodingan Pythonnya dapat dilihat di sini: https://github.com/oscar-sinaga/Analisis-Data-Magang-MBKM-Batch-4/blob/master/Analisis%20Data%20Lowongan%20Magang%20MBKM%20Batch%204.ipynb

3. Tableau : Disini saya melakukan pengolahan dan analisis data lebih lanjut, seperti bisa dilihat pada : https://public.tableau.com/views/AnalisisDataLowonganMagangMBKMBatch4Data16Januari2023/AnalisisDataLowonganMagangMBKMBatch4Data16Januari2023?:language=en-US&:display_count=n&:origin=viz_share_link.
