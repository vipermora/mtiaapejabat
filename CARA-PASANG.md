# Pelancar SISTEM PEJABAT (ikon logo di telefon & laptop)

Folder ini ialah halaman kecil yang memaparkan logo MTIAA dan membuka web app Apps Script. Pengguna menambahnya ke skrin utama, dan ikon yang dipaparkan ialah logo MTIAA.

## 1. Masukkan pautan web app
Buka `index.html` dengan Notepad. Cari baris berikut:

    const WEB_APP_URL = 'TAMPAL_URL_WEB_APP_DI_SINI';

Gantikan teks dalam tanda petik dengan **Web app URL** anda (yang berakhir dengan `/exec`), kemudian simpan.

## 2. Hos folder ini (percuma). Pilih SATU cara.

**Cara A: Netlify (paling mudah)**
1. Daftar akaun percuma di https://app.netlify.com.
2. Pergi ke **Sites > Add new site > Deploy manually**.
3. Seret (drag) **seluruh folder `pelancar`** ke kotak muat naik.
4. Anda akan menerima pautan seperti `https://nama-rawak.netlify.app`. Pautan ini boleh ditukar di **Site configuration > Change site name**, contohnya `https://mtiaa-pejabat.netlify.app`.

**Cara B: GitHub Pages**
1. Cipta repositori awam baharu, contohnya `mtiaa-pejabat`, dan muat naik semua fail dalam folder ini.
2. Pergi ke **Settings > Pages > Source: Deploy from a branch > main / (root) > Save**.
3. Pautannya ialah `https://NAMA-GITHUB.github.io/mtiaa-pejabat/`.

## 3. Kongsi pautan pelancar dengan pengguna
Kongsi pautan **pelancar** (Netlify/GitHub), bukan pautan Apps Script. Pengguna buka pautan itu dan:
- **iPhone/iPad (Safari):** tekan **Share > Add to Home Screen**.
- **Android (Chrome):** tekan **⋮ > Add to Home screen** atau **Install app**.
- **Laptop (Chrome/Edge):** klik ikon **Install** di bar alamat.

Bila ikon di skrin utama ditekan, sistem akan dibuka terus.

## Jika Web app URL berubah
Kemas kini `index.html` dan muat naik semula. Ikon yang telah dipasang pengguna akan terus berfungsi.
