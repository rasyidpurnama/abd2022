# abd2022
Repositori tugas ABD 2022

### `Tugas 1 - Proposal Pengembangan Aplikasi Big Data`
- [Link dokumen proposal awal](https://docs.google.com/document/d/14ZHgpPaUfuuSwOg0My1x7XkgHbmdp2sq/edit?usp=sharing&ouid=106859921835530588208&rtpof=true&sd=true)
- [Link dokumen proposal revisi](https://docs.google.com/document/d/1VPR5t35H9Pxqw3gW4oZk0P1oahgzrQHX/edit?usp=sharing&ouid=106859921835530588208&rtpof=true&sd=true)

### `Tugas 2 - Link Github dan Web Scraping Menjadi Dataset`
- Web scrapping dilakukan pada situs [mtsamples.com](mtsamples.com).
- Web scrapping dilakukan dengan library selenium yang dijalankan pada google colaboratory, berikut [tutorial install](https://stackoverflow.com/questions/51046454/how-can-we-use-selenium-webdriver-in-colab-research-google-com) selenium ke google colaboratory.
- Dataset berupa data medical transcription dengan kode sebagai berikut ([link](https://github.com/rasyidpurnama/abd2022/blob/main/mtsamples_scraping_colab.ipynb)).
- Hasil dari web scrapping berupa csv sebagai berikut ([link](https://github.com/rasyidpurnama/abd2022/blob/main/mtsamples_20220222.csv)).

### `Tugas 3 - Skrip Map Reduce`
- Map Reduce dilakukan agar suatu data besar dapat diproses secara tercluster dengan konsep key/values.
- Membandingkan map reduce dan manual process dengan bantuan library numpy.
- Berikut adalah file implementasi skrip map reduce ([link](https://github.com/rasyidpurnama/abd2022/blob/main/mtsamples_mapreduce_colab.ipynb)).

### `Tugas 4 - Skrip SparkNLP`
- SparkNLP adalah library spark untuk python pada domain nlp yang dikembangkan oleh [JohnSnowLabs](https://nlp.johnsnowlabs.com/).
- SparkNLP digunakan untuk mengimplementasikan algoritma clustering di cluster spark.
- Berikut adalah file implementasi skrip SparkNLP ([link](https://github.com/rasyidpurnama/abd2022/blob/main/mtsamples_sparknlp_colab.ipynb)).

### `Tugas 5 - Skirp SparkSQL`
- Spark SQL adalah modul yang ditujukan untuk memahami pemrosesan data secara struktural yang terbentuk di dalam inti dari Apache Spark.
- Spark SQL terintegrasi dengan program Spark yang membiarkan penggunanya untuk meminta data terstruktur dari program-program Spark dengan menggunakan SQL atau DataFrame API. Fungsi ini dapat digunakan untuk Java, Scala, Python, dan R.
- Berikut adalah file implementasi skrip SparkSQL ([link](https://github.com/rasyidpurnama/abd2022/blob/main/mtsamples_sparksql_colab.ipynb)).

### `Tugas 6 - Tugas Kelompok`
- Pada tugas ini kami menggunakan library sparknlp-healthcare yang memerlukan kode token untuk mendapatkan akses ke pretrained modelnya, berikut kode token yang kami gunakan dengan batas waktu tertentu, hubungi kami jika ada suatu kendala [link](https://github.com/rasyidpurnama/abd2022/blob/main/spark_nlp_for_healthcare_spark_ocr_4547.json)
- [Link Tugas Kelompok](https://github.com/mhihsan/abd/tree/main/project_kelompok)
