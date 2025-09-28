# UMKM Blockchain–IPFS

## 📌 Abstrak
UMKM sebagai tulang punggung perekonomian membutuhkan sistem pencatatan transaksi yang aman, transparan, dan tahan manipulasi. Penelitian ini merancang dan membangun sistem pencatatan transaksi UMKM berbasis Blockchain dan InterPlanetary File System (IPFS) dengan penerapan enkripsi Advanced Encryption Standard (AES) serta pengelolaan kunci melalui USB Security Key. Data transaksi terenkripsi disimpan pada IPFS dengan alamat berbasis konten (Content Identifier/CID), sementara hash/CID dan informasi terkait dicatat ke dalam Blockchain sebagai bukti integritas. Pendekatan ini memberikan solusi penyimpanan transaksi yang terdistribusi, menjaga kerahasiaan data, serta memastikan integritas dan keaslian catatan transaksi UMKM.

## 🏗 Arsitektur Sistem
- **Blockchain** → mencatat hash/CID transaksi, timestamp, dan owner.
- **IPFS** → menyimpan file transaksi terenkripsi dengan content-addressing (CID).
- **AES** → algoritma enkripsi simetris untuk menjaga kerahasiaan data.
- **USB Security Key** → mengamankan kunci enkripsi (DEK/KEK).

## ✨ Fitur Utama
- Pencatatan transaksi UMKM dengan proof-of-integrity berbasis Blockchain.
- Penyimpanan file transaksi terenkripsi di IPFS.
- Manajemen kunci enkripsi menggunakan USB Security Key.
- Rotasi DEK harian untuk memperkuat keamanan.

## 📂 Struktur Repo
