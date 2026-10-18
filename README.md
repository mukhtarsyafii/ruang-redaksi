# Ruang Redaksi

Papan redaksi (editorial board) untuk kelas radio komunitas warga. Satu file HTML statis — tidak perlu build.

## Fitur

- Header: pemilih kelas, tombol Ekspor, pengaturan Kelas, Tambah konten
- Stats bar per status: Semua, Pitching, Produksi, Editing, Siap Tayang, Tayang, Ditunda (klik sebagai filter)
- Toolbar: pencarian judul/PIC, filter status, filter rubrik
- Tabel konten: judul + tag rubrik, format, PIC, deadline produksi (dengan penanda terlambat), badge status, tautan draft, aksi Edit/Hapus

## Menjalankan

Buka langsung `index.html` di browser, atau lihat di:

https://mukhtarsyafii.github.io/ruang-redaksi/

## Teknis

- Tailwind CSS via CDN (`cdn.tailwindcss.com`) — tanpa langkah build
- Token tema (`--foreground`, `--card`, `--border`, dst.) didefinisikan di `:root` agar halaman berdiri sendiri
- Font: Instrument Serif (logo) + Inter (UI)

## Status

Mockup tampilan. Tombol, filter, dan form belum punya logika — data di tabel masih statis.
