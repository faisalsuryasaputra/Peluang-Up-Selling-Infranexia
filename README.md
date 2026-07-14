

Proyek ini bertujuan untuk mengoptimalkan strategi *sales* Infranexia dengan memprediksi peluang *upselling* (penambahan layanan baru) dari mitra (OLO/Mitra).

## 🚀 Fitur Utama
- **Data Pipeline Otomatis:** Membaca dan membersihkan data dari format *Berita Acara* (Excel/CSV) secara dinamis.
- **Profil Mitra:** Mengekstrak rekam jejak transaksi setiap mitra untuk analisis lebih dalam.
- **Predictive Modeling:** Menggunakan *Random Forest Classifier* untuk klasifikasi peluang *upselling*.
- **Hot Leads Radar:** Memberikan daftar prioritas mitra yang paling berpotensi untuk dihubungi oleh tim *Sales*.

## 🛠 Teknologi
- **Python** (Pandas, Scikit-Learn)
- **Visualisasi** (Matplotlib, Seaborn)

## 📊 Cara Penggunaan
1. Pastikan seluruh file data transaksi berada di folder yang sama.
2. Jalankan notebook `PeluangUpSelling.ipynb`.
3. Hasil prediksi akan muncul pada tabel **DAFTAR PRIORITAS MITRA (HOT LEADS)**.

## 👥 Kontributor
**Faisal Surya Saputra**
*Informatics Student at Telkom University*
"""

# Menulis file README.md
with open("README.md", "w") as f:
    f.write(readme_content)

print("File README.md berhasil dibuat!")
