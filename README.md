<h1 align="center">
  Projects by Yetazyyy
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Compression-bz2-yellow?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" />
</p>

---

### 📁 Download Termux
[https://f-droid.org/repo/com.termux_117.apk](https://f-droid.org/repo/com.termux_117.apk)

---

### 🖼️ Screenshot
<p align="center">
  <img src="https://github.com/Yetazyyy/Bz2/blob/main/Screenshot_2025-09-09-08-17-07-902_ru.iiec.pydroid3-edit.jpg?raw=true" alt="Screenshot 1" style="max-width: 100%; height: auto;" />
  <br />
  <img src="https://github.com/Yetazyyy/Bz2/blob/main/Screenshot_2025-09-09-18-21-04-763_ru.iiec.pydroid3-edit.jpg?raw=true" alt="Screenshot 2" style="max-width: 100%; height: auto;" />
</p>

---

### ✨ Tujuan
Menjalankan kode Python yang telah dikompresi menggunakan modul `bz2`.  
Manfaatnya antara lain:
- Menyembunyikan source code agar tidak langsung terbaca
- Menyimpan script dalam bentuk kompresi yang lebih ringkas
- Memuat kode dari file atau string yang terenkripsi/terkompresi

---

### Cara Penggunaan

1. Salin script Python yang sudah dikompresi ke file, misalnya `YetaHubX.py`.
2. Jalankan script tersebut menggunakan aplikasi Pydroid 3 atau Termux.

Contoh script sederhana untuk menjalankan kode Python terkompresi:

```python
import bz2

# Contoh kode Python yang akan dikompresi
source_code = """
print("Halo dari kode terkompresi!")
"""

# Kompresi kode sumber
compressed_code = bz2.compress(source_code.encode('utf-8'))

# Dekompresi kode
decompressed_code = bz2.decompress(compressed_code).decode('utf-8')

# Eksekusi kode hasil dekompresi
exec(decompressed_code)
