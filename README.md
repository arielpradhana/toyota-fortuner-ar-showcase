# 🚗 Toyota Fortuner AR Showcase

Aplikasi **Augmented Reality berbasis marker** yang menampilkan model 3D Toyota Fortuner secara real-time menggunakan **Unity** dan **Vuforia Engine**. Arahkan kamera ke marker, Fortuner langsung muncul!

![Unity](https://img.shields.io/badge/Unity-2022.3_LTS-black?logo=unity) ![Vuforia](https://img.shields.io/badge/Vuforia-Engine_11-brightgreen) ![Platform](https://img.shields.io/badge/Platform-Windows-blue)

---

## 📱 Tentang Aplikasi

Project ini dibuat sebagai Mini Project mata kuliah **Augmented Reality** di Universitas Jember. Aplikasi mendeteksi gambar marker melalui webcam, lalu menampilkan objek 3D mobil Toyota Fortuner di atasnya secara real-time.

**Fitur:**
- Deteksi marker real-time via webcam
- Model 3D Toyota Fortuner dengan material & texture
- Marker custom buatan sendiri (rating ⭐⭐⭐⭐)

---

## 🛠️ Teknologi

| Tools | Keterangan |
|-------|-----------|
| Unity 2022.3 LTS | Game engine, Built-In Render Pipeline |
| Vuforia Engine 11 | SDK untuk fitur AR berbasis marker |
| glTFast | Plugin untuk membaca file model 3D format `.glb` / `.gltf` |

---

## ⚙️ Persiapan Sebelum Menjalankan

### 1. Install Vuforia Engine

Karena file Vuforia melebihi batas ukuran GitHub (100MB), Vuforia perlu diinstall manual setelah clone.

**Langkah install:**
1. Buka browser → login di **developer.vuforia.com**
2. Masuk ke menu **Downloads**
3. Klik **Download for Unity** → file `.unitypackage` akan terdownload
4. Buka Unity dengan project ini
5. Di Unity: **Assets → Import Package → Custom Package**
6. Pilih file `.unitypackage` Vuforia yang baru didownload
7. Klik **Import** → tunggu selesai

> Kalau muncul popup "Update", klik **Update**

---

### 2. Install glTFast

Model 3D Fortuner menggunakan format `.gltf`, sehingga perlu plugin glTFast.

**Langkah install:**
1. Di Unity: **Window → Package Manager**
2. Klik tombol **＋** di kiri atas
3. Pilih **Add package by name**
4. Masukkan:
   ```
   com.unity.cloud.gltfast
   ```
5. Klik **Add** → tunggu selesai

---

### 3. Buka Scene AR

Setelah semua package terinstall:
1. Di panel **Project** → buka folder **Assets → Scenes**
2. **Double click SampleScene**
3. Scene AR dengan AR Camera dan Image Target akan muncul

---

## 🚀 Cara Menjalankan

1. Clone repo ini:
   ```bash
   git clone https://github.com/arielpradhana/toyota-fortuner-ar-showcase.git
   ```
2. Buka project di **Unity Hub** → tunggu loading selesai (5-10 menit)
3. Install **Vuforia** dan **glTFast** (lihat panduan di atas)
4. Buka scene **Assets → Scenes → SampleScene**
5. Klik **▶ Play**
6. Arahkan webcam ke gambar marker → Fortuner muncul!

> **Catatan:** Pastikan webcam aktif dan gambar marker tersedia (ada di folder `/marker/`)

---

## 🖼️ Marker

File marker: `/marker/FortunerMarker.png`

Cetak gambar marker atau tampilkan di HP/layar lain, lalu arahkan kamera ke sana saat demo.

---

## ❗ Troubleshooting

| Masalah | Solusi |
|---------|--------|
| Error "Tarball package cannot be found" | Vuforia belum diinstall — ikuti panduan install Vuforia di atas |
| Assets folder kosong saat pertama buka | Tunggu Unity generate Library (5-10 menit), jangan ditutup |
| Marker tidak terdeteksi | Pastikan pencahayaan cukup dan marker dicetak/ditampilkan jelas |
| Objek 3D tidak muncul | Pastikan glTFast sudah terinstall |
| Scene kosong / Untitled | Buka manual: Assets → Scenes → double click SampleScene |

---

## 🎬 Demo Video

[![YouTube](https://img.shields.io/badge/▶_Tonton_Demo-YouTube-red?logo=youtube)](https://youtu.be/t0zvfOuyQAM)

---

## 👤 Identitas

| | |
|-|-|
| Nama | FIQRI ARIEL PRADHANA |
| NIM | 232410102085 |
| Mata Kuliah | Augmented Reality (KTU1042) |
| Dosen | Narandha Arya Ranggianto, S.Kom., M.Kom. |
| Universitas | Universitas Jember — Fasilkom |

---

## 📚 Referensi

- [Vuforia Getting Started with Unity](https://developer.vuforia.com/library/vuforiaengine/getting-started/development-environments/getting-started-vuforia-engine-unity/)
- [Unity Documentation 2022.3](https://docs.unity3d.com/2022.3/Documentation/Manual/index.html)
- [glTFast Documentation](https://docs.unity3d.com/Packages/com.unity.cloud.gltfast@6.0/manual/index.html)
