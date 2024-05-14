# Menambah kolom
```mysql
alter table mobil add batas_peminjaman varchar(10) after peminjaman;
```

- AFTER opsional untuk di gunaka, jika menggunakan klausa ini maka secara defaul kolom yang dibuat di akhir , jika kolom ingin ditaruh pada awal kolom gunakan klausa FIRST
- silahkan tampilkan struktur tabel
**Gambar table sebelum menggunakan Query Alter**
![[h.kolom lama.png]]


# Alter table

## Struktur
```mysql

```

## Contoh Query
```mysql
alter table mobil add batas_peminjaman varchar(10) after peminjam;
```

## Hasil
**Gambar Table sesudah  menggunakan Query Alter Ini Hasilnya**
![[h.alter table.png]]

# Query update


## Contoh Query

## Hasil
**Kita telah menambahkan isi peminjam**