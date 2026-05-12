Sistem Monitoring & Ranking Akademik Mahasiswa

Program sederhana berbasis Python untuk menentukan status aktif mahasiswa dan saya menambahakan ranking berdasarkan tingkat kedisiplinan (kehadiran dan penyelesaian tugas) menggunakan konsep **Decision Tree (IF-ELSE)**.

## 📋 Deskripsi Tugas
Tugas ini merupakan bagian dari praktikum pemrograman yang bertujuan untuk mengimplementasikan logika percabangan pada studi kasus dunia nyata, yaitu sistem presensi akademik.

## 🛠️ Fitur Utama
- **Status Otomatis**: Menentukan status "Aktif" atau "Tidak Aktif" berdasarkan data kehadiran.
- **Logika Decision Tree**: Memproses data menggunakan aturan IF-ELSE untuk menentukan klasifikasi mahasiswa.
- **Ranking Mahasiswa Terrajin**: Fitur tambahan yang secara otomatis menyaring mahasiswa dengan kualifikasi "Tinggi" (Kehadiran) dan "Lengkap" (Tugas).
- **Rekapitulasi Data**: Menampilkan ringkasan total mahasiswa aktif dan tidak aktif di akhir program.
- **Data Extensibility**: Memudahkan penambahan data mahasiswa baru ke dalam sistem.

## 📐 Aturan Keputusan (Decision Tree)
1. **Status Aktif**: Didapat jika Kehadiran bersifat **Tinggi**.
2. **Status Tidak Aktif**: Didapat jika Kehadiran bersifat **Rendah**.
3. **Mahasiswa Disiplin**: Jika Kehadiran **Tinggi** DAN Tugas **Lengkap**.

## 🚀 Cara Menjalankan di Visual Studio Code

1. **Persiapan**:
   - Pastikan **Python** sudah terinstal di komputer Anda.
   - Instal ekstensi **Python** dari Microsoft di VS Code.

2. **Membuka Proyek**:
   - Buka halaman repositori ini di GitHub.
   - Klik tombol hijau **"<> Code"**, pilih tab **HTTPS**, lalu klik ikon salin (clipboard).
   - Buka **Terminal** atau **Git Bash** di komputer Anda, lalu masuk ke folder tujuan dan jalankan perintah:
     ```bash
     git clone [https://github.com/zaldyfadhlulrohman/Program_Monitoring_Zaldy.git]
   - Cari dan pilih folder hasil clone tadi (folder Program_Monitoring_Zaldy), lalu klik Select Folder.
   - Di bilah sisi kiri (Explorer), klik file Decision Tree sederhana.py untuk membukanya.

3. **Menjalankan Program**:
Terdapat dua cara untuk menjalankan program di Visual Studio Code:

*   **Cara 1 (Tombol Run):**
    Klik ikon **Play** (▷) yang terletak di pojok kanan atas jendela editor VS Code.
*   **Cara 2 (Terminal VS Code):**
    1. Buka terminal internal dengan menekan shortcut `Ctrl` + ` ` ` (backtick) atau melalui menu **Terminal > New Terminal**.
    2. Ketik perintah berikut dan tekan **Enter**:
       ```bash
       python "Decision Tree sederhana.py"
       ```
 
4. **Output**:
```bash
[Running] python -u "c:\Users\suriy\web_form_mhs\web_form_mhs\tugas_bug_hunt\Decision Tree sederhana.py"
==================================================
       SISTEM INFORMASI AKADEMIK MAHASISWA        
==================================================
Nama       : Andi
Kehadiran  : Tinggi
Tugas      : Lengkap
Status     : Aktif
Keterangan : Mahasiswa Disiplin
--------------------------------------------------
Nama       : Budi
Kehadiran  : Rendah
Tugas      : Tidak Lengkap
Status     : Tidak Aktif
Keterangan : -
--------------------------------------------------
Nama       : Citra
Kehadiran  : Tinggi
Tugas      : Tidak Lengkap
Status     : Aktif
Keterangan : -
--------------------------------------------------
Nama       : Deni
Kehadiran  : Rendah
Tugas      : Lengkap
Status     : Tidak Aktif
Keterangan : -
--------------------------------------------------
Nama       : Eka
Kehadiran  : Tinggi
Tugas      : Lengkap
Status     : Aktif
Keterangan : Mahasiswa Disiplin
--------------------------------------------------

**************************************************
        --- DAFTAR MAHASISWA TERRAJIN ---         
**************************************************
 Ranking 1 : Andi (Sangat Disiplin)
 Ranking 2 : Eka (Sangat Disiplin)
**************************************************

==================================================
              REKAP DATA KESELURUHAN              
==================================================
 Jumlah Mahasiswa Aktif       : 3
 Jumlah Mahasiswa Tidak Aktif : 2
 Total Mahasiswa              : 5
==================================================
```
---
**Disusun oleh:** Zaldy Fadhlulrohman  
**NIM:** 202412040  
**Program Studi:** Teknik Informatika
