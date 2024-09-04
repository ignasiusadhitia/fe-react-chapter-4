# Dasar-dasar Bootstrap

Proyek ini menampilkan penggunaan dasar-dasar Bootstrap 5, framework front-end yang populer untuk pengembangan web yang responsif dan modern. Bootstrap menyediakan berbagai elemen dan komponen siap pakai yang memudahkan pembuatan tata letak yang konsisten dan elegan.

## Menu Penting pada Dokumentasi Bootstrap

Bootstrap memiliki dokumentasi yang sangat lengkap dan terbagi menjadi beberapa bagian penting:

- **Layout**: Berisi informasi tentang layout seperti sistem grid, breakpoint, dan lainnya.
- **Content**: Berisi informasi tentang isi konten seperti tipografi, gambar, dan tabel.
- **Forms**: Berisi informasi tentang komponen formulir dan validasi formulir.
- **Components**: Berisi informasi tentang berbagai komponen yang tersedia di Bootstrap, seperti tombol, navbar, dan modal.
- **Utilities**: Berisi informasi tentang utilitas tambahan seperti flexbox, warna, float, dan lainnya.

## Typography pada Bootstrap

Bootstrap menyediakan styling tipografi secara default, yang sudah diatur sedemikian rupa sehingga kita tidak perlu melakukan banyak penyesuaian. Dengan menggunakan kelas-kelas Bootstrap, kita bisa mengatur heading, paragraf, dan elemen teks lainnya dengan mudah.

## Container pada Bootstrap

Bootstrap menggunakan kelas `.container` untuk mengatur lebar konten utama agar tidak terlalu lebar dan tetap responsif. Kelas ini memastikan bahwa konten berada di tengah halaman dengan margin otomatis.

## Padding dan Margin pada Bootstrap

Bootstrap menyediakan kelas utilitas untuk mengatur padding dan margin, yang diwakili oleh properti `p` dan `m`, diikuti oleh ukuran dari `1` sampai `5`. Kita juga bisa menentukan arah padding atau margin dengan menambahkan `t` (top), `l` (left), `r` (right), `x` (left and right), atau `y` (top and bottom).

## Coloring pada Bootstrap

Bootstrap menyediakan berbagai kelas utilitas untuk mengatur warna teks, latar belakang, dan elemen tombol dengan cepat dan mudah. Beberapa kategori utama termasuk `text-primary`, `bg-success`, dan `btn-danger`.

## Component Button pada Bootstrap

Untuk menerapkan styling pada tombol, kita cukup menambahkan kelas `btn` pada tag `<button>`, lalu diikuti dengan jenis tombol seperti `btn-primary` dan ukuran seperti `btn-lg` atau `btn-sm`. Contoh:

```html
<button type="button" class="btn btn-primary btn-lg">Tombol Besar</button>
```
