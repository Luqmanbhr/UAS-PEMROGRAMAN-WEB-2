# Catatan
## Instalasi:
- Clone repositori ini
- Pada folder `htdocs`, buat folder `penduduk`
- Copy repositori ini ke folder tersebut
- Jika Anda menggunakan linux, mungkin perlu mengubah permissionnya menjadi 755 (`sudo chmod -R 755`)
- Buat database `db_warga`
- Import skema yang ada di folder `database` ke dalam database tersebut
- Buka `http://localhost/penduduk`
- Masukkan username dan password

## Todo list:
- ~~User hanya bisa lihat yang rt dan rw'nya sama dengan user tersebut saja~~ (batal)
- ~~Pembatasan akses halaman berdasarkan status_user~~
- Jika menambahkan id_kepala_keluarga, maka otomatis menambahkannya pada pivot
- Ubah dari # id menjadi nomor urut


## USername dan Password
- Admin 
	usarename : admin	password : 123
	Punya semua akses
- Ketua
	usarename : ketua password : 123
	Punya semua akses
- Staff
	username : furqon password : 123
	hanya bisa melihat atau read only