# 🚗 Toyota Fortuner AR Showcase

Aplikasi **Augmented Reality berbasis marker** yang menampilkan model 3D Toyota Fortuner secara real-time menggunakan **Unity** dan **Vuforia Engine**. Arahkan kamera ke marker, Fortuner langsung muncul!

![Unity](https://img.shields.io/badge/Unity-2022.3_LTS-black?logo=unity) ![Vuforia](https://img.shields.io/badge/Vuforia-Engine_11-brightgreen) ![Platform](https://img.shields.io/badge/Platform-Windows-blue)

---

## 📱 Tentang Aplikasi

Project ini dibuat sebagai Mini Project mata kuliah **Augmented Reality** di Universitas Jember. Aplikasi mendeteksi gambar marker melalui webcam, lalu menampilkan objek 3D mobil Toyota Fortuner di atasnya secara real-time.

**Fitur:**
- Deteksi marker real-time via webcam
- Model 3D Toyota Fortuner dengan material & texture
- Marker custom buatan sendiri (rating ⭐⭐⭐⭐⭐)

---

## 🛠️ Teknologi

| Tools | Keterangan |
|-------|-----------|
| Unity 2022.3 LTS | Game engine, Built-In Render Pipeline |
| Vuforia Engine 11 | SDK untuk fitur AR berbasis marker |
| glTFast | Plugin untuk membaca file model 3D format `.glb` / `.gltf` |

---

## 📦 Plugin yang Dibutuhkan

### glTFast — Import Model 3D Format GLTF/GLB

Model 3D yang digunakan berformat `.gltf` / `.glb`, sehingga membutuhkan plugin **glTFast** dari Unity Package Manager.

**Cara install:**

1. Buka Unity, masuk ke **Window → Package Manager**
2. Klik tombol **＋** di kiri atas
3. Pilih **Add package by name**
4. Masukkan nama package berikut:
   ```
   com.unity.cloud.gltfast
   ```
5. Klik **Add** → tunggu proses install selesai

> Setelah install, file `.gltf` / `.glb` sudah bisa langsung di-drag ke Scene atau Hierarchy di Unity.

---

## 🚀 Cara Menjalankan

1. Clone repo ini
2. Buka project di **Unity Hub**
3. Install plugin **glTFast** via Package Manager (lihat panduan di atas)
4. Buka scene `Assets/Scenes/SampleScene`
5. Klik **▶ Play**
6. Arahkan webcam ke gambar marker → Fortuner muncul!

> **Catatan:** Pastikan webcam aktif dan gambar marker tersedia (ada di folder `/marker/`)

---

## 🖼️ Marker

File marker: `/marker/marker.jpg`

Cetak gambar marker atau tampilkan di HP/layar lain, lalu arahkan kamera ke sana saat demo.

---

## 🎬 Demo Video

[![YouTube](https://img.shields.io/badge/▶_Tonton_Demo-YouTube-red?logo=youtube)](https://youtu.be/t0zvfOuyQAM)

---

## 👤 Identitas

| | |
|-|-|
| Nama | FIQRI ARIEL PRADHANA |
| NIM | [232410102085 |
| Mata Kuliah | Augmented Reality A |
| Dosen | Narandha Arya Ranggianto, S.Kom., M.Kom. |
| Universitas | Universitas Jember — Fasilkom |

---

## 📚 Referensi

- [Vuforia Getting Started with Unity](https://developer.vuforia.com/library/vuforiaengine/getting-started/development-environments/getting-started-vuforia-engine-unity/)
- [Unity Documentation 2022.3](https://docs.unity3d.com/2022.3/Documentation/Manual/index.html)
- [glTFast Documentation](https://docs.unity3d.com/Packages/com.unity.cloud.gltfast@6.0/manual/index.html)
