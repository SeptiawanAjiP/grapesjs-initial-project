# Penggunaan GrapesJS

Repository ini bertujuan untuk menunjukkan cara penggunaan GrapesJS, suatu alat pembuat web yang sangat powerful dan keren.

## Situs Web Resmi GrapesJS

Buat informasi lebih lanjut, dokumentasi, dan contoh, langsung cek situs resmi GrapesJS di:

[https://grapesjs.com/](https://grapesjs.com/)

## Repositori GitHub GrapesJS

Kunjungi repositori GitHub GrapesJS untuk melihat kode sumber, melaporkan isu, atau berkontribusi pada proyek:

[https://github.com/GrapesJS/grapesjs](https://github.com/GrapesJS/grapesjs)

## Cara Memulai

1. Clone repository ini:

    ```bash
    git clone https://github.com/SeptiawanAjiP/grapesjs-initial-project
    ```

2. Buka file `index.html` di peramban web kesayangan Anda.

3. Sesuaikan inisialisasi GrapesJS pada tag `<script>` di `index.html` sesuai dengan kebutuhan.

    ```javascript
    var editor = grapesjs.init({
        container: "#gjs",
        components: '<div class="txt-red">Halo dunia!</div>',
        style: ".txt-red{color: red}",
        plugins: [
            "grapesjs-preset-newsletter", 
            "grapesjs-preset-webpage", 
            "grapesjs-plugin-forms", 
            "grapesjs-navbar"
        ],
    });
    ```

## Plugin Tambahan

Repository ini sudah menyertakan beberapa plugin GrapesJS berikut:

- [grapesjs-preset-newsletter](https://github.com/GrapesJS/preset-newsletter)
- [grapesjs-preset-webpage](https://github.com/GrapesJS/preset-webpage)
- [grapesjs-plugin-forms](https://github.com/GrapesJS/components-forms)
- [grapesjs-navbar](https://github.com/GrapesJS/components-navbar)
