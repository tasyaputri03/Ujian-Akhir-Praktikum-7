# Modul-6
Project praktikum modul 6 ini menggunakan MobileNetV2 sebagai model pretrained yang diambil menggunakan pustaka resNet. Instalasi python version >= 3.9.12 dengan https://www.python.org/ftp/python/3.10.0/python-3.10.0-amd64.exe

environment - path : 3.9.12 
Vscode : pip install flask . pip install tensorflow . pip install pillow . pip install opencv-2 pip list python. 
Setelah itu install semua requirements pip install -r requirements Lalu jalankan flask python app.py

Web Image dapat diakses dengan url http://127.0.0.1:2000

Dataset Project ini menggunakan dataset rock, paper, scissors dengan jumlah data sebanyak 2520 file. Load image menggunakan image_dataset_from_directory dari pustaka resNet dengan pembagian train validation dan test validation dengan seed 123. Dataset menggunakan label categorical sehingga label dalam bentuk one hot encoding. Image size menggunakan (224, 244) dan batch size menggunakan 128.

# Modelling
Model yang digunakan adalah MobileNetV2 yang dimana model tersebut akan disimpan pada citra.h5
<img width="1721" alt="Jepretan Layar 2023-12-29 pukul 15 09 39" src="https://github.com/tasyaputri03/Ujian-Akhir-Praktikum-7/assets/103129679/1c52c717-6626-4340-bc79-5e6a15cc7f91">
<img width="1343" alt="Jepretan Layar 2023-12-29 pukul 15 12 11" src="https://github.com/tasyaputri03/Ujian-Akhir-Praktikum-7/assets/103129679/b7d67e33-00ab-4ddf-a2b7-b4dd4efba961">

Evaluation Model
<img width="567" alt="Jepretan Layar 2023-12-29 pukul 15 15 31" src="https://github.com/tasyaputri03/Ujian-Akhir-Praktikum-7/assets/103129679/18726335-3e64-43b6-b69a-04b70c56e239">

Hasil Predict Model yang telah di training
<img width="1685" alt="Jepretan Layar 2023-12-29 pukul 15 17 04" src="https://github.com/tasyaputri03/Ujian-Akhir-Praktikum-7/assets/103129679/c76cb24d-81d5-4325-bd84-b5158fd1461f">

# Local Development

Tampilan Upload File
<img width="1792" alt="Jepretan Layar 2023-12-15 pukul 18 26 53" src="https://github.com/tasyaputri03/Modul-6/assets/103129679/d792b0f1-4220-4585-9b3f-37a488115f06">


Tampilan Result
<img width="1792" alt="Jepretan Layar 2023-12-15 pukul 18 27 26" src="https://github.com/tasyaputri03/Modul-6/assets/103129679/93a167af-f75b-4ee7-a671-3cf8e29a71c7">

