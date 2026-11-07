KABOBS OPERATIONAL HUB — STATIC (TANPA DATABASE)

UPLOAD KE REPOSITORY GITHUB PAGES LAMA:
1. Masuk repository website lama (yang memang memakai GitHub Pages).
2. Buka tab Code > Add file > Upload files.
3. Upload tiga file: index.html, style.css, app.js ke ROOT repository yang dipakai GitHub Pages.
   Bila ada index.html lama, pilih replace/overwrite melalui editor GitHub atau hapus yang lama sebelum upload.
4. Klik Commit changes.
5. Tunggu GitHub Pages menerbitkan perubahan lalu refresh website (Ctrl+Shift+R).

TIDAK PERLU: npm, Node.js, Codespaces, Firebase, Google Sheets, Apps Script, Cloud Run.

PENTING:
- Data disimpan dalam localStorage pada browser/perangkat yang dipakai.
- Tidak ada sinkronisasi antar pengguna/perangkat. AM tidak bisa otomatis melihat input Leader dari perangkat lain.
- Pilihan AM/Leader hanya simulasi antarmuka, bukan login aman. Jangan input data sensitif atau gunakan sebagai portal internal produksi.
- Ekspor JSON secara rutin; impor JSON di browser lain untuk memindahkan data secara manual.
- Ranking hanya berdasarkan data yang ada di browser tersebut.
- Halaman memerlukan JavaScript dan localStorage aktif.
