# Proyek Analisis Data: Air Quality Datasets

## Deskripsi

Proyek ini menganalisis dataset kualitas udara untuk menjawab pertanyaan bisnis tentang distribusi dan pola konsentrasi PM2.5.

## Pertanyaan Bisnis

- Bagaimana distribusi konsentrasi PM2.5 sepanjang tahun?
- Apakah ada pola musiman pada konsentrasi PM2.5 sepanjang tahun?

## Library yang Digunakan

- pandas
- numpy
- matplotlib
- seaborn
- sklearn
- streamlit

## Cara Menjalankan Proyek

### 1. Setup Environment

Jalankan perintah berikut untuk membuat virtual environment dan menginstal dependensi:

```bash
python -m venv env
source env/bin/activate  # Untuk Mac/Linux
env\Scripts\activate  # Untuk Windows
pip install -r requirements.txt
```

### 2. Menjalankan Notebook

Notebook dapat dijalankan menggunakan Jupyter Notebook atau Google Colab.

```bash
jupyter notebook notebook.ipynb
```

### 3. Menjalankan Dashboard Streamlit

Jalankan perintah berikut untuk menjalankan dashboard secara lokal:

```bash
streamlit run dashboard.py
```

Jika terdapat error, pastikan semua dependensi sudah diinstal dengan benar dan periksa kembali kode di `dashboard.py`.

## Kesimpulan

### Pertanyaan 1: Bagaimana distribusi konsentrasi PM2.5 sepanjang tahun?

- Konsentrasi PM2.5 menunjukkan variabilitas yang signifikan dari tahun ke tahun.
- Tahun-tahun tertentu mungkin memiliki median konsentrasi PM2.5 yang lebih tinggi, menunjukkan adanya peningkatan tingkat polusi udara.
- Outlier di setiap tahun menandakan adanya periode atau waktu dengan tingkat polusi yang ekstrem, kemungkinan besar disebabkan oleh aktivitas manusia seperti pembakaran bahan bakar atau faktor cuaca seperti inversi udara.

**Kesimpulan utama:** Polusi udara konsisten menjadi masalah setiap tahun, tetapi pola distribusi dapat berbeda-beda tergantung pada faktor eksternal.

### Pertanyaan 2: Apakah ada pola musiman pada konsentrasi PM2.5 sepanjang tahun?

- Konsentrasi PM2.5 cenderung lebih tinggi pada bulan-bulan musim dingin (misalnya, Desember hingga Februari).
- Konsentrasi menurun selama bulan-bulan musim panas (Mei hingga Agustus), kemungkinan karena peningkatan pengendapan partikel oleh hujan dan aktivitas fotokimia yang membantu membersihkan udara.
- Pola musiman ini menunjukkan bahwa musim dingin memiliki risiko lebih tinggi terhadap polusi udara, mungkin karena pembakaran bahan bakar untuk pemanasan dan kondisi cuaca yang menyebabkan stagnasi udara.

**Kesimpulan utama:** Ada pola musiman yang jelas, dengan musim dingin cenderung memiliki konsentrasi PM2.5 yang lebih tinggi dibandingkan musim panas.

## Rekomendasi

- Pada tahun-tahun dengan median PM2.5 yang lebih tinggi, diperlukan tindakan pengendalian polusi yang lebih ketat, seperti mengurangi emisi dari transportasi dan industri.
- Musim dingin memerlukan perhatian khusus dalam pengendalian polusi, seperti pengurangan pembakaran bahan bakar dan pengawasan terhadap sumber emisi tambahan.
- Pertimbangkan faktor-faktor lain seperti arah angin dan kecepatan angin untuk analisis yang lebih mendalam.
- Edukasi publik tentang dampak kesehatan dari polusi udara dan langkah-langkah pencegahan yang dapat diambil.
- Mendorong penggunaan transportasi umum dan kendaraan ramah lingkungan.
- Meningkatkan pemantauan kualitas udara dan memperluas jaringan stasiun pemantauan.

