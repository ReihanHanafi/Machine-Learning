# Klasifikasi Konten Negatif Web Berbasis Teks Menggunakan Machine Learning
Tugas Akhir Kuliah oleh Reihan Hanafi Wiyanatra

Data yang digunakan adalah Data_Labelsv2.csv

Data per kategori :
1. Porn : 830
2. Gambling : 963
3. Phishing : 576
4. Whitelist : 539

Total data : 2908 data (tapi di CSV ada 2911 data ¯\_(ツ)_/¯)

kolom 'content' adalah Bahasa original dari web.
kolom 'contents' adalah Bahasa yang diterjemahkan ke Bahasa inggris menggunakan rumus : =GOOGLETRANSLATE(C2;DETECTLANGUAGE(C2);"en")

Gunakan file Training v2 untuk melatih datanya.

Cara menggunakannya menggunakan Google Apps: 
1. Untuk pengambilan data pelatihan diambil dari https://github.com/olbat/ut1-blacklists/tree/master/blacklists
2. URL Blacklist dari GitHub disimpan dalam bentuk .txt (misalnya blacklist.txt)
3. File .txt upload di Google Drive rekan, lokasi folder sesuaikan dengan keinginan rekan
4. Gunakan MachineLearning_ScrapingV1.ipynb untuk scraping data
~~~More Coming Soon~~~
