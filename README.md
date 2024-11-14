# Tugas Praktikum Pemrograman Berbasis Objek Kelas A - Pertemuan 10


### 1. Fitur Ubah PIN

**Detail Fitur:**

- Tambahkan opsi **"Ubah PIN"** pada menu utama.
- Buat method dalam kelas **Account** untuk mengubah PIN, yaitu `changePin()`.

**Langkah-langkah:**

1. **Verifikasi PIN lama.**
2. **Minta nasabah untuk memasukkan PIN baru dua kali.**
3. **Validasi bahwa kedua input PIN baru cocok.**
4. **Perbarui PIN jika validasi berhasil.**

**Tampilan Kode:**

![image](https://github.com/user-attachments/assets/915e65e1-4738-41e4-8cf4-44374738f08d)

---

### 2. Validasi Saldo Minimal pada Saat Penarikan

**Detail Fitur:**

- Modifikasi fitur penarikan sehingga nasabah harus menyisakan saldo minimal setelah penarikan dilakukan (misalnya saldo minimal adalah Rp 50.000).

**Langkah-langkah:**

1. Tentukan saldo minimal dan tambahkan konstanta **`MINIMUM_BALANCE`** dalam kelas **Account**.
2. Modifikasi method **`execute()`** dalam kelas **Withdrawal** untuk memeriksa apakah saldo setelah penarikan tidak kurang dari saldo minimal.
3. Jika saldo tidak mencukupi, tampilkan pesan kesalahan.

**Tampilan Kode:**

![image](https://github.com/user-attachments/assets/b2cf4a92-8957-405e-9840-ff6e745b8d79)
