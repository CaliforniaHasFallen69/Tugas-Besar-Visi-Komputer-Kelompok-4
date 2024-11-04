# Tugas Besar Visi Komputer

Object Detection dengan Model Deep Learning "YOLOv5"
Topik: Perabot

# Kelompok 4 - Kelas A

24060121140159 ZAERI HAIKAL RABBANI
24060121140163 RAFIF ABBRAR MAHESWARA
24060121140142 NAUFAL ARIQ DWIKURNIA
24060121120013 IKSAN NUR ROCHIM
24060121140170 YODA RACHMAN NUR SAHID

# Link Video Demo Program

https://www.youtube.com/watch?v=m6dFAzOT2ww

# Deskripsi

- Program ini menggunakan YOLOv5 untuk mendeteksi objek dari foto dan video

# Dataset

Sumber : https://universe.roboflow.com/roboflow-100/furniture-ngpea/dataset/2
Dataset terdiri dari 3 kelas perabot, yaitu :

- Chair
- Sofa
- Table

Sebelum menjalankan program, pastikan Anda telah menginstal:

- Python 3.8.0 atau yang lebih baru

# Penggunaan

1. Clone YOLOv5 Framework dari github
   Sumber Framework : https://github.com/ultralytics/yolov5
2. Install dependensi yang tertera pada file 'requirements.txt dengan command : pip install requirements.txt
3. Download dataset dari roboflow dengan format YOLOv5pytorch.txt
4. Masukkan dataset tersebut dengan nama folder adalah dataset2 dalam satu folder project
5. Jalankan program deteksi objek video dengan command :
   python detect.py --weights runs/train/exp13/weights/best.pt --source AsiaFurniture2.mp4 --img 640 --conf 0.25 (untuk conf, img, dan source bisa disesuaikan)
6. file video akan tersimpan di folder runs

TERIMA KASIH
