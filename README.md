# 📋 Desktop Menu Management (CRUD)

Aplikasi desktop berbasis Visual Programming untuk manajemen data menu menggunakan konsep CRUD (*Create, Read, Update, Delete*). Proyek ini dirancang dengan antarmuka pengguna yang intuitif untuk mempermudah pencatatan, pembaruan, dan pengelolaan menu secara efisien.

---

## ✨ Fitur Utama

- **➕ Create (Tambah Menu)**: Menambahkan data menu baru (Nama menu, Kategori, Harga, Stok/Status).
- **📋 Read (Tampilkan Menu)**: Menampilkan seluruh daftar menu dalam tabel (*DataGridView*).
- **✏️ Update (Perbarui Menu)**: Mengubah detail informasi menu yang sudah tersimpan.
- **🗑️ Delete (Hapus Menu)**: Menghapus data menu dari sistem dengan konfirmasi keamanan.
- **🧹 Reset Form**: Membersihkan kolom input dalam satu klik untuk input data baru.

---

## 🛠️ Teknologi & Kebutuhan Sistem

- **Bahasa Pemrograman**: C# / VB.NET *(sesuaikan dengan proyek Anda)*
- **Framework / UI**: .NET Framework (Windows Forms)
- **Database**: MySQL / SQL Server *(sesuaikan dengan database yang digunakan)*
- **IDE**: Microsoft Visual Studio 2019 / 2022

---

## 🚀 Cara Menjalankan Proyek

1. **Clone atau Unduh Repository**:
   ```bash
   git clone https://github.com/znlilmi/menu-management-crud.git
   ```
2. **Buka Proyek**:
   - Jalankan **Microsoft Visual Studio**.
   - Buka file solusi proyek (`.sln`).
3. **Konfigurasi Database**:
   - Pastikan database server (misal: MySQL/XAMPP atau SQL Server) sudah aktif.
   - Buat database dan sesuaikan *connection string* pada file konfigurasi/koneksi aplikasi.
4. **Build & Run**:
   - Tekan tombol **Start** atau tekan `F5` di Visual Studio untuk menjalankan aplikasi.

---

## 🗄️ Struktur Tabel Database (Contoh)

| Kolom | Tipe Data | Keterangan |
| :--- | :--- | :--- |
| `id_menu` | `INT` | Primary Key, Auto Increment |
| `nama_menu` | `VARCHAR(100)` | Nama menu makanan/minuman |
| `kategori` | `VARCHAR(50)` | Kategori menu |
| `harga` | `DECIMAL / INT` | Harga menu |
| `stok` | `INT` | Jumlah stok tersedia |

---

## 👤 Pembuat

Dibuat oleh [**Zainal Ilmi**](https://github.com/znlilmi).
