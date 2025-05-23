# Belajar Git bersama Foundation by Sandbox IT HSI

Ikuti petunjuk dibawah ini:

1. Buatlah sebuah issue menggunakan template [Profil](https://github.com/hsiabdullahroy/foundation-git/issues/new?template=profil-github-santri-foundation.md)

2. Lakukan fork pada repository ini.

3. Lakukan Clone repository hasil fork ke komputer lokal Anda.

```
git clone https://github.com/<akun-github-anda>/foundation-git.git
```

4. Masuk ke folder project dan buat branch baru berdasarkan NIP HSI Anda

```
cd foundation-git
git switch -c profile-ARN211-09034
```

5. Kemudian, edit file `profile-submission.json`

Tambahkan data profil (NIP HSI Anda dan link Issue yang Anda buat) di baris paling bawah,

> Pastikan tidak ada tanda koma ekstra yang hilang atau kelebihan dan tidak ada error di VSCODE (atau code editor Anda)

6. Simpan perubahan dan push ke repo fork (Github Anda)

```
    git add profile-submission.json
    git commit -m "add: profile-ARN211-09034"
    git push origin profile-ARN211-09034
```

> sesuaikan dengan NIP HSI Anda

8. Buat sebuah Pull Request (PR)
   Setelah push berhasil, buka repository ini di GitHub dan buat Pull Request dari branch Anda.

tulis di kolom deskripsi sesuai dengan yang Anda lakukan, misalnya dalam hal ini menambahkan profil

```
menambahkan profile-ARN211-09034

Closes #3
```

> Gantilah `#3` dengan nomor issue Anda masing-masing. Penulisan `Closes #...` akan menutup issue Anda secara otomatis saat PR di-merge.

9. kemudian Senior Learner akan mengeceknya.
