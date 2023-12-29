# Ujian-Akhir-Praktikum-7
Project Ujian Akhir praktikum ini menggunakan MobileNetV2 sebagai model pretrained yang diambil menggunakan pustaka resNet. Instalasi python version >= 3.9.12 dengan https://www.python.org/ftp/python/3.10.0/python-3.10.0-amd64.exe

environment - path : 3.9.12 Vscode : pip install flask . pip install tensorflow . pip install pillow . pip install opencv-2 pip list python. Setelah itu install semua requirements pip install -r requirements Lalu jalankan flask python app.py

Web Image dapat diakses dengan url http://127.0.0.1:2000

Dataset Project ini menggunakan dataset rock, paper, scissors dengan jumlah data sebanyak 2520 file. Load image menggunakan image_dataset_from_directory dari pustaka resNet dengan pembagian train validation dan test validation dengan seed 123. Dataset menggunakan label categorical sehingga label dalam bentuk one hot encoding. Image size menggunakan (224, 244) dan batch size menggunakan 128.

# Local Development
Tampilan Upload File 
<img width="1792" alt="Jepretan Layar 2023-12-29 pukul 14 55 49" src="https://github.com/tasyaputri03/Ujian-Akhir-Praktikum-7/assets/103129679/ab109234-aaa7-4c60-9202-0b4f4c87ea3f">

Tampilan memasukkan file gambar dari dataset yang digunakan
<img width="1792" alt="Jepretan Layar 2023-12-29 pukul 14 56 14" src="https://github.com/tasyaputri03/Ujian-Akhir-Praktikum-7/assets/103129679/6700f1ad-0eef-470b-8dbd-c7ac33a4e263">

Tampilan Hasil
<img width="1792" alt="Jepretan Layar 2023-12-29 pukul 14 56 24" src="https://github.com/tasyaputri03/Ujian-Akhir-Praktikum-7/assets/103129679/d7d8a278-e1bf-4ec0-84bd-eba4421cca32">

Tampilan jika memasukkan gambar dari  luar dataset yang digunakan
<img width="1792" alt="Jepretan Layar 2023-12-29 pukul 14 56 59" src="https://github.com/tasyaputri03/Ujian-Akhir-Praktikum-7/assets/103129679/ca45ce23-57e8-497e-8389-102e1a06d43e">

Tampilan Hasil
<img width="1792" alt="Jepretan Layar 2023-12-29 pukul 14 57 06" src="https://github.com/tasyaputri03/Ujian-Akhir-Praktikum-7/assets/103129679/d6915912-c00a-4b5a-a854-038dcca5c021">

