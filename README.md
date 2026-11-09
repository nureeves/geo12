# Geografi Kelas XII – MA Syarikat Islam Parakansalak

Situs materi Geografi kelas XII (MkDocs Material, di-hosting di GitHub Pages).

## Cara memasang (sekali saja)

1. Buat repositori baru di GitHub, mis. `geografi-xii-masip` (Public).
2. Unggah **seluruh isi folder ini** ke repositori (cabang `main`).
3. Buka `mkdocs.yml`, ganti `USERNAME` pada `site_url` dan `repo_url` dengan nama akun GitHub Anda.
4. Tunggu GitHub Actions selesai (tab **Actions**, workflow "Deploy situs").
5. Buka **Settings → Pages**, pilih **Source: Deploy from a branch**, cabang **gh-pages**, folder **/ (root)**, lalu Save.
6. Situs aktif di `https://USERNAME.github.io/geografi-xii-masip/`.

## Cara menambah/mengubah materi

- Semua materi ada di folder `docs/`, berupa file Markdown (`.md`).
- Edit langsung di GitHub (ikon pensil), lalu Commit. Situs diperbarui otomatis dalam 1-2 menit.
- Gambar: taruh di `docs/assets/` lalu tulis `![keterangan](../assets/nama.jpg)`. Kompres dulu (maks. ±200 KB) agar ringan di HP.
- Menambah halaman: buat file `.md` baru, lalu daftarkan di bagian `nav:` pada `mkdocs.yml`.
- Template halaman subbab ada di `docs/_template/subbab.md` (salin, lalu isi).

## Pratinjau di komputer (opsional)

```bash
pip install -r requirements.txt
mkdocs serve        # buka http://127.0.0.1:8000
```

## Catatan

- TP pada situs ini adalah **draf** dan harus divalidasi dengan CP resmi (Kepka BSKAP 046/H/KR/2025) serta ATP madrasah.
- Pastikan materi, gambar, dan data bebas hak cipta atau mencantumkan sumber (BPS, Bappenas, Kementerian ATR/BPN, dsb.).
