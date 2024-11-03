# Panduan Deploy Proyek Laravel di Cyberpanel

Panduan ini akan membantu Anda untuk mendepoy proyek ke server pakai panel Cyberpanel.

## Langkah-langkah Deploy

1. **Upload File Proyek Laravel ke `public_html`**

   Upload semua file proyek Anda ke direktori `public_html`. Ini bisa dilakukan menggunakan klien FTP atau melalui file manager.

2. **Atur Permission untuk `storage` dan `bootstrap/cache`**

   Pastikan direktori `storage` dan `bootstrap/cache` memiliki permission yang benar. Atur permission menjadi `775` dengan menggunakan tombol permission di cyberpanel atau pakai perintah berikut jika pakai ssh / terminal:

   ```sh
   chmod -R 775 storage
   chmod -R 775 bootstrap/cache

3. **Code nya ada di atas, sesuai folder `public_html` dan `public`**
