# 🍎 Sistem Pakar Diagnosis Penyakit Tanaman Apel

Repository ini berisi proyek **Sistem Berbasis Pengetahuan (Knowledge-Based System)** untuk mendiagnosis penyakit spesifik pada tanaman apel. Sistem ini dikembangkan menggunakan kerangka kerja **Methontology** dan diimplementasikan ke dalam *Semantic Web* menggunakan perangkat lunak **Protégé**.

Proyek ini disusun sebagai bentuk penyelesaian Ujian Akhir Semester (UAS) mata kuliah Pengembangan Sistem Berbasis Pengetahuan.

## 📖 Deskripsi Kasus
Identifikasi penyakit pada tanaman hortikultura, khususnya apel, sering kali menjadi tantangan bagi petani karena kemiripan gejala visual. Diagnosis yang terlambat atau salah dapat berujung pada kerugian panen yang signifikan. Proyek ini memodelkan pengetahuan pakar ke dalam sistem ontologi untuk mendiagnosis 5 penyakit utama pada apel berdasarkan gejala visual makroskopis:
1. Embun Tepung (*Podosphaera Leucotricha*)
2. Bercak Daun (*Marssonina Coronaria*)
3. Jamur Upas (*Cortisium Salmonicolor*)
4. Kanker (*Botryosphaeria Sp.*)
5. Busuk Buah (*Gloeosporium Sp.*)

## 🎯 Solusi Penyelesaian
Kami membangun sebuah ontologi terstruktur yang merepresentasikan kelas (`Class`), relasi antar konsep (`Object Properties`), dan data spesifik (`Individuals`). Sistem ini menerima input berupa gejala yang diamati pada bagian tanaman (daun, buah, batang), lalu menggunakan *Reasoner* berbasis *Description Logic* (DL) untuk menyimpulkan secara otomatis jenis penyakit yang menyerang beserta patogen penyebabnya.

## 🛠️ Lingkungan Kerja (Tools)
* **Software:** Protégé Desktop (Version 5.x)
* **Metodologi:** Methontology
* **Reasoner:** HermiT / Pellet
* **Format Output:** OWL/XML

## 📺 Demo Aplikasi
Penjelasan lengkap mengenai instalasi tools, lingkungan kerja, deskripsi solusi, hingga **Demo DL Query** dapat disaksikan pada video tutorial berikut:

[![Video Tutorial YouTube](https://img.shields.io/badge/YouTube-Tonton_Demo_Aplikasi-red?style=for-the-badge&logo=youtube)](MASUKKAN_LINK_YOUTUBE_ANDA_DI_SINI)

## 📂 Struktur Direktori
* `/ontology/` : Berisi file *source code* ontologi (`.owl`) yang merupakan hasil akhir perancangan perangkat lunak dan dapat dijalankan langsung di Protégé.
* `/docs/` : Berisi dokumen pendukung, termasuk slide presentasi kelompok dan literatur jurnal ilmiah yang digunakan sebagai *Knowledge Base*.
