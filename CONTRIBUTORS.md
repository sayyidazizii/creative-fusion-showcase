# Contributing Guidelines
> Harap baca panduan ini sebelum berkontribusi ke proyek ini.

## Branching
- Gunakan branch `master` untuk branch utama.
- Buat branch baru dari branch `master` untuk setiap fitur yang akan dikerjakan.
- Format nama branch: `feat/nama-fitur` atau `fix/nama-fitur`.
- Contoh: `feat/login` atau `fix/login`.

## Commit Message
- Gunakan bahasa Inggris.
- Gunakan format: `enhance(nama-fitur): deskripsi-fitur` atau `fix(nama-fitur): deskripsi-fitur`.
- Contoh: `enhance(login): add-validation-on-login-form`.
- Gunakan kata kerja yang sesuai dengan perubahan yang dilakukan.

## Code Style
- Gunakan standar penulisan kode PHP PSR-12.
- Jalan kan `./vendor/bin/phpcbf --standard=PSR12 app/` untuk memperbaiki penulisan kode.
- Jalan kan `./vendor/bin/phpcs --standard=PSR12 app/` untuk memeriksa penulisan kode.
- Jangan lupa untuk memperbarui dokumentasi jika diperlukan.

