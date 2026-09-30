# ☕ Coffee Shop Web App

Website pemesanan dan manajemen coffee shop berbasis **Laravel**. 

Awalnya project ini dibuat untuk menjawab masalah klasik di kedai kopi: kasir yang ribet catat pesanan manual, barista yang sering miss status pesanan dapur, dan owner yang pusing rekap stok sama laporan tiap akhir bulan. 

Di sini semuanya dihubungkan dalam satu alur kerja yang rapi untuk 3 role: **Customer**, **Manager**, dan **Admin**.

---

### ✨ Fitur Utama

#### 1. 📱 Customer (Pesan Tanpa Ribet)
* **Katalog & Detail Menu:** Lihat pilihan kopi, makanan, dan ketersediaan stok secara real-time.
* **Keranjang & Checkout:** Tambah pesanan, atur jumlah, dan langsung checkout.
* **Tracking Order:** Pantau apakah pesanan masih antre, lagi diracik, atau sudah siap dinikmati.
* **Sistem Refund:** Pengajuan refund langsung dari halaman pesanan jika ada kendala.

#### 2. 📋 Manager (Operasional & Dapur)
* **Live Order Processing:** Terima (`Accept`), tolak (`Reject`), proses peracikan (`Process`), hingga pesanan selesai (`Complete`).
* **Pengajuan Menu Baru:** Mau nambah menu baru? Manager bisa submit draft menu lengkap dengan foto dan harga untuk direview Admin.
* **Manajemen Refund:** Review dan putuskan pengajuan refund dari customer langsung di dashboard.

#### 3. 👑 Admin (Kontrol Penuh & Laporan)
* **Approval Menu:** Kontrol kualitas menu sebelum tayang ke customer (Approve/Reject usulan manager).
* **Master Data:** Kelola user (kasir/manager/customer) dan kategori menu.
* **Laporan & Analitik:** Rekap transaksi dan data penjualan untuk pantau performa kedai.

---

### 🛠️ Tech Stack

* **Framework:** Laravel 11 / PHP 8.2+
* **Database:** MySQL
* **Frontend:** Blade Templating + Tailwind CSS
* **Deployment & Container:** Docker & Docker Compose
