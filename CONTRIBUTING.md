# Panduan Berkontribusi

Terima kasih sudah tertarik berkontribusi ke repository `rpl-2026-<NIM>`. Repository ini adalah portofolio belajar RPL, jadi kontribusi yang paling relevan berupa **koreksi, saran perbaikan dokumen, atau perbaikan typo**. Semua kontribusi dipersilakan, selama mengikuti panduan ini.

## Alur singkat

1. **Fork** repository ini (atau *clone* jika Anda sudah menjadi collaborator).
2. **Buat branch baru** dari `main`.
3. **Lakukan perubahan** kecil dan terfokus.
4. **Commit** dengan format pesan di bawah.
5. **Push** branch Anda, lalu buka **Pull Request (PR)** ke `main`.
6. Tunggu *review*, lalu perbaiki jika ada masukan.

## Penamaan branch

Format: `<jenis>/<deskripsi-singkat>` (huruf kecil, pakai tanda hubung).

| Jenis | Kegunaan | Contoh |
|---|---|---|
| `feat` | Menambah konten/fitur baru | `feat/tambah-tugas-02` |
| `fix` | Memperbaiki kesalahan | `fix/typo-readme` |
| `docs` | Perubahan dokumentasi | `docs/perjelas-contributing` |
| `chore` | Perawatan lain (struktur folder, dll.) | `chore/rapikan-folder` |

## Format pesan commit

Mengikuti pola sederhana ala *Conventional Commits*:

```
<jenis>: <ringkasan singkat dalam bahasa imperatif>

[opsional] penjelasan lebih rinci: apa yang berubah dan mengapa.
```

Aturan:
- Ringkasan maksimal ~72 karakter, tanpa titik di akhir.
- Satu commit = satu perubahan logis (jangan campur banyak hal sekaligus).
- Gunakan jenis yang sama dengan penamaan branch (`feat`, `fix`, `docs`, `chore`).

Contoh pesan commit yang baik:
- `docs: add AI policy`
- `docs: add KOMITMEN_KERJA with six work commitments`
- `fix: correct typo in README`

Contoh yang **kurang baik**: `update`, `revisi`, `fix semua`, `final final 2`.

## Pull Request

Pastikan PR Anda:
- punya **judul jelas** (boleh mengikuti format commit);
- memuat **deskripsi** singkat: apa yang diubah, mengapa, dan bagaimana memeriksanya;
- **fokus pada satu tujuan** dan ukurannya kecil agar mudah di-review;
- tidak memuat data pribadi, password, token, atau berkas besar yang tidak perlu.


## Melaporkan masalah

Temukan kesalahan atau punya saran? Buka **Issue** dengan judul jelas dan sertakan langkah/lokasi yang bermasalah. Jika menyangkut **keamanan atau data sensitif**, jangan dipublikasikan di Issue; hubungi saya secara pribadi.

## Etika dan lisensi

- Berkontribusi berarti Anda setuju kontribusi Anda dilisensikan di bawah [MIT License](LICENSE).
- Hanya kirim karya Anda sendiri, atau yang Anda berhak bagikan, dan cantumkan sumbernya jika mengutip.
- Penggunaan AI dalam kontribusi mohon disebutkan di deskripsi PR (lihat [AI_POLICY.md](AI_POLICY.md)).
- Bersikaplah sopan dan menghargai semua pihak.
