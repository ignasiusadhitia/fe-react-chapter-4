# Berkenalan Dengan Git & GitHub

Proyek ini bertujuan untuk memberikan pengenalan dasar tentang Git, alat version control yang sangat populer, serta cara menggunakan GitHub untuk menyimpan dan berkolaborasi dalam proyek pengembangan perangkat lunak.

## Apa Itu Version Control?

Version control (kontrol versi) adalah sistem yang memungkinkan pengembang mencatat perubahan yang terjadi pada sebuah berkas atau kumpulan berkas dari waktu ke waktu. Ini memungkinkan pengembang untuk kembali ke versi sebelumnya jika terjadi kesalahan atau untuk melihat sejarah perubahan yang telah dilakukan pada proyek.

## Berkenalan Dengan Git

### Apa Itu Git?

Git adalah salah satu alat version control yang paling populer. Git memungkinkan banyak orang untuk bekerja bersama-sama pada sebuah proyek tanpa mengkhawatirkan versi mana yang terbaru atau apakah perubahan mereka akan bertabrakan. Dengan Git, Anda dapat melacak semua perubahan yang dilakukan pada proyek, termasuk siapa yang membuat perubahan dan kapan perubahan tersebut dibuat.

### Kegunaan Menggunakan Git

- **Tracking**: Git melacak semua perubahan yang dilakukan pada proyek. Setiap perubahan dicatat sehingga Anda bisa mengetahui siapa yang membuat perubahan dan kapan perubahan tersebut dilakukan.
- **Branching dan Merging**: Git memungkinkan Anda membuat cabang (branch) untuk mengembangkan fitur baru atau memperbaiki bug tanpa mengganggu cabang utama (main branch). Setelah selesai, Anda dapat menggabungkan (merge) cabang tersebut ke cabang utama.

## Cara Instalasi Git

- **Windows**: Unduh dan instal Git dari [https://git-scm.com/download/win](https://git-scm.com/download/win).
- **Mac**: Gunakan Homebrew dengan perintah `brew install git`.
- **Linux**: Gunakan package manager dengan perintah `sudo apt-get install git` (untuk distribusi berbasis Debian).

## Konfigurasi Dasar Git

Setelah instalasi, buka terminal atau command prompt dan lakukan konfigurasi dasar berikut:

```bash
git config --global user.name "Nama Kamu"
git config --global user.email "email@gmail.com"
```

## Perintah-perintah Dasar Git

- `git init`: Membuat repository Git baru di direktori yang sedang aktif.
- `git add`: Menambahkan file atau perubahan ke staging area sebelum di-commit.
- `git commit`: Menyimpan perubahan yang ada di staging area ke repository lokal.
- `git log`: Melihat riwayat commit yang ada di repository.
- `git checkout`: Berpindah antar branch atau commit.

## Membuat Repository di GitHub

- Buat Akun GitHub: Kunjungi GitHub dan klik tombol "Sign Up" untuk membuat akun baru.
- Buat Repository Baru:
  - Setelah login, klik tombol "New Repository".
  - Beri nama repository Anda dan pilih apakah repository akan bersifat publik atau privat.
  - Klik "Create Repository".
- Tautkan Repository Lokal ke GitHub:
  - Setelah membuat repository baru di GitHub, Anda akan diberikan perintah untuk menautkan repository lokal Anda ke GitHub.
```bash
  git remote add origin https://github.com/username/repository-name.git
  git branch -M main
  git push -u origin main
```
