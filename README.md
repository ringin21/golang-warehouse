# Golang Warehouse Project

Proyek microservice sistem warehouse (gudang) berbasis Go, terdiri dari beberapa service independen:

## Struktur Proyek

| Service | Deskripsi |
|---|---|
| `api-gateway` | Gateway tunggal sebagai entry point untuk semua service |
| `user-service` | Manajemen pengguna & autentikasi |
| `merchant-service` | Manajemen data merchant |
| `product-service` | Manajemen katalog produk |
| `warehouse-service` | Manajemen gudang & stok |
| `transaction-service` | Memproses transaksi penjualan/pembelian |
| `notification-service` | Pengiriman notifikasi |

## Prasyarat

- [Go](https://go.dev/dl/) 1.21 atau lebih baru

## Menjalankan Proyek

```bash
# Clone repository
git clone git@github.com:ringin21/golang-warehouse.git
cd golang-warehouse-project
```

Detail cara menjalankan masing-masing service akan didokumentasikan di direktori service terkait.

## Kontribusi

1. Buat branch fitur (`git checkout -b fitur/nama-fitur`)
2. Lakukan commit (`git commit -m 'Tambah fitur X'`)
3. Push ke branch fitur (`git push origin fitur/nama-fitur`)
4. Buka Pull Request
