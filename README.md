## Usage
Pillow : library open-source tambahan untuk Python yang fungsi utamanya adalah memanipulasi file gambar
Flask : Sebuah web framework yang ditulis dengan bahasa Python dan tergolong sebagai jenis microframework. Flask berfungsi sebagai kerangka kerja aplikasi dan tampilan dari suatu web. Dengan menggunakan Flask dan bahasa Python, pengembang dapat membuat sebuah web yang terstruktur dan dapat mengatur behaviour suatu web dengan lebih mudah.
tensorflow : 

## Dataset
https://www.kaggle.com/alessiocorrado99/animals10

```bash
pip install -r requirements.txt

# Put your image files (*.jpg) on static/img

# Then fc6 features are extracted and saved on static/feature
# Note that it takes time for the first time because Keras downloads the VGG weights.
python offline.py

# Now you can do the search via localhost:5000
python server.py
```
